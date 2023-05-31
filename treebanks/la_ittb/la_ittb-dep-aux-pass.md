---
layout: base
title:  'Statistics of aux:pass in UD_Latin-ITTB'
udver: '2'
---

## Treebank Statistics: UD_Latin-ITTB: Relations: `aux:pass`

This relation is a language-specific subtype of <tt><a href="la_ittb-dep-aux.html">aux</a></tt>.

2931 nodes (1%) are attached to their parents as `aux:pass`.

2199 instances of `aux:pass` (75%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.22006141248721.

The following 2 pairs of parts of speech are connected with `aux:pass`: <tt><a href="la_ittb-pos-VERB.html">VERB</a></tt>-<tt><a href="la_ittb-pos-AUX.html">AUX</a></tt> (2930; 100% instances), <tt><a href="la_ittb-pos-NOUN.html">NOUN</a></tt>-<tt><a href="la_ittb-pos-AUX.html">AUX</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 10 aux:pass	color:blue
1	tum	tum	CCONJ	O4	_	2	cc	_	_
2	etiam	etiam	ADV	O4|vgr1	_	0	root	_	_
3	propter	propter	ADP	S4	_	4	case	_	_
4	multa	multus	DET	B1|grn1|casM|gen3	Case=Acc|Gender=Neut|InflClass=IndEurO|Number=Plur|NumType=Card	2	conj	_	_
5	quae	qui	PRON	F1|grn1|casJ|gen3|vgr1	Case=Nom|Gender=Neut|InflClass=LatPron|Number=Plur|PronType=Rel	6	nsubj:pass	_	_
6	praeexiguntur	praeexigo	VERB	L3|modJ|tem1|gen9	Aspect=Imp|InflClass=LatX|Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin|Voice=Pass	4	acl:relcl	_	SpaceAfter=No|TraditionalMood=Indicativus|TraditionalTense=Praesens
7	,	,	PUNCT	Punc	_	9	punct	_	_
8	ut	ut	SCONJ	O4|vgr1	PronType=Rel	9	mark	_	_
9	dictum	dico	VERB	N2|modM|tem4|grp1|casA|gen3	Aspect=Perf|Case=Nom|Gender=Neut|InflClass=LatX|InflClass[nominal]=IndEurO|Number=Sing|VerbForm=Part|Voice=Pass	2	conj	_	TraditionalMood=Participium|TraditionalTense=Perfectum
10	est	sum	AUX	N3|modA|tem1|gen6	InflClass=LatAnom|Number=Sing|VerbForm=Fin	9	aux:pass	_	SpaceAfter=No
11	.	.	PUNCT	Punc	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 11	bgColor:blue
# visual-style 11	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 11 aux:pass	color:blue
1	recte	recte	ADV	B1|grn1|casG	_	4	advmod	_	_
2	igitur	igitur	ADV	O4	_	4	advmod	_	_
3	dici	dico	VERB	N3|modQ|tem1	Aspect=Imp|InflClass=LatX|VerbForm=Inf|Voice=Pass	4	xcomp	_	TraditionalMood=Infinitivus|TraditionalTense=Praesens
4	potest	possum	VERB	N3|modA|tem1|gen6	Aspect=Imp|InflClass=LatAnom|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	TraditionalMood=Indicativus|TraditionalTense=Praesens
5	quod	quod	SCONJ	O4	_	6	mark	_	_
6	uerbum	uerbum	NOUN	B1|grn1|casA|gen3|vgr1	Case=Nom|Gender=Neut|InflClass=IndEurO|Number=Sing	4	nsubj	_	_
7	dei	deus	PROPN	F1|grn1|casB|gen1	Case=Gen|Gender=Masc|InflClass=IndEurO|Number=Sing	6	nmod	_	SpaceAfter=No
8	,	,	PUNCT	Punc	_	9	punct	_	_
9	deus	deus	PROPN	F1|grn1|casA|gen1	Case=Nom|Gender=Masc|InflClass=IndEurO|Number=Sing	6	appos	_	SpaceAfter=No
10	,	,	PUNCT	Punc	_	11	punct	_	_
11	sit	sum	AUX	N3|modB|tem1|gen6	InflClass=LatAnom|Number=Sing|VerbForm=Fin	6	aux:pass	_	_
12	passus	patior	VERB	L2|modM|tem4|grp1|casA|gen1	Aspect=Perf|Case=Nom|Gender=Masc|InflClass=LatX|InflClass[nominal]=IndEurO|Number=Sing|VerbForm=Part|Voice=Pass	6	conj	_	TraditionalMood=Participium|TraditionalTense=Perfectum
13	et	et	CCONJ	O4	_	14	cc	_	_
14	mortuus	morior	VERB	L2|modM|tem4|grp1|casA|gen1	Aspect=Perf|Case=Nom|Gender=Masc|InflClass=LatX|InflClass[nominal]=IndEurO|Number=Sing|VerbForm=Part|Voice=Pass	6	conj	_	SpaceAfter=No|TraditionalMood=Participium|TraditionalTense=Perfectum
15	.	.	PUNCT	Punc	_	4	punct	_	_

~~~


