---
layout: base
title:  'Statistics of cop in UD_Czech-CLTT'
udver: '2'
---

## Treebank Statistics: UD_Czech-CLTT: Relations: `cop`

This relation is universal.

438 nodes (1%) are attached to their parents as `cop`.

402 instances of `cop` (92%) are right-to-left (child precedes parent).
Average distance between parent and child is 2.42009132420091.

The following 6 pairs of parts of speech are connected with `cop`: <tt><a href="cs_cltt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="cs_cltt-pos-AUX.html">AUX</a></tt> (290; 66% instances), <tt><a href="cs_cltt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="cs_cltt-pos-AUX.html">AUX</a></tt> (140; 32% instances), <tt><a href="cs_cltt-pos-PRON.html">PRON</a></tt>-<tt><a href="cs_cltt-pos-AUX.html">AUX</a></tt> (4; 1% instances), <tt><a href="cs_cltt-pos-ADV.html">ADV</a></tt>-<tt><a href="cs_cltt-pos-AUX.html">AUX</a></tt> (2; 0% instances), <tt><a href="cs_cltt-pos-DET.html">DET</a></tt>-<tt><a href="cs_cltt-pos-AUX.html">AUX</a></tt> (1; 0% instances), <tt><a href="cs_cltt-pos-NUM.html">NUM</a></tt>-<tt><a href="cs_cltt-pos-AUX.html">AUX</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 3 cop	color:blue
1	(5)	(5)	PUNCT	Z:-------------	_	4	punct	4:punct	_
2	Rezervy	rezerva	NOUN	NNFP4-----A----	Case=Acc|Gender=Fem|Number=Plur	5	obj	5:obj	_
3	není	být	AUX	VB-S---3P-AA---	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	4	cop	4:cop	_
4	možné	možný	ADJ	AANS1----1A----	Case=Nom|Degree=Pos|Gender=Neut|Number=Sing|Polarity=Pos	0	root	0:root	_
5	používat	používat	VERB	Vf--------A----	Polarity=Pos|VerbForm=Inf	4	csubj	4:csubj	_
6	k	k	ADP	RR--3----------	AdpType=Prep|Case=Dat	7	case	7:case	LId=k-1
7	úpravám	úprava	NOUN	NNFP3-----A----	Case=Dat|Gender=Fem|Number=Plur	5	obl	5:obl:k:dat	_
8	výše	výše	NOUN	NNFS2-----A----	Case=Gen|Gender=Fem|Number=Sing	7	nmod	7:nmod:gen	_
9	ocenění	ocenění	NOUN	NNNS2-----A----	Case=Gen|Gender=Neut|Number=Sing	8	nmod	8:nmod:gen	_
10	aktiv	aktivum	NOUN	NNNP2-----A----	Case=Gen|Gender=Neut|Number=Plur	9	nmod	9:nmod:gen	SpaceAfter=No|LId=aktivum-1
11	.	.	PUNCT	Z:-------------	_	4	punct	4:punct	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 4 cop	color:blue
1	Porušením	porušení	NOUN	NNNP3-----A----	Case=Dat|Gender=Neut|Number=Plur	0	root	0:root	_
2	vzájemného	vzájemný	ADJ	AANS2----1A----	Case=Gen|Degree=Pos|Gender=Neut|Number=Sing|Polarity=Pos	3	amod	3:amod	_
3	zúčtování	zúčtování	NOUN	NNNS2-----A----	Case=Gen|Gender=Neut|Number=Sing	1	nmod	1:nmod:gen	_
4	nejsou	být	AUX	VB-P---3P-NA---	Aspect=Imp|Mood=Ind|Number=Plur|Person=3|Polarity=Neg|Tense=Pres|VerbForm=Fin|Voice=Act	1	cop	1:cop	_
5	případy	případ	NOUN	NNIP1-----A----	Animacy=Inan|Case=Nom|Gender=Masc|Number=Plur	1	nsubj	1:nsubj	_
6	upravené	upravený	ADJ	AAIP1----1A----	Animacy=Inan|Case=Nom|Degree=Pos|Gender=Masc|Number=Plur|Polarity=Pos	5	amod	5:amod	_
7	účetními	účetní	ADJ	AAFP7----1A----	Case=Ins|Degree=Pos|Gender=Fem|Number=Plur|Polarity=Pos	8	amod	8:amod	LId=účetní-1
8	metodami	metoda	NOUN	NNFP7-----A----	Case=Ins|Gender=Fem|Number=Plur	6	obl:arg	6:obl:arg:ins	SpaceAfter=No
9	.	.	PUNCT	Z:-------------	_	1	punct	1:punct	_

~~~


~~~ conllu
# visual-style 11	bgColor:blue
# visual-style 11	fgColor:white
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 10 11 cop	color:blue
1	(1)	(1)	PUNCT	Z:-------------	_	22	punct	22:punct	_
2	Změny	změna	NOUN	NNFP1-----A----	Case=Nom|Gender=Fem|Number=Plur	22	nsubj:pass	22:nsubj:pass	_
3	reálné	reálný	ADJ	AAFS2----1A----	Case=Gen|Degree=Pos|Gender=Fem|Number=Sing|Polarity=Pos	4	amod	4:amod	_
4	hodnoty	hodnota	NOUN	NNFS2-----A----	Case=Gen|Gender=Fem|Number=Sing	2	nmod	2:nmod:gen	_
5	derivátů	derivát	NOUN	NNIP2-----A----	Animacy=Inan|Case=Gen|Gender=Masc|Number=Plur	4	nmod	4:nmod:gen	_
6	určených	určený	ADJ	AAIP2----1A----	Animacy=Inan|Case=Gen|Degree=Pos|Gender=Masc|Number=Plur|Polarity=Pos	5	amod	5:amod	_
7	k	k	ADP	RR--3----------	AdpType=Prep|Case=Dat	8	case	8:case	LId=k-1
8	obchodování	obchodování	NOUN	NNNS3-----A----	Case=Dat|Gender=Neut|Number=Sing	6	obl	6:obl:k:dat	SpaceAfter=No
9	,	,	PUNCT	Z:-------------	_	10	punct	10:punct	_
10	jimiž	jenž	PRON	PJXP7----------	Case=Ins|Number=Plur|PrepCase=Npr|PronType=Rel	5	acl:relcl	5:acl:relcl|5:ref	_
11	jsou	být	AUX	VB-P---3P-AA---	Aspect=Imp|Mood=Ind|Number=Plur|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	10	cop	10:cop	_
12	deriváty	derivát	NOUN	NNIP1-----A----	Animacy=Inan|Case=Nom|Gender=Masc|Number=Plur	10	nsubj	5:nsubj|10:nsubj|15:nsubj	SpaceAfter=No
13	,	,	PUNCT	Z:-------------	_	15	punct	15:punct	_
14	které	který	DET	P4IP1----------	Animacy=Inan|Case=Nom|Gender=Masc|Number=Plur|PronType=Int,Rel	15	nsubj	12:ref	_
15	nesplňují	splňovat	VERB	VB-P---3P-NA---	Mood=Ind|Number=Plur|Person=3|Polarity=Neg|Tense=Pres|VerbForm=Fin|Voice=Act	12	acl:relcl	12:acl:relcl	_
16	podmínky	podmínka	NOUN	NNFP4-----A----	Case=Acc|Gender=Fem|Number=Plur	15	obj	15:obj	_
17	uvedené	uvedený	ADJ	AAFP4----1A----	Case=Acc|Degree=Pos|Gender=Fem|Number=Plur|Polarity=Pos	16	amod	16:amod	_
18	v	v	ADP	RR--6----------	AdpType=Prep|Case=Loc	19	case	19:case	LId=v-1
19	§_52_odst._3	§_52_odst._3	X	X@-------------	_	17	obl	17:obl:v:loc	SpaceAfter=No
20	,	,	PUNCT	Z:-------------	_	15	punct	15:punct	_
21	se	se	PRON	P7-X4----------	Case=Acc|PronType=Prs|Reflex=Yes|Variant=Short	22	expl:pass	22:expl:pass	_
22	účtují	účtovat	VERB	VB-P---3P-AA---	Mood=Ind|Number=Plur|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	0:root	_
23	jako	jako	SCONJ	J,-------------	_	25	mark	25:mark|28:mark	_
24	finanční	finanční	ADJ	AAIS4----1A----	Animacy=Inan|Case=Acc|Degree=Pos|Gender=Masc|Number=Sing|Polarity=Pos	25	amod	25:amod	_
25	náklad	náklad	NOUN	NNIS4-----A----	Animacy=Inan|Case=Acc|Gender=Masc|Number=Sing	2	xcomp	2:xcomp	_
26	nebo	nebo	CCONJ	J^-------------	_	28	cc	28:cc	_
27	finanční	finanční	ADJ	AAIS4----1A----	Animacy=Inan|Case=Acc|Degree=Pos|Gender=Masc|Number=Sing|Polarity=Pos	28	amod	28:amod	_
28	výnos	výnos	NOUN	NNIS4-----A----	Animacy=Inan|Case=Acc|Gender=Masc|Number=Sing	25	conj	2:xcomp|25:conj	SpaceAfter=No
29	.	.	PUNCT	Z:-------------	_	22	punct	22:punct	_

~~~


