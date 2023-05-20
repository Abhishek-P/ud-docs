---
layout: base
title:  'Bororo UD'
udver: '2'
---

# UD for Bororo <span class="flagspan"><img class="flag" src="../../flags/svg/BR.svg" /></span>

## Tokenization and Word Segmentation

Bororo uses all 18 tags. Words are delimited by a whitespace.

*

---
**Instruction**: Describe the general rules for delimiting words (for example, based on whitespace and punctuation) and exceptions to these rules. Specify whether words with spaces and/or multiword tokens occur. Include links to further language-specific documentation if available.

---

## Morphology

### Nouns

#### Gender

The `gender of nouns in Bororo follow the natural gender of the animate nouns, i.e., males take masculine gender and females take feminine gender. Inanimate nouns are genderless but morphologically they follow the masculine pattern. Based on natural gender, some nouns may be marked as feminine.

#### Number

There are different ways of forming the `plural` of nouns in Bororo: deleting the last syllables of nouns ending in -\textit{edu}, substituting the last vowel by \textit{e}, adding \textit{e} to the singular form, adding -\textit{doge} to the stem, adding -\textit{ge} to nouns ending in -\textit{rewy}, -\textit{wy}, -\textit{epa}, -\textit{are}. There are also instances of irregular plural forms, ablaut with change of final vowel, and some forms that do not vary in the plural.

### Tags

## Person indexes

Person  |       Before consonant       | Before vowel          |
--------------------|------------------|-----------------------|
1S      | _i-_      | _it-_, _in-_, _ik-_  |
2S      | _a-_     | _ak-_              |
3S      |_∅_, _u-_     |
3Anaf   |_tu-_, _pu-_ |_t-_, _tud-_, _pud-_,    |
1PL.EX  | _ce-_ | _ced-_, _cen-_, _ceg-_  |
1PL.IN  | _pa-_   | _pag-_   |
2PL     | _ta-_   | _tag-_   |
3PL     | _e-_    | _et-_, _en-_, _ek-_       |
3Anaf   |_tu-_, _pu-_ |_t-_, _tud-_, _pud-_,    |

The first plural of person indexes distinguish between the values `Ex` (exclusive) and `In` (inclusive) for the feature `Clusivity`

* Nouns are either possessed or unpossessed. Possessed nouns are either alienably o inalienably possessed and this distinction is morphologically marked, with inalienably possessed nouns being marked by agreement with the possessor.

```
Imi iia
imi i-ia
I 1SG-mouth
my mouth
```


---
**Instruction**: Specify any unused tags. Explain what words are tagged as PART. Describe how the AUX-VERB and DET-PRON distinctions are drawn, and specify whether there are (de)verbal forms tagged as ADJ, ADV or NOUN. Include links to language-specific tag definitions if any.

---

### Features

*

---
**Instruction**: Describe inherent and inflectional features for major word classes (at least NOUN and VERB). Describe other noteworthy features. Include links to language-specific feature definitions if any.

---

## Syntax

Bororo is of neutral alignmnt type. S, A, and O are marked by the same set of bound indexes.
The only argument of an intransitive verb (S) is marked by agreement on the verb: 

```
Imaragodure
i-maragodu-re
1SG-work-ASS
```

The A argument of transitive verbs is indexed on the mood or aspectul marker, and the O argumend is bound to verb. 

```
adugore emage ewido
adugo-re e-mage e-bito
jaguar-ASS they 3PL-kill
The jaguar killed them
```

---
**Instruction**: Give criteria for identifying core arguments (subjects and objects), and describe the range of copula constructions in nonverbal clauses. List all subtype relations used. Include links to language-specific relations definitions if any.

---

## Treebanks

There are [N](../treebanks/bor-comparison.html) Bororo UD treebanks:

  * [Bororo-A](../treebanks/bor_a/index.html)
  * [Bororo-B](../treebanks/bor_b/index.html)

---
**Instruction**: Treebank-specific pages are generated automatically from the README file in the treebank repository and
from the data in the latest release. Link to the respective `*-index.html` page in the `treebanks` folder, using the language code
and the treebank code in the file name.

---
