---
layout: base
title:  'Chukchi UD'
udver: '2'
---

# UD for Chukchi <span class="flagspan"><img class="flag" src="../../flags/svg/RU-CHU.svg" /></span>

## Tokenisation and Word Segmentation

Tokens in the corpus are defined as sequences of non-whitespace or punctuation
characters separated by whitespace.

Underneath tokens are syntactic words. These are words which take part
in dependency relations.

A single token may be split into more than one word based on the following criteria:

* Emphatic clitics are split (notably *-ъм* and *-а*)
* In non-absolutive noun phrases, attributive modifiers (nouns, adjectives and numerals)
which have been incorporated are split. The splits are based on the provided gloss.

Incorporation into lexical verbs does not involve splitting in the basic representation,
sentences are annotated according to their surface syntax, e.g. a verb
with an incorporated object is annotated as intransitive following its
agreement morphology.

In the enhanced representation, the argument structure is recovered,
incorporated items are given nodes.

## Morphology

### Tags

* [ADJ]() [ADP]() [ADV]() [AUX]() [CCONJ]() [DET]()? [INTJ]() [NOUN]() [NUM]() [PART]() [PRON]() [PROPN]() [PUNCT]() [SCONJ]()? [VERB]() [X]()

The following are described by Dunn as particles, but are annotated here as `AUX`
because they provide the clause with tense-aspect-modality features.

* *ӄырым*:
* *ванэван* (also *ванэ*):

The following are copulae:

* *итык*:
* *вак*:

### Features

## Syntax

* Core arguments are marked on the verb. Subjects of intransitive verbs have agreement markers with `subj`, e.g. `Person[subj]=1`. Subjects of transitive verbs have agreement markers with `agent`, e.g. `Person[agent]=1`. Objects are marked with `obj`, e.g. `Person[obj]=3`.

The following relation subtypes are used in the Chukchi data:

* [acl:attr]() Adnominal clause with attributive morphology
* [acl:relat]() Adnominal clause with *relational* morphology
* [advmod:emph]() Used for discourse "particles" such as *-ым* and *-а/-э*
* [aux:neg]() Negative auxiliary
* [flat:foreign]() Used for chunks of text that are in Russian.
* [flat:name]() Proper noun chunks without internal structure.
* [nmod:attr]() Nominal modifier of a noun phrase with attributive morphology
* [nmod:poss]() Nominal modifier of a noun phrase with possessive morphology
* [nmod:relat]() A noun phrase modifying another noun phrase with *relational* meaning, see Dunn (1999: §8.7)
* [parataxis:rep]() Parataxis where the "dependent" is reported speech.

---

## Treebanks

There is 1 Chukchi UD treebank:

  * [Chukchi-HSE](../treebanks/ckt_hse/index.html)
