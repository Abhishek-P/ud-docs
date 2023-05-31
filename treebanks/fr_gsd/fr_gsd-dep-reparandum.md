---
layout: base
title:  'Statistics of reparandum in UD_French-GSD'
udver: '2'
---

## Treebank Statistics: UD_French-GSD: Relations: `reparandum`

This relation is universal.

21 nodes (0%) are attached to their parents as `reparandum`.

20 instances of `reparandum` (95%) are right-to-left (child precedes parent).
Average distance between parent and child is 2.23809523809524.

The following 13 pairs of parts of speech are connected with `reparandum`: <tt><a href="fr_gsd-pos-DET.html">DET</a></tt>-<tt><a href="fr_gsd-pos-DET.html">DET</a></tt> (3; 14% instances), <tt><a href="fr_gsd-pos-DET.html">DET</a></tt>-<tt><a href="fr_gsd-pos-ADP.html">ADP</a></tt> (2; 10% instances), <tt><a href="fr_gsd-pos-NOUN.html">NOUN</a></tt>-<tt><a href="fr_gsd-pos-ADP.html">ADP</a></tt> (2; 10% instances), <tt><a href="fr_gsd-pos-NOUN.html">NOUN</a></tt>-<tt><a href="fr_gsd-pos-DET.html">DET</a></tt> (2; 10% instances), <tt><a href="fr_gsd-pos-PRON.html">PRON</a></tt>-<tt><a href="fr_gsd-pos-PRON.html">PRON</a></tt> (2; 10% instances), <tt><a href="fr_gsd-pos-PROPN.html">PROPN</a></tt>-<tt><a href="fr_gsd-pos-ADP.html">ADP</a></tt> (2; 10% instances), <tt><a href="fr_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="fr_gsd-pos-PRON.html">PRON</a></tt> (2; 10% instances), <tt><a href="fr_gsd-pos-AUX.html">AUX</a></tt>-<tt><a href="fr_gsd-pos-VERB.html">VERB</a></tt> (1; 5% instances), <tt><a href="fr_gsd-pos-DET.html">DET</a></tt>-<tt><a href="fr_gsd-pos-PRON.html">PRON</a></tt> (1; 5% instances), <tt><a href="fr_gsd-pos-NOUN.html">NOUN</a></tt>-<tt><a href="fr_gsd-pos-AUX.html">AUX</a></tt> (1; 5% instances), <tt><a href="fr_gsd-pos-NOUN.html">NOUN</a></tt>-<tt><a href="fr_gsd-pos-CCONJ.html">CCONJ</a></tt> (1; 5% instances), <tt><a href="fr_gsd-pos-NOUN.html">NOUN</a></tt>-<tt><a href="fr_gsd-pos-X.html">X</a></tt> (1; 5% instances), <tt><a href="fr_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="fr_gsd-pos-AUX.html">AUX</a></tt> (1; 5% instances).


~~~ conllu
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 11	bgColor:blue
# visual-style 11	fgColor:white
# visual-style 11 10 reparandum	color:blue
1	Quand	quand	SCONJ	_	_	3	mark	_	wordform=quand
2	Daniel	Daniel	PROPN	_	_	3	nsubj	_	_
3	arrive	arriver	VERB	_	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	16	advcl	_	_
4	et	et	CCONJ	_	_	5	cc	_	_
5	confirme	confirmer	VERB	_	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	3	conj	_	_
6	que	que	SCONJ	_	_	8	mark	_	_
7	SG-1	SG-1	PROPN	_	_	8	nsubj	_	_
8	était	être	VERB	_	Mood=Ind|Number=Sing|Person=3|Tense=Imp|VerbForm=Fin	5	ccomp	_	_
9	dans	dans	ADP	_	_	12	case	_	_
10	des	un	DET	_	Definite=Ind|Number=Plur|PronType=Art	11	reparandum	_	_
11	ces	ce	DET	_	Number=Plur|PronType=Dem	12	det	_	_
12	vaisseaux	vaisseau	NOUN	_	Gender=Masc|Number=Plur	8	obl:arg	_	SpaceAfter=No
13	,	,	PUNCT	_	_	3	punct	_	_
14	Hammond	Hammond	PROPN	_	_	16	nsubj:caus	_	_
15	fait	faire	AUX	_	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	16	aux:caus	_	_
16	lancer	lancer	VERB	_	VerbForm=Inf	0	root	_	Subject=Generic
17	la	le	DET	_	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	18	det	_	_
18	navette	navette	NOUN	_	Gender=Fem|Number=Sing	16	obj	_	SpaceAfter=No
19	.	.	PUNCT	_	_	16	punct	_	_

~~~


~~~ conllu
# visual-style 27	bgColor:blue
# visual-style 27	fgColor:white
# visual-style 28	bgColor:blue
# visual-style 28	fgColor:white
# visual-style 28 27 reparandum	color:blue
1	Le	le	DET	_	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	2	det	_	wordform=le
2	moteur	moteur	NOUN	_	Gender=Masc|Number=Sing	7	nsubj:pass	_	_
3	à	à	ADP	_	_	4	case	_	_
4	pistons	piston	NOUN	_	Gender=Masc|Number=Plur	2	nmod	_	_
5	a	avoir	AUX	_	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	7	aux:tense	_	_
6	été	être	AUX	_	Gender=Masc|Number=Sing|Tense=Past|VerbForm=Part	7	aux:pass	_	_
7	retiré	retirer	VERB	_	Gender=Masc|Number=Sing|Tense=Past|VerbForm=Part|Voice=Pass	0	root	_	_
8	et	et	CCONJ	_	_	12	cc	_	_
9	le	le	DET	_	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	10	det	_	_
10	réacteur	réacteur	NOUN	_	Gender=Masc|Number=Sing	12	nsubj:pass	_	_
11	été	être	AUX	_	Gender=Masc|Number=Sing|Tense=Past|VerbForm=Part	12	aux:pass	_	_
12	monté	monter	VERB	_	Gender=Masc|Number=Sing|Tense=Past|VerbForm=Part|Voice=Pass	7	conj	_	_
13	sous	sous	ADP	_	_	15	case	_	_
14	l'	le	DET	_	Definite=Def|Number=Sing|PronType=Art	15	det	_	SpaceAfter=No
15	avant	avant	NOUN	_	Gender=Masc|Number=Sing	12	obl:mod	_	_
16	de	de	ADP	_	_	18	case	_	_
17	le	le	DET	_	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	18	det	_	_
18	fuselage	fuselage	NOUN	_	Gender=Masc|Number=Sing	15	nmod	_	_
19	de	de	ADP	_	_	21	case	_	_
20	telle	tel	DET	_	Gender=Fem|Number=Sing|PronType=Ind	21	det	_	_
21	sorte	sorte	NOUN	_	Gender=Fem|Number=Sing	7	obl:mod	_	_
22	que	que	SCONJ	_	_	25	mark	_	_
23	son	son	DET	_	Number=Sing|Number[psor]=Sing|Person[psor]=3|Poss=Yes|PronType=Prs	24	det	_	_
24	échappement	échappement	NOUN	_	Gender=Masc|Number=Sing	25	nsubj	_	_
25	sortait	sortir	VERB	_	Mood=Ind|Number=Sing|Person=3|Tense=Imp|VerbForm=Fin	20	ccomp	_	_
26	sous	sous	ADP	_	_	29	case	_	_
27	de	de	ADP	_	_	28	reparandum	_	_
28	le	le	DET	_	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	29	det	_	_
29	milieu	milieu	NOUN	_	Gender=Masc|Number=Sing	25	obl:mod	_	_
30	de	de	ADP	_	_	32	case	_	_
31	le	le	DET	_	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	32	det	_	_
32	fuselage	fuselage	NOUN	_	Gender=Masc|Number=Sing	29	nmod	_	SpaceAfter=No
33	.	.	PUNCT	_	_	7	punct	_	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 13	bgColor:blue
# visual-style 13	fgColor:white
# visual-style 13 8 reparandum	color:blue
1	Le	le	DET	_	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	2	det	_	wordform=le
2	Ghanéen	ghanéen	NOUN	_	Gender=Masc|Number=Sing	5	nsubj	_	wordform=ghanéen
3	Haminu	Haminu	PROPN	_	_	2	appos	_	_
4	Dramani	Dramani	PROPN	_	_	3	flat:name	_	_
5	ouvre	ouvrir	VERB	_	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
6	le	le	DET	_	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	7	det	_	_
7	score	score	NOUN	_	Gender=Masc|Number=Sing	5	obj	_	_
8	à	à	ADP	_	_	13	reparandum	_	_
9	la	le	DET	_	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	13	reparandum	_	_
10	suite	suite	NOUN	_	_	13	case	_	ExtPos=ADP|Idiom=Yes
11	à	à	ADP	_	_	10	fixed	_	InIdiom=Yes
12	une	un	DET	_	Definite=Ind|Gender=Fem|Number=Sing|PronType=Art	13	det	_	_
13	perte	perte	NOUN	_	Gender=Fem|Number=Sing	5	obl:mod	_	_
14	de	de	ADP	_	_	15	case	_	_
15	balle	balle	NOUN	_	Gender=Fem|Number=Sing	13	nmod	_	_
16	de	de	ADP	_	_	18	case	_	_
17	le	le	DET	_	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	18	det	_	_
18	milieu	milieu	NOUN	_	Gender=Masc|Number=Sing	13	nmod	_	_
19	américain	américain	ADJ	_	Gender=Masc|Number=Sing	18	amod	_	_
20	Claudio	Claudio	PROPN	_	_	18	appos	_	_
21	Reyna	Reyna	PROPN	_	_	20	flat:name	_	SpaceAfter=No
22	.	.	PUNCT	_	_	5	punct	_	_

~~~


