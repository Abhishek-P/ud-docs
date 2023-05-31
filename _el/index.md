---
layout: base
title:  'Greek UD'
udver: '2'
---


# UD for Greek <span class="flagspan"><img class="flag" src="../../flags/svg/GR.svg" /></span>

There are two  UD treebanks of Modern Greek (EL): UD_Greek-GDT, UD_Greek-GUD. GDT and GUD have adopted the same tokenization and word segmentation guidelines. The two treebanks present notable differences as regards morphological annotation. The current UD documentation of EL morphology describes the choices adopted in GUD. The editing of the syntactic annotation in GUD is an ongoing project, so the current UD documentation of EL syntax describes the choices adopted in GDT only. 

## Tokenization and Word Segmentation-GDT,GUD

* Words are generally delimited by whitespace or punctuation. Exceptions:
* Numerical expressions are treated as single words and may contain punctuation or symbols:
  *15*, *2.200*, *0,05%*
* Dates are treated as nouns and in some cases may contain underscores:
  *1871/72*, *1943-44*, *2012-03-25*, *20ετίας*, *'44*, *11/24_Νοεμβρίου_1916*, *5ης_Νοεμβρίου_2001*
* Abbreviations are treated as single words and may contain punctuation: *ΕΕ*, *χλμ.*, *π.Χ.*
* There is one group of contractions that are treated as multi-word tokens and are segmented to individual syntactic words, namely combinations of the preposition *σε* and types of the definite article: *στον = σ + τον* “in/to/on the”.



## Morphology-GDT

### PoS-GDT

* GDT uses 16 universal POS categories, including particles ([PART]()). No interjections ([INTJ]()) exist in the current dataset.
* Words tagged [PART]() are the negative particles *δεν* and *μην*.
* The current set of auxiliary words ([AUX]()) include:
  * the copula *είμαι* (be)
  * the auxiliary verb *έχω* (have), which combines with the infinitive to form perfect tenses
  * the impersonal verb *πρέπει* (must)
  * the indeclinable future marker *θα*
  * the indeclinable subjunctive particle *να*
  * the indeclinable subjunctive particle *ας*
*  The tag [DET]() is used for the definite and the indefinite article. The tag [PRON]() is used for pronouns occurring as the head of a noun phrase, for pronouns preceding or following their nominal head with which they agree in gender, number and case,  or for possessives in the genitive following their head
*  Past participles used adjectivally are  mostly tagged  [ADJ]()

### Features-GDT

* Nouns have inherent [Gender]() and inflect for [Number]() (singular or plural), and [Case]() (nominative, genitive, accusative and vocative). Remnants of the dative case also exist in set phrases.
* Finite verbs of the [Ind]() mood have one of two values of [Voice](): `Act` and `Pass`; one of two values of [Tense](): `Past` and `Pres`; one of two values of [Number](): `Sing` and `Plur`; and one of three values of [Person](): `1`, `2` and `3`.   Finite verbs of the [Imp]() mood have only `2`nd [Person]().  The [Aspect]() feature has `Imp` and `Perf` values. There are three types of nonfinite forms: infinitives used to form perfect tenses, passive voice `-μένος` participles, and active voice `-[ώο]ντας` converbs.
* Adjectives agree with nouns (in both attributive and predicate position) with respect to the [Gender](), [Number]() and [Case]() features.
* Pronouns inflect for [Gender](), [Number](), [Case]() like nouns and adjectives.
* [Degree]() applies to adjectives ([ADJ]()) and adverbs ([ADV]()) and has one of three possible values: `Pos`, `Cmp`, `Sup`


## Morphology-GUD
Major differences at  PoS level between GDT and GUD are the treatement of  *να* and the system of determiners [DET]() as GUD adheres to UD.v2 morphological guidelines quite closely. Other differences also exist, e.g., the treatment of participles, *που*, etc.

### PoS-GUD


* GUD uses 17 universal POS categories. [INT]() is used for words such as *αμήν* "amen", *ναι* / *ne* "yes",  [INTJ]() with [Polarity=Pos](), *όχι* /*ochi* "no/not", [INTJ]() with [Polarity=Neg](), *καλημέρα* / *kalimera* "goodmorning", *καληνύχτα* / *kalinichta* "goodnight", etc.
* The tag [ADJ]() is assigned to:
  *  ordinary adjectives and ordinal numerals
  *    nationalities, , e.g., _Έλληνας_ / *Elinas*  "Greek"
  *  professions, e.g.,  *αστυνομικός* / astinomikos "policeman"
  * some Ancient Greek adverbs that are still in use in EL: *νυν* / *nin* "current", *τέως* / *teos* "past" 
  *  pieces of phrases received from older forms of the language: *καθωσπρέπει* / *kathosprepi* "proper" (originally two words written as one word nowadays).
  *  formations in *-μένος* that are not related to a verb in use in EL, e.g. *χιλιοτραγουδισμένος* / chiliotragoudismenos “storied”, *ξακουσμένος* / ksakousmenos “famous”, etc; these are assigned the  tag ADJ.  
* [AUX]() is not specified for the feature [Aspect](). As auxiliary words ([AUX]()) are considered:
  * *είμαι* "be" when: 
    * when a participle depends on it; the participle is assigned the tag [VERB]() and bears values for the feature [Voice](). 
    * when it is used to assign a property to an entity; typically, properties are denoted with adjectives, e.g., *είμαι ψηλός* "I am tall". 
Otherwise,  *είμαι* "to be"  is assigned the tag [VERB](), e.g., *είμαι στο σπίτι μου* "I am at my place". 
  *  *έχω* "have", in verb complexes, both active and passive ones; when *έχω* is used as a content verb it is assigned the tag [VERB]().
  * the indeclinable *θα*, in verb complexes, both active and passive ones.
  * the indeclinable *να* when:	
	- it introduces the verb of a main clause, e.g., *Να*.[AUX]()  *έρθεις*.[root]() *γρήγορα* "Come early."
	- it  occurs in relative clauses after the relativisers *που*, *o οποίος*, e.g.,  *Στη συνέχεια γράψτε μια συνάρτηση η οποία*. [PRON]() *να*.[AUX]()   _τυπώνει αυτά τα δεδομένα_ "Next, write a function that.[PRON]() will print the data." 
* As coordinating conjunctions [CCONJ]() are considered words like _και_ "and", _ή_ "or" or _αλλά_ "but". In correlative (paired) coordinating conjuctions such as _είτε - είτε_ or _ή - ή_ "either - or", both words are annotated as [CCONJ](). 
*  The tag  [DET]() is assigned to the two articles, certain traditional adjectives (and their comparatives) and to a set of pronouns, namely: definite and indefinite article, adjectives denoting quantities and their comparatives, demonstrative and indefinite pronouns. [DET]() is also assigned to interrogative and relative pronouns when they are followed by a noun.
* The negative particles *δεν*, *μην* and  *όχι* (the last one, is considered a particle only in limited contexts) are tagged as [PART](). Οther words assigned the tag [PART]() are *ας*, *καν*, *μπας (και)*,	*μην*, *να* (limited contexts),	 *πάρα*, *μακάρι*.
*   The tag [PRON]() is used for pronouns occurring as the head of a noun phrase, for pronouns preceding or following their nominal head with which they agree in gender, number and case,  or for possessives in the genitive following their head. The indeclinable word *που*  is assigned the tag [PRON]() if it refers to a noun, otherwise it is considered a CCONJ or an SCONJ.
*  The tag [SCONJ]() is assigned to the indeclinable words *να* and  *που* as described below:
	*  *να* is mainly used as a subordinating conjunction and is assigned the tag [SCONJ](); the clauses it introduces function as	verb arguments, clausal nominal modifiers, goal denoting clauses where *να* or  *για να* introduce the clause, and adverbial modifiers where *να* co-occurs with other uniflected words, e.g.,  *αντί να, δίχως να, που να, πριν να, σαν να, χωρίς να, ώσπου να,  ώστε να*. 
	*   *που* is assigned the tag [SCONJ]() when it introduces a  complement of saying or sense verbs  (diagnostic: it can be replaced with the word *ότι* with somewhat different implications), a temporal clause together with the [ADP]() *μετά*  (diagnostic: the multiword conjunction _μετά που_ can be replaced with the [ADP]() _αφού_) or an etiological clause  (diagnostic:  it can be replaced with the word *γιατί*)."
* The tag [VERB]() is assigned to:
   *  verbs, including  *είμαι* "be" and *έχω* "have" when they are used as content verbs (not auxiliaries)  
   *  participles ending in *-μένος* and *-θείς*. Ηowever, formations in *-μένος* not related to a verb in use, e.g., *χιλιοτραγουδισμένος* / *chiliotragoudismenos* “storied”, *ξακουσμένος* / _ksakousmenos_ “famous”, are assigned the  tag [ADJ]().
   *  non-inflecting verb forms ending in *-όντας, -ώντας* (adverbial participles) that share properties and usage of adverbs and verbs  

### Features-GUD

* Adjectives agree with nouns (in both attributive and predicate position) with respect to the [Gender](), [Number]() and [Case]() features.
* Case is an inflectional feature of [nouns](el-pos/NOUN), [proper nouns](el-pos/PROPN), [adjectives](el-pos/ADJ), [determiners](el-pos/DET), [pronouns](el-pos/PRON),  [numerals ](el-pos/NUM) and [verbs](el-pos/VERB) (participles). ΕL morphology distinguishes four cases:
`Nom`, `Gen`,  `Acc`, `Voc`. Dative was used in older forms of the Greek language; in EL it  occurs only in fixed expressions inherited from older Creek, e.g. γαία _πυρί_ μιχθήτω 'let earth be mixed with fire". 
* [Degree]() applies to nouns ([NOUN]()), adjectives ([ADJ]()) and adverbs ([ADV]()):
   *  _Degree of comparison_ is an inflectional feature of 
[adjectives](el-pos/ADJ) and some [adverbs](el-pos/ADV). EL marks morphologically the positive, comparative and absolute superlative degree  while the superlative degree of adjectives is composite (definite article + comparative degree). 
   *  EL expresses _degree modification_ of nouns, adjectives, past participles and adverbs with a set of prefixes and suffixes (and a set of syntactic means). All affixation cases are assigned the feature [el-DegreeMod]()  with one of the two available values, [Dim]() or [Aug](). 
*  Gender is a lexical feature of [nouns](el-pos/NOUN), [proper nouns](el-pos/PROPN), [adjectives](el-pos/ADJ), [determiners](el-pos/DET), [pronouns](el-pos/PRON),  [numerals ](el-pos/NUM) and [verbs](el-pos/VERB)(participles). There are three values of gender: masculine, feminine, and neuter.  EL gender is grammatical  although, in the case of annimates, it is more likely that  grammatical gender denotes the sex. 
* Nouns have lexical [Gender]()  and inflect for [Number]() (singular or plural), and [Case]().
* Pronouns inflect for [Gender](), [Number](), [Case]() like nouns and adjectives.
* The feature [PronType]() applies to EL pronouns, determiners and adverbs. The following values have been used: [Art](): article, [Dem](): demonstrative pronoun, determiner or adverb, [Emp](): emphatic determiner, [Ind](): indefinite pronoun, determiner or adverb, [Int](): interrogative pronoun, determiner or adverb, [Neg](): negative pronoun, determiner or adverb, [Prs](): personal pronoun or determiner, [Rel](): relative pronoun, determiner or adverb, [Tot](): total (collective) pronoun, determiner or adverb.
* Finite verbs of the [Ind]() mood have one of two values of [Voice](): `Act` and `Pass`; one of two values of [Tense](): `Past` and `Pres`; one of two values of [Number](): `Sing` and `Plur`; and one of three values of [Person](): `1`, `2` and `3`.   Finite verbs of the [Imp]() mood have only `2`nd [Person]().  The [Aspect]() feature has `Imp` and `Perf` values. There are three types of nonfinite forms: infinitives, passive voice  participles ending in `-μένος`, and active voice  converbs ending in `-[ώ/ο]ντας`. The so-called infinitives are received from the perfective form of the verb and are used with the auxiliary _έχω_ "have" to form certain composite tenses. It has no other usage in the language and it is not used as the lemma form (as infinitives are traditionally used).
* Modern Greek verb tenses are formed periphrastically mainly (composite tenses). In the GUD treebanks there are three stand-alone verb forms, i.e., not supported by auxiliaries, that bear Tense: one that is classified  as "Pres" but it is also used in the so-called Future tense formations, and two forms marked for "Past" that differ in terms of aspect (perfect, imperfect). There is no verb form marked for Future; instead, there is the particle _θα_ that is considered an auxiliary in the Greek UD treebanks and is assigned the tense feature "Fut" (but it would be probably more accurate to consider it a marker of potentiality and drop the feature 'Fut' from the Greek UD treebanks). 

<b>All verb and auxiliary forms in composite tenses preserve their tense and mood features, if they are defined for them.</b>

## Syntax-GDT

* Nominal subjects ([nsubj]()) are in the nominative case, without adpositions.
* Objects occur in the accusative case (direct objects) or in the genitive (indirect objects). 
* All prepositional objects are currently labeled with the oblique relation.
* Case marking of subjects and objects allows all possible word order variations. However, when introducing new information the most frequent word orders are SVO and VSO. OVS sentences occur when the object is topicalized and they often involve a combination of an object and an object clitic.
* The copula verb *είμαι* (be) is used in equational, attributional, locative, possessive and benefactory nonverbal clauses. Different verbs like *υπάρχω* are typically used in existential clauses.
* The following subtypes are used in Greek:
  * [acl:relcl]() for relative clauses
  * [csubj:pass]() for clausal subjects of passive verbs
  * [nsubj:pass]() for nominal subjects of passive verbs
  * [obl:agent]() for agents of passive verbs


## Syntax-GUD

Ongoing work.

## Treebanks

There are two Modern Greed UD treebanks: UD_Greek-GDT and UD_Greek-GUD.

  * [Greek-GDT](../treebanks/el_gdt/index.html)
  * Greek-GUD will be uploaded soon. 
