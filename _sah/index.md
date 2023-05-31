---
layout: base
title:  'Yakut UD'
udver: '2'
---

# UD for Yakut <span class="flagspan"><img class="flag" src="[../../flags/svg/RU-SA.svg](https://upload.wikimedia.org/wikipedia/commons/e/eb/Flag_of_Sakha.svg)" /></span>


## Tokenization and Word Segmentation

* Words are delimited by whitespase characters.
* According to typographical rules, punctuation marks are attached to a neighboring word. They are given as separate tokens (words).

---

### Tags

* Yakut uses all 17 universal POS categories.

Mapping UPOS to Yakut XPOS 

 UPOS | XPOS |
:----: | :------: |
 NOUN  | n        |
 VERB  | v, vi, vt, vd|
 ADV   | adv      |
 ADJ   | adj       |
 INTJ  | intj     |
 PROPN | propn      |
 ADP   | adp       |
 AUX   | aux      |
 CCONJ | cconj       |
 DET   | det      |
 NUM   | num      |
 PART  | part      |
 PRON  | pron      |
 SCONJ | sconj       |
 PUNCT | punct    |
 SYM   | sym      |
 X     | x        |
 
---

## Morphology

* Yakut nouns are not marked for gender.
* The feature `Number` may take the values [sing](https://universaldependencies.org/u/feat/Number.html#sing-singular-number) or [plur](https://universaldependencies.org/u/feat/Number.html#plur-plural-number).
* The plural suffix -_лар_ is used for both nouns and adjectives. The suffix yields 16 variants.

<b>Table of plural suffixes </b> <a name="plural-suf"></a>

Terminal letter of the stem  |     Form of the affix         |           Example            |
:--------------------------: | :---------------------: | :-------------------------:  |
Vowels and diphthongs        |  _-лар, -лэр, -лор, -лөр_ | _паарталар, кинигэлэр, оҕолор, бөрөлөр_ |
Voiceless consonants: _к, п, с, т, х_| _-тар, -тэр, -тор, -төр_ | _харандаастар, түннүктэр, оһохтор_  |
_й, р_  | _-дар, -дэр, -дор, - дөр_ | _сарайдар, үчүгэйдэр, томтордор_ |
Nasal consonants: _м, н, ҥ_  | _-нар, -нэр, -нор, - нөр_ | _ааннар, тииҥнэр, ороннор_ |


* There are 8 `cases`: [nominative](https://universaldependencies.org/u/feat/Case.html#nom-nominative--direct), [accusative](https://universaldependencies.org/u/feat/Case.html#acc-accusative--oblique), [dative](https://universaldependencies.org/u/feat/Case.html#dat-dative), [partitive](https://universaldependencies.org/u/feat/Case.html#par-partitive), [ablative](https://universaldependencies.org/u/feat/Case.html#abl-ablative), [instrumental](https://universaldependencies.org/u/feat/Case.html#ins-instrumental--instructive), [comitative](https://universaldependencies.org/u/feat/Case.html#com-comitative--associative), [comparative](https://universaldependencies.org/u/feat/Case.html#cmp-comparative).


<b>Table of cases</b>

Case                     | Form of the affix |       Examples      |
:----------------------: | :---------------: | :-----------------: |
Nominative               | -                   | _таба, ат_            |
Partitive                | -_та_               | _табата, атта_        |
Dative                   | -_ҕа_               | _табаҕа, акка_        |
Accusative               | -_ны (ы)_           | _табаны, аты_         |
Ablative                 | -_ттан (-тан)_      | _табаттан, аттан_     |
Instrumental             | -_нан (-ынан)_      | _табанан, атынан_     |
Comitative               | -_лыын_             | _табалыын, аттыын_    |
Comparative              | -_тааҕар_           | _табатааҕар, аттаҕар_ |


* Possession is expressed by suffixes, which correspond to possessive pronouns my, your, and so on. The suffixes differ according to [person](https://universaldependencies.org/u/feat/Person.html) and [number](https://universaldependencies.org/u/feat/Number.html). It is often strengthenes by a personal pronoun standing in front of the noun that is in the possessive form. However, the personal pronoun of the first and the second person may be absent.

<b>Possessive declension: Singular</b>

Case             | First Person | Second Person | Third Person |
:--------------: | :--------:   | :-----------: |:-----------: |
Nominative       | _атым_         | _атыҥ_          | _ата_          |
Partitive        | -            | -             | -            |
Dative           | _аппар_        | _аккар_         | _атыгар_       |
Accusative       | _аппын_        | _аккын_         | _атын_         |
Ablative         | _аппыттан_     | _аккыттан_      | _атыттан_      |
Instrumental     | _аппынан_      | _аккынан_       | _атынан_       |
Comitative       | _аппыныын_     | _аккыныын_      | _атыныын_      |
Comparative      | _аппынааҕар_   | _аккынааҕар_    | _атынааҕар_    |


<b>Possessive declension: Plural</b>

Case             | First Person   | Second Person | Third Person |
:--------------: | :------------: | :-----------: |:-----------: |
Nominative       | _аппыт_        | _аккыт_       | _ата_        |
Partitive        | -              | -             | -            |
Dative           | _аппытыгар_      | _аккытыгар_     | _аттарыгар_    |
Accusative       | _аппытын_        | _аккытын_       | _аттарын_      |
Ablative         | _аппытыттан_     | _аккытыттан_    | _аттарыттан_   |
Instrumental     | _аппытынан_      | _аккытынан_     | _аттарынан_    |
Comitative       | _аппытыныын_     | _аккытыныын_    | _аттапыныын_   |
Comparative      | _аппытынааҕар_   | _аккытынааҕар_  | _аттарынааҕар_ |

* Nouns that are being used as predicates take particular possession affixes, distinguished according to person and number, e.g. саха - a Yakut -> _Мин сахабын_ - “I am a Yakut”.

<b>Predication form: Singular</b>

Person   | Terminal letter of the stem   | Form of the affix | Example |
:------: | :------------: | :-----------: |:-----------: |
First    | Vowels, diphthongs; _й, л, р_ | _-бын, -бин, -бун, - бүн_  | _аҕа - аҕабын (I am a father), киһи - киһибин, оҕо - оҕобун_     |
First    | _к, п, с, т, х_               | _-пын, -пин, -пун, - пүн_  | _ударник - ударникпын, үлэһит - үлэһиппин, оҕоһут - оҕоһуппун_   |
First    | _м, н, ҥ_                     | _-мын, -мин, -мун, - мүн_  | _капитан - капитаммын, түргэн - түргэммин, агроном - агрономмун_ |
Second   | Wide vowels _(а, э, о, ө)_ and diphthongs | _-ҕын, -ҕин, -ҕун, - ҕүн_       | _аҕа - аҕаҕын, эһэ - эһэҕин, оҕо - оҕоҕун, көнө - көнөҕүн_ |
Second   | Narrow vowels _(ы, и, у, ү); й, л, р_     | _-гын, -гин, -гун, - гүн_    | _сатыы - сатыыгын, киһи - киһигин, уол - уолгун, үчүгэй - үчүгэйгин_ |
Second   | _к, п, с, т_      | _-кын, -кин, -кун, - күн_     | _үлэһит - үлэһиккин, кыыс - кыыскын, оҕоһут - оҕоһуккун_ |
Second   | _х_     | _-хын, -хин, -хун, - хүн_    | _саалаах - саалааххын, тиистээх - тиистээххин, оҕолоох - оҕолооххун_ |
Second   | _м, н, ҥ_   | _-ҥын, -ҥин, -ҥун, - ҥүн_  | _капитан - капитаҥҥын, түргэн - түргэҥҥин, бөдөҥ - бөдөҥҥүн_ |
Third    | -   | -  | - |

<b>Predication form: Plural</b>

Person   | Terminal letter of the stem   | Form of the affix | Example |
:------: | :------------: | :-----------: |:-----------: |
First    | Vowels, diphthongs: _й, л, р_ | _-быт, -бит, -бут, - бүт_  |      |
First    | _к, п, с, т, х_               | _-пыт, -пит, -пут, - пүт_  |    |
First    | _м, н, ҥ_                    | _-мыт, -мит, -мут, - мүт_  |  |
Second   | Wide vowels _(а, э, о, ө)_ and diphthongs | _-ҕыт, -ҕит, -ҕут, - ҕүт_       |  |
Second   | Narrow vowels _(ы, и, у, ү); й, л, р_     | _-гыт, -гит, -гут, -гүт_    |  |
Second   | _к, п, с, т_      | _-кыт, -кит, -кут, - күт_     |  |
Second   | _х_     | _-хыт, -хит, -хут, - хүт_    |  |
Second   | _м, н, ҥ_   | _-ҥыт, -ҥит, -ҥут, - ҥүт_  |  |
Third    | The form of the plural   | see [Plural suffixes](#plural-suf)  |  |


---
# Tense 

## Present Tense

### Affirmative

|   | Sing   |   ас    |   | Plur     | сиэ     |
|---|--------|--------|---|----------|----------|
| 1 | -бын | аһабын |   | -быт | сиибит |
| 2 | -ҕын | аһаҕын |   | -гыт | сиигит |
| 3 | -ар    | аһар  |   | -лар | сииллэр |


### Negative

|   | Sing   |    ас  |   | Plur     |   сиэ      |
|---|--------|--------|---|----------|----------|
| 1 | -па -пын | аспаппын |   | -бэ -пит | сиэбэппит |
| 2 | -па -кын | аспаккын |   | -бэ -кыт | сиэбэккит |
| 3 | -па -т   | аспат |   | -бэ -тэр | сиэбэттэр |

---

## NearPast Tense

### Affirmative

|   | Sing   |  бар, ас, кэл      |   | Plur     |     бар, сиэ     |
|---|--------|--------|---|----------|----------|
| 1 | -ты -м | бардым, астым, кэл-л-им |   | -ты -быт | бардыбыт, сиэтибит |
| 2 | -ты -ҥ | бардыҥ, астыҥ, кэл-л-иҥ |   | -ты -гыт | бардыгыт, сиэтигит |
| 3 | -та    | барда, аста, кэл-л-э  |   | -ты -лар | бардылар, сиэтилэр |


### Negative

|   | Sing   |    ас, кэл    |   | Plur     |   сиэ, кэл       |
|---|--------|--------|---|----------|----------|
| 1 | -па -т -ым | аспатым, кэлбэтим |   | -бэ -т -ыбыт | сиэбэтибит, кэлбэтибит |
| 2 | -па -т -ыҥ | аспатыҥ, кэлбэтиҥ |   | -бэ -т -ыгыт | сиэбэтигит, кэлбэтигит |
| 3 | -па -т -а    | аспата, кэлбэтэ |   | -бэ -т -ылар | сиэбэтилэр, кэлбэтилэр |

---

## PastPerf Tense

### Affirmative

|   | Sing   |   ас, бар      |   | Plur     |     бар, кэл     |
|---|--------|--------|---|----------|----------|
| 1 | -пыт -ым |  аспытым, бар-быт-ым |   | - бип -пит | бар-бып-пыт  |
| 2 | -пыт -ыҥ | аспытыҥ,  бар-быт-ыҥ|   | -бик -кит | бар-бык-кыт  |
| 3 | -пыт -а    | аспыта,  бар-быт-а |   | -бит -тара | бар-быт-тара  |


### Negative

|   | Sing   |    бар, туп    |   | Plur     |   бар, туп       |
|---|--------|--------|---|----------|----------|
| 1 | -батаҕ -ым | бар-батаҕ-ым, туп-патаҕ-ым |   | -батаҕ -пыт | бар-батаҕ-пыт, туп-патах-пыт |
| 2 | -батаҕ -ыҥ | бар-батаҕ-ыҥ, туп-патаҕ-ыҥ |   | -батаҕ -хыт | бар-батаҕ-хыт, туп-патах-хыт |
| 3 | -батаҕ -а    | бар-батаҕ-а, туп-патаҕ-а |   | -батаҕ -тара | бар-батаҕ-тара, туп-патах-тара |



---

## PastResultI Tense

### Affirmative

|   | Sing   |   бар      |   | Plur     |     бар     |
|---|--------|--------|---|----------|----------|
| 1 | -бып -пын |  бар-бып-пын |   | - бып -пыт | бар-бып-пыт  |
| 2 | -бык -кыҥ |  бар-бык-кын |   | -бык -кыт | бар-бык-кыт  |
| 3 | -быт   |  бар-быт |   | -быт -тар | бар-быт-тар  |


### Negative

|   | Sing   |    бар  |   | Plur     |   бар, туп       |
|---|--------|--------|---|----------|----------|
| 1 | -батах -пын | бар-батах-пын|   | -батах -пыт | бар-батах-пыт|
| 2 | -батах -хын | бар-батах-хын |   | -батах -хыт | бар-батах-хыт |
| 3 | -батах   | бар-батах|   | -батах -тар | бар-батах-тар |




---

## Future Tense

### Affirmative

|   | Sing   |   аһаа      |   | Plur     |     аһаа     |
|---|--------|--------|---|----------|----------|
| 1 | -ыаҕым |  аһыаҕым |   | -ыахпыт | аһыахпыт,  |
| 2 | -ыаҕыҥ |  аһыаҕыҥ |   | -ыаххыт | аһыаххыт,  |
| 3 | -ыаҕа   |  аһыаҕа |   | -ыахтара | аһыахтара,  |


### Negative

---

* `PronTypes` are [collective](https://universaldependencies.org/u/feat/PronType.html#tot-total-collective-pronoun-determiner-or-adverb), [demonstrative](https://universaldependencies.org/u/feat/PronType.html#dem-demonstrative-pronoun-determiner-numeral-or-adverb), [indefinite](https://universaldependencies.org/u/feat/PronType.html#ind-indefinite-pronoun-determiner-numeral-or-adverb), [interrogative](https://universaldependencies.org/u/feat/PronType.html#int-interrogative-pronoun-determiner-numeral-or-adverb), [personal/possessive](https://universaldependencies.org/u/feat/PronType.html#prs-personal-or-possessive-personal-pronoun-or-determiner).
* `NumType` distinguish [ordinal](https://universaldependencies.org/u/feat/NumType.html#ord-ordinal-number-or-corresponding-interrogative--relative--indefinite--demonstrative-word) and [cardinal](https://universaldependencies.org/u/feat/NumType.html#card-cardinal-number-or-corresponding-interrogative--relative--indefinite--demonstrative-word).
* As it is common among Turkic languages, there is a rich verbal system.  (`tense`): [present](https://universaldependencies.org/u/feat/Tense.html#pres-present--non-past-tense--aorist), [future](https://universaldependencies.org/u/feat/Tense.html#fut-future-tense), definite past, remote past, past imperfect, past episodic, resultative, [pluperfect](https://universaldependencies.org/u/feat/Tense.html#pqp-pluperfect),  pluperfect episodic.
* Ten `moods` are distinguished in Yakut: [indicative](https://universaldependencies.org/u/feat/Mood.html#ind-indicative-or-realis), [imperative](https://universaldependencies.org/u/feat/Mood.html#imp-imperative), [conditional](https://universaldependencies.org/u/feat/Mood.html#cnd-conditional), affirmative, obligative, habitual, dubitative, unrealized, [subjunctive](https://universaldependencies.org/u/feat/Mood.html#sub-subjunctive--conjunctive), suppositional.
* Non-finite verb forms include: perfect-participle, aorist-participle, future-participle, not-yet-participle.
* There are [converbs](https://universaldependencies.org/u/feat/VerbForm.html#conv-converb-transgressive-adverbial-participle-verbal-adverb).


* The second-person singular imperative of a verb is identical in form to the infinitive.
* Adjectival modifiers precede the noun they modify. It does not agree with the determinandum, and takes no affixes.
---

### Features

*

---

## Syntax

* Differential object-marking is found depending on definiteness. If the object of a transitive verb is definite, the accusative case is used. With an indefinite object, the nominative case is used:

```
Уол кинигэни ааҕар.
Уол кинигэ-ни ааҕ-ар
boy book-ACC.Sing  read-PRES.3.SG
`A boy reads the book.'
```

```
Уол кинигэ ааҕар.
Уол кинигэ ааҕ-ар
boy book.NOM.SG read-PRES.3.SG
`A boy reads a book.'
```

* The following valency change devices (`voice`) are found: [passive](https://universaldependencies.org/u/feat/Voice.html#pass-passive-or-patient-focus-voice), [causative](https://universaldependencies.org/u/feat/Voice.html#cau-causative-voice), [reciprocal](https://universaldependencies.org/u/feat/Voice.html#rcp-reciprocal-voice).


---

## Treebanks

There is 1 Yakut UD treebank:

  * [Yakut-A](https://github.com/UniversalDependencies/UD_Yakut-YKTDT)

---

