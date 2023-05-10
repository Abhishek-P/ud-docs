---
layout: base
title:  'Statistics of aux in UD_Latin-UDante'
udver: '2'
---

## Treebank Statistics: UD_Latin-UDante: Relations: `aux`

This relation is universal.
There are 1 language-specific subtypes of `aux`: <tt><a href="la_udante-dep-aux-pass.html">aux:pass</a></tt>.

52 nodes (0%) are attached to their parents as `aux`.

30 instances of `aux` (58%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.53846153846154.

The following 3 pairs of parts of speech are connected with `aux`: <tt><a href="la_udante-pos-VERB.html">VERB</a></tt>-<tt><a href="la_udante-pos-AUX.html">AUX</a></tt> (44; 85% instances), <tt><a href="la_udante-pos-ADJ.html">ADJ</a></tt>-<tt><a href="la_udante-pos-AUX.html">AUX</a></tt> (6; 12% instances), <tt><a href="la_udante-pos-NOUN.html">NOUN</a></tt>-<tt><a href="la_udante-pos-AUX.html">AUX</a></tt> (2; 4% instances).


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 2 aux	color:blue
1	Nulla	nullus	DET	dpfsn	Case=Nom|Gender=Fem|InflClass=LatPron|Number=Sing|Polarity=Neg|PronType=Ind	4	det	_	_
2	est	sum	AUX	va5ips3	Aspect=Imp|InflClass=LatAnom|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	3	aux	_	TraditionalMood=Indicativus|TraditionalTense=Praesens
3	cessura	cedo	VERB	va3pfsfn	Aspect=Perf|Case=Nom|Gender=Fem|InflClass=LatX|InflClass[nominal]=IndEurA|Number=Sing|VerbForm=Part|Voice=Act	0	root	_	TraditionalMood=Participium|TraditionalTense=Perfectum
4	voluptas	uoluptas	NOUN	sfs3n	Case=Nom|Gender=Fem|InflClass=IndEurX|Number=Sing	3	nsubj	_	SpaceAfter=No
5	.	.	PUNCT	Pu	_	3	punct	_	_

~~~


~~~ conllu
# visual-style 16	bgColor:blue
# visual-style 16	fgColor:white
# visual-style 17	bgColor:blue
# visual-style 17	fgColor:white
# visual-style 17 16 aux	color:blue
1	Ad	ad	ADP	e	_	4	mark	_	_
2	bene	bene	ADV	r	_	4	advmod	_	_
3	quoque	quoque	PART	r	Form=Emp	8	discourse	_	_
4	venandum	uenor	VERB	vd1fga	Aspect=Prosp|Case=Acc|Gender=Neut|InflClass=LatA|InflClass[nominal]=IndEurO|Number=Sing|VerbForm=Part|Voice=Pass	8	advcl	_	TraditionalMood=Gerundium
5	veritatem	ueritas	NOUN	sfs3a	Case=Acc|Gender=Fem|InflClass=IndEurX|Number=Sing	4	obj	_	_
6	quesiti	quaesitum	NOUN	sns2g	Case=Gen|Gender=Neut|InflClass=IndEurO|Number=Sing|VerbForm=Part	5	nmod	_	_
7	scire	scio	VERB	va4fp	Aspect=Imp|VerbForm=Inf|Voice=Act	8	csubj	_	TraditionalMood=Infinitivus|TraditionalTense=Praesens
8	oportet	oportet	VERB	va2*ips3	Aspect=Imp|InflClass=LatE|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	TraditionalMood=Indicativus|TraditionalTense=Praesens
9	quod	quod	SCONJ	cs	PronType=Rel	17	mark	_	_
10	divinum	diuinus	ADJ	ans1n	Case=Nom|Gender=Neut|InflClass=IndEurO|Number=Sing	11	amod	_	_
11	iudicium	iudicium	NOUN	sns2n	Case=Nom|Gender=Neut|InflClass=IndEurO|Number=Sing	17	nsubj:pass	_	_
12	in	in	ADP	e	_	13	case	_	_
13	rebus	res	NOUN	sfp5b	Case=Abl|Gender=Fem|InflClass=IndEurE|Number=Plur	17	obl	_	_
14	quandoque	quandoque	ADV	r	AdvType=Tim|Form=Emp|PronType=Rel	17	advmod:tmod	_	_
15	hominibus	homo	NOUN	smp3d	Case=Dat|Gender=Masc|InflClass=IndEurX|Number=Plur	17	obl	_	_
16	est	sum	AUX	va5ips3	Aspect=Imp|InflClass=LatAnom|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	17	aux	_	TraditionalMood=Indicativus|TraditionalTense=Praesens
17	manifestum	manifestus	ADJ	ans1n	Case=Nom|Compound=Yes|Gender=Neut|InflClass=IndEurO|Number=Sing	7	ccomp	_	SpaceAfter=No
18	,	,	PUNCT	Pu	_	20	punct	_	_
19	quandoque	quandoque	ADV	r	AdvType=Tim|Form=Emp|PronType=Rel	20	advmod:tmod	_	_
20	occultum	occultus	ADJ	ans1n	Case=Nom|Gender=Neut|InflClass=IndEurO|Number=Sing	17	conj	_	SpaceAfter=No
21	.	.	PUNCT	Pu	_	8	punct	_	_

~~~


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 6 aux	color:blue
1	In	in	ADP	e	_	2	case	_	_
2	principio	principium	NOUN	sns2b	Case=Abl|Gender=Neut|InflClass=IndEurO|Number=Sing	5	obl	_	_
3	huius	hic	DET	dpnsg	Case=Gen|Gender=Neut|InflClass=LatPron|Number=Sing|PronType=Dem	4	det	_	_
4	operis	opus	NOUN	sns3g	Case=Gen|Gender=Neut|InflClass=IndEurX|Number=Sing	2	nmod	_	_
5	propositum	propositum	NOUN	sns2n	Case=Nom|Gender=Neut|InflClass=IndEurO|Number=Sing	0	root	_	_
6	fuit	sum	AUX	va5irs3	Aspect=Perf|InflClass=LatAnom|Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin	5	aux	_	TraditionalMood=Indicativus|TraditionalTense=Perfectum
7	de	de	ADP	e	_	9	case	_	_
8	tribus	tres	NUM	aufpb	Case=Abl|Gender=Fem|InflClass=IndEurI|Number=Plur|NumType=Card	9	nummod	_	_
9	questionibus	quaestio	NOUN	sfp3b	Case=Abl|Gender=Fem|InflClass=IndEurX|Number=Plur	15	obl	_	SpaceAfter=No
10	,	,	PUNCT	Pu	_	9	punct	_	_
11	prout	prout	SCONJ	cs	Compound=Yes	13	mark	_	_
12	materia	materia	NOUN	sfs1n	Case=Nom|Gender=Fem|InflClass=IndEurA|Number=Sing	13	nsubj	_	_
13	pateretur	patior	VERB	vd3cis3	Aspect=Imp|InflClass=LatI2|Mood=Sub|Number=Sing|Person=3|Tense=Past|VerbForm=Fin|Voice=Pass	15	advcl	_	SpaceAfter=No|TraditionalMood=Subiunctivus|TraditionalTense=Imperfectum
14	,	,	PUNCT	Pu	_	13	punct	_	_
15	inquirere	inquiro	VERB	va3fp	Aspect=Imp|VerbForm=Inf|Voice=Act	5	ccomp	_	SpaceAfter=No|TraditionalMood=Infinitivus|TraditionalTense=Praesens
16	;	;	PUNCT	Pu	_	20	punct	_	_
17	de	de	ADP	e	_	20	case	_	_
18	quarum	qui	PRON	prepfg	Case=Gen|Gender=Fem|InflClass=LatPron|Number=Plur|PronType=Rel	20	nmod	_	_
19	duabus	duo	NUM	aufpb	Case=Abl|Gender=Fem|InflClass=IndEurA|Number=Plur|NumType=Card	20	nummod	_	_
20	primis	primus	ADJ	afp1b	Case=Abl|Gender=Fem|InflClass=IndEurA|Number=Plur|NumType=Ord	29	obl	_	_
21	in	in	ADP	e	_	23	case	_	_
22	superioribus	superior	ADJ	amp1bc	Case=Abl|Degree=Cmp|Gender=Masc|InflClass=IndEurX|Number=Plur	23	amod	_	_
23	libris	liber	NOUN	smp2b	Case=Abl|Gender=Masc|InflClass=IndEurO|Number=Plur	29	obl	_	SpaceAfter=No
24	,	,	PUNCT	Pu	_	23	punct	_	_
25	ut	ut	SCONJ	r	PronType=Rel	26	mark	_	_
26	credo	credo	VERB	va3ips1	Aspect=Imp|InflClass=LatX|Mood=Ind|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin|Voice=Act	29	advcl:cmp	_	SpaceAfter=No|TraditionalMood=Indicativus|TraditionalTense=Praesens
27	,	,	PUNCT	Pu	_	26	punct	_	_
28	sufficienter	sufficienter	ADV	r	VerbForm=Part	29	advmod	_	_
29	peractum	perago	VERB	vp3*irs3	Aspect=Perf|Case=Nom|Gender=Neut|InflClass=LatX|InflClass[nominal]=IndEurO|Number=Sing|VerbForm=Part|Voice=Pass	15	conj	_	TraditionalMood=Participium|TraditionalTense=Perfectum
30	est	sum	AUX	va5ips3	Aspect=Imp|InflClass=LatAnom|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	29	aux:pass	_	SpaceAfter=No|TraditionalMood=Indicativus|TraditionalTense=Praesens
31	.	.	PUNCT	Pu	_	5	punct	_	_

~~~


