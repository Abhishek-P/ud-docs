---
layout: base
title:  'Statistics of amod in UD_Italian-VIT'
udver: '2'
---

## Treebank Statistics: UD_Italian-VIT: Relations: `amod`

This relation is universal.

17537 nodes (6%) are attached to their parents as `amod`.

12047 instances of `amod` (69%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.28129098477505.

The following 14 pairs of parts of speech are connected with `amod`: <tt><a href="it_vit-pos-NOUN.html">NOUN</a></tt>-<tt><a href="it_vit-pos-ADJ.html">ADJ</a></tt> (16249; 93% instances), <tt><a href="it_vit-pos-PROPN.html">PROPN</a></tt>-<tt><a href="it_vit-pos-ADJ.html">ADJ</a></tt> (436; 2% instances), <tt><a href="it_vit-pos-ADJ.html">ADJ</a></tt>-<tt><a href="it_vit-pos-ADJ.html">ADJ</a></tt> (271; 2% instances), <tt><a href="it_vit-pos-VERB.html">VERB</a></tt>-<tt><a href="it_vit-pos-ADJ.html">ADJ</a></tt> (241; 1% instances), <tt><a href="it_vit-pos-PRON.html">PRON</a></tt>-<tt><a href="it_vit-pos-ADJ.html">ADJ</a></tt> (176; 1% instances), <tt><a href="it_vit-pos-NUM.html">NUM</a></tt>-<tt><a href="it_vit-pos-ADJ.html">ADJ</a></tt> (74; 0% instances), <tt><a href="it_vit-pos-ADV.html">ADV</a></tt>-<tt><a href="it_vit-pos-ADJ.html">ADJ</a></tt> (42; 0% instances), <tt><a href="it_vit-pos-X.html">X</a></tt>-<tt><a href="it_vit-pos-ADJ.html">ADJ</a></tt> (20; 0% instances), <tt><a href="it_vit-pos-SYM.html">SYM</a></tt>-<tt><a href="it_vit-pos-ADJ.html">ADJ</a></tt> (19; 0% instances), <tt><a href="it_vit-pos-CCONJ.html">CCONJ</a></tt>-<tt><a href="it_vit-pos-ADJ.html">ADJ</a></tt> (2; 0% instances), <tt><a href="it_vit-pos-NOUN.html">NOUN</a></tt>-<tt><a href="it_vit-pos-ADV.html">ADV</a></tt> (2; 0% instances), <tt><a href="it_vit-pos-NOUN.html">NOUN</a></tt>-<tt><a href="it_vit-pos-NOUN.html">NOUN</a></tt> (2; 0% instances), <tt><a href="it_vit-pos-SCONJ.html">SCONJ</a></tt>-<tt><a href="it_vit-pos-ADJ.html">ADJ</a></tt> (2; 0% instances), <tt><a href="it_vit-pos-DET.html">DET</a></tt>-<tt><a href="it_vit-pos-ADJ.html">ADJ</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 4 amod	color:blue
1	Ha	avere	VERB	V	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
2	l'	il	DET	RD	Definite=Def|Number=Sing|PronType=Art	3	det	_	SpaceAfter=No
3	acqua	acqua	NOUN	S	Gender=Fem|Number=Sing	1	obj	_	_
4	calda	caldo	ADJ	A	Gender=Fem|Number=Sing	3	amod	_	SpaceAfter=No
5	,	,	PUNCT	FF	_	10	punct	_	_
6	più	più	ADV	B	_	10	advmod	_	_
7	o	o	CCONJ	CC	_	8	cc	_	_
8	meno	meno	ADV	B	_	6	conj	_	_
9	si	si	PRON	PC	Clitic=Yes|Person=3|PronType=Prs	10	expl	_	_
10	veste	vestire	VERB	V	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	1	conj	_	SpaceAfter=No
11	.	.	PUNCT	FS	_	1	punct	_	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 2 amod	color:blue
1	Signori	Signori	PROPN	SP	_	0	root	_	_
2	ottimista	ottimista	ADJ	A	Number=Sing	1	amod	_	SpaceAfter=No
3	,	,	PUNCT	FF	_	4	punct	_	_
4	Zeman	Zeman	PROPN	SP	_	1	conj	_	_
5	velenoso	velenoso	ADJ	A	Gender=Masc|Number=Sing	4	amod	_	SpaceAfter=No
6	:	:	PUNCT	FC	_	4	punct	_	_
7	assurdo	assurdo	ADJ	A	Gender=Masc|Number=Sing	9	amod	_	SpaceAfter=No
8	,	,	PUNCT	FF	_	9	punct	_	_
9	Balbo	Balbo	PROPN	SP	_	4	appos	_	_
10	italiano	italiano	ADJ	A	Gender=Masc|Number=Sing	9	amod	_	SpaceAfter=No
11	"	"	PUNCT	FB	_	9	punct	_	SpaceAfter=No
12	.	.	PUNCT	FS	_	1	punct	_	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 5 amod	color:blue
1	sono	essere	AUX	VA	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	2	cop	_	_
2	cose	cosa	NOUN	S	Gender=Fem|Number=Plur	0	root	_	_
3	dette	detto	ADJ	A	Gender=Fem|Number=Plur	2	amod	_	_
4	e	e	CCONJ	CC	_	5	cc	_	_
5	ridette	ridetto	ADJ	A	Gender=Fem|Number=Plur	3	amod	_	SpaceAfter=No
6	,	,	PUNCT	FF	_	7	punct	_	_
7	note	noto	ADJ	A	Gender=Fem|Number=Plur	3	conj	_	_
8	e	e	CCONJ	CC	_	9	cc	_	_
9	stranote	stranoto	ADJ	A	Gender=Fem|Number=Plur	3	conj	_	SpaceAfter=No
10	.	.	PUNCT	FS	_	2	punct	_	_

~~~


