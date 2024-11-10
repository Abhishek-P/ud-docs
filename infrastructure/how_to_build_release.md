---
layout: base
title:  'UD release checklist'
udver:  '2'
---

# UD release checklist for the task force

This checklist describes the steps needed in order to release a new version of the UD data.
It is meant for the maintenance task force rather than individual treebank teams.
See [here](release_checklist.html) for the checklist for data contributors.

## Determining which treebanks will be released

* Make sure that you have local clones of all UD_* repositories that should be released.
  This step cannot be automated (unless you write a script that queries Github about all
  repositories belonging to the UniversalDependencies organization).
* Make sure you have the most current content of all the repositories (note that this
  command assumes you have not modified your local copy of the data without pushing it
  back; if this is the case, you will see lists of modified files in the output and you
  will have to resolve it). Also make sure that you are working with the `dev` branch:<br />

	```bash
	for i in UD_* ; do echo $i ; cd $i ; git checkout dev ; git pull --no-edit ; cd .. ; echo ; done
	```

* Make sure there are no untracked files in your local copies of the repositories.
  Otherwise they could be mistakenly picked for the release.<br />

	```bash
	for i in UD_* ; do echo $i ; cd $i ; git status ; if git status | grep -P '(Untracked files|ahead of)' > /dev/null ; then echo XXXXXXXXXXXXXXXXXXXXXXXXXXXXXX UNCLEAN GIT STATUS XXXXXXXXXXXXXXXXXXXXXXXXXXXXXX ; sleep 10 ; fi; cd .. ; echo ; done
	```

* Update version numbers in the commands in this file (`docs/infrastructure/how_to_build_release.md`).
  In the example here in this point (intentionally made up so that bulk replacements will not alter them)
  we assume that we are going to build release 1.13 in November 2020.
  Besides batch-replacing the previous release number to the new release number (replace all
  occurrences of 1.12 with 1.13), the pre-previous release is occasionally mentioned (replace 1.11
  with 1.12). Furthermore, the next step mentions the month when the next release is expected
  (replace November 2020 with May 2021) and one of the steps below mentions the current release
  date (replace 2020-05-15 with 2020-11-15).
* Run `check_release.pl`.
  The script will visit all repositories and report any missing files, unexpected or unexpectedly named files.
  It will download the [online validation report](http://quest.ms.mff.cuni.cz/udvalidator/)
  and check whether the treebanks are valid (prerequisite: all UD repositories are registered
  on the validation server `quest.ms.mff.cuni.cz`).
  It will also collect information such as the list of contributors (we need this metadata for Lindat).

	```bash
	tools/check_release.pl --release 2.15 --next-expected 'May 2025' --oldpath /net/data/universal-dependencies-2.14 |& tee release-2.15-report.txt | less
	```

* Freeze the list of treebanks that will be released (i.e., contain valid data).
  Take the list from the output of `tools/check_release.pl` and save it as
  `released_treebanks.txt` (just one line, names of UD folders separated by whitespace).
* You can get an estimate of what the treebanks do in enhanced graphs. There are several scripts in
  the `tools` repository that try to figure that out. Both `enhanced_graph_properties.pl` and
  `enhanced_classify_relations.pl` can do it for individual treebanks, each using slightly different
  heuristics (the latter script is newer and I tend to trust it more). These scripts can be applied
  in a loop on all UD subfolders of the current folder; but then one has to examine the log by naked
  eye and locate treebanks that actually have enhanced representation. There is also another script,
  `survey_enhancements.pl`, which takes care of the loop (using `enhanced_graph_properties.pl` on
  individual treebanks), can take the subset of treebanks we are interested in (the ones to be released)
  and prints only those that really have enhancements.

	```bash
	tools/survey_enhancements.pl --datapath `pwd -P` --tbklist released_treebanks.txt | tee estats.log
	```

	```bash
	( for i in UD_* ; do echo $i ; ( cat $i/*.conllu | enhanced_graph_properties.pl ) ; echo ; done ) |& tee estats.log
	```

	```bash
	( for i in UD_* ; do echo $i ; ( cat $i/*.conllu | enhanced_classify_relations.pl > /dev/null ) ; echo ; done ) |& tee estats.log
	```

  * If a treebank fills the DEPS column by mistake and it has not been caught by the validator
    (for example, only two enhanced edges in the treebank differ from their basic counterparts
    and it does not correspond to any of the defined enhancements), clear DEPS:

	```bash
	for i in UD_Bad-XXX/*.conllu ; do echo $i ; cp $i backup.conllu ; udapy -s util.Eval node='node.deps = {}' < backup.conllu > $i ; rm backup.conllu ; done
	```

* Check the [validation report](http://quest.ms.mff.cuni.cz/udvalidator/) for legacy exceptions that are no longer needed.
  Edit [valdan/dispensations.json](https://github.com/UniversalDependencies/docs-automation/blob/master/valdan/dispensations.json)
  and remove those exceptions:

	```bash
	cd docs-automation/valdan ; git pull --no-edit ; update-dispensations.pl --json dispensations.json ; git commit -a -m 'Updated validation dispensations.' ;  git push ; cd ../..
	```

* Save the list of the released treebanks in [valdan/releases.json](https://github.com/UniversalDependencies/docs-automation/blob/master/valdan/releases.json)
  by running

	```bash
	docs-automation/valdan/save-release-json.pl --json docs-automation/valdan/releases.json --releasenum 2.15 --releasedate 2024-11-15 $(cat released_treebanks.txt) ; cd docs-automation ; git commit -a -m 'Updated release list.' ; git push ; cd ..
	```

  Note that if a treebank was renamed between the last two releases, it must be entered manually in a separate structure in `releases.json` before running the script!

## Processing the data before releasing them

* Make sure that there are not significant overlaps between training and dev/test files of treebanks of one language.<br />
  <code>tools/check_overlaps.pl $(cat released_treebanks.txt) |& tee overlap.log</code>
* Update statistics in the `stats.xml` file in each repository:<br />
  <code>for i in $(cat released_treebanks.txt) ; do echo $i ; cd $i ; ( ../tools/conllu-stats.pl *.conllu > stats.xml ) ; git add stats.xml ; git commit -m 'Updated statistics.' ; git push ; cd .. ; echo ; done</code>
* Merge the `dev` branch into `master` in the released repositories.
  The `master` branch should not be touched the next six months and it should have exactly the contents that was officially
  released.
  (Exceptions: the script `package_ud_release.sh`, that we will later use to create the release,
  generates plain text files from the CoNLL-U files. The plain text files appear only in the
  released package but not in the Github treebank repository.
  On the other hand, below we generate treebank evaluation log that appears only in the `master`
  branch but not in the `dev` branch nor in the released package.)
  <br />
  <code>for i in $(cat released_treebanks.txt) ; do echo $i ; cd $i ; git checkout master ; git pull --no-edit ; git merge dev --no-edit ; git push ; git checkout dev ; cd .. ; echo ; done</code>
  * Check for conflicts from the previous step. If people misbehaved and pushed commits to `master`, even after a revert automatic merging may no longer be possible. We must resolve all conflicts manually before going on! The conflicted repositories are still switched to the `master` branch and git will not allow any further operations with them!<br />
    <code>for i in $(cat released_treebanks.txt) ; do echo $i ; cd $i ; if ( git status | grep conflict ) ; then echo XXXXXXXXXXXXXXXXXXXXXXXXXXXXXX CONFLICT XXXXXXXXXXXXXXXXXXXXXXXXXXXXXX ; sleep 10 ; else echo OK ; fi ; cd .. ; echo ; done</code>
    * <code>cd UD_...(the-one-with-conflict) ; git status</code> will show what files have a problem. Let's assume that only `README.md` has a problem. This is how we replace it with the version from the `dev` branch and conclude the merge:<br />
      <code>git checkout --theirs README.md ; git add README.md ; git commit -m 'Merge branch dev' ; git push ; git checkout dev ; cd ..</code>
  * After resolving the conflicts do not forget to checkout the `dev` branch again! (If there were no conflicts, we are already back in `dev`.)<br />
    <code>for i in $(cat released_treebanks.txt) ; do echo $i ; cd $i ; git checkout dev ; cd .. ; echo ; done</code>
* Re-evaluate the treebanks for the star ranking on the website. This is done only in the master branch and the result is stored there.<br />
  <code>for i in $(cat released_treebanks.txt) ; do echo $i ; cd $i ; git checkout master ; cd .. ; perl -I tools tools/evaluate_treebank.pl $i --verbose &gt;&amp; $i/eval.log ; cd $i ; git add eval.log ; git commit -m 'Updated treebank evaluation.' ; git push ; git checkout dev ; cd .. ; done</code>

## Updating automatically generated parts of documentation

* Run the script that refreshes the title page of Universal Dependencies (list of languages, treebanks and their properties).<br />
  <code>cd docs ; git pull --no-edit ; cd ../docs-automation ; git pull --no-edit ; make all ; cd ../docs ; git commit -a -m 'Updated title page.' ; git push ; cd ..</code>
* Run the `conllu-stats.pl` script again (but with different settings) and generate the long statistics that are displayed in the docs; note that the script takes the release number as a parameter and puts it in the generated index page:<br />
  <code>cd docs ; git pull --no-edit ; cd .. ; for i in $(cat released_treebanks.txt) ; do echo $i ; tools/conllu-stats.pl --oformat newdetailed --release 2.15 --treebank $i --docs docs ; echo ; done ; cd docs ; git add treebanks/*/*.md ; git commit -m 'Updated statistics.' ; git push ; cd ..</code>
* Generate side-by-side comparison whenever there are multiple treebanks of one language:<br />
  <code>perl tools/generate_comparison_of_treebanks.pl $(cat released_treebanks.txt) ; cd docs ; git add treebanks/*-comparison.md ; git commit -m 'Updated comparison of treebanks.' ; git push ; cd ..</code>
* Run two other scripts that generate the lists of language-specific features and dependency
  relation subtypes for the docs repository.
  Once the two files are updated, we must commit and push them to Github of course.<br />
  <code>perl tools/survey_features.pl --tbklist released_treebanks.txt &gt; docs/ext-feat-index.md<br />
  perl tools/survey_deprel_subtypes.pl --tbklist released_treebanks.txt &gt; docs/ext-dep-index.md<br />
  cd docs ; git pull --no-edit ; git status ; git commit -a -m 'Updated list of features and relations.' ; git push ; cd ..</code>
* Run the script `makedata.sh` in the docs repository. It will regenerate the YAML files in the folder `_data`; this is needed
  for cross-lingual links between documentation pages devoted to individual UPOS tags, features and relations.<br />
  <code>cd docs ; ./makedata.sh ; git commit -a -m 'Updated crosslingual links.' ; git push ; cd ..</code><br />
* Tag the current commit in all repositories including docs with the tag of the current release (`git tag r2.15` for UD 2.15).
  Push the tag to Github: `git push origin --tags`.
  You may even tag a particular commit retroactively: `git tag -a r2.1 9fceb02`.
  If the repository is updated after you assigned the tag and you need to re-assign the tag to a newer commit,
  this is how you remove the tag from where it is now: `git tag -d r2.1`.
  And this is how you remove it from Github: `git push origin :refs/tags/r2.1`.<br />
  <code>for i in $(cat released_treebanks.txt) docs tools ; do echo $i ; cd $i ; git tag r2.15 ; git push --tags ; cd .. ; echo ; done</code>

## Releasing the data

* Run the script <tt>tools/package_ud_release.sh</tt>, which must find the release number in the environment,
  and its arguments are names of folders to be released.<br />
  <code>RELEASE=2.15 tools/package_ud_release.sh $(cat released_treebanks.txt)</code>
  * If we later find out that we need to fix a bug in one (or a few) repository, we can update the release folder without building everything from scratch:<br />
    <code>RELEASE=2.15 tools/package_ud_release.sh --update UD_X UD_Y</code>
* Make the release packages temporarily available for download somewhere and ask the treebank providers to check them before we archive them in Lindat.
* Tell Milan Straka that he can start training UDPipe models of the new data.
  Tell Maarten Janssen that he can start importing the data to TEITOK.
* Update the list of licenses for Lindat. See the [LICENSE repository](https://github.com/UniversalDependencies/LICENSE)
  and the README file there. The script <tt>generate_license_for_lindat.pl</tt> can be invoked from the parent folder
  and it will create a HTML and a XML file in the LICENSE folder. Add and push the files to the LICENSE repository,
  then make sure it reaches the Lindat staff, either by e-mail at lindat-help@ufal.mff.cuni.cz, or by a pull request
  as described in the [README](https://github.com/UniversalDependencies/LICENSE/blob/master/README.md) file.
  <br />
  <code>LICENSE/generate_license_for_lindat.pl --release 2.15 --date 2022/05/15 $(cat released_treebanks.txt) ; cd LICENSE ; git add license-ud-* ; git commit -a -m 'Generated license for UD 2.15.' ; git push ; cd ..</code>
* Once the Lindat staff make the new license list available in their system, we can create
  a new Lindat item for the new version of UD. The preferable way: Create the new item as
  a new version of the item representing the previous release of Universal Dependencies.
  When signed in, go to the
  [list of your previous contributions](https://lindat.mff.cuni.cz/repository/xmlui/submissions),
  check the box next to the line with the most recent release of UD, then go down and press the
  button that says “Add new version”. If this is not possible because you are not the user who
  created the item for the previous version, you can
  [create a new Lindat item from scratch](https://lindat.mff.cuni.cz/repository/xmlui/submit).
  Then the server starts by asking you to “select a community”. Choose LINDAT / CLARIN.
  In the note for the editors (last page of the form), ask them to mark the previous UD release
  as obsolete and to add a link pointing from the previous release to the new one.
  Note that the Lindat staff may help to automate other tasks as well.
  For example, we have an extraordinarily long list of authors. Instead of typing them on the Lindat website one-by-one,
  they can batch-upload the list we send them. Once everything is ready and we submit the item, they will review it
  and archive it. At that moment the release is officially out and no changes to the data files are permitted
  (changes to metadata are possible if necessary, but this is done on demand only).
  The item will get a persistent URL (handle.net); that is the URL that we want to publish on the UD website.
  Note that you can now see the persistent URL in the record even before it has been approved. It will not
  change on approval and you can save it; however, it will not be operational as a URL until the item is archived.
* Update the title page of Universal Dependencies. Send out announcement to lingfil-ud@lists.uu.se, corpora@list.elra.info etc.
  <!-- We used to also send it to ACL but the ACL web now seems to accept only announcements about events, not about data. -->
* In the script that serves the online validation report (`docs-automation/valdan/validation-report.pl`),
  locate the function `get_timer()` and update the date to the next data freeze deadline.
* Upload the data to the search engines (PML-TQ, Kontext etc.)
* Check the issues of the docs repository on Github, close the ones that have been solved, and create a new milestone for the others.
* Generate Deep UD based on the new UD release.

<div style="color:lightgrey; font-size:smaller">
<pre>
# Copy metadata to biblio.

# Check that Treex knows all new language codes (the script will say what to do if not).
# Then copy the new release from Dan's workspace to /net/data/universal-dependencies-2.xx.
$HAMLEDT/release_ud_ufal.pl --release 2.15

# Import the data to PML-TQ.
cd $HAMLEDT
perl ./populate_ud.pl 2.15
cd normalize ; make qpmltq
# Follow instructions in ud-to-pmltq manual ($HAMLEDT/pmltq/navod_na_export_ud_do_pmltq.odt).
</pre>
</div>
