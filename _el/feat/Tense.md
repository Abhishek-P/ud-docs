---
layout: feature
title: 'Tense'
shortdef: 'tense'
udver: '2'
---

<table class="typeindex" border="1">
<tr>
  <td style="background-color:cornflowerblue;color:white"><strong>Values:</strong> </td>
  <td><a href="#Fut">Fut</a></td>
  <td><a href="#Past">Past</a></td>
  <td><a href="#Pres">Pres</a></td>
</tr>
</table>

Tense is a feature pertaining to finite verb and auxiliary forms and participles only; it specifies the time when the action took /
takes / will take place, in relation to the current moment or to
another action in the utterance.

Modern Greek verb tenses are formed periphrastically mainly (composite tenses). In the GUD treebanks there are three stand-alone verb forms, i.e., not supported by auxiliaries, that bear Tense: one that is classified  as "Pres" but it is also used in the so-called Future tense formations, and two forms marked for "Past" that differ in terms of aspect (perfect, imperfect). There is no verb form marked for Future; instead, there is the particle _θα_ that is considered an auxiliary in the Greek UD treebanks and is assigned the tense feature "Fut" (but it would be probably more accurate to consider it a marker of potentiality and drop the feature 'Fut' from the Greek UD treebanks). 

<b>All verb and auxiliary forms in composite tenses preserve their tense and mood features, if they are defined for them.</b>

### <a name="Past">`Past`</a>: past tense

The past tense denotes actions that happened before the current
moment. Modern Greek morphologically distinguishes between a perfective past tense (Αόριστος) and an Imperfective one (Παρατατικός). 

#### Examples
* Perfective past tense: _έγραψα_ "I wrote"
* Imperfective past tense: _έγραφα_ "I was writing"

Periphrasticalloy formed tenses (composite tenses) describe situations occurring before a specified point in time, now, in the past or the future, with the use of auxiliaries, namely the verbs 'have' and 'be'. In these cases, each form (the auxiliary and the verb) are assigned their own tense features. Certain composite tenses are formed with a form of the content verb  that is tagged as 'infinitive' [VerbForm](el-feature/VerbForm) and is not specified for tense and mood.

#### Examples

* _έχω.PRES γράψει.INF_ "I have written"
* _είχα.PAST γράψει.INF_ "I had written"

* _είμαι.PRES γραμμένος.(VerbForm=Part)_ "I am written"
* _ήμουν.PAST γραμμένος.(VerbForm=Part)_ "I was written"



### <a name="Pres">`Pres`</a>: present tense

The present tense denotes actions that are happening right now or that
usually happen.


#### Examples

* _έρχομαι σπίτι_ “I _come/am coming_ home.” 
* _γράφω το γράμμα_ "I  _write/am writing _ the letter."

### <a name="Fut">`Fut`</a>: future tense

The future tense denotes actions that will happen after the current
moment. In Modern Greek, the feature future 'Fut' is always assigned to the auxiliarry _θα_ that, however, combines with all
the finite verbal formations of Modern Greek; the latter preserve their normal taggs. So _θα_ combines with verb forms that bear Past or Present Tense features or no Tense features at all. It is important to note here that _θα_ is often argued to express potentiality rather than the future tense per se. 


#### Examples
* _θα γράφω_ "Ι will be writing"
* _θα γράψω_ "Ι will write"* _θα είχα γράψει.INF_ "Ι would have written"
* _θα έχω γράψει.INF_ "Ι will have written"
* _θα έγραφα_ "Ι would write"


* _θα έγραψα_ "Ι would have written"
* _θα γράφομαι_ "Ι will be being written"
*  _θα γραφτώ_ "Ι will be written"
* _θα γραφόμουν_ "Ι would be being written"
*  _θα γράφτηκα_ "Ι would be written"
* _θα έχω γραφτεί.INF_ "Ι will have been written"
* _θα είχα γραφτεί.INF_ "Ι would have been written"


<!-- Interlanguage links updated Út 9. května 2023, 20:03:49 CEST -->
