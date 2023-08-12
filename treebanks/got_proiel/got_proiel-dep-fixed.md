---
layout: base
title:  'Statistics of fixed in UD_Gothic-PROIEL'
udver: '2'
---

## Treebank Statistics: UD_Gothic-PROIEL: Relations: `fixed`

This relation is universal.

11 nodes (0%) are attached to their parents as `fixed`.

11 instances of `fixed` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.18181818181818.

The following 8 pairs of parts of speech are connected with `fixed`: <tt><a href="got_proiel-pos-SCONJ.html">SCONJ</a></tt>-<tt><a href="got_proiel-pos-PRON.html">PRON</a></tt> (3; 27% instances), <tt><a href="got_proiel-pos-SCONJ.html">SCONJ</a></tt>-<tt><a href="got_proiel-pos-ADV.html">ADV</a></tt> (2; 18% instances), <tt><a href="got_proiel-pos-ADJ.html">ADJ</a></tt>-<tt><a href="got_proiel-pos-ADJ.html">ADJ</a></tt> (1; 9% instances), <tt><a href="got_proiel-pos-ADV.html">ADV</a></tt>-<tt><a href="got_proiel-pos-ADV.html">ADV</a></tt> (1; 9% instances), <tt><a href="got_proiel-pos-CCONJ.html">CCONJ</a></tt>-<tt><a href="got_proiel-pos-SCONJ.html">SCONJ</a></tt> (1; 9% instances), <tt><a href="got_proiel-pos-NUM.html">NUM</a></tt>-<tt><a href="got_proiel-pos-NUM.html">NUM</a></tt> (1; 9% instances), <tt><a href="got_proiel-pos-SCONJ.html">SCONJ</a></tt>-<tt><a href="got_proiel-pos-ADP.html">ADP</a></tt> (1; 9% instances), <tt><a href="got_proiel-pos-VERB.html">VERB</a></tt>-<tt><a href="got_proiel-pos-VERB.html">VERB</a></tt> (1; 9% instances).


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 6 fixed	color:blue
1	ahma	ahma	NOUN	Nb	Case=Nom|Gender=Masc|Number=Sing	4	nsubj	_	ref=LUKE_4.18
2	fraujins	frauja	NOUN	Nb	Case=Gen|Gender=Masc|Number=Sing	1	nmod	_	ref=LUKE_4.18
3	ana	ana	ADP	R-	_	4	case	_	ref=LUKE_4.18
4	mis	ik	PRON	Pp	Case=Dat|Gender=Masc|Number=Sing|Person=1|PronType=Prs	0	root	_	ref=LUKE_4.18
5	in	in	SCONJ	G-	_	7	mark	_	ref=LUKE_4.18
6	þizei	saei	PRON	Pr	Case=Gen|Gender=Masc|Number=Sing|PronType=Rel	5	fixed	_	ref=LUKE_4.18
7	gasalboda	ga-salbon	VERB	V-	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Pass	4	advcl	_	ref=LUKE_4.18
8	mik	ik	PRON	Pp	Case=Acc|Gender=Masc|Number=Sing|Person=1|PronType=Prs	7	obj	_	ref=LUKE_4.18
9	du	du	ADP	R-	_	10	mark	_	ref=LUKE_4.18
10	wailamerjan	wailamerjan	VERB	V-	Tense=Pres|VerbForm=Inf|Voice=Act	7	advcl	_	ref=LUKE_4.18
11	unledaim	unleþs	ADJ	A-	Case=Dat|Degree=Pos|Gender=Masc|Number=Plur|Strength=Strong	10	obl:arg	_	ref=LUKE_4.18

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 3 fixed	color:blue
1	iþ	iþ	CCONJ	C-	_	6	cc	_	ref=LUKE_10.6
2	jabai	jabai	SCONJ	G-	_	6	advcl	_	ref=LUKE_10.6
3	ni	ni	ADV	Df	Polarity=Neg	2	fixed	_	ref=LUKE_10.6
4	du	du	ADP	R-	_	5	case	_	ref=LUKE_10.6
5	izwis	jūs	PRON	Pp	Case=Dat|Gender=Fem,Masc|Number=Plur|Person=2|PronType=Prs	6	obl	_	ref=LUKE_10.6
6	gawandjai	ga-wandjan	VERB	V-	Mood=Opt|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	ref=LUKE_10.6

~~~


~~~ conllu
# visual-style 31	bgColor:blue
# visual-style 31	fgColor:white
# visual-style 30	bgColor:blue
# visual-style 30	fgColor:white
# visual-style 30 31 fixed	color:blue
1	ni	ni	ADV	Df	Polarity=Neg	3	advmod	_	ref=MARK_10.29
2	ƕashun	ƕashun	PRON	Px	Case=Nom|Gender=Masc|Number=Sing	3	nsubj	_	ref=MARK_10.29
3	ist	wisan	VERB	V-	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	ref=MARK_10.29|LId=1
4	saei	saei	PRON	Pr	Case=Nom|Gender=Masc|Number=Sing|PronType=Rel	5	nsubj	_	ref=MARK_10.29
5	aflailoti	af-letan	VERB	V-	Mood=Opt|Number=Sing|Person=3|Tense=Past|VerbForm=Fin|Voice=Act	2	acl	_	ref=MARK_10.29
6	gard	gards	NOUN	Nb	Case=Acc|Gender=Masc|Number=Sing	5	obj	_	ref=MARK_10.29
7	aiþþau	aiþþau	CCONJ	C-	_	8	cc	_	ref=MARK_10.29
8	broþruns	broþar	NOUN	Nb	Case=Acc|Gender=Masc|Number=Plur	6	conj	_	ref=MARK_10.29
9	aiþþau	aiþþau	CCONJ	C-	_	10	cc	_	ref=MARK_10.29
10	swistruns	swistar	NOUN	Nb	Case=Acc|Gender=Fem|Number=Plur	6	conj	_	ref=MARK_10.29
11	aiþþau	aiþþau	CCONJ	C-	_	12	cc	_	ref=MARK_10.29
12	aiþein	aiþei	NOUN	Nb	Case=Acc|Gender=Fem|Number=Sing	6	conj	_	ref=MARK_10.29
13	aiþþau	aiþþau	CCONJ	C-	_	14	cc	_	ref=MARK_10.29
14	attan	atta	NOUN	Nb	Case=Acc|Gender=Masc|Number=Sing	6	conj	_	ref=MARK_10.29
15	aiþþau	aiþþau	CCONJ	C-	_	16	cc	_	ref=MARK_10.29
16	qen	qens	NOUN	Nb	Case=Acc|Gender=Fem|Number=Sing	6	conj	_	ref=MARK_10.29
17	aiþþau	aiþþau	CCONJ	C-	_	18	cc	_	ref=MARK_10.29
18	barna	barn	NOUN	Nb	Case=Acc|Gender=Neut|Number=Plur	6	conj	_	ref=MARK_10.29
19	aiþþau	aiþþau	CCONJ	C-	_	20	cc	_	ref=MARK_10.29
20	haimoþlja	haimoþli	NOUN	Nb	Case=Acc|Gender=Neut|Number=Plur	6	conj	_	ref=MARK_10.29
21	in	in	ADP	R-	_	22	case	_	ref=MARK_10.29
22	meina	ik	PRON	Pp	Case=Gen|Gender=Masc|Number=Sing|Person=1|PronType=Prs	5	obl	_	ref=MARK_10.29
23	jah	jah	CCONJ	C-	_	26	cc	_	ref=MARK_10.29
24	in	in	ADP	R-	_	26	case	_	ref=MARK_10.29
25	þizos	sa	DET	Pd	Case=Gen|Gender=Fem|Number=Sing	26	det	_	ref=MARK_10.29
26	aiwaggeljons	aiwaggeljo	NOUN	Nb	Case=Gen|Gender=Fem|Number=Sing	22	conj	_	ref=MARK_10.29
27	saei	saei	PRON	Pr	Case=Nom|Gender=Masc|Number=Sing|PronType=Rel	29	nsubj	_	ref=MARK_10.30
28	ni	ni	ADV	Df	Polarity=Neg	29	advmod	_	ref=MARK_10.30
29	andnimai	and-niman	VERB	V-	Mood=Opt|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	5	conj	_	ref=MARK_10.30
30	·r·	taihuntaihundfalþs	ADJ	A-	Case=Acc|Degree=Pos|Gender=Neut|Number=Sing|Strength=Strong	29	advmod	_	ref=MARK_10.30
31	falþ	falþ	ADJ	A-	Case=Acc|Degree=Pos|Gender=Neut|Number=Sing|Strength=Strong	30	fixed	_	ref=MARK_10.30
32	nu	nu	ADV	Df	_	29	advmod	_	ref=MARK_10.30
33	in	in	ADP	R-	_	35	case	_	ref=MARK_10.30
34	þamma	sa	DET	Pd	Case=Dat|Gender=Masc,Neut|Number=Sing	35	det	_	ref=MARK_10.30
35	mela	mel	NOUN	Nb	Case=Dat|Gender=Neut|Number=Sing	29	obl	_	ref=MARK_10.30
36	gardins	gards	NOUN	Nb	Case=Acc|Gender=Masc|Number=Plur	29	obj	_	ref=MARK_10.30
37	jah	jah	CCONJ	C-	_	38	cc	_	ref=MARK_10.30
38	broþruns	broþar	NOUN	Nb	Case=Acc|Gender=Masc|Number=Plur	36	conj	_	ref=MARK_10.30
39	jah	jah	CCONJ	C-	_	40	cc	_	ref=MARK_10.30
40	swistruns	swistar	NOUN	Nb	Case=Acc|Gender=Fem|Number=Plur	36	conj	_	ref=MARK_10.30
41	jah	jah	CCONJ	C-	_	42	cc	_	ref=MARK_10.30
42	attan	atta	NOUN	Nb	Case=Acc|Gender=Masc|Number=Sing	36	conj	_	ref=MARK_10.30
43	jah	jah	CCONJ	C-	_	44	cc	_	ref=MARK_10.30
44	aiþein	aiþei	NOUN	Nb	Case=Acc|Gender=Fem|Number=Sing	36	conj	_	ref=MARK_10.30
45	jah	jah	CCONJ	C-	_	46	cc	_	ref=MARK_10.30
46	barna	barn	NOUN	Nb	Case=Acc|Gender=Neut|Number=Plur	36	conj	_	ref=MARK_10.30
47	jah	jah	CCONJ	C-	_	48	cc	_	ref=MARK_10.30
48	haimoþlja	haimoþli	NOUN	Nb	Case=Acc|Gender=Neut|Number=Plur	36	conj	_	ref=MARK_10.30
49	miþ	miþ	ADP	R-	_	50	case	_	ref=MARK_10.30
50	wrakom	wraka	NOUN	Nb	Case=Dat|Gender=Fem|Number=Plur	29	obl	_	ref=MARK_10.30
51	jah	jah	CCONJ	C-	_	56	cc	_	ref=MARK_10.30
52	in	in	ADP	R-	_	53	case	_	ref=MARK_10.30
53	aiwa	aiws	NOUN	Nb	Case=Dat|Gender=Masc|Number=Sing	56	orphan	_	ref=MARK_10.30
54	þamma	sa	DET	Pd	Case=Dat|Gender=Masc,Neut|Number=Sing	55	det	_	ref=MARK_10.30
55	anawairþin	anawairþs	ADJ	A-	Case=Dat|Degree=Pos|Gender=Masc,Neut|Number=Sing|Strength=Weak	53	nmod	_	ref=MARK_10.30
56	libain	libains	NOUN	Nb	Case=Acc|Gender=Fem|Number=Sing	29	conj	_	ref=MARK_10.30
57	aiweinon	aiweins	ADJ	A-	Case=Acc|Degree=Pos|Gender=Fem|Number=Sing|Strength=Weak	56	amod	_	ref=MARK_10.30

~~~


