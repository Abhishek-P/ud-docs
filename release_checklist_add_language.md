---
layout: base
title:  'UD new language checklist'
udver:  '2'
---

This checklist describes the steps needed in order to add a new language or treebank to UD.
It is meant for the maintenance task force rather than individual treebank teams.
See [here](release_checklist.html) for the checklist for data contributors.

# How to add a language to UD

* Make sure the language name, ISO code, family and flag is listed in docs-automation in `codes_and_flags.yaml`.
  * It should be the English name of the language, and it should contain only English letters or the space.
    Avoid special characters such as diacritics or apostrophes (we enforce this since the beginning, to be
    sure that we do not face any surprises with our infrastructure; the language will be part of a file/folder
    name).
  * There is a one-to-one mapping between language names and ISO 639 (-1 or -3) codes.
    A language that does not have its own code must be treated as a variant of another language.
    Renaming a language is painful (see below), so one should be careful: is it possible that somebody will
    fall under the same language in the future, and will not like this name?
  * We use flags just as a visual enhancement of the website and we have a disclaimer on the title page that
    they are not a political statement of any sort. We give a flag to every language, although there are
    occasional troubles (e.g., a historical language gets a flag of a modern country because there was no flag
    in the times the language was spoken). If there are multiple candidate flags, we pick one as central and
    put it to `codes_and_flags.yaml`. While this flag will be displayed on the title page of UD, in the
    language-specific documentation there is room for multiple flags (see, e.g., German).
* Create the language collection in the docs repository. Run `addlanguage.sh langcode langname flagcode`
  (If the name of the language consists of multiple words, replace spaces by underscores.)
  * A [template for the language documentation page](https://github.com/UniversalDependencies/docs/blob/pages-source/_template/template-index.md) will be also created. How to force the contributors
    to fill it with contents? (Note that the page must also be renamed from template-index.md to index.md.)
* Create at least one treebank repository in that language (see the steps below).
* See the README.md file in docs-automation. Perform the steps necessary to regenerate the “accordion tables”
  of treebanks on the front page of Universal Dependencies.

# How to add a treebank to UD

* If this is the first UD treebank of its language, see above for how to add the language.
* Create a new Github repository called UD_${language}-${treebank} where ${language} is the
  English name of the language (if it consists of multiple words, replace spaces by underscores)
  and ${treebank} is an acronym or a short word identifying the treebank (only English letters,
  CamelCase, no digits or special characters). Example: "UD_Ancient_Greek-PROIEL".

```Shell
# If you have the gh tool, run:
gh repo create UniversalDependencies/UD_Ancient_Greek-PROIEL --public --add-readme --team Contributors
git clone git@github.com:UniversalDependencies/UD_Ancient_Greek-PROIEL.git
cd UD_Ancient_Greek-PROIEL
copy ..\UD_ZZZ-Template\README.md .
copy ..\UD_ZZZ-Template\CONTRIBUTING.md .
copy ..\UD_ZZZ-Template\LICENSE.txt .
git add CONTRIBUTING.md LICENSE.txt
```

* Populate README.md, CONTRIBUTING.md and LICENSE.txt with default values.
* Create two branches, "master" and "dev". Protect the master branch so that only the core group
  can push to it. Protect the dev branch, too – not against pushing by ordinary members, but
  simply marking the branch as protected means that people with push access will not be able to
  perform force pushes and alter the history on Github (which would be destructive for our
  validation infrastructure).
  * (Note that these steps can be automated with a script that uses the Github API.
    It is not ready yet but a prototype exists in `docs-automation/ghapi`.)

```Shell
git commit -a -m "Initialization and the last commit to the master branch; switching to dev now."
git checkout -b dev
git push --all --set-upstream
perl docs-automation\ghapi\ghapi.pl --protect UD_Ancient_Greek-PROIEL
```

* Make the dev branch writable by the Contributors team (by default they cannot push to the repository
  at all).
* Clone the repository to Dan's local system.
* Clone the repository to Dan's validation server (`quest`).

# How to rename a treebank in UD

Normally, the names of the treebank repositories should be stable because the infrastructure depends on them
(which is also partially illustrated by this section). However, between releases 2.1 and 2.2 we want to rename
the repositories that were so far named only by language (e.g., UD_Czech) so that all repository names also
contain a treebank-specific suffix (e.g., UD_Czech-PDT, where PDT is the suffix). The change of the name involves
at least the following steps:

1.  Go to the Settings tab of the website of the repository. Change the name (e.g. from "UD_Czech" to "UD_Czech-PDT") and click the Rename button.
2.  Go to the server where the automatic validation and evaluation runs (currently quest.ms.mff.cuni.cz, operated by Dan).
    Remove the old clone of the repository and the reports from validation and evaluation.
    <pre>oldrepo=UD_Czech
newrepo=UD_Czech-PDT</pre>
    <pre>rm -rf $oldrepo
rm log/$oldrepo.log
rm log/$oldrepo.eval.log
grep -v -P '^'$oldrepo':' validation-report.txt > /tmp/newreport.txt
mv /tmp/newreport.txt validation-report.txt
chmod 666 validation-report.txt
setfacl -m u:zeman:rw,u:www-data:rw validation-report.txt
grep -v -P '^'$oldrepo'\t' evaluation-report.txt > /tmp/newreport.txt
mv /tmp/newreport.txt evaluation-report.txt
chmod 666 evaluation-report.txt
setfacl -m u:zeman:rw,u:www-data:rw evaluation-report.txt</pre>
3.  Call
    <pre>docs-automation/valdan/clone_one.sh $newrepo
./update-validation-report.pl $newrepo</pre>
4.  Go to one of the places where you have local clones of all UD repositories. Remove the old clone.
    Create a new clone under the new name. Check out the dev branch.
5.  Rename the data files in the dev branch (e.g. from "cs-ud-test.conllu" to "cs_pdt-ud-test.conllu").
6.  Check the README.md and LICENSE.txt files for any mentions of the treebank name that may have to be modified.
    In the README file, add a line to the Changelog, e.g.:
    <pre>* 2018-04-15 v2.2
  * Repository renamed from UD_Czech to UD_Czech-PDT.</pre>
7.  Commit and push the changes. This should also trigger an automatic re-validation of the treebank under the new name.
    There will be a README error because the treebank is not recognized as previously released; see the next step.
8.  Go to the `tools` repository to the Perl module `udlib.pm` and locate the function `check_metadata()`.
    There is a back up list of treebanks and their "Data available since" metadata. Replace `UD_Czech` with `UD_Czech-PDT`,
    keeping it in the list for the release where `UD_Czech` appeared for the first time. (We will probably change the way how this is checked in the future.)
9.  Go to the `docs-automation` repository.
    Open the file `valdan/releases.json`. In the line of the release where the new name will appear for the first time,
    we need this at the end of the release record:
    <pre>, "renamed": [["UD_Czech", "UD_Czech-PDT"]]</pre>
    <strong>The problem is that at the time of renaming the repository, the release process probably has not started and there
    is no line for the next release yet.</strong>
10. If there are other places where you maintain local clones of UD repositories (e.g., one is your laptop and the other is your
    university network), go to each of them, do a new git clone ; git checkout dev ; rm old clone.
11. Finally, we want to regenerate the title page of Universal Dependencies.
    Go to docs-automation. Assumption: all UD treebank repositories, and the docs repository are cloned as siblings of docs-automation
    in the file-folder hierarchy. They are switched to the dev branch. (It does not matter for us because we will switch them to
    master in any case; but we assume that we do this temporarily, and we will switch back to dev when we are done.)
12. Remove the old cached metadata:
    <pre>rm _corpus_metadata/UD_Czech.json</pre>
13. Generate new metadata for the treebank (this script switches the repo temporarily to master):
    <pre>./refresh_corpus_data.sh ../UD_Czech-PDT</pre>
14. Regenerate the UD title page and push it to Github:
    <pre>make dan
cd ../docs
git pull --no-edit</pre>
15. Rename the folder with the treebank hub page in the `docs` repository. Then push the changes.
    <pre>git mv treebanks/cs treebanks/cs_pdt
git status
git diff</pre> then press Q and
    <pre>git commit -a -m 'Renamed treebank repository.'
git push
cd ..</pre>
