---
layout: base
title:  'Statistics of aux in UD_Icelandic-IcePaHC'
udver: '2'
---

## Treebank Statistics: UD_Icelandic-IcePaHC: Relations: `aux`

This relation is universal.

19915 nodes (2%) are attached to their parents as `aux`.

17467 instances of `aux` (88%) are right-to-left (child precedes parent).
Average distance between parent and child is 2.18026613105699.

The following 13 pairs of parts of speech are connected with `aux`: <tt><a href="is_icepahc-pos-VERB.html">VERB</a></tt>-<tt><a href="is_icepahc-pos-AUX.html">AUX</a></tt> (17759; 89% instances), <tt><a href="is_icepahc-pos-AUX.html">AUX</a></tt>-<tt><a href="is_icepahc-pos-AUX.html">AUX</a></tt> (657; 3% instances), <tt><a href="is_icepahc-pos-PRON.html">PRON</a></tt>-<tt><a href="is_icepahc-pos-AUX.html">AUX</a></tt> (413; 2% instances), <tt><a href="is_icepahc-pos-ADJ.html">ADJ</a></tt>-<tt><a href="is_icepahc-pos-AUX.html">AUX</a></tt> (306; 2% instances), <tt><a href="is_icepahc-pos-ADV.html">ADV</a></tt>-<tt><a href="is_icepahc-pos-AUX.html">AUX</a></tt> (235; 1% instances), <tt><a href="is_icepahc-pos-PART.html">PART</a></tt>-<tt><a href="is_icepahc-pos-AUX.html">AUX</a></tt> (222; 1% instances), <tt><a href="is_icepahc-pos-NOUN.html">NOUN</a></tt>-<tt><a href="is_icepahc-pos-AUX.html">AUX</a></tt> (200; 1% instances), <tt><a href="is_icepahc-pos-DET.html">DET</a></tt>-<tt><a href="is_icepahc-pos-AUX.html">AUX</a></tt> (48; 0% instances), <tt><a href="is_icepahc-pos-CCONJ.html">CCONJ</a></tt>-<tt><a href="is_icepahc-pos-AUX.html">AUX</a></tt> (32; 0% instances), <tt><a href="is_icepahc-pos-PROPN.html">PROPN</a></tt>-<tt><a href="is_icepahc-pos-AUX.html">AUX</a></tt> (21; 0% instances), <tt><a href="is_icepahc-pos-ADP.html">ADP</a></tt>-<tt><a href="is_icepahc-pos-AUX.html">AUX</a></tt> (20; 0% instances), <tt><a href="is_icepahc-pos-INTJ.html">INTJ</a></tt>-<tt><a href="is_icepahc-pos-AUX.html">AUX</a></tt> (1; 0% instances), <tt><a href="is_icepahc-pos-NUM.html">NUM</a></tt>-<tt><a href="is_icepahc-pos-AUX.html">AUX</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 1 aux	color:blue
1	Skal	skulu	AUX	MDPI	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	5	aux	_	IFD_tag=sfg3en
2	maður	maður	NOUN	N-N	Case=Nom|Definite=Ind|Gender=Masc|Number=Sing	5	nsubj	_	IFD_tag=nken
3	eftir	eftir	ADP	P	_	4	case	_	IFD_tag=ao
4	mann	maður	NOUN	N-A	Case=Acc|Definite=Ind|Gender=Masc|Number=Sing	5	obl	_	IFD_tag=nkeo
5	lifa	lifa	VERB	VB	VerbForm=Inf|Voice=Act	0	root	_	IFD_tag=sng|SpaceAfter=No
6	.	.	PUNCT	.	_	5	punct	_	IFD_tag=.

~~~


~~~ conllu
# visual-style 11	bgColor:blue
# visual-style 11	fgColor:white
# visual-style 12	bgColor:blue
# visual-style 12	fgColor:white
# visual-style 12 11 aux	color:blue
1	segir	segja	VERB	VBPI	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	IFD_tag=sfg3en
2	að	að	SCONJ	C	_	5	mark	_	IFD_tag=c
3	þeirra	það	PRON	PRO-G	Case=Gen|Gender=Fem|Number=Plur|PronType=Dem	4	nmod:poss	_	IFD_tag=favfe
4	vinátta	vinátta	NOUN	N-N	Case=Nom|Definite=Ind|Gender=Fem|Number=Sing	5	nsubj	_	IFD_tag=nven
5	skal	skulu	AUX	MDPI	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	1	ccomp	_	IFD_tag=sfg3en
6	nú	nú	ADV	ADV	_	5	advmod	_	IFD_tag=aa
7	sýnu	sýnn	ADJ	ADJ-D	Case=Dat|Definite=Ind|Degree=Pos|Gender=Neut|Number=Sing	8	obl	_	IFD_tag=lheþsf
8	betri	góður	ADJ	ADJR-N	Case=Nom|Definite=Def|Degree=Cmp|Gender=Fem|Number=Sing	5	amod	_	IFD_tag=lvenvm
9	en	en	SCONJ	P	_	12	mark	_	IFD_tag=c
10	áður	áður	ADV	ADV	_	12	advmod	_	IFD_tag=aa
11	hefur	hafa	AUX	HVPI	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	12	aux	_	IFD_tag=sfg3en
12	verið	vera	AUX	BEN	VerbForm=Sup|Voice=Act	8	advcl	_	IFD_tag=ssg|SpaceAfter=No
13	.	.	PUNCT	.	_	12	punct	_	IFD_tag=.

~~~


~~~ conllu
# visual-style 13	bgColor:blue
# visual-style 13	fgColor:white
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 10 13 aux	color:blue
1	eða	eða	CCONJ	CONJ	_	3	cc	_	IFD_tag=c
2	er	vera	AUX	BEPI	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	3	cop	_	IFD_tag=sfg3en
3	sumt	sumur	DET	Q-N	Case=Nom|Gender=Neut|Number=Sing|PronType=Ind	0	root	_	IFD_tag=fohen
4	af	af	ADP	P	_	5	case	_	IFD_tag=aþ
5	hégóma	hégómi	NOUN	N-D	Case=Dat|Definite=Ind|Gender=Masc|Number=Sing	3	obl	_	IFD_tag=nkeþ
6	við	við	ADP	RP	_	3	compound:prt	_	IFD_tag=aa
7	þótt	þótt	SCONJ	P	_	9	mark	_	IFD_tag=c
8	ég	ég	PRON	PRO-N	Case=Nom|Number=Sing|Person=1|PronType=Prs	9	nsubj	_	IFD_tag=fp1en
9	ætla	ætla	VERB	VBPI	Mood=Ind|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin|Voice=Act	3	advcl	_	IFD_tag=sfg1en
10	það	það	PRON	PRO-A	Case=Acc|Gender=Neut|Number=Sing|PronType=Prs	9	acl	_	IFD_tag=fpheo
11	síður	síður	ADV	ADVR	Degree=Cmp	10	advmod	_	IFD_tag=aam
12	vera	vera	AUX	BE	VerbForm=Inf|Voice=Act	10	cop	_	IFD_tag=sng
13	munu	munu	AUX	MD	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	10	aux	_	IFD_tag=sfg3fn|SpaceAfter=No
14	.	.	PUNCT	.	_	13	punct	_	IFD_tag=.

~~~


