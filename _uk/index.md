---
layout: base
title:  'Ukrainian UD'
udver: '2'
---

# UD for Ukrainian <span class="flagspan"><img class="flag" src="../../flags/svg/UA.svg" /></span>

## Tokenization and Word Segmentation

* In general, words are delimited by whitespace characters. Description of exceptions follows.
* According to typographical rules, many punctuation marks are attached to a neighboring word. We always tokenize them as separate tokens (words); that holds even for hyphenated compounds such as _українсько-чеський&nbsp;_ “Ukrainian-Czech” (three tokens) and for abbreviations such as _[і] т.i.&nbsp;_ “and so on” (four tokens).
* A whitespace separating digits in a large number is not treated as a word separator. For example, _1&nbsp;000&nbsp;000_ (“1,000,000” by English rules) is one token.
* There are two closed classes of contractions that are treated as multi-word tokens and segmented to individual syntactic words:
  1. Pronouns like _ні́де_ (_немає де_) “there is nowhere to”, _ні́кому_ (_немає кому_) “there is no one to” (not to confuse with _ніде́&nbsp;_ “nowhere”, _ніко́му&nbsp;_ “to no one”; notice the accent).
  2. Nouns fused with a numeral _пів&nbsp;_ “half of”: _півметра&nbsp;_ “half a meter”. Such spelling is now deprecated in standard Ukrainian and it is now correct to use a whitespace: _пів метра_.

## Morphology

### Tags

This is an overview only. For more detailed discussion and examples, see the list of [Ukrainian POS tags](pos/index.html)
and [Ukrainian features](feat/index.html).

* Ukrainian uses all 17 universal POS categories, including particles ([PART]()).
  At present, more than 100 word types are tagged [PART]().
* The pronoun ([PRON]()) vs. determiner ([DET]()) distinction is based on word lists because the traditional grammar does not define determiners.
  In general, words that inflect for gender, to be able to agree with a modified noun, are tagged [DET](), even if they act independently in a given sentence; that includes possessives.
  Pronominal quantifiers (which the traditional grammar includes in numerals) are [DET]() as well.
* Ukrainian has just one auxiliary verb ([AUX]()), _бути_ (“to be”) with its derivative _бувати_.
* In other words, _бути_ and _бувати_ are the only lemmas that occur with the [AUX]() tag.
  They may still occur also as normal [VERB]() if they are used in purely existential sentences
  (i.e. such that don’t even indicate location because if they do, then _бути_ is treated as copula).
  * Note that this may be changed in future. Existential sentences could be treated as elliptical versions of locational sentences; then the verb would be the root, but it could still be tagged as `AUX` and the `AUX`-`VERB` distinction could be anchored in the lexicon.
* Verbs with modal meaning are not considered auxiliary in Ukrainian.
* There are five main (de)verbal forms, distinguished by the UPOS tag and the value of the [VerbForm]() feature:
  * Infinitive `Inf`, tagged [VERB]() or [AUX]().
  * Finite verb `Fin`, tagged [VERB]() or [AUX]().
  * Participle `Part`, tagged [VERB]() or [AUX]() (the so-called l-participle) or [ADJ]() (all other participle types).
  * Converb `Conv`, tagged [VERB]() or [AUX]().
  <!-- * Verbal noun `Vnoun`, tagged [NOUN](). -->

### Nominal Features

* Nominal words ([NOUN](), [PROPN]() and [PRON]()) have an inherent [Gender]() feature with one of three values: `Masc`, `Fem` or `Neut`.
  In some cases the masculine gender is further subclassified by the [Animacy]() values `Anim` and `Inan`.
  Feminine and neuter nominals do not distinguish animacy grammatically.
  * The following parts of speech inflect for `Gender` and `Animacy` because they must agree with nouns: [ADJ](), [DET](), [NUM](),
    [VERB](), [AUX](). For verbs (including auxiliaries), only participles and converbs inflect for gender. Finite verbs don’t.
* The two main values of the [Number]() feature are `Sing` and `Plur`. The following parts of speech inflect for number:
  [NOUN](), [PROPN](), [PRON](), [ADJ](), [DET](), [VERB](), [AUX]() (finite, participles and converbs), marginally [NUM]().
  * Remnants of the `Dual` number occur only in the instrumental [Case]() of a few nouns and all the agreeing parts of speech.
  * Selected nouns are plurale tantum (`Ptan`) or singulare tantum (`Coll`). These two values are lexical and cannot be used with
    the agreeing adjectives, determiners or verbs. They also never occur with pronouns.
* [Case]() has 7 possible values: `Nom`, `Gen`, `Dat`, `Acc`, `Voc`, `Loc`, `Ins`.
  It occurs with the nominal words, i.e., [NOUN](), [PROPN](), [PRON](), [ADJ](), [DET](), [NUM]().
  It can occur with participles but only with those tagged as `ADJ`. It never occurs with verbs.
  * The `Case` feature also occurs with prepositions ([ADP]()). Here it is a lexical feature. Prepositions do not inflect for case
    but they subcategorize for the case of their noun phrase.

### Verbal Features

* Verbs have a lexical [Aspect](), either imperfective (`Imp`) or perfective (`Perf`).
  * The `Aspect` feature should be also used with the corresponding derived nouns and adjectives (participles), if they have the `VerbForm` feature.
* Finite verbs always have one of three values of [Mood](): `Ind`, `Imp`. Ukrainian conditional is formed periphrastically using the past participle of the content verb and a special form of the [auxiliary verb](uk-pos/AUX)
_б._
* Verbs in the indicative mood always have one of three values of [Tense](): `Past`, `Pres` or `Fut`.
  * Imperative forms do not have the `Tense` feature.
* There are two values of the [Voice]() feature: `Act` and `Pass`. Only the passive participle has `Voice=Pass`. All other verb forms have `Voice=Act`.

<!-- ### Pronouns, Determiners, Quantifiers

* [PronType]() is used with pronouns ([PRON]()), determiners ([DET]()) and adverbs ([ADV]()).
* [NumType]() is used with numerals ([NUM]()), adjectives ([ADJ]()), determiners ([DET]()) and adverbs ([ADV]()).
* The [Poss]() feature marks possessive personal determiners (e.g. _мій&nbsp;_ “my”),
  possessive interrogative, relative, indefinite or negative determiners (e.g. _чий&nbsp;_ “whose”),
  and can be used with possessive adjectives (e.g. _мамин&nbsp;_ “mother’s”).
* The [Reflex]() feature marks reflexive pronouns _(se, si)_ and determiners _(svůj)_.
  In Ukrainian it is always used together with `PronType=Prs`.
* [Person]() is a lexical feature of personal pronouns ([PRON]()) and has three values, `1`, `2` and `3`.
  With personal possessive determiners ([DET]()), the feature actually encodes the person of the possessor.
  Person is not marked on other types of pronouns and on nouns, although they can be almost always interpreted as the 3rd person.
  * As a cross-reference to subject, person is also marked on finite verbs ([VERB](), [AUX]()).
* There are two [layered features](../../u/overview/feat-layers.html), [Gender[psor]]() and [Number[psor]]().
  They appear with certain possessive adjectives and determiners and encode the lexical gender/number of the possessor.
  The extra layer is needed to distinguish these lexical features from the inflectional gender and number that mark agreement with the modified (possessed) noun. -->

<!-- ### Other Features

* Besides the layered features listed above, there are several other language-specific features:
  * [NameType]()
  * [AdpType]()
  * [ConjType]()
  * [Hyph]()
  * [Style]()
  * [PrepCase]()
  * [Variant]() ... distinguishes short and long forms of adjectives, a Slavic-wide phenomenon
* The following universal features are not used in Ukrainian: [Definite](), [Evident](), [Polite](). -->

## Syntax

This is an overview only. For more detailed discussion and examples, see the list of [Ukrainian relations](dep/index.html).

### Core Arguments, Oblique Arguments and Adjuncts

* Nominal subject ([nsubj]()) is a noun phrase in the nominative case, without preposition.
  * If the noun phrase is quantified, it may be in the genitive, which is required by the quantifier.
    If this is the case, then the quantifier is attached using a special relation, either [nummod:gov]() or [det:numgov]().
  * An infinitive verb may serve as the subject and is labeled as clausal subject, [csubj]().
    On the other hand, verbal nouns as subjects are just `nsubj`.
  * A finite subordinate clause may serve as the subject and is labeled `csubj`.
* Objects defined in the Ukrainian grammar may be bare noun phrases in accusative, dative, genitive or instrumental, or prepositional phrases in accusative, dative, genitive, locative or instrumental.
  * Bare accusative, dative, genitive and instrumental objects are considered core.
  * All prepositional objects are considered oblique.
  * Accusative objects of some verbs alternate with finite clausal complements, which are labeled [ccomp]().
  * If a verb subcategorizes for the infinitive (e.g. modal verbs or verbs of control), the infinitival complement is labeled [xcomp]().
  * If a verb subcategorizes for two core objects, one of them accusative (or `ccomp`) and the other non-accusative, then the non-accusative object is labeled [iobj](). Core nominal objects in other situations are labeled just [obj]().
* Adjuncts (a.k.a adverbial modifiers realized as noun phrases) are usually prepositional phrases, but they can be bare noun phrases as well. They are labeled [obl]():
  * Temporal modifiers realized as accusative noun phrases: _повернусь днями&nbsp;_ “I will come back next days.”
  <!-- todo: -->
  <!-- * Dative noun phrases with benefactive or possessive role (i.e. if the verb does not subcategorize for a single dative object and if it is not a verb of giving (or similar), where the dative could be interpreted as the recipient.
    Example: _приготувала йому обід&nbsp;_ “she cooked (for) him a lunch.” -->
  * Instrumental noun phrases expressing the way or means with which something was done.
    Example: _побив пса палкою&nbsp;_ “he beat up the dog with a stick.”
  * All prepositional phrases that are not prepositional objects (i.e., their role and form is not defined lexically by the predicate) are adjuncts.

### Non-verbal Clauses

* The copula verb _бути_ (be) is used in equational, attributional, locative, possessive and benefactory nonverbal clauses. Purely existential clauses (without indicating location) use _бути_ as well but it is treated as the head of the clause and tagged [VERB]().

### Relations Overview

* The following relation subtypes are used in Ukrainian:
  * [acl:adv]() adverbs acting as amod
  * [acl:relcl]() relative clauses
  * [advcl:pred]() `advcl` with secondary predication
  * [advcl:svc]() adverbial infinitive
  * [advmod:det]() adverbial modification by a determiner
  * [compound:svc]() 
  * [conj:svc]() coordination of serial verbs
  * [det:numgov]() pronominal quantifiers that are attached as children of the quantified noun but govern its case 
  * [det:nummod]() pronominal quantifiers in cases in which they do not govern the case of the quantified noun
  * [flat:abs]() clausal absolutive
  * [flat:foreign]() non-first words in foreign phrases
  * [flat:name]() human names
  * [flat:range]() numerical and temporal ranges
  * [flat:repeat]() repetitions
  * [flat:sibl]() 
  * [flat:title]() 
  * [nummod:gov]() cardinal numbers that are attached as children of the counted noun but govern its case
  * [parataxis:discourse]() clausal `discourse`
  * [parataxis:newsent]() connects sentences inside of a multi-sentence quote where it’s impossible to split the parent sentence
  * [parataxis:rel]() clauses relative to the whole parent sentence, that is, to the parent sentence predication itself
  * [vocative:cl]() clausal `vocative`
  * [xcomp:pred]() `xcomp` with secondary predication
* The following relation types are not used in Ukrainian at all:
  [clf]()


## Treebanks

Currently there is a single Ukrainian UD treebank:

  * [Ukrainian-IU](../treebanks/uk_iu/index.html)
