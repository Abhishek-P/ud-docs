---
layout: base
title:  'Tagalog UD'
udver: '2'
---

# UD for Tagalog <span class="flagspan"><img class="flag" src="../flags/svg/PH.svg" /></span>

## Tokenization and Word Segmentation

* Words are generally delimited by whitespace. Exceptions:
  * compound words separated by a hyphen are tokenized independently (e.g. *bukod*  + *-* + *tangi*) if each word can be taken as a separate semantic expression forming a whole
  * contractions are tokenized independently whenever possible (e.g. *iba* + *'t*)
  * occurrences of the linker *-ng* are annotated as multi-word tokens, (e.g. surface form: *maraming*, underlying words: *marami* + *-ng*)
* Words with spaces do not regularly occur in Tagalog.

## Morphology

### Tags

* Tagalog uses all the 17 universal POS tags.
  * The only word that is currently tagged as auxiliary ([AUX]()) is the negative imperative (prohibitive) marker _huwag_. There are no copulas.
* Several word types are classified as particles ([PART](https://universaldependencies.org/u/pos/PART.html)). These fall under two categories:
  * grammatical particles (the inversion marker *ay*; and relative or linking markers *na* and *-ng*)
  * lexical particles (the question marker *ba*, the negation marker *hindi*, fillers such as *e*, *o*, and *a*, and the honorific *po*)
* Quantifiers (including the pluralizer *mga* and indefinite quantifiers such as *marami* "many" and *ilan* "some") are classified as determiners ([DET](https://universaldependencies.org/u/pos/DET.html)). Possessive pronouns are classified under pronouns ([PRON](https://universaldependencies.org/u/pos/PRON.html)) since several identical word forms are also used to indicate the objective case.
* Like other Philippine-type languages, Tagalog employs nominal markers that have characteristics of both determiners (‘articles’) and prepositions (Himmelmann 2005, pages 145–147). Their functions include case marking, semantic role marking, topic and definiteness marking. There is no standard terminology in use for these words in the literature. Some authors classify them as prepositions (e.g., Schachter and Shopen 2007, page 35), some as articles or determiners (e.g., Dryer 2007, pages 94–95 and 121–122), and many authors avoid either of the terms and use the term ‘markers’ instead (e.g., Andrews 2007, page 203). Within the UD framework, we have to choose either the [ADP]() tag or the [DET]() tag and the corresponding dependency relations; the adposition analysis has been adopted. The markers include:
  * the topic nominative marker *ang*
  * the non-topic genitive marker *ng*
  * oblique markers such as dative *sa*, *mula sa*, *para sa*, *sa pamamamgitan ng*, etc.



### Nominal Features

* Nouns ([NOUN]()) and proper nouns ([PROPN]()) do not have [Number]() because plural, if overtly expressed, is signaled by the function word _mga_ or by reduplication. In the former case, the pluralizel _mga_ bears the feature `Number=Plur`. In case of reduplication, there are two tokens connected via [compound:redup]() and neither bears a `Number` feature.
* However, the [Number]() feature is marked for pronouns ([PRON]()), with three possible values: `Sing`, `Dual`, `Plur` (the dual is used only with one pronoun that refers to the speaker and the listener).
* Some nouns have an inherent [Gender]() with one of two values: `Masc`, `Fem`. This involves mostly person-denoting loanwords from Spanish and personal first names. Other nouns do not have the feature.
* [Case]() has 3 primary values: `Nom`, `Gen`, `Dat`. The case names are not without controversy, as some authors would argue for an ergative analysis of the Philippine languages (while others would either use the labels adopted here, or use `Acc` instead of `Gen`, or argue that the Philippine type is neither ergative-absolutive nor nominative-accusative).
  * The nominative case corresponds to the subject of a clause regardless of voice (like in many European languages).
  * The genitive case is used for non-subject core participants in a clause, and for modifiers of other nominals.
  * The dative case is oblique and may encompass various locative and directional meanings.
  * In full noun phrases, [Case]() is a lexical feature of the case-marking word or phrase, i.e., [ADP](). For case markers of obliques, more fine-grained values may be specified, e.g. `Loc` for locative *sa*, `Ben` for benefactive *para sa*, and `Ins` for instrumental *sa pamamagitan ng*. Note that there are also other prepositions which are not tagged with any [Case]() feature, although they are attached to a noun via the [case]() relation.
  * For pronouns ([PRON]()), [Case]() is their inflectional feature.

### Degree and Polarity

* [Degree]() applies to adjectives ([ADJ]()) and has one of two possible values: `Pos`, `Sup`.
  Note that the comparative is not formed morphologically.
* [Polarity]() has two values, `Pos` and `Neg`, and applies marginally to some existential verbs ([VERB]()),
  as well as to the negation particle _hindi_ and to the response interjections _oo_ and _hindi_.

### Verbal Features

* Verbs inflect for [Mood](), [Aspect]() (rather than [Tense]()) and [Voice]().
* The current data contain only verbs in the indicative mood (`Ind`).
* Aspect is perfective (`Perf`), imperfective (`Imp`), prospective (`Prosp`) and habitual (`Hab`).
* The Austronesian [Voice]() system is quite different from the active-passive opposition in Indo-European languages. The morphological voice of the verb “focuses” on one particular argument, which is annotated as subject. However, the voices are symmetric in the sense that focusing on the more patient-like argument (“passive” voice) does not transform a transitive clause into intransitive: the more agent-like argument, if present, is still a core argument. Moreover, it is possible to focus on arguments with other semantic roles as well. (Note that the “focus” of the verb on a particular semantic role should not be confused with pragmatic focus as in topic-focus articulation. The focused argument here is actually always the topic, not the focus of the utterance.) The following [Voice]() features are defined in the universal guidelines and apply to multiple Philippine languages. Not all verbs have forms for all the voices, though.
  * To reduce proliferation of feature values, the actor-focus voice uses the same label as the active voice in Indo-European languages, that is, `Voice=Act`.
  * Analogously, the undergoer-focus voice is conflated with Indo-European passive (`Voice=Pass`), although its grammatical behavior is different, as explained above.
  * The locative-focused voice (`Voice=Lfoc`) marks the location as the topic of the sentence.
  * The beneficiary-focused voice (`Voice=Bfoc`) marks the beneficiary as the topic of the sentence.

### Pronouns, Determiners, Quantifiers

* [PronType]() is used with pronouns ([PRON]()), determiners ([DET]()) and adverbs ([ADV]()).
* [NumType]() is used with cardinal numerals ([NUM]()).
* The [Reflex]() feature marks the reflexive pronoun _sarili_.
  It is always used together with `PronType=Prs`, although it does not bear the `Person` feature.
* [Person]() is a lexical feature of personal pronouns ([PRON]()) and has three values, `1`, `2` and `3`.
  Person is not marked on other types of pronouns and on nouns, although they can be almost always interpreted as the 3rd person.
* [Clusivity]() is used with 1st person plural (and dual) pronouns, and distinguishes inclusive _tayo_ “we” from exclusive _kami_ “we”.
* [Deixis]() is a lexical feature of demonstratives ([PRON](), [ADV]()) and has three values, `Prox`, `Med`, `Remt`.

### Other Features

* [PartType]() distinguishes various Tagalog-specific particles (besides the negative particle _hindi_, which is tagged with `Polarity=Neg`):
  * `Int` ... question particle _ano_ (tag question), _ba_ (yes-no question), _kaya_ (speculative yes-no question).
     The particle _ano_ is actually a conversion from the pronoun _ano_ “what”, but as a tag question marker it no longer is a pronoun and should be tagged [PART]() rather than [PRON]().
  * `Des` ... particle _sana_ “hopefully”
  * `Nfh` ... non-first-hand particle _daw_ “they say”
* [Link]()`=Yes` is currently used in the TRG treebank to signal the linker suffix.
  In the Ugnayan treebank, linkers are treated as separate syntactic words and the surface word is treated as a multi-word token.



## Syntax

### Core Arguments and Adjuncts

* Tagalog uses the [Austronesian voice system](https://en.wikipedia.org/wiki/Austronesian_alignment), a typologically unusual class of morphosyntactic alignment. In Tagalog, two core arguments (the topic argument and non-topic argument) are marked by prepositions, with their semantic roles determined by voice affixes on the verb. For the purposes of UD annotation, the following guidelines are used:
  * The topic/nominative argument (marked by the preposition *ang*) is attached to the predicate using the [nsubj](https://universaldependencies.org/u/dep/nsubj.html) relation.
  * The non-topic/genitive argument (marked by the preposition *ng*) is attached to the predicate using the [obj](https://universaldependencies.org/u/dep/obj.html) relation.
  * If there are two *ng*-arguments, the more agent-like argument is attached as [obj]() and the more patient-like argument is attached as [iobj]().
  * Other nominals are attached to the predicate using the [obl](https://universaldependencies.org/u/dep/obl.html) relation.

### Non-verbal Predicates

* Non-verbal clauses (such as noun, adverb, or adjective phrases) may be used as predicates in Tagalog. In these instances, the highest node of the clause is labeled as [root](https://universaldependencies.org/u/dep/root.html), and all other nodes typically connected to the root verb are instead connected to this node. There is no copula.

### Relations Overview

* The following relation subtypes are used in Tagalog:
  * [nsubj:pass]() for nominal subjects of verbs in patient-focused voice
  * [nsubj:lfoc]() for nominal subjects of verbs in location-focused voice
  * [nsubj:bfoc]() for nominal subjects of verbs in beneficiary-focused voice
  * [csubj:pass]() for clausal subjects of verbs in patient-focused voice
  * [csubj:lfoc]() for clausal subjects of verbs in location-focused voice
  * [csubj:bfoc]() for clausal subjects of verbs in beneficiary-focused voice
  * [obj:agent]() for agents (actors) of verbs in a non-actor-focused voice
  * [iobj:patient]() for patients (undergoers) of verbs in a voice where neither agent nor patient is the subject
  * [compound:redup]() for reduplicated nouns and adjectives (reduplication intensifies their meaning)
  * [nmod:poss]() for possessive relation between nominals
  * [acl:relcl]() for relative adnominal clauses
* The following relation types are not used in Tagalog at all:
  [clf](), [expl](), [dislocated]()



## Treebanks

There are [2](../treebanks/tl-comparison.html) Tagalog UD treebanks:

  * [Tagalog-TRG](../treebanks/tl_trg/index.html)
  * [Tagalog-Ugnayan](../treebanks/tl_ugnayan/index.html)



## References

* Avery D. Andrews (2007). The major functions of the noun phrase. In Timothy Shopen (ed.): Language Typology and Syntactic Description vol. I: Clause Structure. Cambridge University Press, Cambridge, UK.
* Matthew S. Dryer (2007). Word order. In Timothy Shopen (ed.): Language Typology and Syntactic Description vol. I: Clause Structure. Cambridge University Press, Cambridge, UK.
* Nikolaus P. Himmelmann (2005). Typological characteristics. In Alexander Adelaar and Nikolaus P. Himmelmann (eds.): The Austronesian Languages of Asia and Madagascar. Routledge, London and New York.
* Paul Schachter and Timothy Shopen (2007). Parts-of-speech systems. In Timothy Shopen (ed.): Language Typology and Syntactic Description vol. I: Clause Structure. Cambridge University Press, Cambridge, UK.
