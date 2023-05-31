---
layout: base
title:  'Statistics of flat:foreign in UD_Estonian-EDT'
udver: '2'
---

## Treebank Statistics: UD_Estonian-EDT: Relations: `flat:foreign`

This relation is a language-specific subtype of <tt><a href="et_edt-dep-flat.html">flat</a></tt>.

304 nodes (0%) are attached to their parents as `flat:foreign`.

304 instances of `flat:foreign` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.96381578947368.

The following 4 pairs of parts of speech are connected with `flat:foreign`: <tt><a href="et_edt-pos-X.html">X</a></tt>-<tt><a href="et_edt-pos-X.html">X</a></tt> (179; 59% instances), <tt><a href="et_edt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="et_edt-pos-X.html">X</a></tt> (114; 38% instances), <tt><a href="et_edt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="et_edt-pos-X.html">X</a></tt> (10; 3% instances), <tt><a href="et_edt-pos-X.html">X</a></tt>-<tt><a href="et_edt-pos-PROPN.html">PROPN</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 3 flat:foreign	color:blue
1	"	"	PUNCT	Z	_	2	punct	2:punct	SpaceAfter=No
2	Po	po	X	T	Foreign=Yes	0	root	0:root	_
3	russkii	russkii	X	T	Foreign=Yes	2	flat:foreign	2:flat	_
4	gavarish	gavarish	X	T	Foreign=Yes	2	flat:foreign	2:flat	SpaceAfter=No
5	?	?	PUNCT	Z	_	2	punct	2:punct	SpaceAfter=No
6	"	"	PUNCT	Z	_	2	punct	2:punct	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 8 flat:foreign	color:blue
1	Samalaadse	sama_laadne	ADJ	A	Case=Gen|Degree=Pos|Number=Sing	2	amod	2:amod	_
2	mõjuga	mõju	NOUN	S	Case=Com|Number=Sing	0	root	0:root	_
3	oli	olema	AUX	V	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin|Voice=Act	2	cop	2:cop	_
4	sojaõli	soja_õli	NOUN	S	Case=Nom|Number=Sing	2	nsubj:cop	2:nsubj	_
5	(	(	PUNCT	Z	_	6	punct	6:punct	SpaceAfter=No
6	Scaife	Scaife	PROPN	S	Case=Nom|Number=Sing	4	parataxis	4:parataxis	NE=B-Per
7	et	et	X	T	Foreign=Yes	6	flat	6:flat	_
8	al.	al	X	T	Abbr=Yes|Foreign=Yes	6	flat:foreign	6:flat	SpaceAfter=No
9	,	,	PUNCT	Z	_	6	punct	6:punct	_
10	1990	1990	NUM	N	NumForm=Digit|NumType=Card	6	parataxis	6:parataxis	SpaceAfter=No
11	)	)	PUNCT	Z	_	6	punct	6:punct	SpaceAfter=No
12	.	.	PUNCT	Z	_	2	punct	2:punct	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 5 flat:foreign	color:blue
1	Ainult	ainult	ADV	D	_	3	advmod	3:advmod	_
2	viieks	viis	NUM	N	Case=Tra|Number=Sing|NumForm=Word|NumType=Card	3	nummod	3:nummod	_
3	minutiks	minut	NOUN	S	Case=Tra|Number=Sing	0	root	0:root	SpaceAfter=No
4	,	,	PUNCT	Z	_	3	punct	3:punct	_
5	please	please	X	T	Foreign=Yes	3	flat:foreign	3:flat	SpaceAfter=No
6	.	.	PUNCT	Z	_	3	punct	3:punct	_

~~~


