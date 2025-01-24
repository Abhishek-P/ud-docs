---
layout: base
title:  'Ancient Hebrew UD'
udver: '2'
---

# UD for Ancient Hebrew <span class="flagspan"><img class="flag" src="../../flags/svg/IL.svg" /></span>

## Tokenization and Word Segmentation

No tokens in the Ancient Hebrew treebank should contain whitespace. The following are made into separate tokens:

* Prepositions (ב, כ, ל, מ)
  * There is an exception for לאמר, which remains a single token when it serves as a subordinating conjunction introducing a direct quotation
* Possessive and object pronouns (ני, נו, ו, ם, ...)
  * The corresponding independent pronoun is used as the lemma
* Conjunction ו
* Definite determiner ה
  * This includes ה when it appears as demonstrative agreement on adjectives, participles, and demonstrative determiners
  * Since the text includes vowels diacritics, ה is included as a token even when it does not correspond to a full character in the consonantal text.

## Morphology

### Tags

All tags are used except `X` and `SYM`. `AUX` is used for the copula היה.

The positive and negative existentials ישׁ and אין are tagged [VERB]().

Participles are tagged either [VERB]() or [NOUN](). If they have arguments or obliques, they are tagged as [VERB](), but if they do not then they are tagged as [NOUN]() if they participate in nominal phrases.

### Features

The following universal features are in use:

* [Aspect](hbo-feat/Aspect): [AUX](hbo-pos/AUX), [VERB](hbo-pos/VERB)
* [Gender](hbo-feat/Gender): [ADJ](hbo-pos/ADJ), [AUX](hbo-pos/AUX), [NOUN](hbo-pos/NOUN), [PRON](hbo-pos/PRON), [VERB](hbo-pos/VERB)
* [Mood](hbo-feat/Mood): [VERB](hbo-pos/VERB)
* [Number](hbo-feat/Number): [NOUN](hbo-pos/NOUN), [PRON](hbo-pos/PRON), [ADJ](hbo-pos/ADJ), [VERB](hbo-pos/VERB)
* [Person](hbo-feat/Person): [AUX](hbo-pos/AUX), [VERB](hbo-pos/VERB)
* [Tense](hbo-feat/Tense): [VERB](hbo-pos/VERB)
* [VerbForm](hbo-feat/VerbForm): [NOUN](hbo-pos/NOUN), [VERB](hbo-pos/VERB)

The following language-specific features are in use:

* [HebBinyan](hbo-feat/HebBinyan): [VERB](hbo-pos/VERB) ([AUX](hbo-pos/AUX), [NOUN](hbo-pos/NOUN))

The following MISC features are present:

* `Gloss`
  * Currently taken from [the BHSA `gloss` feature](https://etcbc.github.io/bhsa/features/gloss/)
* `Ref`
  * Book abbreviations currently in use are `GEN` for Genesis and `RUTH` for Ruth
* `SpaceAfter=No`
* `Translit`
  * The value of this field follows the [Library of Congress romanization standard](https://www.loc.gov/catdir/cpso/romanization/hebrew.pdf)

## Syntax

The subtypes [compound:smixut](hbo-dep/compound-smixut), [nmod:poss](hbo-dep/nmod-poss), and [obl:npmod](hbo-dep/obl-npmod) are used. The relation `compound` is currently unused.

The relations `iobj`, and `clf` are unused.

The relations `list`, `goeswith`, `reparandum`, and `dep` are currently unused, but may be used in future.

## Treebanks

There is [1](../treebanks/hbo-comparison.html) Ancient Hebrew UD treebank:

  * [Ancient Hebrew-PTNK](../treebanks/hbo_ptnk/index.html)
