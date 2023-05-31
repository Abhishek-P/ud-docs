---
layout: base
title:  'Old East Slavic UD'
udver: '2'
---

# UD for Old East Slavic <span class="flagspan"><img class="flag" src="../../flags/svg/RU-IVAN.svg" /></span>

## Tokenization and Word Segmentation

* In general tokens are delimited by spaces.
* It should be noted that many of the texts are based on manuscripts in scripta continua, i.e. words are not separated by spaces. The spaces are therefore editorial. When texts are based on independent editions, the spacing may differ from our general tokenisation policy. This sometimes causes tokens with spaces.
* UD_Old_Russian_RNC, the manusctipt page boundary markers are preserved within the token just as they are marked in the publication, cf. _жень||{л._55}скую_ “feminime, page boundary, beginning of p. 55”. The normalized spelling (Norm=женьскую) is placed in the MISC field. Hyphen is considered either token separator or not depending the grammatical status of elements before and after the hyphen.
* Punctuation is not included in **UD_Old_East_Slavic-TOROT**.
* Punctuation is included in UD_Old_Russian_RNC.

## Morphology

### Tags
This is a brief overview of the use of POS tags in **UD_Old_East_Slavic-TOROT**:

* The POS category PART is not in use, instead we use ADV for particle-like items.
* DET is used for traditional demonstrative and indefinite pronouns. Possessive pronouns are tagged ADJ. All other pronouns are tagged PRON.
* Verbal forms, including participles, are tagged VERB or AUX. Only deverbal nouns with clearly nominal properties are tagged NOUN.
* Only _быти_ and _не быти_ (with incorporated negation) are analysed as auxiliaries and have the AUX tag.
* TOROT was originally tagged in the PROIEL dependency format, an overview of the tagset can be found here: https://proiel.github.io/handbook/developer/#the-proiel-xml-format

This is a brief overview of the use of POS tags in **UD_Old_East_Slavic-RNC**:

* The treebank uses all 17 universal POS categories.
* The DET category includes possessive (including reflexive and relative possessive), demonstrative, interrogative/relative, indefinite, negative, and universal (total) determiners that inflect for gender. The relative pronoun _который_ is tagged either PRON or DET depending its syntactic role.
* The verb forms, including participles, are tagged VERB or AUX. Verbal nouns with clearly nominal properties are tagged NOUN.
* Only _быти_ and conditional markers _бы_, _бъ_ are tagged AUX.
* RNC is tagged in parallel in native UD and RNC format, an overview of the tagset and cross-mapping can be found here: [https://github.com/olesar/UD_MidRussian](https://github.com/olesar/UD_MidRussian).

### Features
This is a brief overview of the features used in **UD_Old_East_Slavic-TOROT**:

* [VERB]() and [AUX]() can have the following features:
  * [Person]() (1, 2, 3)
  * [Number]() (Sing, Dual, Plur)
  * [Tense]() (Pres, Past, Fut)
  * [Aspect]() (Perf, Imp, Res)
  * [Mood]() (Ind, Imp)
  * [VerbForm]() (Fin, Inf, Part, Sup)
  * [Voice]() (Act, Pass)
* It should be noted that the Aspect feature is only used to distinguish the aorist (`Tense=Past|Aspect=Perf`) from the imperfect (`Tense=Past|Aspect=Imp`), and to distinguish the resultative l-participle from other participles (`VerbForm=Part|Aspect=Res`).
* Participles also have the features
  * [Gender]() (Fem, Masc, Neut)
  * [Case]() (Nom, Acc, Gen, Dat, Ins, Loc, Voc)
  * Strength (Strong, Weak). The latter feature separates short (nominal) forms (Strong) from long (pronominal) forms (Weak). As of release 2.8, `Strength=Strong` has been converted to `Variant=Short`, and `Strength=Weak` to nothing, to make the annotation compatible with other Slavic UD treebanks.
* Note that we do not recognise gerunds even for the latest texts, they are conservatively tagged at face value as short-form participles (`VerbForm=Part|Variant=Short`).

* [NOUN]() and [PROPN]() can have the following features (with the specifications above):
  * Case
  * Gender
  * Number
* Note that animate genitive-accusatives are annotated with Case=Gen. There is no Animacy feature.

* [ADJ]() can have the following features (with the specifications above):
  * Case
  * Gender
  * Number
  * Strength (deprecated, see above)
  * [Degree]() (Pos, Cmp, Sup)

This is a brief overview of the features used in **UD_Old_East_Slavic-RNC**:

* [VERB]() and [AUX]() can have the following features:
  * Person (1, 2, 3)
  * [Number]() (Sing, Dual, Plur)
  * Tense (Pres, Past, Fut)
  * Aspect (Perf, Imp)
  * Mood (Ind, Imp, Cnd)
  * [VerbForm]() (Fin, Inf, Sup, Conv, Part, PartRes)
  * Voice (Act, Pass, Mid)
  * Reflex (Yes)
  * Polarity (Neg)
  * Analyt (Yes)
* Participles also have the features
  * Gender (Fem, Masc, Neut)
  * Case (Nom, Acc, Gen, Dat, Ins, Loc)
  * [Variant]() (Short). The latter feature is applied to short forms; long forms are not marked explicitely. Variant=Short in UD-RNC corresponds directly to Strength=Weak in UD-TOROT
* Unlike in UD-Torot, l-participles are tagged [VerbForm]()=PartRes and distinguish Aspect (Perf, Imp), converbs are tagged [VerbForm]()=Conv in UD-RNC.
* At the moment, the Aspect and [Analyt]() features are tagged only in some parts of the treebank.

* [NOUN]() and [PROPN]() can have the following features:
  * [Number]() (Sing, Dual, Plur, Count)
  * Gender (Fem, Masc, Neut)
  * Case (Nom, Acc, Gen, Dat, Ins, Loc, Voc)
  * Animacy (Anim, Inan). The latter feature is only used to distinguish animate and inanimate accusative forms.

* [ADJ]() can have the following features (with the specifications above):
  * Case
  * Gender
  * Number
  * Variant
  * Degree (Pos, Cmp, Sup)
  * Poss (Yes)
  * Reflex (Yes)

* [DET]() can have the following features (with the specifications above):
  * Case
  * Gender
  * Number
  * Animacy
  * Variant
  * Poss
  * Reflex

* [PRON]() can have the following features: Case, Gender, Number, Animacy, Person, PronType, Poss, Reflex, Analyt (with the specifications above).

* [NUM]() can have the following features: Case, Animacy, NumForm; Gender, Number, and Degree (Cmp) are tagged on a few numerals.

* Other lexical features include:
  * Abbr (Yes)

* Language-specific features include:
  * [Analyt]() (Yes) is a marker of the analytic verb forms
  * [Variant]() distinguishes short and long forms of adjectives and participles.


## Syntax

* We accept nominative subjects (nsubj), as well as genitive subjects under negation. Clausal subjects are tagged csubj. Potential subjects in other cases (such as the dative) are tagged iobj.
* Objects of transitive verbs are tagged obj. Normally such objects are in the accusative, but they can also be in the genitive due to negation, partitive semantics or animacy. Supines also obligatorily take genitive objects, which are tagged obj if the verb is normally transitive. Arguments in other cases are tagged iobj. Prepositional arguments are tagged obl.
* The copula verb is _быти_. It is increasingly omitted in the present tense in the later texts.
* We use the following subtype relations: aux:pass, csubj:pass, flat:foreign, flat:name, nsubj:pass, obl:agent.

## Treebanks

There are [3](../treebanks/orv-comparison.html) Old East Slavic UD treebanks:

  * [Old East Slavic RNC](../treebanks/orv_rnc/index.html)
  * [Old East Slavic TOROT](../treebanks/orv_torot/index.html)
  * [Old East Slavic Ruthenian](../treebanks/orv_ruthenian/index.html)
