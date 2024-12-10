---
layout: base
title:  'Dataset release checklist'
udver: '2'
---

# Release checklist

This checklist is meant to provide guidance for teams contributing treebank data for a new release of Universal Dependencies.
It was created for release v1.2 and applies, unless otherwise noted, to any upcoming release.

Contents:

* [New language or treebank](#new-language-or-treebank)
* [Executive summary](#executive-summary)
* [Repository and files](#repository-and-files)
  - [Data split](#data-split)
  - [The README file](#the-readme-file)
  - [Treebank metadata](#treebank-metadata)
  - [Repository branches](#repository-branches)
* [Validation](#validation)
* [Fixing errors in treebanks](#fixing-errors-in-treebanks)
* [Language-specific guidelines](#language-specific-guidelines)

# New language or treebank

If you want to write UD guidelines and/or provide annotated data for a language that is currently not listed on the UD website,
make sure you have a [github account](https://github.com/) and contact a member of our release and documentation task force:
Dan Zeman (zeman@ufal.mff.cuni.cz).
They will get you going.
Similarly, if you want to contribute a new treebank of a language that is already listed on the UD website,
contact the release task force and they will create a new treebank repository.

In both cases, think of an acronym or short word that will be used as the treebank identifier in the name of the repository
(for example, UD_English-LinES and UD_English-ParTUT are two different English UD treebanks
and their identifiers are LinES and ParTUT).
It can be an acronym of your annotation project (such as XTB, where X is the initial of the language name), or your institution, or even your own initials, but preferably it should be short. It can contain uppercase and lowercase English letters (the first letter uppercase) but it cannot contain additional underscores, hyphens or other special characters.
Tell your preferred treebank acronym to the release task force when you ask for the repository.

For some languages, there may be multiple candidates for the name of the language. It deserves some
thought before the first treebank repository of the language is created, as the language name is
not supposed to be changed in the future (although renaming is not impossible, it is painful because
many places in the infrastructure have to be carefully checked manually by the maintenance crew).
We stick with the ISO 639 language codes. If a language does not have its own code, it will be treated
as a variant of its closest relative, and they will share the language prefix of the repository name.
Try to imagine how likely it is that somebody will want to cover another variant in the future, and
whether or not they will like the language name you propose now. In any case, we only use English
letters in the repository name (which should bear the _English_ name of the language). Various
special characters, diacritics or apostrophes may be linguistically more appropriate but you have to
save them for the documentation, and avoid them in the repository name.

While you are waiting for your repository, read the instructions below. They explain what you need to do
so that your treebank works well with our infrastructure and can be released.
And do not forget to subscribe to the [UD mailing list](https://lists.uu.se/sympa/info/lingfil-ud).
Important announcements for the data providers are circulated through this list.

# Executive summary

* Make sure [your repository has the right files](#repository-and-files), [correct metadata](#treebank-metadata) in the README, and data being prepared for the next release [lives on the `dev` branch](#repository-branches).
* Make sure your data and repository pass the [format and content validation](#validation): [direct link](https://quest.ms.mff.cuni.cz/udvalidator/cgi-bin/unidep/validation-report.pl) to the validator output.

# Repository and files

Every treebank has its own GitHub repository called `UD_Language-Treebank`, where `Language` is the name of the language and
`Treebank` is a unique identifier of a treebank within a language. For example, `UD_Finnish-TDT` and `UD_Finnish-FTB` are repositories
of two different treebanks of Finnish: `TDT` stands for “Turku Dependency Treebank”, and `FTB` stands for “FinnTreeBank”.
If treebanks in different languages are strongly related (especially if they are parallel translations of the same text),
it is desirable that they have the same treebank identifier. For example, `UD_English-LinES` and `UD_Swedish-LinES` are two halves
of an English-Swedish parallel treebank. On the other hand, it is allowed that two unrelated treebanks in different languages have
identical identifiers simply by chance. For example, `UD_French-FTB` (standing for “French TreeBank”) uses the identifier `FTB`
although it is not related to FinnTreeBank.

Every treebank repository should contain the following files (where `xx` is the ISO code for the
given language, and `y` is the lowercased treebank identifier). For example, `fi_tdt` is the code
used in the Turku Dependency Treebank of Finnish.
Small treebanks may have just the test file but no training and development data; see below for
more detailed recommendations for train-dev-test data splits. Since release 2.10, there is also
a minimum requirement on treebank size: 20 sentences and 100 words (both numbers must be reached
or exceeded; it shouldn't be difficult to reach with a translation of the examples from the
[Cairo Cicling Corpus](https://github.com/UniversalDependencies/cairo/blob/master/translations.txt)).

1. `README.md` or `README.txt`
2. `LICENSE.txt`
3. `CONTRIBUTING.md`
4. `xx_y-ud-test.conllu`
5. `xx_y-ud-train.conllu`
6. `xx_y-ud-dev.conllu`

The `README.md` file contains basic documentation of the treebank and machine-readable metadata
for the UD main page (see below) and the `LICENSE.txt` specifies under what license the treebank
is made available. The file `CONTRIBUTING.md` warns users about UD Github branch policies; this
file is added when the repository is created and treebank maintainers do not have to care about
it.

The data files (training, development and test set) must be in the `CoNLL-U` format and conform to
the universal guidelines. They need to be validated as described below.

Repositories of released treebanks also contain a `stats.xml` file, which is generated as part of
the release-building process, using the script `conllu-stats.pl` available from the `tools`
repository. Data providers do not have to care about this file; it will be generated by the
release task force.

Any other files (treebank source files, processing scripts etc.) must be placed in a subfolder
named `not-to-release`.

## Data split

These guidelines are strong recommendations rather than strict rules. 

The general underlying idea is that we do not want to ban tiny datasets from
being released, but we only want to distinguish training and test sets if
the test set will be large enough (the 10K-word threshold was set in the
CoNLL 2017 shared task) and if the data that is left for training is at least
as large as the test set. Making an official split is useful for comparison
of experiments evaluated on the treebank, but with small treebanks people
should do ten-fold cross-validation anyway.

There is one exception to that general idea. If this is the only UD treebank
in the given language, we may set aside a small sample and call it “train”.
This may be useful if the treebank is used in a shared task where the systems
are supposed to use cross-lingual projection techniques and cannot access the test data,
but the developers should have access at least to a small sample of the language
so they can see the annotation, language properties, etc.
In other situations, users should still use the entire data for training and
testing via cross-validation.
Providing the sample is completely optional.
Note that it does not make sense to set aside a sample
if a larger treebank of the same language exists and has training data.

1. If you have less than 20K words:
   * Option A: Keep everything as test data. Users will have to do 10-fold cross-validation if they want to train on it.
   * Option B: Only if there are no larger treebanks of this language, keep almost everything as test data but set aside a small sample (20 to 50 sentences) and call it “train”. Consider translating and annotating the 20 examples from the [Cairo Cicling Corpus](https://github.com/UniversalDependencies/cairo/blob/master/translations.txt) (CCC) and providing them as the sample.
2. If you have between 20K and 110K words, take a minimum of 10K words as test data, 10% of the remainder as dev data, and the remainder as training data.
3. If you have more than 110K words, take between 10K words and 10% of the data as test data, take another between 10K words and 10% of the data as dev data, and the remainder as test data.
4. If the treebank contains running text (rather than random shuffled sentences), make sure you split the data on document boundaries. Shuffling sentences should be avoided if possible, but sometimes it is necessary in order to prevent copyright issues. If you must shuffle, consider shuffling blocks of sentences (up to N characters long) rather than individual sentences.
5. If the treebank contains different domains or genres, try to distribute them proportionally to training, dev and test. Ideally, it should also be possible to tell them apart by sentence ids.
6. If the data in the treebank overlap with another UD treebank of the same language, make sure that the overlapping sentences end up in the same part (training/dev/test) in both treebanks! (By overlap we mean duplicate source text but not individual simple sentences that occur naturally at different positions of independent texts.)
7. If this is one language of a multi-lingual parallel treebank, make sure that corresponding sentences in all languages end up in the same part (training/dev/test)!
8. It is desirable that the data split of one treebank is stable across UD releases, i.e., a sentence that was in training data in release N is not moved to dev or test data in release N+1. We want to prevent accidental misguided results of experiments where people take a parser trained on UD 1.1 and apply it to test data from UD 1.2. In exceptional cases some restructuring that violates this rule can be approved by the release team, provided there are good reasons for it. (One obviously valid reason is that a growing treebank exceeds the 20K-word threshold and is split to training and test.) If at all possible, please try to plan ahead and minimize the need for re-splits in the future.

[//]: # (See also [this e-mail thread](https://cl.lingfil.uu.se/pipermail/ud/2015-November/000095.html). ChrisM: This link is dead in 2024.)

## The README file

The `README` file is distributed together with the data and summarizes information about the treebank for its users;
the contents of the file is also displayed by Github when readers land on the Github homepage of the treebank repository.
At the same time, certain pre-defined parts of the `README` file are automatically copied to the UD website to places
where individual treebanks are described. In these cases, the contents is interpreted as MarkDown and you can use the
[MarkDown syntax](https://guides.github.com/features/mastering-markdown/)
to add a little formatting (but please remember that some users will read directly the `README` file, so it should stay
reasonably human-readable).
The last part of the `README` file contains machine-readable metadata (described below) where selected vital information
must be provided in a fixed pre-defined way.

Similarly to the data files, the `README` file can be only modified in the `dev` branch of the repository, and changes are
propagated to the master branch and to other places twice a year at release time
(see the [Repository Branches](#repository-branches) section below for details).
Therefore, the `README` file should be in shape by the data freeze deadline; do not postpone it until after the release!
The most visible places of the website are based on the contents of the master branch and you will not be able to edit them
between releases (think of the website as of a journal with two numbers per year: you can publish information about your
treebank in the next issue, but you cannot publish corrections before the next issue is out).

MarkDown source files usually have the `.md` extension (`README.md`); but for historical reasons,
it is also possible to name the file `README.txt`.
Only one of these files must be present, it is not permitted to have both `README.md` and `README.txt`!

The `README` file should minimally contain the following information:

1. A description of the treebank and its origin (creation method, data sources, etc.)
2. A description of how the data was split into training, development and test sets
3. If there are multiple genres/domains, can they be told apart by sentence ids? Does the treebank consist of complete documents, or just randomly shuffled sentences?
4. Acknowledgments and references that should be cited when using the treebank
5. A [changelog](http://en.wikipedia.org/wiki/Changelog) section for treebanks that will be released for the second (or subsequent) time
6. A machine-readable section with treebank metadata. This is described below.

MarkDown uses the `#` character to mark section headings. Several sections with fixed names are expected in every `README`
and will be searched for by various scripts. Use the following template (from Swedish) to adjust your `README`.
The first section, called _Summary_, should be rather short (one-two lines), so it can appear in an index page listing all
treebanks. An automatically generated treebank page in the UD documentation will take over the sections _Summary, Introduction_
and _Acknowledgments._ Note that the pre-defined section headings must be top-level headings, i.e. just one `#` character
at the beginning of the line! Any nested subsections (two or more `#` characters at the beginning of the line) are considered part
of the superordinate section and will be copied with it.

<pre>
# Summary

UD Swedish-TP is a conversion of the Prose section of Talbanken, originally annotated in the MAMBA annotation scheme,
and consisting of a variety of informative text genres, including textbooks, information brochures and newspaper articles.

# Introduction

UD Swedish-TP is a conversion of the Prose section of Talbanken (Einarsson, 1976), originally annotated…

# Acknowledgments

The new conversion has been performed by Joakim Nivre and Aaron Smith at Uppsala University. We thank everyone who…

# (possibly any number of extra sections)

…

# Changelog

* 2015-05-15 v1.1
  * Added lemmas
  * Corrected tokenization in sentences 123 and 456
* 2015-01-15 v1.0
  * First release in UD

&lt;pre&gt;
=== Machine-readable metadata (DO NOT REMOVE!) ================================
(described in more detail below)
</pre>

## Treebank metadata

The table on the front page is automatically generated from special lines (metadata)
in the `README.txt` or `README.md` file for every treebank. The metadata are used for various
other automated tasks as well, for example the list of contributors to every UD release is
collected from the READMEs.

The metadata describe individual treebanks and there are often multiple treebanks per language.
If we want to work on UD documentation for a new language without having actual data, we still
must create a Github repository for the future treebank, and fill in the metadata so that the
language appears on the front page. The names of the contributors to the documentation should
be listed among the treebank contributors, otherwise they will not be included in the overall
UD list of contributors.

Here is an example of the treebank metadata block from the [Czech README file](https://github.com/UniversalDependencies/UD_Czech/blob/dev/README.md)

    <pre>
    === Machine-readable metadata (DO NOT REMOVE!) ================================
    Data available since: UD v1.0
    License: CC BY-NC-SA 3.0
    Includes text: yes
    Genre: news
    Lemmas: converted from manual
    UPOS: converted from manual
    XPOS: manual native
    Features: converted from manual
    Relations: converted from manual
    Contributors: Zeman, Daniel; Hajič, Jan
    Contributing: elsewhere
    Contact: zeman@ufal.mff.cuni.cz
    ===============================================================================
    </pre>

This block should be the last thing in the `README` file. The properties are as follows:

* `Data available since` can be `UD v1.0`, `UD v1.1`, `UD v1.2`, `UD v1.3`, `UD v1.4`, `UD v2.0`, `UD v2.1` etc.
  Pick the number of the first release where this treebank appears.
  Do not change it when the treebank is released the next time.
* `License`: anything containing the string `BY-NC-SA` will be given the CC non-commercial logo, `BY-SA` or `BY` the CC logo, and `GNU` the GNU logo. To add any other license, please provide a suitable icon to zeman@ufal.mff.cuni.cz.
  * `Includes text`: Most treebanks should say `yes` here. But there are a few instances where
    the license of the underlying text does not allow redistribution. Here, the UD repository
    contains only the annotation without words and lemmas, but with a merging script that the
    user can run and merge the annotation with the corpus that they obtained through another
    channel. Such treebanks should say `no` here.
* `Genre`: this is simply a space-separated list of genres which gets mapped into symbols in the table. The possible genres are listed in [this file](https://github.com/UniversalDependencies/docs-automation/blob/master/genre_symbols.json)
  (symbols from [the *FontAwesome* list](https://fortawesome.github.io/Font-Awesome/icons/)).
  If you don't see yours, try to think of a less specific or similar genre that is on the list.
  Remember that this is just an approximation and we are not aiming at a fine-grained hierarchy of all possible genres.
  If you believe you really need a new genre, contact the release task force and try to persuade them.
  Note that simply editing the file will no longer help you because the validation software has its own list of known genres.
* Source of annotation of lemmas, POS tags, morphological features and dependency relations.
  There are several possible values:
  * `manual native` ... means that the annotation was done manually, directly in the UD annotation scheme.
    Note that manual verification of automatic annotation (e.g. you pre-parse the text before you give it to humans)
    counts as manual annotation.
  * `converted from manual` ... means that it was originally annotated in a non-UD scheme, then converted to UD by a program,
    but the converted annotation has not been verified by a human annotator.
  * `converted with corrections` ... significant spot-checking and manual corrections occurred after the conversion;
    however, it does not qualify as full manual annotation because not all words were visited systematically.
    This is an intermediate level between “converted from manual” and “manual native”.
  * `automatic` ... means that the annotation was predicted by a program such as tagger or parser.
  * `automatic with corrections` ... significant spot-checking and manual corrections occurred after the automatic prediction;
    however, it does not qualify as full manual annotation because not all words were visited systematically.
    This is an intermediate level between “automatic” and “manual native”.
  * `not available` ... means that this type of annotation is not present.
* Note that some values are available only for some types of annotation.
  UPOS tags and relations must always be available and cannot be automatic.
  * `Lemmas` ... `manual native | converted from manual | converted with corrections | automatic | automatic with corrections | not available`
  * `UPOS` ... `manual native | converted from manual | converted with corrections`
  * `XPOS` ... `manual native | automatic | automatic with corrections | not available`
  * `Features` ... `manual native | converted from manual | converted with corrections | automatic | automatic with corrections | not available`
  * `Relations` ... `manual native | converted from manual | converted with corrections`
* `Contributors`: the list of contributors to be included with the data release and in the LINDAT download page. This is a semicolon-separated list where every name is in the `Last, First` form and the `README` file should be utf-8 encoded to make sure special characters are preserved correctly.
* `Contributing`:
  * `here` ... The changes are done directly in the dev branch of the UD repository. Bugs can be fixed via pull requests.
  * `here source` ... The changes are done in the UD repository but not directly in the final CoNLL-U files. Instead, there is a folder called `not-to-release` where source files have to be located and fixed.
  * `elsewhere` ... Do not submit pull requests; create issues. Main development happens somewhere else. If there is a bug, either the original data or the conversion procedure must be fixed.
  * `to be adopted` ... The treebank currently misses a maintainer. If you know the language, please consider adopting the treebank.
* `Contact`: please add an e-mail address where the current maintainer of the data can be contacted. You can also include several e-mail addresses separated by commas.

If you want to see what web content will be generated from your README file, run the
`generate_treebank_hub.pl` script from the tools repository on your treebank folder,
e.g.

    tools/generate_treebank_hub.pl UD_Czech > for_web.md

## Repository branches

While the official UD release is always through Lindat, many users of UD source their data from the GitHub language repositories. Therefore, the `master` branch of every language should contain the last, officially released version of the data for the given language. The development in between releases should happen on the `dev` branch of the repository.
Treebank maintainers should never touch the `master` branch, they should always push to `dev`.
(Ordinary contributors are not even able to push to `master`, the branch is protected.)
At release time, the release task force will take care of merging the contents of the `dev` branch into `master`.
<strong>Please do not submit pull requests from the dev branch (or from anywhere else) to the master branch.</strong>
This is not needed for the release merge to take place, and if someone overlooks the destination branch and accepts the pull request,
it will again result in a commit to the master branch at wrong time.

(To make things a bit more confusing, this policy of data repositories does not apply to some other repositories that we use. In the `docs` repository you must work with the `pages-source` branch. That is done automatically if you edit the documentation in your browser via the _edit page_ link. You will also need to access the `tools` repository and upload the `deprel` and `feat_val` files specific for your treebank. In this case, please use the `master` branch.)

If you have no previous experience with Git, here is a quick tutorial on how to deal with the branches. Please refer to on-line documentation of Git and Github for more details. The tutorial assumes that you are communicating with Github from a Linux shell. The interface may be different if your OS is Windows. If you are working only with the Github web interface, you are not dependent on your operating system but you must remember to switch the `Branch: master` drop-down menu (left-hand side of the page) to `Branch: dev`; it always starts in `master` by default. In contrast, when you want to clone the repository to your local system, you need the address that is hidden under `Clone or download` in the right-hand side of the page, and that address is common for all branches. Our example is the [Italian ISDT repository](https://github.com/UniversalDependencies/UD_Italian-ISDT/tree/dev). Here is how you clone the repo to your system (`git clone` is the command, the remainder is the address copied from the Github web):

<pre>
git clone git@github.com:UniversalDependencies/UD_Italian-ISDT.git
<span style="color:blue">Cloning into 'UD_Italian-ISDT'...
remote: Counting objects: 215, done.
remote: Total 215 (delta 0), reused 0 (delta 0), pack-reused 215
Receiving objects: 100% (215/215), 6.98 MiB | 4.55 MiB/s, done.
Resolving deltas: 100% (134/134), done.
Checking connectivity... done.</span>
</pre>

Then enter the cloned folder and switch to ("checkout") the `dev` branch. Your copy of the repository knows that such a branch exists on the server but it only creates your local copy of that branch once you ask for it. You may subsequently want to call `git pull` to make sure that you have the latest contents of the dev branch from the server:

<pre>
cd UD_Italian-ISDT
git checkout dev
<span style="color:blue">Branch dev set up to track remote branch dev from origin.
Switched to a new branch 'dev'</span>
git branch
<span style="color:blue">* dev
master</span>
git pull
<span style="color:blue">Already up-to-date.</span>
</pre>

Once you do this, you are all set. Your copy will stay switched to the dev branch unless you call `git checkout master` (or other `git checkout`) again. You will probably mostly need just `git status`, `git diff`, `git add`, `git commit`, `git push` and `git pull` commands. All pushes and pulls will be done against the remote `dev` branch.

<strong>Never ever modify the history of the git commits!</strong> While this is a bad practice in a collaborative environment in general, the immediate consequence in UD is that you will break the automatic re-validation of your treebank. (The validation server has its own copy of your repository, with the whole history. If a previously existing commit disappears from Github, it will look as if that commit is a local change on the validation server, and the validation server will no longer be able to automatically update its copy from Github.) So if you accidentaly commit a modification that is later found wrong, do not remove the commit from the history. Instead, revert the changes of the commit so that the inverse changes appear in your working copy, then add these changes to a new commit and push it to Github.



# Validation

Up-to-date automatic validation runs of the repositories are available
[here](http://quest.ms.mff.cuni.cz/udvalidator/). Depending on the size of the treebank, the report
will be updated within one to twenty minutes after pushing changes to Github. The report is based
on the `dev` branch of the data and combines the output of two scripts: `check_files.pl` and
`validate.py`. The former checks whether the treebank repository contains the expected files,
whether the metadata in `README` look good and whether the language-specific documentation exists
in the `docs` repository. The latter checks the actual contents of the CoNLL-U files within the
treebank. This is the official UD validator, described in more detail below. You may want to
download `validate.py` and check your data locally before uploading them; but even if you do so,
always check the on-line validation report after uploading any changes to your repository. If you
run your local validator with wrong configuration (or if you do not have the latest version of the
validator), you may be led to think that your treebank is in good shape, while the fact is that the
server will reject it.

See a separate page on [validation rules](validation-rules.html), which explains the various
validation levels, as well as the consequences of your treebank's not being valid at release time.

The validation script is available in the [tools](https://github.com/UniversalDependencies/tools)
repository and you can use it to test your data locally before you upload them to Github. Make sure
that you always have the latest update of the tools repository.

    $ git clone git@github.com:UniversalDependencies/tools.git
    $ cd tools
    $ python validate.py -h

Note that you need Python 3 to run the validator, and you need a third-party
Python module called `regex` installed via pip, so when needed try this before
invoking the validator:

    $ sudo apt-get install python3-pip; python3 -m pip install regex

See also the [README file](https://github.com/UniversalDependencies/tools/blob/master/README.md)
in the tools repository.

In general, you validate the data like so:

    $ python validate.py --lang=xx --max-err=0 [file.conllu]

for example for Finnish:

    $ python validate.py --lang=fi --max-err=0 ../UD_Finnish-TDT/fi_tdt-ud-dev.conllu
    *** PASSED ***

Among other items, the script also validates the language-specific set
of morphological features and relations and therefore it needs to know about these.
Until release 2.7, language-specific lists were stored in the `data` folder in the `tools`
repository and they could be edited directly by users working on individual languages. This
practice is now deprecated. The `data` folder will contain necessary information in JSON files
that cannot be edited directly. Instead, language-specific labels will be registered through
a web interface and the data in the `tools` repository will be automatically updated when a change
is saved in the web interface.

At present, morphological features can be registered
[here](https://quest.ms.mff.cuni.cz/udvalidator/cgi-bin/unidep/langspec/specify_feature.pl),
dependency relations for basic trees
[here](https://quest.ms.mff.cuni.cz/udvalidator/cgi-bin/unidep/langspec/specify_deprel.pl) and
case markers for enhanced relations
[here](https://quest.ms.mff.cuni.cz/udvalidator/cgi-bin/unidep/langspec/specify_edeprel.pl).

It is possible to register language-specific features and relations only if they
[have been properly documented](contributing_language_specific.html). If a feature or relation does not have
its own documentation page in the `docs` repository (either as part of the universal guidelines
or in the language-specific folder), or if the page is not in the prescribed (machine-recognizable)
format, the web interface will not allow to register the feature or relation as valid, and consequently, the
validator will not accept it in the data.

Since the `v2.0` release, whitespace is allowed in the `FORM` and `LEMMA` fields under conditions
specified [here](v2/segmentation.html). This is supported in the validator through the UD-wide
file `data/tokens_w_space.ud` and its language-specific variants `data/tokens_w_space.xx`. In
these files, each line is a [Python regular expression](https://docs.python.org/3/library/re.html)
defining the permissible forms and lemmas that can contain a whitespace.

The validator also checks that certain closed classes (currently auxiliaries and copula) appear
only with documented lemmas. Since release 2.7, auxiliaries can be [defined at the on-line validation
site](https://quest.ms.mff.cuni.cz/udvalidator/cgi-bin/unidep/langspec/specify_auxiliary.pl).
When adding an auxiliary (or the copula), the user can see some relevant points from the UD
guidelines, as well as the list of auxiliaries that have been defined in other languages
(related languages are shown first). This is to improve cross-lingual parallelism and to reduce
the danger that maintainers of neighboring languages will employ dramatically different interpretations
of the guidelines and end up with divergent notions of what qualifies as an auxiliary.
All auxiliaries must be explained and accompanied by an example; in the future, the information
collected this way could be propagated to the UD documentation. The site initially includes some
auxiliaries that were previously listed (but not documented) in the source code of the validator.
The user has to provide the missing information for all existing auxiliaries before they can add
new ones.

When validating language-specific lists of morphological features, auxiliary verbs etc., the validator
can temporarily switch to a language different from the main language of the file. This is useful
in cases of code-switching, i.e., when a foreign language phrase is inserted in the text, and the
annotators decided to annotate it according to the foreign language guidelines (instead of simply
tagging everything as `X` and connecting it as a `flat` structure). The alternative language is
signaled for individual tokens using the `Lang` attribute in the MISC column. Its value is the ISO
639 language code, as registered for the language in UD (either two letters from ISO 639-1, or
three letters from ISO 639-3, lowercased!)

Some additional tests are available in the
[Udapi](https://github.com/udapi/udapi-python/blob/master/udapi/block/ud/markbugs.py)
tool. They may reveal configurations that are not necessarily invalid but are suspicious and should be checked manually.



# Fixing errors in treebanks

Previously released treebanks are not always perfect and they may contain inconsistencies or errors.
In some cases new tests are implemented in the official validator and new errors are discovered in
previously valid treebanks. Other errors or inconsistencies cannot be detected by the validator but
they can be spotted and reported by human users.

It is primarily the responsibility of the data providers (or of current treebank maintainers, if
the treebank was adopted by a new team) to fix these errors. However, we want to encourage contributions
from non-maintainers of a treebank in the form of pull requests. Such pull requests must be based on
the previous contents of the dev branch (not the master branch, as it may contain files that would
render the dev branch invalid!) and they must be directed again at the dev branch (never the master
branch). Submitting a pull request does not automatically mean that the treebank maintainer must
accept it (in particular, some treebanks are maintained outside UD and then automatically converted
to UD), but the maintainers should respond to the request, and if they do not accept and merge it,
other possible solutions should be discussed.

We expect that the treebank maintainers would consider such requests within 6 months. If no response
is received from maintainers, the UD infrastructure maintainers have the authority to assume
responsibility for reviewing and accepting the pull request.



# Language-specific guidelines

Every language should have a set of language-specific guidelines at [http://universaldependencies.org/](http://universaldependencies.org/).
If there are multiple UD treebanks in one language, all should follow the same language-specific
guidelines. It is common responsibility of the teams providing the treebanks to also provide the
language-specific documentation.

There are [guidelines specifying the requirements on
language-specific documentation.](contributing_language_specific.html) Also see the general guidelines about
[how to contribute](contributing.html) (which covers the conventions used in writing UD
documentation, such as how to format examples).

# For the maintenance crew

Documentation of the infrastructure is [here](infrastructure/index.html).
