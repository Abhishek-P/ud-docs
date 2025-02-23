---
layout: base
title:  'Pashto UD'
udver: '2'
---

# UD for Pashto <span class="flagspan"><img class="flag" src="../../flags/svg/AF.svg" /></span> <span class="flagspan" style="padding-left:1em"><img class="flag" src="../../flags/svg/PK.svg" /></span>

For the principles of transliteration of Pashto used in UD see the [Transliteration page](transliteration.html).

## Tokenization and Word Segmentation

* The words are delimited by whitespaces and punctuation. Any possible exceptions have not yet been established.
* Multiword tokens are used in several cases:
  * Partially separable verbs (see below) in forms, when the two parts are connected (بندوم _bandawë́m_ “I close” → کوم _band_ + بند _kawë́m_).
  * Separeted verb prefixes connected with negative particle (به **ونه** خورم _bë **wënë́** xorëm_ “I will not eat” → و _wë_ + نه _në_).

## Morphology

### Lemmatization

* Direct (nominative) singular masculine (if applicable) form is used as lemma for nominals.
* Infinitive (in the direct case) is used as lemma for verbs, with these exceptions:
  * The verb “to be”, used as copula and as auxiliary verb for perfect tenses, does not have the infitinive, so the form of first person singular of the present tense یم _yëm_ “I am” is used instead.
  * The existential word شته _šta_ “there is / there are”, tagged as [VERB](), has only one form, so it is used as the lemma.

### Tags

* Pashto uses all 17 universal tags.
* Several words are tagged as [PART]():
  * Negative particles نه _në_ and مه _ma_ “no/not” and the affirmative particle هو _ho_ “yes”.
  * Modal particles: باید _bấyad_ (necessity “must / have to”).
* Only the verb یم _yëm_ “to be” (used as copula and auxiliary verb for perfect tenses) and some uses of the verb کېدل _kedë́l_ “to become” (when used as auxiliary verb for passive voice or potential forms) are tagged as [AUX](). Modal verbs, such as غوښتل _ġox̌të́l_ “to want to”, are tagged as [VERB]() (besides that, some modal meanings are expressed using modal particles or using the mentioned potential verb forms). Light verbs are tagged also as VERB, with the nominal part depending on them with `xcomp` relation.
* Pronouns that depend on nouns and behave similarly like their attributes (some of them even agree with the nouns in number, case and gender) are tagged as [DET](); possessive pronouns are mostly treated this way. Pronouns used individually (often as arguments of a verb) are tagged as [PRON](). This includes e.g. relative or non-possessive personal pronouns. Various interrogative, demonstrative or indefinite pronouns can be tagged both ways depending on the situation. Enclitic weak pronouns, used as unstressed core arguments or as alternative possessive pronouns, are always tagged as PRON, even when marking possession, because they do not have the attributive relation to the noun, e.g. they follow the noun, while all other pronouns tagged as DET precede it. Directional pronouns, merged with several prepositions, are separated from them with a PRON tag.
* The deverbal forms like infinitive or participles (sometimes behaving like verbal noun and verbal adjectives) are usually tagged as VERB. Only nouns and adjectives originally derived from infinitives or participles, but now perceived clearly as nouns and adjectives, are tagged as [NOUN]() and [ADJ]().
* Adjectives and adverbs derived from adjectives have often the same form. Their tagging as [ADJ]() or [ADV]() depends on the context.

### Features

* There are three [VerbForm]() values used in Pashto: finite `Fin`, infinitive `Inf` and participle `Part`.
* An important feature of Pashto verbs is [Aspect](), which strictly divides verb forms to imperfect `Imp` and perfecgt `Perf`.
* The finite verb forms inflect for [Mood]() feature with indicative `Ind`, imperative `Imp`, subjunctive `Sub` and potential `Pot` values.
* The finite verb forms conjugate for [Tense]() feature taking present `Pres`, past `Past` or future `Fut` mark.
* The finite verb forms inflect also for the [Person]() feature with the common three values, which is also an inherent feature of many personal pronouns.
* Generally all inlfectional parts of speech inflect for [Number]() taking a singular `Sing` or a plural `Plur` value. Infinitives always behave like plural, so they do not have the number tagged. Non-past finite verb forms do not have the number feature in the third person, since the forms for both numbers are always identical.
* Nominals, participles and infinitives inflect for [Case]() feature. There are five cases tagged in UD for Pashto: direct (marked as nominative) `Nom`, oblique (marked as accusative) `Acc`, locative `Loc`, ablative `Abl` and vocative `Voc`.
* Nouns and some pronouns have inherent [Gender]() feature with two possible values: masculine `Masc` and feminine `Fem`. Adjectives, other pronouns and participles inflect for the gender in order to agree with nouns. Finite verb forms inflect for the gender only in the past forms in the third person (both singular and plural).
* Verbs and pronouns use the feature [Variant]() to distinguish between various forms, denoted long `Long`, short `Short`, weak `Weak` and directional `Dir`.
  
## Syntax

### Core Arguments
* Core arguments (subjects and objects) in Pashto are mostly nouns, pronouns or infinitives (behaving like verbal nouns) in either bare direct case `Nom` or bare oblique case `Acc`. The exact use of these cases depends on the inherent transitivity of the verb and the voice and tense used (language phenomenon called _split ergativity_ occurring also in other Indo-Iranian langages)
* The only argument (i.e. the subject) of intransitive verbs or of transitive verbs used in the passive voice are always in the direct case `Nom`.
* For transitive verbs in the active voice holds:
  * The **subject** in **non-past** tenses is always in the **direct** case `Nom`.
  * The **subject** in **past** tenses is always in the **oblique** case `Acc`.
  * The **object** in **all** tenses is almost always in the **direct** case `Nom`.
    * The only exceptions are personal pronouns for the first and the second person singular in **non-past** tenses, where oblique forms ما _mâ_ “me”, تا _tâ_ “you” are used instead of the direct رۀ _zë_ “I”, تۀ _të_ “you”.
  * The subject usually comes before the object regardless of the case.
  * The verb agrees in `Person` and `Number` (and also `Gender` in the third person of past tenses) with the subject in non-past tenses and with the object in past tenses.

<table class="typeindex" border="1">
<tr>
  <td align="middle" rowspan="2"></td>
  <td align="middle">intransitive</td>
  <td align="middle" colspan="2">transitive</td>
</tr>
<tr>
  <td align="middle">nsubj</td>
  <td align="middle">nsubj</td>
  <td align="middle">obj</td>
</tr>
<tr>
  <td align="middle">non-past</td>
  <td align="middle"><b>direct</b></td>
  <td align="middle"><b>direct</b></td>
  <td align="middle"><b>direct *</b></td>
</tr>
<tr>
  <td align="middle">past</td>
  <td align="middle"><b>direct</b></td>
  <td align="middle"><b>oblique</b></td>
  <td align="middle"><b>direct</b></td>
</tr>
</table>
* exceptions: ما _mâ_, تا _tâ_ (see above)

### Non-verbal Clauses
* The copula verb یم _yëm_ “be” (or more precisely “I am”) is used in most non-verbal clauses.
* The nominal part of the predicate is usually in the direct case `Nom`
* In the existential clauses the word شته _šta_ “there is / there are” is used, but it is tagged [VERB]()

### Relations Overview
* The following relation subtypes are used in Pashto:
  * aux:pass
  * nsubj:pass
  * compound:prt
  * orphan:nsubjobj

---
**Instruction**: Include links to language-specific relations definitions if any.
---

## Treebanks

There is currently no Pashto UD treebank.


---
**Instruction**: Treebank-specific pages are generated automatically from the README file in the treebank repository and
from the data in the latest release. Link to the respective `*-index.html` page in the `treebanks` folder, using the language code
and the treebank code in the file name.

---
