---
layout: relation
title: 'amod'
shortdef: 'adjectival modifier'
udver: '2'
---

An adjectival modifier of a noun is any adjectival phrase that serves to modify the meaning of the noun.

Exception: if the modifying adjectival word is pronominal (i.e. tagged [uk-pos/DET]()), the relation is [det]() instead of `amod`.

~~~ sdparse
Ніна їсть зелене яблуко . \n Nina is-eating (a) green apple .
amod(яблуко, зелене)
amod(apple, green)
~~~

<!--~~~ conllu-->
<!--1	Ніна	Ніна	NPROP	NSN	_	2	nsubj	_	_-->
<!--2	їсть	їсти	VERB	VPR3s	_	0	root	_	_-->
<!--3	зелене	зелений	ADJ	ASA	_	4	amod	_	_-->
<!--4	яблуко	яблуко	NOUN	NSA	_	2	dobj	_	_-->
<!--~~~-->

~~~ sdparse
Ігор взяв десятитисячну позику . \n Igor has taken (a) ten_thousand loan .
amod(позику, десятитисячну)
amod(loan, ten_thousand)
~~~

~~~ sdparse
Перший бігун був швидкий . \n The_first racer was fast .
amod(бігун, Перший)
amod(racer, The_first)
nsubj(швидкий, бігун)
nsubj(fast, racer)
~~~

~~~ sdparse
Швидкий бігун був перший . \n The_fast racer was first .
amod(бігун, Швидкий)
amod(racer, The_fast)
nsubj(перший, бігун)
nsubj(first, racer)
~~~
<!-- Interlanguage links updated Po 11. listopadu 2024, 20:10:25 CET -->
