---
layout: base
title:  'Statistics of csubj:pass in UD_Latin-ITTB'
udver: '2'
---

## Treebank Statistics: UD_Latin-ITTB: Relations: `csubj:pass`

This relation is a language-specific subtype of <tt><a href="la_ittb-dep-csubj.html">csubj</a></tt>.
There are also 2 other language-specific subtypes of `csubj`: <tt><a href="la_ittb-dep-csubj-cleft.html">csubj:cleft</a></tt>, <tt><a href="la_ittb-dep-csubj-relcl.html">csubj:relcl</a></tt>.

1680 nodes (0%) are attached to their parents as `csubj:pass`.

1461 instances of `csubj:pass` (87%) are left-to-right (parent precedes child).
Average distance between parent and child is 6.96309523809524.

The following 8 pairs of parts of speech are connected with `csubj:pass`: <tt><a href="la_ittb-pos-VERB.html">VERB</a></tt>-<tt><a href="la_ittb-pos-VERB.html">VERB</a></tt> (1323; 79% instances), <tt><a href="la_ittb-pos-VERB.html">VERB</a></tt>-<tt><a href="la_ittb-pos-AUX.html">AUX</a></tt> (168; 10% instances), <tt><a href="la_ittb-pos-VERB.html">VERB</a></tt>-<tt><a href="la_ittb-pos-NOUN.html">NOUN</a></tt> (89; 5% instances), <tt><a href="la_ittb-pos-VERB.html">VERB</a></tt>-<tt><a href="la_ittb-pos-ADJ.html">ADJ</a></tt> (67; 4% instances), <tt><a href="la_ittb-pos-VERB.html">VERB</a></tt>-<tt><a href="la_ittb-pos-PRON.html">PRON</a></tt> (13; 1% instances), <tt><a href="la_ittb-pos-VERB.html">VERB</a></tt>-<tt><a href="la_ittb-pos-DET.html">DET</a></tt> (10; 1% instances), <tt><a href="la_ittb-pos-VERB.html">VERB</a></tt>-<tt><a href="la_ittb-pos-PROPN.html">PROPN</a></tt> (8; 0% instances), <tt><a href="la_ittb-pos-VERB.html">VERB</a></tt>-<tt><a href="la_ittb-pos-NUM.html">NUM</a></tt> (2; 0% instances).


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 7 csubj:pass	color:blue
1	relinquitur	relinquo	VERB	L3|modJ|tem1|gen6	Aspect=Imp|InflClass=LatX|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Pass	0	root	_	TraditionalMood=Indicativus|TraditionalTense=Praesens
2	quod	quod	SCONJ	O4	_	7	mark	_	_
3	deum	deus	PROPN	F1|grn1|casD|gen1	Case=Acc|Gender=Masc|InflClass=IndEurO|Number=Sing	4	nsubj	_	_
4	esse	sum	AUX	N3|modH|tem1	VerbForm=Inf	7	csubj:pass	_	_
5	per	per	ADP	S4	_	6	case	_	_
6	se	se	PRON	F1|grn1|casD|gen3	Case=Acc|InflClass=LatAnom|PronType=Prs|Reflex=Yes	7	obl	_	_
7	notum	nosco	VERB	L2|modM|tem4|grp1|casA|gen3	Aspect=Perf|Case=Nom|Gender=Neut|InflClass=LatX|InflClass[nominal]=IndEurO|Number=Sing|VerbForm=Part|Voice=Pass	1	csubj:pass	_	TraditionalMood=Participium|TraditionalTense=Perfectum
8	est	sum	AUX	N3|modA|tem1|gen6	InflClass=LatAnom|Number=Sing|VerbForm=Fin	7	cop	_	SpaceAfter=No
9	.	.	PUNCT	Punc	_	1	punct	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 4 csubj:pass	color:blue
1	relinquitur	relinquo	VERB	L3|modJ|tem1|gen6	Aspect=Imp|InflClass=LatX|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Pass	0	root	_	TraditionalMood=Indicativus|TraditionalTense=Praesens
2	quod	quod	SCONJ	O4	_	7	mark	_	_
3	deum	deus	PROPN	F1|grn1|casD|gen1	Case=Acc|Gender=Masc|InflClass=IndEurO|Number=Sing	4	nsubj	_	_
4	esse	sum	AUX	N3|modH|tem1	VerbForm=Inf	7	csubj:pass	_	_
5	per	per	ADP	S4	_	6	case	_	_
6	se	se	PRON	F1|grn1|casD|gen3	Case=Acc|InflClass=LatAnom|PronType=Prs|Reflex=Yes	7	obl	_	_
7	notum	nosco	VERB	L2|modM|tem4|grp1|casA|gen3	Aspect=Perf|Case=Nom|Gender=Neut|InflClass=LatX|InflClass[nominal]=IndEurO|Number=Sing|VerbForm=Part|Voice=Pass	1	csubj:pass	_	TraditionalMood=Participium|TraditionalTense=Perfectum
8	est	sum	AUX	N3|modA|tem1|gen6	InflClass=LatAnom|Number=Sing|VerbForm=Fin	7	cop	_	SpaceAfter=No
9	.	.	PUNCT	Punc	_	1	punct	_	_

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 7 csubj:pass	color:blue
1	ostensum	ostendo	VERB	L2|modM|tem4|grp1|casA|gen3	Aspect=Perf|Case=Nom|Gender=Neut|InflClass=LatX|InflClass[nominal]=IndEurO|Number=Sing|VerbForm=Part|Voice=Pass	0	root	_	TraditionalMood=Participium|TraditionalTense=Perfectum
2	autem	autem	PART	O4	_	1	discourse	_	_
3	est	sum	AUX	N3|modA|tem1|gen6	InflClass=LatAnom|Number=Sing|VerbForm=Fin	1	aux:pass	_	_
4	deum	deus	PROPN	F1|grn1|casD|gen1	Case=Acc|Gender=Masc|InflClass=IndEurO|Number=Sing	7	nsubj	_	_
5	esse	sum	AUX	N3|modH|tem1	VerbForm=Inf	7	cop	_	_
6	primam	primus	ADJ	A1|grn1|casD|gen2	Case=Acc|Gender=Fem|InflClass=IndEurA|Number=Sing|NumType=Ord	7	amod	_	_
7	causam	causa	NOUN	A1|grn1|casD|gen2|vgr1	Case=Acc|Gender=Fem|InflClass=IndEurA|Number=Sing	1	csubj:pass	_	SpaceAfter=No
8	.	.	PUNCT	Punc	_	1	punct	_	_

~~~


