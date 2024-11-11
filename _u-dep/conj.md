---
layout: relation
title: 'conj'
shortdef: 'conjunct'
udver: '2'
---

A conjunct is the relation between two elements connected by a
coordinating conjunction, such as _and, or,_ etc. Coordinate structures 
are in principle symmetrical, but the first conjunction is by convention 
treated as the parent (or “technical head”) of all subsequent coordinated clauses 
via the `conj` relation.

~~~ sdparse
Bill is big and honest
conj(big, honest)
~~~

<div id="punct1" class="sd-parse">
We have apples , pears , oranges , and bananas .
obj(have, apples)
conj(apples, pears)
conj(apples, oranges)
conj(apples, bananas)
cc(bananas, and)
punct(pears, ,-4)
punct(oranges, ,-6)
punct(bananas, ,-8)
</div>

Coordinated clauses are treated the same way as coordination of other constituent types:

~~~ sdparse
He came home , took a shower and immediately went to bed .
conj(came, took)
conj(came, went)
punct(took, ,-4)
cc(went, and)
~~~

Coordination may be _asyndetic,_ which means that the coordinating conjunction is omitted.
Commas or other punctuation symbols will delimit the conjuncts in the typical case.
Asyndetic coordination may be more frequent in some languages, while in others,
conjunction will appear between every two conjuncts _(John and Mary and Bill)._

~~~ sdparse
Veni , vidi , vici .
conj(Veni, vidi)
conj(Veni, vici)
punct(vidi, ,-2)
punct(vici, ,-4)
~~~

### Shared Dependents and Effective Parents in Coordination

Note that the current basic annotation scheme cannot distinguish between a dependent of the first conjunct
and a shared dependent of the whole coordination:

~~~ sdparse
He met her at the station and kissed her .
conj(met, kissed)
nsubj(met, He)
~~~

vs.

~~~ sdparse
He met her at the station and she kissed him .
conj(met, kissed)
nsubj(met, He)
nsubj(kissed, she)
~~~

In contrast, the additional dependencies in the [enhanced representation](/u/overview/enhanced-syntax.html)
can be used to encode the fact that in the first case, _he_ is also subject of _kissed:_

~~~ sdparse
He met her at the station and kissed her .
conj(met, kissed)
nsubj(met, He)
nsubj(kissed, He)
~~~

Furthermore, the enhanced representation can also capture the relation of each conjunct
to the parent of the coordination. Nevertheless, the effective parents can be found
algorithmically and showing them explicitly is for convenience only, while
the information about shared dependents is otherwise not available.

~~~ sdparse
I saw that he met her at the station and kissed her .
conj(met, kissed)
nsubj(met, he)
nsubj(kissed, he)
ccomp(saw, met)
ccomp(saw, kissed)
~~~

If a dependent is shared among conjuncts, the basic representation always links it to the
first conjunct (coordination head), while the enhanced representation shows all dependencies.
In the following example, relations that are only part of the enhanced representation are shown in red.

~~~ conllu
# visual-style 6 1 amod color:red
# visual-style 4 3 amod color:red
# visual-style 6 3 amod color:red
1 American   _ _ _ _ 4 amod 6:amod        _
2 and        _ _ _ _ 3 cc   _             _
3 British    _ _ _ _ 1 conj 4:amod|6:amod _
4 professors _ _ _ _ 0 root _             _
5 and        _ _ _ _ 6 cc   _             _
6 students   _ _ _ _ 4 conj 0:root        _
~~~

### Nested Coordination

Note further that the basic annotation scheme has only a limited capability to capture nested coordination
such as _apples and pears or oranges and lemons._
Consider coordinations

* A, B, C
* (A, B), C
* A, (B, C)

The first two cases, i.e., (A, B, C) and ((A, B), C), lead to the same tree:

~~~ sdparse
A B C
conj(A, B)
conj(A, C)
~~~

Only the right-nesting case (A, (B, C)) can be distinguished because its tree is different:

~~~ sdparse
A B C
conj(B, C)
conj(A, B)
~~~

### _Etc._

The item _etc._, used as a set-expander—especially in coordinations after at least two other items,
and typically not preceded by a conjunction (though _and etc._ is attested in English)—is treated
as a [NOUN]() and final conjunct. Its distribution is, however, atypical of nouns in that it is
restricted to enumeration contexts, does not permit modification except by reduplication, and may
be post-coordinated with things that are not nominals. Note that this guideline applies to English
and other languages that borrowed the string _etc._ from Latin. The situation may be different in
languages that have their own equivalent of _etc._ For example, German _usw. (und so weiter)_ and
Czech _atd. (a tak dále)_, both meaning literally “and so further”, are [ADV]() rather than `NOUN`,
because their main element is an adverb; yet they are still attached as [conj]() to the head of
the preceding list or coordination.

<div id="etc1" class="sd-parse">
We have apples/NOUN , pears/NOUN , etc./NOUN
nsubj(have, We)
obj(have, apples)
conj(apples, pears)
conj(apples, etc.)
punct(pears, ,-4)
punct(etc., ,-6)
</div>

<div id="usw1" class="sd-parse">
nur ein paar Minuten Fußmarsch zu Fisherman/PROPN 's Wharf , Lombard/PROPN Street , usw/ADV ...
advmod(Minuten, nur)
det(paar, ein)
det(Minuten, paar)
nmod(Minuten, Fußmarsch)
case(Fisherman, zu)
flat(Fisherman, 's)
flat(Fisherman, Wharf)
conj(Fisherman, Lombard)
punct(Lombard, ,-10)
flat(Lombard, Street)
conj(Fisherman, usw)
punct(usw, ,-13)
punct(Minuten, ...)
</div>

<div id="etc2" class="sd-parse">
People were running/VERB , jumping/VERB , dancing/VERB , etc./NOUN all around us .
nsubj(running, People)
aux(running, were)
conj(running, jumping)
conj(running, dancing)
conj(running, etc.)
punct(jumping, ,-4)
punct(dancing, ,-6)
punct(etc., ,-8)
obl(running, us)
case(us, around)
punct(running, .)
</div>

<div id="etc3" class="sd-parse">
They gave Amy an apple , Bob a banana , Carl a carrot , etc./NOUN
nsubj(gave, They)
iobj(gave, Amy)
obj(gave, apple)
conj(gave, banana)
conj(gave, carrot)
conj(gave, etc.)
orphan(banana, Bob)
orphan(carrot, Carl)
det(apple, an)
det(banana, a-8)
det(carrot, a-12)
punct(banana, ,-6)
punct(carrot, ,-10)
</div>

<div id="etc4" class="sd-parse">
It is commonplace to buy flowers etc./NOUN for Valentine 's Day .
conj(flowers, etc.)
</div>

<!-- Interlanguage links updated Po 11. listopadu 2024, 20:10:41 CET -->
