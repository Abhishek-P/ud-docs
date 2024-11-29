---
layout: relation
title: 'fixed'
shortdef: 'fixed multiword expression'
udver: '2'
---

The `fixed` relation is used for certain fixed grammaticized expressions that behave
like function words or short adverbials, and for which a unique head cannot be identified.
These are a _subset_ of multiword expressions that are morphosyntactically "fixed"
in that they resist internal modification and inflection.
(Compare: [flat]() for headless expressions not behaving like function words; 
[compound]() for headed expressions that morphosyntactically resemble single words; 
and [goeswith]() for words that contain improper spacing.)

Fixed expressions are annotated in a flat, head-initial structure, in which all words in the expression modify the first one using the
`fixed` label. The first word bears the [ExtPos]() feature indicating the holistic category of the expression.

At present, this relation is used inside the following expressions, semantically grouped for convenience: 

| Category | Expressions |
|----------|-------------|
| [Augmentative/substitutive/conjunctive](#augmentativesubstitutiveconjunctive-expressions) | *as well*, *as well as*, *rather than*, *instead of*, *let alone* |
| [Causal](#causal-connectives) | *because of*, *due to*, *how come*, *in order*, *so as to*, *so that*, *such that* |
| [Spatiotemporal](#spatiotemporal-markers) | *in between*, *prior to*, *on board* |
| [Circumstantial/conditional](#circumstantialconditional-connectives) | *in case (of)*, *whether or not* |
| [Approximators](#approximators-quantity-modifiers) | with a quantity: *more than*, *less than*, *up to*, *as many/much/few/little as*, *all of* |
| [Attributional](#attributional-markers) | *according to* |
| [Exemplification](#exemplification) | *such as* |
| [Reciprocal Pronouns](#reciprocal-pronouns) | *each other*, *one another* |
| [Pragmatic/miscellaneous](#pragmaticmiscellaneous-markers) | *all but*, *as for*, *as if*, *as opposed to*, *as to*, *at least* (non-quantity), *in that*, *kind/sort of* (hedge), *not to mention*, *of course*, *that is* |

Below the description of `fixed` expressions are a few idiomatic combinations that are [analyzed without `fixed`](#not-fixed). These are summarized as follows:

| Non-`fixed` Expressions |
|-------------------------|
| Double spatial prepositions: *out of*, *off of*, etc. |
| *about to*; *as soon/long as*; *at all*, *at best/worst*, *by far*; *at most/least* (with quantities); *compared to/with*; *had better*; *nothing/anything but*; *so long*; *what about*, *what if* |

## `fixed` expressions

### Augmentative/substitutive/conjunctive expressions

*as well*

~~~ sdparse
I like dogs as/ADV[ExtPos=ADV] well/ADV
advmod(like, as)
fixed(as, well)
~~~

*as well as*

~~~ sdparse
I like dogs as/ADV[ExtPos=CCONJ] well/ADV as/ADP cats
fixed(as-4, well)
fixed(as-4, as-6)
cc(cats, as-4)
conj(dogs, cats)
~~~

<!-- TODO: add POS tags for remaining examples -->

*rather than* <!-- https://github.com/UniversalDependencies/UD_English-EWT/issues/182 -->

Typically analyzed as a coordinating conjunction:

~~~ sdparse
I decided to get a dog rather/[ExtPos=CCONJ] than a cat
fixed(rather, than)
cc(cat, rather)
conj(dog, cat)
~~~

However, when fronted, it attaches as `case` or `mark`:

~~~ sdparse
Rather/[ExtPos=ADP] than a cat , I decided to get a dog.
fixed(Rather, than)
case(cat, Rather)
obl(decided, cat)
~~~

*instead of* <!-- https://github.com/UniversalDependencies/UD_English-EWT/issues/182 -->

Similar in meaning to *rather than*, but never analyzed as a coordinating conjunction, always `case` or `mark`:

~~~ sdparse
John went instead/[ExtPos=ADP] of Mary
fixed(instead, of)
case(Mary, instead)
~~~

~~~ sdparse
John left early instead/[ExtPos=SCONJ] of staying for the whole thing
fixed(instead, of)
mark(staying, instead)
~~~

*let alone*

~~~ sdparse
He could n't handle being hurt , let/VERB[ExtPos=CCONJ] alone/ADJ hurt by you
fixed(let, alone)
cc(hurt-10, let)
conj(hurt-6, hurt-10)
~~~


### Causal connectives

*because of* (and other forms, such as *b c of* and *b/c of*)

~~~ sdparse
He cried because/ADP[ExtPos=ADP] of/ADP you
case(you, because)
fixed(because, of)
~~~

*due to* (and other forms, such as *d t* and *d/t*)

~~~ sdparse
He cried due/ADJ[ExtPos=ADP] to/ADP the fact that you hurt him
case(fact, due)
fixed(due, to)
~~~

*how come*

~~~ sdparse
How/[ExtPos=ADV] come John left early ?
fixed(How, come)
advmod(left, How)
~~~

*in order*

~~~ sdparse
He cried in/[ExtPos=SCONJ] order to make you feel bad
mark(feel, in)
fixed(in, order)
~~~

~~~ sdparse
He cried in/[ExtPos=SCONJ] order that you might feel bad
mark(feel, in)
fixed(in, order)
~~~

~~~ sdparse
He cried in/[ExtPos=SCONJ] order for you to have something to feel bad about
mark(have, in)
fixed(in, order)
~~~

*so as to*

~~~ sdparse
John left early so/[ExtPos=SCONJ] as to miss the meeting
fixed(so, as)
fixed(so, to)
mark(miss, so)
~~~

*so that*

~~~ sdparse
He cried so/[ExtPos=SCONJ] that you would feel bad
mark(feel, so)
fixed(so, that)
~~~

*such that*

~~~ sdparse
Let the rectangle KL be applied to DE such/[ExtPos=SCONJ] that KL equals BC
mark(equals, such)
fixed(such, that)
~~~


### Spatiotemporal markers

*in between*

~~~ sdparse
John left in/ADP[ExtPos=ADP] between/ADP meetings
fixed(in, between)
case(meetings, in)
~~~

*prior to*

~~~ sdparse
John left prior/ADJ[ExtPos=ADP] to/ADP the meeting
fixed(prior, to)
case(meeting, prior)
~~~

*on board*

~~~ sdparse
on/ADP[ExtPos=ADP] board/NOUN the ship
fixed(on, board)
case(ship, on)
~~~


### Circumstantial/conditional connectives

*in case*

~~~ sdparse
I always back up my files in/[ExtPos=SCONJ] case my computer crashes
fixed(in, case)
mark(crashes, in)
~~~

~~~ sdparse
I always back up my files just in/[ExtPos=ADV] case
fixed(in, case)
advmod(back, in)
advmod(in, just)
~~~

*in case of*

~~~ sdparse
I always back up my files in/[ExtPos=ADP] case of a crash
fixed(in, case)
fixed(in, of)
case(crash, in)
~~~

*whether or not*

~~~ sdparse
He 's crying whether/[ExtPos=SCONJ] or not you feel bad about it
fixed(whether, or)
fixed(whether, not)
mark(feel, whether)
~~~


### Approximators (quantity modifiers)

*more than* (when used synonymously with "over" in a quantity)

~~~ sdparse
More/[ExtPos=ADV] than 90 percent
advmod(percent, More)
fixed(More, than)
~~~

*less than* (when used synonymously with "under" in a quantity)

~~~ sdparse
Less/[ExtPos=ADV] than ten percent
advmod(percent, Less)
fixed(Less, than)
~~~

*up to* (when used in quantities)

~~~ sdparse
Up/[ExtPos=ADV] to fifty percent
fixed(Up, to)
advmod(percent, Up)
~~~

*as many/much/few/little as* (when used in quantities)  <!-- https://github.com/UniversalDependencies/UD_English-EWT/issues/281 -->

~~~ sdparse
As/[ExtPos=ADV] much as fifty percent
fixed(As, much)
fixed(As, as)
advmod(percent, As)
~~~

*all of* (when used in quantities)

~~~ sdparse
All/[ExtPos=ADV] of ten minutes
fixed(All, of)
advmod(minutes, All)
~~~

### Attributional markers

*according to*

~~~ sdparse
According/[ExtPos=ADP] to John
fixed(According, to)
case(John, According)
~~~


### Exemplification

*such as*

~~~ sdparse
I like fluffy animals , such/[ExtPos=ADP] as dogs
case(dogs, such)
fixed(such, as)
~~~


## Reciprocal Pronouns

The first word is marked as [PronType]()=`Rcp`. See discussion at [PRON]().

*each other*

~~~ sdparse
They saw each/DET[ExtPos=PRON] other/ADJ
fixed(each, other)
obj(saw, each)
~~~

*one another*

~~~ sdparse
They saw one/PRON[ExtPos=PRON] another/DET
fixed(one, another)
obj(saw, one)
~~~


### Pragmatic/miscellaneous markers

*all but*

~~~ sdparse
John has all/DET[ExtPos=ADV] but/ADP left
fixed(all, but)
advmod(left, all)
~~~

*as for*

~~~ sdparse
As/[ExtPos=ADP] for me , I love dogs!
fixed(As, for)
case(me, As)
obl(love, me)
~~~

*as if*

~~~ sdparse
It was as/[ExtPos=SCONJ] if he cried to make you feel bad
fixed(as, if)
mark(cried, as)
~~~

*as opposed to*

~~~ sdparse
John decided to leave early , as/[ExtPos=ADP] opposed to Mary
fixed(as, opposed)
fixed(as, to-9)
case(Mary, as)
~~~

*as to*

~~~ sdparse
As/[ExtPos=SCONJ] to whether I love dogs ...
fixed(As, to)
mark(love, As)
~~~

~~~ sdparse
As/[ExtPos=ADP] to my love of dogs ...
fixed(As, to)
case(love, As)
~~~

*at least* (when not used for quantities)

~~~ sdparse
At/ADP[ExtPos=ADV] least/ADJ I like dogs
fixed(At, least)
advmod(like, At)
~~~

*kind of*, *sort of* (as a hedge)

~~~ sdparse
I kind/[ExtPos=ADV] of like dogs
fixed(kind, of)
advmod(like, kind)
~~~

*in that*

~~~ sdparse
I agree in/[ExtPos=SCONJ] that the food is tasty
fixed(in, that)
mark(tasty, in)
advcl(agree, tasty)
~~~

*not to mention*

~~~ sdparse
This restaurant is pretty cheap with good food , not/[ExtPos=CCONJ] to mention their friendly staff
fixed(not, to)
fixed(not, mention)
cc(staff, not)
conj(food, staff)
~~~

*of course*

~~~ sdparse
I like dogs , of/[ExtPos=ADV] course
advmod(like, of)
fixed(of, course)
~~~

*that is*

~~~ sdparse
The dogs need to be housebroken -- that/[ExtPos=ADV] is , '' potty - trained ''
fixed(that, is)
advmod(trained, that)
~~~

## Not `fixed`
The following are **not** annotated as `fixed`, but are instead labeled according to their apparent internal structure.

*out of*, *off of* (All double prepositions denoting spatial relations are annotated with two cases on the nominal)

~~~ sdparse
Get out of there !
nmod(Get, there)
case(there, out)
case(there, of)
~~~

~~~ sdparse
Get off of that !
nmod(Get, that)
case(that, off)
case(that, of)
~~~ 

*by far*

~~~ sdparse
Dogs are the best animal by far
nmod(animal, far)
case(far, by)
~~~

*what about*

~~~ sdparse
What about John ?
nmod(What, John)
case(John, about)
~~~

*at all*

~~~ sdparse
I don't like her at all
nmod(like, all)
case(all, at)
~~~

*at most*, *at least* (when used for quantities. To determine whether *at least* should be an `fixed` or not in borderline cases, substitute it with *at most*; if the sentence remains grammatical, it should receive its surface analysis)

~~~ sdparse
at most 50 percent
nmod(percent, most)
case(most, at)
~~~

~~~ sdparse
at least 50 percent
nmod(percent, least)
case(least, at)
~~~

*at best*, *at worst*

~~~ sdparse
At/ADP best/ADV , they were guesses
nmod(guesses, best)
case(best, At)
~~~

~~~ sdparse
At/ADP worst/ADV , they were lies
nmod(lies, worst)
case(worst, At)
~~~

*what if*

~~~ sdparse
What if John left early ?
advcl(What, left)
mark(left, if)
~~~

*so long*

~~~ sdparse
So long , Ham 's ... you will be missed
advmod(long, So)
vocative(long, Ham)
parataxis(long, missed)
~~~

*nothing but X*, *anything but X*: *but* is treated as a preposition like *except* <!-- https://github.com/UniversalDependencies/UD_English-EWT/issues/272 -->

~~~ sdparse
Harriet eats nothing but tomato sandwiches
nmod(nothing, sandwiches)
case(sandwiches, but)
~~~

*compared to/with X*: *compared* is treated as a verb <!-- https://github.com/UniversalDependencies/UD_English-EWT/issues/78 -->

~~~ sdparse
This glass is tall compared to that one
advcl(tall, compared)
obl(compared, one)
case(one, to)
~~~

*as soon as*, *as long as* (standard [comparative analysis](/u/overview/specific-syntax.html#comparatives); contrast coordinating *as well as* above)

~~~ sdparse
Let 's leave as soon as it ends .
advmod(leave, soon)
advmod(soon, as-4)
advcl(soon, ends)
mark(ends, as-6)
nsubj(ends, it)
~~~

*had better* (and *'d better*) ([issue #803](https://github.com/UniversalDependencies/docs/issues/803))

~~~ sdparse
You had/AUX better/ADV apologize
aux(apologize, had)
advmod(apologize, better)
~~~

*about to* ([issue EWT#430](https://github.com/UniversalDependencies/UD_English-EWT/issues/430))

~~~ sdparse
We are/AUX about/ADJ to/PART leave
nsubj(about, We)
cop(about, are)
xcomp(about, leave)
mark(leave, to)
~~~

<!-- Interlanguage links updated Po 11. listopadu 2024, 20:10:54 CET -->
