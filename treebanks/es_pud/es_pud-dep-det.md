---
layout: base
title:  'Statistics of det in UD_Spanish-PUD'
udver: '2'
---

## Treebank Statistics: UD_Spanish-PUD: Relations: `det`

This relation is universal.

3503 nodes (15%) are attached to their parents as `det`.

3503 instances of `det` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.11904082215244.

The following 12 pairs of parts of speech are connected with `det`: <tt><a href="es_pud-pos-NOUN.html">NOUN</a></tt>-<tt><a href="es_pud-pos-DET.html">DET</a></tt> (2963; 85% instances), <tt><a href="es_pud-pos-NOUN.html">NOUN</a></tt>-<tt><a href="es_pud-pos-PRON.html">PRON</a></tt> (257; 7% instances), <tt><a href="es_pud-pos-PROPN.html">PROPN</a></tt>-<tt><a href="es_pud-pos-DET.html">DET</a></tt> (112; 3% instances), <tt><a href="es_pud-pos-NUM.html">NUM</a></tt>-<tt><a href="es_pud-pos-DET.html">DET</a></tt> (51; 1% instances), <tt><a href="es_pud-pos-PRON.html">PRON</a></tt>-<tt><a href="es_pud-pos-DET.html">DET</a></tt> (51; 1% instances), <tt><a href="es_pud-pos-PRON.html">PRON</a></tt>-<tt><a href="es_pud-pos-PRON.html">PRON</a></tt> (25; 1% instances), <tt><a href="es_pud-pos-VERB.html">VERB</a></tt>-<tt><a href="es_pud-pos-DET.html">DET</a></tt> (20; 1% instances), <tt><a href="es_pud-pos-SYM.html">SYM</a></tt>-<tt><a href="es_pud-pos-DET.html">DET</a></tt> (19; 1% instances), <tt><a href="es_pud-pos-ADV.html">ADV</a></tt>-<tt><a href="es_pud-pos-DET.html">DET</a></tt> (2; 0% instances), <tt><a href="es_pud-pos-DET.html">DET</a></tt>-<tt><a href="es_pud-pos-DET.html">DET</a></tt> (1; 0% instances), <tt><a href="es_pud-pos-PROPN.html">PROPN</a></tt>-<tt><a href="es_pud-pos-PRON.html">PRON</a></tt> (1; 0% instances), <tt><a href="es_pud-pos-X.html">X</a></tt>-<tt><a href="es_pud-pos-DET.html">DET</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 1 det	color:blue
1	El	el	DET	DT	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	2	det	_	_
2	máximo	máximo	NOUN	NN	Gender=Masc|Number=Sing	4	nsubj	_	_
3	permitido	permitir	VERB	VBN	Gender=Masc|Number=Sing|Tense=Past|VerbForm=Part	2	acl	_	_
4	es	ser	VERB	VBC	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
5	de	de	ADP	IN	_	7	case	_	_
6	5 000	5 000	NUM	CD	Gender=Masc|NumForm=Digit|NumType=Card	7	nummod	_	_
7	$	$	NOUN	NN	Gender=Masc|Number=Plur	4	obl	_	_
8	por	por	ADP	IN	_	9	case	_	_
9	persona	persona	NOUN	NN	Gender=Fem|Number=Sing	7	nmod	_	SpaceAfter=No
10	.	.	PUNCT	.	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 8 det	color:blue
1	Eso	eso	DET	DT	Gender=Masc|Number=Sing|PronType=Dem	2	nsubj	_	_
2	es	ser	VERB	VBC	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
3	lo	él	PRON	DT	Case=Acc|Gender=Masc|Number=Sing|Person=3|PrepCase=Npr|PronType=Prs	4	det	_	_
4	que	que	PRON	REL	Gender=Masc|Number=Sing|PronType=Rel	6	obj	_	_
5	no	no	ADV	RB	Polarity=Neg	6	advmod	_	_
6	necesitamos	necesitar	VERB	VBC	Mood=Ind|Number=Plur|Person=1|Tense=Pres|VerbForm=Fin	2	ccomp	_	_
7	en	en	ADP	IN	_	9	case	_	_
8	nuestro	nuestro	PRON	DTP$	Gender=Masc|Number=Sing|Person=1|Poss=Yes|PronType=Prs	9	det	_	_
9	país	país	NOUN	NN	Gender=Masc|Number=Sing	6	obl	_	SpaceAfter=No
10	,	,	PUNCT	,	_	11	punct	_	_
11	amigos	amigo	NOUN	NN	Gender=Masc|Number=Plur	2	vocative	_	SpaceAfter=No
12	.	.	PUNCT	.	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 3 det	color:blue
1	Trabajó	trabajar	VERB	VBC	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin	0	root	_	_
2	para	para	ADP	IN	_	4	case	_	_
3	la	el	DET	DT	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	4	det	_	_
4	BBC	BBC	PROPN	NNP	Gender=Fem|Number=Sing	1	obl	_	_
5	durante	durante	ADP	IN	_	7	case	_	_
6	una	uno	NUM	CD	Gender=Fem|NumForm=Word|NumType=Card	7	nummod	_	_
7	década	década	NOUN	NN	Gender=Fem|Number=Sing	1	obl	_	SpaceAfter=No
8	.	.	PUNCT	.	_	1	punct	_	_

~~~


