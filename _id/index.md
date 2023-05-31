---
layout: base
title:  'Indonesian UD'
udver: '2'
---

# UD for Indonesian <span class="flagspan"><img class="flag" src="../../flags/svg/ID.svg" /></span>

## Tokenization and Word Segmentation

* In general, words are delimited by whitespace characters. Special treatments are given to multiword tokens and punctuations.

* Special treatments of multiword tokens:
  * Multiword tokens that ended with particles _-lah/-kah/-tah/-pun_ are split into two tokens. These particles are usually used to emphasize the word before them. Particles of -lah/-kah/-tah are clitics, while particle pun can be written as clitic or a single token. The examples of how to tokenize these clitic particles are as follows:
    * _baca**lah**_ is split into _baca_ "read" and _**lah**_
    * _dia**kah**_ is split into _dia_ "he/she" and _**kah**_
    * _apa**tah**_ is split into _apa_ "what" and _**tah**_
    * _walau**pun**_ is split into _walau_ "although" and _**pun**_
    * The particle _kah_ marks yes-no questions and its position may emphasize the previous word as the focus of the question. The word _apa_ "what", when placed at the beginning of a sentence, also functions as a question particle, and it may be optionally strengthened by _kah_, resulting in _apakah_, as in _Apa(kah) dia guru?_ "Is she a teacher?" However, _apa_ is also used as an interrogative pronoun, even sentence-initially, as in _Apa pendapatmu?_ "What do you think?" Finally, _kah_ can be also added to interrogative words (_apa_ "what", _siapa_ "who", _di mana_ "where", _kapan_ "when", _bagaimana_ "how") in open questions; when _-kah_ is added, the tone becomes more polite.

  * Multiword tokens that contain clitics of _-ku_ "me/my", _-mu_ "you/your", _-nya_ "he/him/she/her/it" are split into two tokens, with exceptions for certain words ending with _-nya_.
    * Words ending with _-nya_ where _-nya- itself serves as  a pronoun or determiner are split into two tokens. For example:
      * Word _-nya_ as pronoun, as in _mencintai**nya**_ "love **him/her/it**", this token is split into _mencintai_ "love" and _**nya**_ "him/her/it".
      * Word _-nya_ as posessive pronoun, as in _buku**nya**_ "**his/her/its** book", this token is split into _buku_ "book" and _**nya**_ "his/her/its".
      * Word _-nya_ as determiner in predicate nominalisation case, as in _meningkat**nya**_ "**the** increase", this token is split into _meningkat_ "increase" and _**nya**_ "the".

    * Words ending with _-nya_ that functions as adverbs, adjectives or auxiliary are **not** split. For example:
      * adverbs ended with _-nya_: _khusus**nya**_ "especially", _awal**nya**_ "initially", _akhir**nya**_ "finally"
      * adjectives ended with _-nya_: _sebelum**nya**_ "previous", _sesudah**nya**_ "next", _berikutnya_ "next"
      * auxiliary ended with _-nya_: _seharus**nya**/sebaik**nya**_ "shall/should"

* Special treatments for punctuations. All punctuation symbols are separated from the words, except in two cases:
  * Hyphen in reduplicated words. Indonesian has many reduplicated words as nouns (both singular and plural), verbs, adjectives, adverbs, and so on. These reduplicated words are not split and remain one token. The examples of reduplicated words are:
    * Singular noun: _mata-mata_ "spy"
    * Plural noun: _anak-anak_ "children", from _anak_ "child"
    * Verb: _merobek-robek_ "shredding"
    * Adjective: _hiruk-pikuk_ "noisy"
    * Adverb: _terus-menerus_ "continuously"
  * For abbreviations. All abbreviations such as Mr., M.Sc. Tn., are not split and remain one token.

## Morphology

### Tags

* We refer to [KBBI](https://kbbi.kemdikbud.go.id/) (Kamus Besar Bahasa Indonesia/Indonesian Great Dictionary) as the reference dictionary. However, since this dictionary only defines 7 word classes: noun, verb, adjective, adverb, pronoun, particle and number, we need to make adjustments so that the tags conform to UD v2.
* Indonesian UD treebanks use all 17 universal POS categories.
* [PART]() is used for:
  * negation words: _tidak/tak/bukan_ "no/not", _belum_ "not yet", _jangan_ "don't + VERB"
  * particles of _-lah, -kah, -tah, pun_, that have been discussed in the previous section.
* The auxiliary ([AUX]()) vs. [VERB]() distinction is based on examples for English treebank, since initially there is no AUX type in KBBI. We defined 14 Indonesian words as AUX as follows:
  * _adalah_ and _ialah_ “be” serve as copulas.
  * Tenses-related AUX:
    * _akan_ “will/would” for the future tense.
    * _sedang/tengah_ “be” for the present tense.
    * _telah/sudah_ “have/has/had” for the past tense.
  * Modal-related AUX:
    * _harus/mesti/wajib_ as the equivalents of modal “must”.
    * _sebaiknya/seharusnya_ as the equivalents of modal 'shall/should'.
    * _bisa/dapat/sanggup/mampu_ as the equivalents of modal “can/could”.
    * _boleh_ as the equivalent of modal “may”.
    * _mungkin_ as the equivalent of modal “might”.
* The pronoun ([PRON]()) vs. determiner ([DET]()) distinction is also based on examples for English treebank, since DET word class also is not defined in KBBI.
  * The following word types are tagged as PRON:
    * personal pronouns, such as _saya/aku/ku_ "I", _kamu/mu/anda_ "you", _dia/ia/nya_ "he/she/it/him/her/its", _kami/kita_ "we/us/our", _mereka_ "they/them/their"
    * interrogative pronouns, _apa_ "what", _siapa_ "who" as in _**Apa** yang kamu inginkan?_ "**What** do you want?"
    * relative pronouns: _apa_ "what", _siapa_ "who" as in _Saya tahu **siapa** yang kamu maksud._ "I know **who** you mean"
    * indefinite pronouns: _seseorang_ "seomeone/somebody", _sesuatu_ "something"
    * total pronouns, such as _semua_ "all" as in _**Semua** kecuali bukumu_ "**All** except your books".
    * demonstrative pronouns: _ini_ "this" as in _**Ini** bukan salahmu._ "**This** is not your fault".
  * The following word types are tagged as DET:
    * demonstrative determiners: _ini_ "this" as in _Kota **ini** sangat indah_ "**This** city is beautiful"
    * pronominal numerals: _beberapa, berbagai, para_ "some/many", _semua_ "all" as in _**semua** siswa_ "**all** students"
* Indonesian has the following coordinating conjunction words ([CCONJ]()):
  * _dan, serta, maupun_ as the equivalents of "and" in English
  * _atau_ "or"
  * _tapi, tetapi, namun, melainkan_ as the equivalents of "but" in English
* Clauses can be **nominalized** by attaching the clitic _-nya_ to the predicate. In the annotation, the clitic is analyzed as a separate syntactic word, functioning as a determiner. However, the predicate keeps the [VERB]() tag, so there may be a verb with a determiner attached to it.
  * _meningkat_ "to increase" is a verb
  * _meningkatnya_ "the increase" is a nominalized form; however, since _-nya_ is also used with regular nouns and functions like a definite article, _meningkatnya_ is treated as a multi-word token _meningkat+nya_, where _nya_ is attached as a [det]() to the verb _meningkat_
  * Since _meningkat_ stays tagged as a verb, it will attach to its parent as a clause rather than a nominal. So if it is a subject of another clause, it will be [csubj]() rather than [nsubj]().

### Features

* We propose the use of 15 of 24 features defined in UD v2 that are relevant to Indonesian grammar:
  * [Abbr](), with one possible value: `Yes`. This feature can be applied to all UPOS categories, except [PUNCT]() and [SYM]().

  * [Clusivity](), applies to [PRON]() with two possible values: `Ex` and `In`.
    1. `Clusivity=Ex` for _kami_ "we/our"
    2. `Clusivity=In` for _kita_ "we/our"

  * [Definite](), applies to [DET]() with two values: `Def` and `Ind`.
  
  * [Degree](), applies to [ADJ]() with one possible value: `Sup`.
    * `Degree=Sup` for superlative adjectives, such as _terbaik_ "the best", _tercantik_ "the most beautiful".

  * [Foreign](), with one possible value: `Yes`. This feature only applies to [X]().

  * [Mood](), applies to [VERB](), with two possible values: `Ind`, and `Imp`
    1. `Mood=Ind` for verb in declarative sentences.
    2. `Mood=Imp` for verb in imperative sentences.


  * [Number](), applies to [DET](), [NOUN](), and [PRON](), with two possible values: `Sing`, or `Plur`.
    1. `Number=Sing` is used for singular nouns, determiner, or pronouns.
    2. `Number=Plur` is used for plural nouns, determiner, or pronouns.

  * [NumType](), applies to [NUM]() and [ADJ](), with two possible values: `Card` or `Ord`.
    1. `NumType=Card` is used for cardinal numbers tagged as `NUM`.
    2. `NumType=Ord` is used for ordinal numbers tagged as `ADJ`.

  * [Person](), applies to [PRON]() with three possible values: `1`, `2`, `3`.

  * [Polarity](), with one possible value: `Neg`, applies to [PART]() and [INTJ]().
    * `Polarity=Neg` for [PART]() applies for negation particles as in _Saya **tidak** menyukainya_ "I do **not** like him/her/it". The word _tidak_ "no" will be tagged with `Polarity=Neg`.
    * `Polarity=Neg` for [INTJ]() as in _**Tidak**, terima kasih_ "**No**, thanks". The word _tidak_ "no" will be given feature `Polarity=Neg`.


  * [Polite](), applies to [PRON]() with two possible values: `Form` and `Infm`.
    1. `Polite=Form`, applies to `PRON`, such as for _saya_ "I", _anda_ "you", and _beliau_ "him/her".
    2. `Polite=Infm`, applies to `PRON`, such as for _aku_ "I", _kamu_ "you" (singular), and _kalian_ "you" (plural).


  * [PronType](), applies to [PRON](), [DET](), and [ADV](). For Indonesian, eight possible values can be applied:
    1. `PronType=Art`, applies to `DET`, such as for _sebuah, seorang_ and _-nya_
    2. `PronType=Dem`, applies to `ADV`, `DET`, and `PRON` such as for _itu_ "that" in _**Itu** masalahmu._ "**That** is your problem."
    3. `PronType=Emp`, applies to `DET` such as for _sendiri_ "self" in _Kamu harus percaya pada dirimu **sendiri**_ "You have to believe in your**self**".
    4. `PronType=Ind`, applies to `ADV`, `DET`, and `PRON` such as for _seseorang_ "someone/somebody" or _sesuatu_ "something"
    5. `PronType=Int`, applies to `PRON` and `ADV`.
      * `PronType=Int` for `PRON`, such as for _apa_ "what" and _siapa_ "who" in interrogative sentences
      * `PronType=Int` for `ADV`, such as for _bagaimana_ "how" and _kapan_ "when" in interrogative sentences
    6. `PronType=Prs`, applies to `PRON`for all personal pronouns.
    7. `PronType=Rel`, applies to `PRON` and `ADV`.
      * `PronType=Rel` for `PRON`, such as for _apa_ "what", _siapa_ "who", _yang_ "that".
      * `PronType=Rel` for `ADV`, such as for _di mana_ "where", _bagaimana_ "how" and _kapan/saat/ketika_ "when" in non-interrogative sentences
    8. `PronType=Tot`, applies to `ADV`, `DET`, and `PRON`.
      * `PronType=Tot` for `PRON`, such as for _semua_ "all" in _**Semua** adalah milikmu._ "**All** is yours."
      * `PronType=Tot` for `DET`, such as for _semua_ "all" in _**Semua** siswa terlihat senang._ "**All** students look happy."
      * `PronType=Tot` for `ADV`, such as for _selalu_ "always" in _Dia **selalu** terlambat_. "She is **always** late."

  * [Reflex](), applies to [PRON]() with one possible value: `Yes`. Only one word qualifies to this feature: _diri_ "self".

  * [Typo](), with one possible value, `Yes`. This feature can be applied to all UPOS categories except [PUNCT]() and [SYM]().

  * [Voice](), applies to [VERB]() with two possible values: `Act` and `Pass`. Voice alternation is treated as inflection and the active and passive counterparts have the same lemma.
    1. `Voice=Act` for active verbs that have characteristic of using base word, prefixes _me-, ber-_
      * Active verbs without affix: _duduk_ "sit", _pergi_ "go"
      * Active verbs with prefix _me-_: _memperbaiki_ "fix", _mengakui_ "admit"
      * Active verbs with prefix _ber-_: _belajar_ "study", _bekerja_ "work"
    2. `Voice=Pass` for passive verbs that have characteristic of using prefixes _di-, ter-_ or circumfix _ke-an_.
      * Passive verbs with prefix _di-_ : _dipublikasikan_ "be published", _dilepaskan_ "be released"
      * Passive verbs with prefix _ter-_: _terbakar_ "on fire", _terjatuh_ "fell", _terkejut_ "shocked"
      * Passive verbs with confix _ke-an_: _ketinggalan_ "lag behind", _kecurian_ "be stolen"


* We consider these 9 UD v2 features are not relevant to Indonesian grammar:
  * `Gender`. Indonesian words have no gender.
  * `Animacy`. Similar with Gender, there is no requirements of agreements between words in Indonesian.
  * `NounClass`, with the same reason for Gender and Animacy
  * `Case`, with the same reason for Gender, Animacy, and NounClass
  * `Tense`. Indonesian verbs have the same form in all tenses.
  * `Aspect`, with the same reason for Tense.
  * `Evident`
  * `Poss`
  * `VerbForm`

## Syntax

### Core Arguments, Oblique Arguments and Adjuncts

* The default word order is SVO, so the subject ([nsubj]()) normally precedes and the object follows the verb (with the exception of inverted sentences).
* A verb may serve as the subject and is labeled as clausal subject, either as [csubj]() or [csubj:pass]().
* Transitive verbs will have a noun phrase as the object ([obj]()).
* Passive verbs could be followed by agent ([obl:agent]()), such as in _Pesan yang dikirimkan **presiden**_ "Messages sent by **president**", _presiden_ "president" is the agent of predicate _dikirimkan_ "be sent".
* Verbs can have oblique arguments ([obl]()). Special for temporal modifiers, we label it as [obl:tmod]().

### Non-verbal Clauses

* The copula _ialah_ or _adalah_ (be) is optionally used in equational, attributional, locative, possessive and benefactory nonverbal clauses. The two forms are interchangeable but _adalah_ is more common. For example: "This **is** my house.", in Indonesian can be written as:
  * _Ini rumahku._, without copula
  * _Ini **adalah** rumahku._, with copula _adalah_

### Relations Overview

* Among 37 universal dependency relations in UDv2:
  * 31 deprels are represented in the Indonesian-CSUI (except: `compound`, `expl`, `goeswith`, `list`, `reparandum`, and `vocative`)
  * 33 deprels are represented in the Indonesian-PUD (except: `dep`, `expl`, `list`, and `reparandum`)
  * 34 deprels are represented in the Indonesian-GSD (except: `dislocated`, `expl`, and `reparandum`)

* We provide additional docummentation with examples in Indonesian for some of universal deprels:
  * [aux]()
  * [cop]()
  * [clf]()
  * [fixed]()

* The following 14 relation subtypes could be used in Indonesian UD treebank:
  1. [acl:relcl]() for relative clauses that modify a noun phrase.
  2. [advmod:emph]() for particles ([PART]()) _-lah, -kah, -tah and , pun_ that emphasize other words.
  3. [case:adv]() for adposition ([ADP]()) that is not a nominal dependent.
  4. [cc:preconj]() for  word _baik_ in clause _baik A maupun B_ "both A and B".
  5. [compound:a]() for adjective compounds
  6. [csubj:pass]() for clausal subjects of passive verbs.
  7. [flat:foreign]() to label sequences of foreign words.
  8. [flat:name]() to label sequences of names of PROPN-PROPN pairs.
  9. [nmod:lmod]() for locative nouns.
  10. [nmod:poss]() for possessive relationship.
  11. [nmod:tmod]() for temporal modifier of a noun phrase.
  12. [nsubj:pass]() for nominal subjects of passive verbs.
  13. [obl:agent]() for agents of passive verbs.
  14. [obl:tmod]() for temporal modifier for a [VERB]()/[ADJ]().

## Treebanks

There are [3](../treebanks/id-comparison.html) Indonesian UD treebanks:

  * [Indonesian-GSD](../treebanks/id_gsd/index.html)
  * [Indonesian-PUD](../treebanks/id_pud/index.html)
  * [Indonesian-CSUI](../treebanks/id_csui/index.html)

