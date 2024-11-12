---
layout: feature
title: 'Mood'
shortdef: 'mood'
udver: '2'
---

`Mood` expresses the modality, a speaker's perspective, in finite verbs.
Uyghur verbs may carry a wide range of mood information.
Different moods are indicated by a number of suffixes, which also interact with [tense](Tense) and [aspect](Aspect) of the verb.

### <a name="Ind">`Ind`</a>: indicative

The indicative can be considered the default mood. A verb in indicative merely states that something happens, has happened or will happen, without adding any attitude of the speaker.

#### Examples

* *eve gidiyor* 'she is going home'
* *eve gitti* 'she went home'

### <a name="Int">`Int`</a>: interrogative

The interrogative suffix _-mu_ converts the clause into a yes-no question.

#### Examples

* يېدىڭىز<b>مۇ</b>؟ / _yëdingiz<b>mu</b>?_ “Have you eaten?”

### <a name="Imp">`Imp`</a>: imperative

In Turkish imperatives are expressed by lack of any tense/aspect/modality marker. The form of imperative may indicate second or third person plural/singular. Note that, forms other than second person singular may indicate a wish rather than a command, so may be marked as `Opt` (see below).

#### Examples

* *eve git* 'go home!'
* *eve gidin* '(you-PLU) go home!'
* *eve gitsin* '(I am ordering him/her to) go home!'

### <a name="Prs">`Prs`</a>: persuasive (**new, not in UD**)

Turkish has a particular form of imperative, where the request is not an order, but an attempt to persuade.

#### Examples

* *eve gitsene* '(please) go home'
* *eve gitsenize* '(you-PLU, please) go home'

### <a name="Cnd">`Cnd`</a>: conditional

This expresses conditionality.
It is the primary means of forming conditionals in Turkish ('if ...').
The suffix responsible for this mood is *-sA*.
The suffix is ambiguous between `Cnd` and `Des` (see below).

#### Examples

* *eve gittiyse* 'if she went home'
* *eve gidiyorsa* 'if she is going home'
* *eve giderse* 'if she goes home'
* *eve gidecekdiyse* 'if she was going to go home'

### <a name="Des">`Des`</a>: desiderative

This mood expresses a wish.
It shares the same form as the `Cnd` mood.
It may be disambiguated by particles (*keşke*: desire, *eğer*: condition) or by the context.
For example, desires do not work well with fixed time references.
In general it is difficult to automatically disambiguate between these two moods.

#### Examples

* *(keşke) uyusa* 'I wish she sleeps'
* *(keşke) uyusaydı* 'I wish she slept'

### <a name="Opt">`Opt`</a>: optative

Optative suffix (*-(y)A*) in Turkish typically combines with first person markers and expresses a suggestion.
The use with second/third person markers express a wish, but it is rare.
With third person singular agreement the imperative form may also express a wish or suggestion, and more common than *-(y)A* forms.

#### Examples

* *eve gidelim* 'let's go home'
* *bakayım* 'let's me see'
* *gele* 'I wish he/she comes'
* *gelesin* 'I wish you come'

### <a name="Nec">`Nec`</a>: necessitative

This expresses some sort of necessity (mush/should/have to in English).

#### Examples

* *eve gitmeli* 'she should go home'
* *eve gitmeliydi* 'she should have gone home'

### <a name="Gen">`Gen`</a>: generalized modality (**new proposal, not in UD**)

Turkish modal system includes a distinction between statements of direct experience (`Ind`) and statements with a more general or theoretical nature (Göksel & Kerslake, 2005, p.295).
This mood is typically marked by the aorist marker on verbs, and with *-DIr* suffix on nominal predicates.

(**NOTE:** this mood interacts with evidentiality.  One may consider the status of evidentiality expressed by this suffix to be "inferred". Hence, an alternative way of marking this could be `Evidential=Infer`, or something similar)

#### Examples

* *park yapılmaz* 'one does not park = no parking'
* *iki, iki daha dört eder* 'two plus two is four'
* *ikinin karesi dörttür* 'two's square is four'
* *Ali işe geç gider* 'Ali goes to work late'
* *hastadır* '(I hypothesize/deduce that) she must be sick'

### <a name="Pot">`Pot`</a>: potential

The suffix *-Abil* may indicate ability or possibility.
These moods are normally distinct, and the same verb may express both at the same time (see the last example below).
However, it is also very difficult to disambiguate between these two moods.

#### Examples
* *eve gidebilir* 'she can go home' ('she is capable of going home', or 'she just may go home')
* *yağmur yağabilir* 'it may rain'
* *eve gidemeyebilir* 'she may not be able to go home' (it is possible that she is not capable of going home)

### References
- Aslı Göksel and Celia Kerslake. _Turkish: A Comprehensive Grammar_.
  London: Routledge, 2005.

<!-- Interlanguage links updated Po 11. listopadu 2024, 20:09:48 CET -->
