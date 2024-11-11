---
layout: base
title:  'Statistics of expl:pv in UD_Czech-PDT'
udver: '2'
---

## Treebank Statistics: UD_Czech-PDT: Relations: `expl:pv`

This relation is a language-specific subtype of .
There are also 1 other language-specific subtypes of `expl`: <tt><a href="cs_pdt-dep-expl-pass.html">expl:pass</a></tt>.

3780 nodes (1%) are attached to their parents as `expl:pv`.

3101 instances of `expl:pv` (82%) are right-to-left (child precedes parent).
Average distance between parent and child is 2.30634920634921.

The following 4 pairs of parts of speech are connected with `expl:pv`: <tt><a href="cs_pdt-pos-VERB.html">VERB</a></tt>-<tt><a href="cs_pdt-pos-PRON.html">PRON</a></tt> (3674; 97% instances), <tt><a href="cs_pdt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="cs_pdt-pos-PRON.html">PRON</a></tt> (104; 3% instances), <tt><a href="cs_pdt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="cs_pdt-pos-PRON.html">PRON</a></tt> (1; 0% instances), <tt><a href="cs_pdt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="cs_pdt-pos-PRON.html">PRON</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 2 expl:pv	color:blue
1	Zdá	zdát	VERB	VB-S---3P-AAI--	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	0:root	Functor=0:PRED
2	se	se	PRON	P7-X4----------	Case=Acc|PronType=Prs|Reflex=Yes|Variant=Short	1	expl:pv	1:expl:pv	LGloss=(zvr._zájmeno/částice)
3	vám	vy	PRON	PP-P3--2-------	Case=Dat|Number=Plur|Person=2|PronType=Prs	1	obl:arg	1:obl:arg:dat	Entity=(cmpr9410009c1--1-gstype:gen)|Functor=1:ACT|SpaceAfter=No
4	,	,	PUNCT	Z:-------------	_	8	punct	8:punct	_
5	že	že	SCONJ	J,-------------	_	8	mark	8:mark	LId=že-1
6	finanční	finanční	ADJ	AAIS1----1A----	Animacy=Inan|Case=Nom|Degree=Pos|Gender=Masc|Number=Sing|Polarity=Pos	7	amod	7:amod	Functor=7:RSTR
7	úřad	úřad	NOUN	NNIS1-----A----	Animacy=Inan|Case=Nom|Gender=Masc|Number=Sing	8	nsubj	8:nsubj	Functor=8:ACT
8	nepostupoval	postupovat	VERB	VpYS----R-NAI--	Aspect=Imp|Gender=Masc|Number=Sing|Polarity=Neg|Tense=Past|VerbForm=Part|Voice=Act	1	csubj	1:csubj	Functor=1:PAT
9	správně	správně	ADV	Dg-------1A----	Degree=Pos|Polarity=Pos	8	advmod	8:advmod	SpaceAfter=No|LDeriv=správný|Functor=8:MANN
10	?	?	PUNCT	Z:-------------	_	1	punct	1:punct	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 13	bgColor:blue
# visual-style 13	fgColor:white
# visual-style 13 8 expl:pv	color:blue
1	Dá	dát	VERB	VB-S---3P-AAP--	Aspect=Perf|Mood=Ind|Number=Sing|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	0:root	LId=dát-1
2	se	se	PRON	P7-X4----------	Case=Acc|PronType=Prs|Reflex=Yes|Variant=Short	1	expl:pass	1:expl:pass	LGloss=(zvr._zájmeno/částice)
3	určit	určit	VERB	Vf--------A-P--	Aspect=Perf|Polarity=Pos|VerbForm=Inf	1	xcomp	1:xcomp	Functor=1:PRED
4	nějaký	nějaký	DET	PZYS1----------	Case=Nom|Gender=Masc|Number=Sing|PronType=Ind	5	det	5:det	Entity=(ln9420736c200--2|Functor=5:RSTR
5	mezník	mezník	NOUN	NNIS1-----A----	Animacy=Inan|Case=Nom|Gender=Masc|Number=Sing	1	nsubj:pass	1:nsubj:pass|13:obl	Functor=1:PAT|SpaceAfter=No
6	,	,	PUNCT	Z:-------------	_	13	punct	13:punct	_
7	kdy	kdy	ADV	Db-------------	PronType=Int,Rel	13	advmod	5:ref	Entity=(ln9420736c200--1)|Functor=13:TWHEN
8	si	se	PRON	P7--3----------	Case=Dat|PronType=Prs|Reflex=Yes|Variant=Short	13	expl:pv	13:expl:pv	Entity=(ln9420736c74--1-gstype:gen)|Functor=13:BEN|LGloss=(zvr._zájmeno/částice)
9	je	být	AUX	VB-S---3P-AAI--	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	13	cop	13:cop	Functor=13:RSTR
10	nevidomý	nevidomý	NOUN	NNMS1-----A----	Animacy=Anim|Case=Nom|Gender=Masc|Number=Sing	13	nsubj	13:nsubj	Entity=(ln9420736c74--1-gstype:gen)|Functor=13:ACT.cop|LId=nevidomý-2
11	sám	samý	DET	PLYS1----------	Case=Nom|Gender=Masc|Number=Sing|PronType=Emp|Variant=Short	10	xcomp	10:xcomp	LGloss=(samotný)|Functor=10:COMPL
12	sebou	se	PRON	P6--7----------	Case=Ins|PronType=Prs|Reflex=Yes	13	obl:arg	13:obl:arg:ins	Entity=(ln9420736c201--1-gstype:gen)|Functor=13:COMPL|LGloss=(zvr._zájmeno/částice)
13	jistý	jistý	ADJ	AAMS1----1A----	Animacy=Anim|Case=Nom|Degree=Pos|Gender=Masc|Number=Sing|Polarity=Pos	5	acl:relcl	5:acl:relcl	Entity=ln9420736c200)|Functor=5:PAT|SpaceAfter=No
14	?	?	PUNCT	Z:-------------	_	1	punct	1:punct	_

~~~


~~~ conllu
# visual-style 20	bgColor:blue
# visual-style 20	fgColor:white
# visual-style 19	bgColor:blue
# visual-style 19	fgColor:white
# visual-style 19 20 expl:pv	color:blue
1	V	v	ADP	RR--6----------	AdpType=Prep|Case=Loc	3	case	3:case	LId=v-1
2	takovém	takový	DET	PDZS6----------	Case=Loc|Gender=Masc,Neut|Number=Sing|PronType=Dem	3	det	3:det	_
3	případě	případ	NOUN	NNIS6-----A----	Animacy=Inan|Case=Loc|Gender=Masc|Number=Sing	7	obl	7:obl:v:loc	_
4	totiž	totiž	CCONJ	J^-------------	_	7	cc	7:cc	LId=totiž-1
5	v	v	ADP	RR--6----------	AdpType=Prep|Case=Loc	6	case	6:case	LId=v-1
6	renesanci	renesance	NOUN	NNFS6-----A----	Case=Loc|Gender=Fem|Number=Sing	7	obl	7:obl:v:loc	LGloss=(^DD**renezance)
7	nedošlo	dojít	VERB	VpNS----R-NAP--	Aspect=Perf|Gender=Neut|Number=Sing|Polarity=Neg|Tense=Past|VerbForm=Part|Voice=Act	0	root	0:root	_
8	ke	k	ADP	RV--3----------	AdpType=Voc|Case=Dat	9	case	9:case	LId=k-1
9	ztotožnění	ztotožnění	NOUN	NNNS3-----A----	Case=Dat|Gender=Neut|Number=Sing|VerbForm=Vnoun	7	obl:arg	7:obl:arg:k:dat	LDeriv=ztotožnit
10	reálného	reálný	ADJ	AAIS2----1A----	Animacy=Inan|Case=Gen|Degree=Pos|Gender=Masc|Number=Sing|Polarity=Pos	11	amod	11:amod	_
11	prostoru	prostor	NOUN	NNIS2-----A----	Animacy=Inan|Case=Gen|Gender=Masc|Number=Sing	9	nmod	9:nmod:gen	_
12	s	s	ADP	RR--7----------	AdpType=Prep|Case=Ins	13	case	13:case	LId=s-1
13	prostorem	prostor	NOUN	NNIS7-----A----	Animacy=Inan|Case=Ins|Gender=Masc|Number=Sing	9	nmod	9:nmod:s:ins	_
14	geometrickým	geometrický	ADJ	AAIS7----1A----	Animacy=Inan|Case=Ins|Degree=Pos|Gender=Masc|Number=Sing|Polarity=Pos	13	amod	13:amod	SpaceAfter=No
15	,	,	PUNCT	Z:-------------	_	19	punct	19:punct	_
16	ale	ale	CCONJ	J^-------------	_	19	cc	19:cc	_
17	jen	jen	ADV	Db-------------	_	19	advmod:emph	19:advmod:emph	LId=jen-4|LGloss=(pouze)
18	k	k	ADP	RR--3----------	AdpType=Prep|Case=Dat	19	case	19:case	LId=k-1
19	uvědomění	uvědomění	NOUN	NNNS3-----A----	Case=Dat|Gender=Neut|Number=Sing|VerbForm=Vnoun	9	conj	7:obl:arg:k:dat|9:conj	LDeriv=uvědomit
20	si	se	PRON	P7--3----------	Case=Dat|PronType=Prs|Reflex=Yes|Variant=Short	19	expl:pv	19:expl:pv	LGloss=(zvr._zájmeno/částice)
21	toho	ten	DET	PDZS2----------	Case=Gen|Gender=Masc,Neut|Number=Sing|PronType=Dem	19	amod	19:amod	SpaceAfter=No
22	,	,	PUNCT	Z:-------------	_	27	punct	27:punct	_
23	že	že	SCONJ	J,-------------	_	27	mark	27:mark	LId=že-1
24	v	v	ADP	RR--6----------	AdpType=Prep|Case=Loc	26	case	26:case	LId=v-1
25	obou	oba	NUM	CnXP6----------	Case=Loc|Number=Plur|NumForm=Word|NumType=Card	26	nummod	26:nummod	LNumValue=2
26	případech	případ	NOUN	NNIP6-----A----	Animacy=Inan|Case=Loc|Gender=Masc|Number=Plur	27	obl	27:obl:v:loc	_
27	jde	jít	VERB	VB-S---3P-AAI--	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	21	acl	21:acl:že	_
28	o	o	ADP	RR--4----------	AdpType=Prep|Case=Acc	30	case	30:case	LId=o-1
29	týž	týž	DET	PDIS4----------	Animacy=Inan|Case=Acc|Gender=Masc|Number=Sing|PronType=Dem	30	det	30:det	_
30	prostor	prostor	NOUN	NNIS4-----A----	Animacy=Inan|Case=Acc|Gender=Masc|Number=Sing	27	obl:arg	27:obl:arg:o:acc	SpaceAfter=No
31	,	,	PUNCT	Z:-------------	_	27	punct	27:punct	_
32	či	či	CCONJ	J^-------------	_	37	cc	37:cc	LId=či-1
33	lépe	lépe	ADV	Dg-------2A----	Degree=Cmp|Polarity=Pos	34	advmod	34:advmod	_
34	řečeno	řečený	ADJ	VsNS----X-APP--	Aspect=Perf|Degree=Pos|Gender=Neut|Number=Sing|Polarity=Pos|Variant=Short|VerbForm=Part|Voice=Pass	19	obl	19:obl|37:obl	SpaceAfter=No|LDeriv=říci
35	,	,	PUNCT	Z:-------------	_	34	punct	34:punct	_
36	k	k	ADP	RR--3----------	AdpType=Prep|Case=Dat	37	case	37:case	LId=k-1
37	počátkům	počátek	NOUN	NNIP3-----A----	Animacy=Inan|Case=Dat|Gender=Masc|Number=Plur	19	conj	7:obl:arg:k:dat|19:conj	_
38	cílevědomého	cílevědomý	ADJ	AANS2----1A----	Case=Gen|Degree=Pos|Gender=Neut|Number=Sing|Polarity=Pos	39	amod	39:amod	_
39	těžení	těžení	NOUN	NNNS2-----A----	Case=Gen|Gender=Neut|Number=Sing|VerbForm=Vnoun	37	nmod	37:nmod:gen	LDeriv=těžit
40	z	z	ADP	RR--2----------	AdpType=Prep|Case=Gen	41	case	41:case	LId=z-1
41	toho	ten	DET	PDZS2----------	Case=Gen|Gender=Masc,Neut|Number=Sing|PronType=Dem	39	det	39:det	SpaceAfter=No
42	,	,	PUNCT	Z:-------------	_	47	punct	47:punct	_
43	že	že	SCONJ	J,-------------	_	47	mark	47:mark	LId=že-1
44	v	v	ADP	RR--6----------	AdpType=Prep|Case=Loc	46	case	46:case	LId=v-1
45	obou	oba	NUM	CnXP6----------	Case=Loc|Number=Plur|NumForm=Word|NumType=Card	46	nummod	46:nummod	LNumValue=2
46	případech	případ	NOUN	NNIP6-----A----	Animacy=Inan|Case=Loc|Gender=Masc|Number=Plur	47	obl	47:obl:v:loc	_
47	jde	jít	VERB	VB-S---3P-AAI--	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	41	acl	41:acl:že	_
48	o	o	ADP	RR--4----------	AdpType=Prep|Case=Acc	50	case	50:case	LId=o-1
49	týž	týž	DET	PDIS4----------	Animacy=Inan|Case=Acc|Gender=Masc|Number=Sing|PronType=Dem	50	det	50:det	_
50	prostor	prostor	NOUN	NNIS4-----A----	Animacy=Inan|Case=Acc|Gender=Masc|Number=Sing	47	obl:arg	47:obl:arg:o:acc	SpaceAfter=No
51	.	.	PUNCT	Z:-------------	_	7	punct	7:punct	_

~~~


