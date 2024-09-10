---
layout: feature
title: 'Voice'
shortdef: 'voice'
udver: '2'
---

<table class="typeindex" border="1">
<tr>
  <td style="background-color:cornflowerblue;color:white"><strong>Values:</strong> </td>
  <td><a href="#Act">Act</a></td>
  <td><a href="#Antip">Antip</a></td>
  <td><a href="#Bfoc">Bfoc</a></td>
  <td><a href="#Cau">Cau</a></td>
  <td><a href="#Dir">Dir</a></td>
  <td><a href="#Inv">Inv</a></td>
  <td><a href="#Lfoc">Lfoc</a></td>
  <td><a href="#Mid">Mid</a></td>
  <td><a href="#Pass">Pass</a></td>
  <td><a href="#Rcp">Rcp</a></td>
</tr>
</table>

Voice is typically a feature of [verbs](u-pos/VERB).
It may also occur with other parts of speech
([nouns](u-pos/NOUN), [adjectives](u-pos/ADJ), [adverbs](u-pos/ADV)),
depending on whether borderline word forms such as gerunds and participles
are classified as verbs or as the other category.

For Indo-European speakers, voice means mainly the active-passive
distinction. In other languages, other shades of verb meaning are
categorized as voice.

### <a name="Act">`Act`</a>: active or actor-focus voice

The subject of the verb is the doer of the action (agent), the object
is affected by the action (patient). This label is also used for the
actor-focus voice of Austronesian languages. <!-- which is labeled AGFOC in UniMorph -->

#### Examples

* [cs] _<b>Napadli</b> jsme nepřítele._ “We <b>attacked</b> the enemy”
  (the active participle _napadli_ can be used to form either past
  tense or conditional mood; here it forms the past tense.)
* [grc] _<b>λύει</b> τὸν ἵππον μου (<b>luei</b> ton hippon mou)_ “he frees my horse”
* [hu] _<b>mos</b>_ “wash”
* [tr] _Barış Filiz’i <b>öptü</b>._ “Barış kissed Filiz.”
* [tl] _<b>Naglilinis</b> siya ng bahay._ “He/she <b>cleans</b> a/the house.”
* [yii] _Waguɖaŋgu guda:ga <b>wawa:l</b>._ “The man <b>saw</b> the dog.”
  (lit. man-ERG dog.ABS see.ACT-PAST)

### <a name="Mid">`Mid`</a>: middle voice

Between active and passive, needed e.g. in Ancient Greek or Sanskrit.
The subject is both doer and undergoer in a sense:
he is acting upon himself.

#### Examples

* [grc] _<b>λύομαι</b> τὸν ἵππον (<b>luomai</b> ton hippon)_ “I free (my own) horse”

([source](https://ancientgreek.pressbooks.com/chapter/21/))

### <a name="Rcp">`Rcp`</a>: reciprocal voice

In a plural subject, all members are doers and undergoers,
acting upon each other.

#### Examples

* [tr] _Filiz ve Barış <b>öpüştüler</b>._ “Filiz and Barış kissed.”

### <a name="Pass">`Pass`</a>: passive or patient-focus voice

The subject of the verb is affected by the action (patient). The doer
(agent) is either unexpressed or it appears as an oblique dependent
or an object of the verb. This label is also used for the patient-focus
voice of Austronesian languages. <!-- which is labeled PFOC in UniMorph -->

#### Examples

* [cs] _Jsme <b>napadeni</b> nepřítelem._ “We are <b>attacked</b> by
  the enemy” (the passive participle _napadeni_ is used to form
  passive in all tenses; here it forms the present passive.)
* [tl] _<b>Nililinis</b> niya ang bahay._ “He/she <b>cleans</b> the house.”

### <a name="Antip">`Antip`</a>: antipassive voice

In ergative-absolutive languages, the absolutive P argument is demoted
to an oblique dependent and the ergative A argument takes the absolutive
form, thus transforming a transitive clause into intransitive.

#### Examples

* [yii] _Wagu:ɖa gudaganda <b>wawa:ɖiɲu</b>._ “The man <b>saw</b> the dog.”
  (lit. man.ABS dog-DAT see-ANTIP-PAST)

### <a name="Lfoc">`Lfoc`</a>: location-focus voice

The subject of the verb indicates location or direction, while the
doer and the undergoer/theme are coded as objects.

#### Examples

* [tl] _<b>Aalisan</b> ng babae ng bigas ang sako para sa bata._ “A/the woman <b>will take</b> some rice out of the sack for a/the child.”

### <a name="Bfoc">`Bfoc`</a>: beneficiary-focus voice

The subject of the verb indicates the beneficiary, while the
doer and the undergoer/theme are coded as objects.

#### Examples

* [tl] _<b>Ipagaalis</b> ng babae ng bigas sa sako ang bata._ “A/the woman <b>will take</b> some rice out of a/the sack for the child.”

### <a name="Dir">`Dir`</a>: direct voice

Used in direct-inverse voice systems, e.g. in Algonquian languages of North America.
Direct means that the argument that is higher in salience hierarchy is the subject.
Example hierarchy: human 1st person – 2nd – 3rd – non-human animate – inanimate.

#### Examples

* [crk] _<b>Niwīcihānānak</b>._ “We help them.” (_ni-wīcih-ā-nān-ak_ lit. 1PL[subj]-help-DIR-3[obj]-PL[obj])

### <a name="Inv">`Inv`</a>: inverse voice

Used in direct-inverse voice systems, e.g. in Algonquian languages of North America.
Inverse voice marking means that the argument lower in the hierarchy functions as subject.

#### Examples

* [crk] _<b>Niwīcihikonānak</b>._ “They help us.” (_ni-wīcih-iko-nān-ak_ lit. 1PL[subj]-help-INV-3[obj]-PL[obj])

### <a name="Cau">`Cau`</a>: causative voice

Causative forms of verbs are classified as a voice category because,
when compared to the basic active form, they change the number of
participants and their mapping on semantic roles.
(See, e.g., the [documentation](https://wiki.ufal.ms.mff.cuni.cz/_media/user:zeman:treebanks:ttbankkl.pdf)
of the METU Sabanci treebank (page 26).)
Note that this is a feature of verbs. There are languages that have
also the causative case of nouns.

#### Examples

* [hu] _<b>mosat</b>_ “make somebody wash”
* [tr] _<b>karıştırıyor</b>_ “is confusing” (= is causing somebody to be confused)

<!-- Interlanguage links updated Ne 5. května 2024, 18:20:28 CEST -->
