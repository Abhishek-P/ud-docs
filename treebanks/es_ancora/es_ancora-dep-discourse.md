---
layout: base
title:  'Statistics of discourse in UD_Spanish-AnCora'
udver: '2'
---

## Treebank Statistics: UD_Spanish-AnCora: Relations: `discourse`

This relation is universal.

4 nodes (0%) are attached to their parents as `discourse`.

4 instances of `discourse` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 3.25.

The following 4 pairs of parts of speech are connected with `discourse`: <tt><a href="es_ancora-pos-ADV.html">ADV</a></tt>-<tt><a href="es_ancora-pos-INTJ.html">INTJ</a></tt> (1; 25% instances), <tt><a href="es_ancora-pos-PRON.html">PRON</a></tt>-<tt><a href="es_ancora-pos-INTJ.html">INTJ</a></tt> (1; 25% instances), <tt><a href="es_ancora-pos-VERB.html">VERB</a></tt>-<tt><a href="es_ancora-pos-INTJ.html">INTJ</a></tt> (1; 25% instances), <tt><a href="es_ancora-pos-VERB.html">VERB</a></tt>-<tt><a href="es_ancora-pos-PRON.html">PRON</a></tt> (1; 25% instances).


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 1 discourse	color:blue
1	Sí	sí	INTJ	rg	_	3	discourse	3:discourse	SpaceAfter=No
2	,	,	PUNCT	fc	PunctType=Comm	1	punct	1:punct	_
3	incluso	incluso	ADV	rg	_	0	root	0:root	_
4	a	a	ADP	sps00	_	5	mark	5:mark	_
5	rodar	rodar	VERB	vmn0000	VerbForm=Inf	3	advcl	3:advcl	Entity=(CESSCASTP20001001136c7--1
6	con	con	ADP	sps00	_	7	case	7:case	_
7	cucarachas	cucaracha	NOUN	ncfp000	Gender=Fem|Number=Plur	5	obl	5:obl	ArgTem=argM:mnr|Entity=(NOCOREF:Gen--1-gstype:gen)
8	como	como	SCONJ	cs	_	10	mark	10:mark	_
9	lo	él	PRON	pp3msa00	Case=Acc|Gender=Masc|Number=Sing|Person=3|PrepCase=Npr|PronType=Prs	10	obj	10:obj	ArgTem=arg1:pat|Entity=(CESSCASTP20001001136c7--1-CorefType:dx.token)
10	hice	hacer	VERB	vmis1s0	Mood=Ind|Number=Sing|Person=1|Tense=Past|VerbForm=Fin	5	advcl	5:advcl	ArgTem=argM:adv|Entity=CESSCASTP20001001136c7)
11	y	y	CCONJ	cc	_	28	cc	28:cc	_
12	si	si	SCONJ	cs	_	15	mark	15:mark	_
13	me	yo	PRON	pp1cs000	Case=Dat|Number=Sing|Person=1|PrepCase=Npr|PronType=Prs	15	obl:arg	15:obl:arg	ArgTem=arg2:ben|Entity=(CESSCASTP20001001136c1-person-1-CorefType:ident,gstype:spec)
14	hubiera	haber	AUX	vasi3s0	Mood=Sub|Number=Sing|Person=3|Tense=Imp|VerbForm=Fin	15	aux	15:aux	_
15	hecho	hacer	VERB	vmp00sm	Gender=Masc|Number=Sing|Tense=Past|VerbForm=Part	28	advcl	28:advcl	CxnElt=28:Conditional-NegativeEpistemic.Protasis@f
16	poner	poner	VERB	vmn0000	VerbForm=Inf	15	xcomp	15:xcomp	ArgTem=arg1:pat|Entity=(CESSCASTP20001001136c8--1
17	la	el	DET	da0fs0	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	18	det	18:det	Entity=(NOCOREF:Gen--2-gstype:gen
18	cabeza	cabeza	NOUN	ncfs000	Gender=Fem|Number=Sing	16	obj	16:obj	ArgTem=arg1:pat|Entity=NOCOREF:Gen)
19	debajo	debajo	ADV	sps00	_	22	case	22:case	MWE=debajo_de|MWEPOS=ADP
20	de	de	ADP	_	_	19	fixed	19:fixed	_
21	la	el	DET	da0fs0	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	22	det	22:det	Entity=(NOCOREF:Gen--2-gstype:gen,HomoDD
22	pata	pata	NOUN	ncfs000	Gender=Fem|Number=Sing	16	obl	16:obl	ArgTem=arg2:loc
23	de	de	ADP	sps00	_	25	case	25:case	_
24	un	uno	DET	di0ms0	Definite=Ind|Gender=Masc|Number=Sing|PronType=Art	25	det	25:det	Entity=(NOCOREF:Gen--2-gstype:gen
25	elefante	elefante	NOUN	ncms000	Gender=Masc|Number=Sing	22	nmod	22:nmod	Entity=NOCOREF:Gen)NOCOREF:Gen)CESSCASTP20001001136c8)
26	lo	él	PRON	pp3msa00	Case=Acc|Gender=Masc|Number=Sing|Person=3|PrepCase=Npr|PronType=Prs	28	obj	28:obj	ArgTem=arg1:pat|Entity=(CESSCASTP20001001136c8--1-CorefType:dx.token)
27	habría	haber	AUX	vaic3s0	Mood=Cnd|Number=Sing|Person=3|VerbForm=Fin	28	aux	28:aux	_
28	hecho	hacer	VERB	vmp00sm	Gender=Masc|Number=Sing|Tense=Past|VerbForm=Part	10	conj	10:conj	SpaceAfter=No|Cxn=Conditional-NegativeEpistemic|CxnElt=28:Conditional-NegativeEpistemic.Apodosis@p
29	.	.	PUNCT	fp	PunctType=Peri	3	punct	3:punct	_

~~~


~~~ conllu
# visual-style 21	bgColor:blue
# visual-style 21	fgColor:white
# visual-style 22	bgColor:blue
# visual-style 22	fgColor:white
# visual-style 22 21 discourse	color:blue
1	"	"	PUNCT	fe	PunctType=Quot	4	punct	4:punct	SpaceAfter=No
2	Sólo	sólo	ADV	rg	_	4	advmod	4:advmod	_
3	me	yo	PRON	pp1cs000	Case=Dat|Number=Sing|Person=1|PrepCase=Npr|PronType=Prs	4	obl:arg	4:obl:arg	ArgTem=arg2:exp|Entity=(CESSCASTP2002090211c5-person-1-CorefType:ident,gstype:spec)
4	faltaba	faltar	VERB	vmii3s0	Mood=Ind|Number=Sing|Person=3|Tense=Imp|VerbForm=Fin	44	ccomp	44:ccomp	ArgTem=arg1:pat
5	el	el	DET	da0ms0	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	6	det	6:det	Entity=(NOCOREF:Gen--2-gstype:gen
6	principio	principio	NOUN	ncms000	Gender=Masc|Number=Sing	4	nsubj	4:nsubj	SpaceAfter=No|ArgTem=arg1:tem|Entity=NOCOREF:Gen)
7	,	,	PUNCT	fc	PunctType=Comm	8	punct	8:punct	_
8	entonces	entonces	ADV	rg	_	10	advmod	10:advmod	SpaceAfter=No|ArgTem=argM:tmp
9	,	,	PUNCT	fc	PunctType=Comm	8	punct	8:punct	_
10	pongo	poner	VERB	vmip1s0	Mood=Ind|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin	4	advcl	4:advcl	_
11	la	el	DET	da0fs0	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	12	det	12:det	Entity=(NOCOREF:Gen--2-gstype:gen,HomoDD
12	radio	radio	NOUN	ncfs000	Gender=Fem|Number=Sing	10	obj	10:obj	ArgTem=arg1:pat|Entity=NOCOREF:Gen)
13	y	y	CCONJ	cc	_	14	cc	14:cc	_
14	oigo	oír	VERB	vmip1s0	Mood=Ind|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin	10	conj	10:conj	_
15	a	a	ADP	sps00	_	16	case	16:case	_
16	José	José	PROPN	np00000	_	14	obj	14:obj	MWE=José_María_García|MWEPOS=PROPN|ArgTem=arg1:pat|Entity=(NOCOREF:Spec.person-person-1-gstype:spec
17	María	María	PROPN	_	_	16	flat	16:flat	_
18	García	García	PROPN	_	_	16	flat	16:flat	Entity=NOCOREF:Spec.person)
19	diciendo	decir	VERB	vmg0000	VerbForm=Ger	14	xcomp	14:xcomp	ArgTem=argM:adv
20	'	'	PUNCT	fz	PunctType=Quot	22	punct	22:punct	SpaceAfter=No
21	Ojo	ojo	INTJ	_	_	22	discourse	22:discourse	ArgTem=arg1:pat
22	lo	él	PRON	da0ns0	Case=Acc|Definite=Def|Gender=Masc|Number=Sing|Person=3|PrepCase=Npr|PronType=Prs	19	ccomp	19:ccomp	Entity=(NOCOREF:Gen--1-gstype:gen
23	que	que	PRON	pr0cn000	PronType=Rel	25	nsubj	25:nsubj	ArgTem=arg1:tem
24	se	él	PRON	p0300000	Case=Acc|Person=3|PrepCase=Npr|PronType=Prs|Reflex=Yes	25	expl:pv	25:expl:pv	_
25	avecina	avecinar	VERB	vmip3s0	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	22	acl	22:acl	SpaceAfter=No
26	,	,	PUNCT	fc	PunctType=Comm	32	punct	32:punct	_
27	a	a	ADP	sps00	_	32	case	32:case	MWE=a_la_vuelta_de|MWEPOS=ADP
28	la	el	DET	_	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	27	fixed	27:fixed	_
29	vuelta	vuelta	NOUN	_	_	27	fixed	27:fixed	_
30	de	de	ADP	_	_	27	fixed	27:fixed	_
31	la	el	DET	da0fs0	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	32	det	32:det	_
32	esquina	esquina	NOUN	ncfs000	Gender=Fem|Number=Sing	25	obl	25:obl	SpaceAfter=No|ArgTem=arg2:loc|Entity=NOCOREF:Gen)
33	'	'	PUNCT	fz	PunctType=Quot	22	punct	22:punct	SpaceAfter=No
34	,	,	PUNCT	fc	PunctType=Comm	37	punct	37:punct	_
35	y	y	CCONJ	cc	_	37	cc	37:cc	_
36	me	yo	PRON	pp1cs000	Case=Dat|Number=Sing|Person=1|PrepCase=Npr|PronType=Prs	37	obl:arg	37:obl:arg	ArgTem=arg3:exp|Entity=(CESSCASTP2002090211c5-person-1-CorefType:ident,gstype:spec)
37	hizo	hacer	VERB	vmis3s0	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin	10	conj	10:conj	_
38	mucha	mucho	DET	di0fs0	Gender=Fem|Number=Sing|NumType=Card|PronType=Ind	39	det	39:det	Entity=(NOCOREF:Gen--2-gstype:gen
39	gracia	gracia	NOUN	ncfs000	Gender=Fem|Number=Sing	37	obj	37:obj	ArgTem=arg2:atr|Entity=NOCOREF:Gen)
40	la	el	DET	da0fs0	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	41	det	41:det	Entity=(NOCOREF:Gen--2-gstype:gen
41	rima	rima	NOUN	ncfs000	Gender=Fem|Number=Sing	37	nsubj	37:nsubj	SpaceAfter=No|ArgTem=arg1:tem|Entity=NOCOREF:Gen)
42	"	"	PUNCT	fe	PunctType=Quot	4	punct	4:punct	SpaceAfter=No
43	,	,	PUNCT	fc	PunctType=Comm	4	punct	4:punct	_
44	recuerda	recordar	VERB	vmip3s0	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	0	root	0:root	SpaceAfter=No
45	.	.	PUNCT	fp	PunctType=Peri	44	punct	44:punct	_

~~~


~~~ conllu
# visual-style 25	bgColor:blue
# visual-style 25	fgColor:white
# visual-style 33	bgColor:blue
# visual-style 33	fgColor:white
# visual-style 33 25 discourse	color:blue
1	Los	el	DET	da0mp0	Definite=Def|Gender=Masc|Number=Plur|PronType=Art	2	det	2:det	Entity=(NOCOREF:Gen--2-gstype:gen,HomoDD
2	sensacionalistas	sensacionalista	NOUN	nccp000	Number=Plur	6	nsubj	6:nsubj	ArgTem=arg1:tem|Entity=NOCOREF:Gen)
3	fueron	ser	AUX	vsis3p0	Mood=Ind|Number=Plur|Person=3|Tense=Past|VerbForm=Fin	6	cop	6:cop	_
4	aún	aún	ADV	rg	_	6	advmod	6:advmod	_
5	más	más	ADV	rg	Degree=Cmp	4	advmod	4:advmod	_
6	categóricos	categórico	ADJ	aq0mp0	Gender=Masc|Number=Plur	0	root	0:root	SpaceAfter=No|ArgTem=arg2:atr
7	:	:	PUNCT	fd	PunctType=Colo	10	punct	10:punct	_
8	The	The	PROPN	np00000	_	10	nsubj	10:nsubj	MWE=The_Sun|MWEPOS=PROPN|ArgTem=arg0:agt|Entity=(CESSCASTP2002010223c6-organization-1-gstype:spec
9	Sun	Sun	PROPN	_	_	8	flat	8:flat	Entity=CESSCASTP2002010223c6)
10	tituló	titular	VERB	vmis3s0	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin	6	parataxis	6:parataxis	_
11	su	su	DET	dp3cs0	Number=Sing|Person=3|Poss=Yes|PronType=Prs	13	det	13:det	Entity=(NOCOREF:Gen--3-gstype:gen(CESSCASTP2002010223c6-organization-1-CorefType:ident,gstype:spec)
12	primera	primero	ADJ	ao0fs0	Gender=Fem|Number=Sing|NumType=Ord	13	amod	13:amod	_
13	portada	portada	NOUN	ncfs000	Gender=Fem|Number=Sing	10	obj	10:obj	ArgTem=arg1:pat
14	de	de	ADP	spcms	_	16	case	16:case	_
15	el	el	DET	_	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	16	det	16:det	_
16	2002	2002	NOUN	_	_	13	nmod	13:nmod	Entity=(NOCOREF:Spec.date-time-1-gstype:spec)NOCOREF:Gen)
17	con	con	ADP	sps00	_	22	case	22:case	_
18	"	"	PUNCT	fe	PunctType=Quot	22	punct	22:punct	SpaceAfter=No|Entity=(NOCOREF:Spec.other-other-5-gstype:spec
19	El	el	DET	np00000	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	20	det	20:det	MWE=El_euro_ha_nacido_y_,_gracias_a_Dios_,_el_Reino_Unido_no_forma_parte_de_él|MWEPOS=PROPN|ArgTem=argM:adv
20	euro	euro	NOUN	_	_	22	nsubj	22:nsubj	_
21	ha	haber	AUX	_	VerbForm=Fin	22	aux	22:aux	_
22	nacido	nacido	VERB	_	VerbForm=Fin	10	parataxis	10:parataxis	_
23	y	y	CCONJ	_	_	33	cc	33:cc	SpaceAfter=No
24	,	,	PUNCT	_	PunctType=Comm	25	punct	25:punct	_
25	gracias	gracias	INTJ	_	_	33	discourse	33:discourse	_
26	a	a	ADP	_	_	27	case	27:case	_
27	Dios	dios	PROPN	_	_	25	obl:arg	25:obl:arg	SpaceAfter=No
28	,	,	PUNCT	_	PunctType=Comm	25	punct	25:punct	_
29	el	el	DET	_	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	30	det	30:det	_
30	Reino	reino	PROPN	_	_	33	nsubj	33:nsubj	_
31	Unido	unido	PROPN	_	_	30	flat	30:flat	_
32	no	no	PART	_	_	33	advmod	33:advmod	_
33	forma	formar	VERB	_	VerbForm=Fin	22	conj	22:conj	_
34	parte	parte	NOUN	_	_	33	obj	33:obj	_
35	de	de	ADP	_	_	36	case	36:case	_
36	él	él	PRON	_	Case=Acc,Nom|Gender=Masc|Number=Sing|Person=3|PronType=Prs	34	nmod	34:nmod	SpaceAfter=No
37	"	"	PUNCT	fe	PunctType=Quot	22	punct	22:punct	SpaceAfter=No|Entity=NOCOREF:Spec.other)
38	.	.	PUNCT	fp	PunctType=Peri	6	punct	6:punct	_

~~~


