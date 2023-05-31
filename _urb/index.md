---
layout: base
title:  'Kaapor UD'
udver: '2'
---

# UD for Kaapor <span class="flagspan"><img class="flag" src="../../flags/svg/BR.svg" /></span>

## Tokenization and Word Segmentation

* In general, words are delimited by whitespace characters. Description of exceptions follows.
* According to typographical rules, many punctuation marks are attached to a neighboring word. We always tokenize them as separate tokens (words);
* There are no adjectives in Tupinambá. Modification is made by composition, so when a lexical root is modified by another a new word appears as in *kuɲãporaŋ* (*kuɲã* 'woman' + *poraŋ* 'beauty'). Such words are treated as [multiword tokens](https://universaldependencies.org/format.html#morphological-annotation).



## Morphology

* Tupinambá nouns are not marked for gender. Number is optionally marked.
* Nous can take the following [Cases](https://universaldependencies.org/u/feat/Case.html): `Tra` and `Loc`. There different locatives, which areasigned the following features: `Case=LocPunc` (punctual locative), `CASE=LocDif` (diffuse locative).
* What has been traditionally called circunstantial mood or indicative II in some Tupí-Guaraní languages referes to the nominalization of a predicate and the fronting of an adverbial expression. The nominalized form of the verb takes `Nomz=Circ` as feature and value.


### Tags

This is an overview only. For more detailed discussion and examples, see the list of [Czech POS tags](pos/index.html) and [Czech features](feat/index.html).

* Tupinambá uses 16 of the 17 universal POS categories. [ADJ](https://universaldependencies.org/u/pos/ADJ.html) is not used.
* The (de)verbal forms used, are: infinitive `Inf`, finite verb `Fin`, tagged, converb `Conv`, gerund `Ger`.



Mapping UPOS to XPOS Ka'apor

 UPOS | XPOS |
:----: | :------: |
 ADV   | adv      |
 INTJ  | intj     |
 NOUN  | n        |
 PROPN | ppn      |
 VERB  | v, vi, vt|
 ADP   | pp       |
 AUX   | aux      |
 CCONJ | cc       |
 DET   | det      |
 NUM   | num      |
 PART  | pcl      |
 PRON  | pro      |
 SCONJ | sc       |
 PUNCT | punct    |
 SYM   | sym      |
 X     | x        |

---
---

### Features

* The relational markers `Rel`, which indicate contiguity or non-contiguity between a head and its dependent, take respectively the following features: `Rel=Cont` and `Rel=NCont`. A third type or rletional indicates that a possessor is not present, neither contiguously or non-contiguously. This relational is tagged `Rel=Abs`, for relational absolute. 
* As a head marking language, Tupinambá cross-references arguments on the predicate, mostly when the object is third person: *a-s-epjak* 1.SG-3-see 'I see him'. The [PERSON](https://universaldependencies.org/u/feat/Person.html) feature in this case will be `Person=33`.
* The protmanteau markers, 1 -> 2 are asigned the [PERSON](https://universaldependencies.org/u/feat/Person.html) feature `Person12Sg` and `Person12Pl`.
* Tupinambá is reach in nominalizations. Lxical roots can be nominalized by suffixes that receive the following features: nominalizatin of circusntance `Nomzr=Circ` (*-saβ* 'thing, way of VERB'), deverbal passive nominalization `Nomzr=DevPass` (*-pɨr* 'one that is VERB').

---
**Instruction**: Describe inherent and inflectional features for major word classes (at least NOUN and VERB). Describe other noteworthy features. Include links to language-specific feature definitions if any.

---

## Syntax

*

---
**Instruction**: Give criteria for identifying core arguments (subjects and objects), and describe the range of copula constructions in nonverbal clauses. List all subtype relations used. Include links to language-specific relations definitions if any.

---

## Treebanks

There are [N](../treebanks/urb-comparison.html) Kaapor UD treebanks:

  * [Kaapor-A](../treebanks/urb_a/index.html)
  * [Kaapor-B](../treebanks/urb_b/index.html)

---
**Instruction**: Treebank-specific pages are generated automatically from the README file in the treebank repository and
from the data in the latest release. Link to the respective `*-index.html` page in the `treebanks` folder, using the language code
and the treebank code in the file name.

---
