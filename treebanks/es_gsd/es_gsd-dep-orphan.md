---
layout: base
title:  'Statistics of orphan in UD_Spanish-GSD'
udver: '2'
---

## Treebank Statistics: UD_Spanish-GSD: Relations: `orphan`

This relation is universal.

2 nodes (0%) are attached to their parents as `orphan`.

2 instances of `orphan` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 2.

The following 2 pairs of parts of speech are connected with `orphan`: <tt><a href="es_gsd-pos-ADV.html">ADV</a></tt>-<tt><a href="es_gsd-pos-NOUN.html">NOUN</a></tt> (1; 50% instances), <tt><a href="es_gsd-pos-PROPN.html">PROPN</a></tt>-<tt><a href="es_gsd-pos-DET.html">DET</a></tt> (1; 50% instances).


~~~ conllu
# visual-style 41	bgColor:blue
# visual-style 41	fgColor:white
# visual-style 40	bgColor:blue
# visual-style 40	fgColor:white
# visual-style 40 41 orphan	color:blue
1	Mora	mora	PROPN	_	_	4	nsubj	_	_
2	es	ser	AUX	_	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	4	cop	_	_
3	el	el	DET	_	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	4	det	_	_
4	cantón	cantón	NOUN	_	Gender=Masc|Number=Sing	0	root	_	_
5	número	número	NOUN	_	Gender=Masc|Number=Sing	4	appos	_	_
6	7	7	NUM	_	NumType=Card	5	appos	_	_
7	de	de	ADP	_	_	9	case	_	_
8	la	el	DET	_	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	9	det	_	_
9	provincia	provincia	NOUN	_	Gender=Fem|Number=Sing	4	nmod	_	_
10	de	de	ADP	_	_	12	case	_	_
11	San	san	PROPN	_	_	12	amod	_	_
12	José	josé	PROPN	_	_	9	nmod	_	SpaceAfter=No
13	,	,	PUNCT	_	_	14	punct	_	_
14	Costa	costa	PROPN	_	_	9	appos	_	_
15	Rica	rica	PROPN	_	_	14	amod	_	SpaceAfter=No
16	,	,	PUNCT	_	_	17	punct	_	_
17	establecido	establecer	VERB	_	Gender=Masc|Number=Sing|VerbForm=Part	4	acl	_	_
18	en	en	ADP	_	_	19	case	_	_
19	1883	1883	NUM	_	NumType=Card	17	obl	_	_
20	con	con	ADP	_	_	22	case	_	_
21	el	el	DET	_	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	22	det	_	_
22	nombre	nombre	NOUN	_	Gender=Masc|Number=Sing	17	obl	_	_
23	indígena	indígeno	ADJ	_	Gender=Masc|Number=Sing	22	amod	_	_
24	de	de	ADP	_	_	25	case	_	_
25	Pacaca	pacaca	PROPN	_	_	22	nmod	_	SpaceAfter=No
26	,	,	PUNCT	_	_	31	punct	_	_
27	que	que	SCONJ	_	_	31	mark	_	_
28	en	en	ADP	_	_	30	case	_	_
29	esa	ese	DET	_	Gender=Fem|Number=Sing|PronType=Dem	30	det	_	_
30	época	época	NOUN	_	Gender=Fem|Number=Sing	31	obl	_	_
31	llevaba	llevar	VERB	_	Mood=Ind|Number=Sing|Person=3|Tense=Imp|VerbForm=Fin	4	acl:relcl	_	_
32	la	el	DET	_	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	33	det	_	_
33	población	población	NOUN	_	Gender=Fem|Number=Sing	31	obj	_	_
34	cabecera	cabecero	ADJ	_	Gender=Fem|Number=Sing	33	amod	_	_
35	posteriormente	posteriormente	ADV	_	_	36	advmod	_	_
36	denominada	denominar	VERB	_	Gender=Fem|Number=Sing|VerbForm=Part	33	acl	_	_
37	Villa	Villa	PROPN	_	_	36	xcomp	_	_
38	Colón	Colón	PROPN	_	_	37	flat	_	_
39	y	y	CCONJ	_	_	40	cc	_	_
40	actualmente	actualmente	ADV	_	_	36	conj	_	_
41	Ciudad	ciudad	NOUN	_	Gender=Fem|Number=Sing	40	orphan	_	_
42	Colón	Colón	PROPN	_	_	41	flat	_	SpaceAfter=No
43	.	.	PUNCT	_	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 36	bgColor:blue
# visual-style 36	fgColor:white
# visual-style 33	bgColor:blue
# visual-style 33	fgColor:white
# visual-style 33 36 orphan	color:blue
1	En	en	ADP	_	_	3	case	_	_
2	la	el	DET	_	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	3	det	_	_
3	práctica	práctica	NOUN	_	Gender=Fem|Number=Sing	16	obl	_	_
4	de	de	ADP	_	_	5	case	_	_
5	artes	arte	NOUN	_	Number=Plur	3	nmod	_	_
6	marciales	marcial	ADJ	_	Number=Plur	5	amod	_	SpaceAfter=No
7	,	,	PUNCT	_	_	11	punct	_	_
8	cuando	cuando	SCONJ	_	_	11	mark	_	_
9	los	el	DET	_	Definite=Def|Gender=Masc|Number=Plur|PronType=Art	10	det	_	_
10	practicantes	practicante	NOUN	_	Number=Plur	11	nsubj	_	_
11	trabajan	trabajar	VERB	_	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	16	advcl	_	_
12	por	por	ADP	_	_	13	case	_	_
13	parejas	pareja	NOUN	_	Gender=Fem|Number=Plur	11	obl	_	SpaceAfter=No
14	,	,	PUNCT	_	_	11	punct	_	_
15	se	él	PRON	_	Case=Acc,Dat|Person=3|PrepCase=Npr|PronType=Prs|Reflex=Yes	16	expl:pv	_	_
16	llama	llamar	VERB	_	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
17	nage	nage	PROPN	_	Gender=Masc|Number=Sing	16	xcomp	_	SpaceAfter=No
18	,	,	PUNCT	_	_	22	punct	_	_
19	o	o	CCONJ	_	_	22	cc	_	_
20	en	en	ADP	_	_	22	case	_	_
21	algunas	alguno	DET	_	Gender=Fem|Number=Plur|PronType=Ind	22	det	_	_
22	disciplinas	disciplina	NOUN	_	Gender=Fem|Number=Plur	17	conj	_	_
23	tori	tori	PROPN	_	_	22	conj	_	SpaceAfter=No
24	,	,	PUNCT	_	_	26	punct	_	_
25	a	a	ADP	_	_	26	case	_	_
26	aquel	aquel	PRON	_	Gender=Masc|Number=Sing|PronType=Dem	16	obl:arg	_	_
27	que	que	SCONJ	_	_	28	mark	_	_
28	aplica	aplicar	VERB	_	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	26	acl:relcl	_	_
29	una	uno	DET	_	Definite=Ind|Gender=Fem|Number=Sing|PronType=Art	30	det	_	_
30	técnica	técnica	NOUN	_	Gender=Fem|Number=Sing	28	obj	_	_
31	determinada	determinado	ADJ	_	Gender=Fem|Number=Sing|VerbForm=Part	30	amod	_	_
32	y	y	CCONJ	_	_	33	cc	_	_
33	uke	uke	PROPN	_	_	16	conj	_	SpaceAfter=No
34	,	,	PUNCT	_	_	36	punct	_	_
35	a	a	ADP	_	_	36	case	_	_
36	el	el	DET	_	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	33	orphan	_	_
37	que	que	PRON	_	PronType=Rel	38	nsubj	_	_
38	recibe	recibir	VERB	_	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	36	acl:relcl	_	_
39	la	el	DET	_	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	40	det	_	_
40	técnica	técnica	NOUN	_	Gender=Fem|Number=Sing	38	obj	_	SpaceAfter=No
41	.	.	PUNCT	_	_	16	punct	_	_

~~~


