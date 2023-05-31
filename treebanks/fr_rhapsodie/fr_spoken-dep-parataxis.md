---
layout: base
title:  'Statistics of parataxis in UD_French-Spoken'
udver: '2'
---

## Treebank Statistics: UD_French-Spoken: Relations: `parataxis`

This relation is universal.
There are 2 language-specific subtypes of `parataxis`: <tt><a href="fr_spoken-dep-parataxis-insert.html">parataxis:insert</a></tt>, <tt><a href="fr_spoken-dep-parataxis-parenth.html">parataxis:parenth</a></tt>.

42 nodes (0%) are attached to their parents as `parataxis`.

42 instances of `parataxis` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 4.42857142857143.

The following 6 pairs of parts of speech are connected with `parataxis`: <tt><a href="fr_spoken-pos-VERB.html">VERB</a></tt>-<tt><a href="fr_spoken-pos-VERB.html">VERB</a></tt> (29; 69% instances), <tt><a href="fr_spoken-pos-VERB.html">VERB</a></tt>-<tt><a href="fr_spoken-pos-NOUN.html">NOUN</a></tt> (5; 12% instances), <tt><a href="fr_spoken-pos-VERB.html">VERB</a></tt>-<tt><a href="fr_spoken-pos-PRON.html">PRON</a></tt> (4; 10% instances), <tt><a href="fr_spoken-pos-VERB.html">VERB</a></tt>-<tt><a href="fr_spoken-pos-ADJ.html">ADJ</a></tt> (2; 5% instances), <tt><a href="fr_spoken-pos-VERB.html">VERB</a></tt>-<tt><a href="fr_spoken-pos-AUX.html">AUX</a></tt> (1; 2% instances), <tt><a href="fr_spoken-pos-VERB.html">VERB</a></tt>-<tt><a href="fr_spoken-pos-INTJ.html">INTJ</a></tt> (1; 2% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 5 parataxis	color:blue
1	je	il	PRON	_	Number=Sing|Person=1|PronType=Prs	3	nsubj	_	_
2	me	lui	PRON	_	_	3	iobj	_	_
3	disais	dire	VERB	_	Mood=Ind|Number=Sing|Person=1|Tense=Imp|VerbForm=Fin	0	root	_	_
4	j'	il	PRON	_	Number=Sing|Person=1|PronType=Prs	5	nsubj	_	_
5	irai	aller	VERB	ETRE	Number=Sing|Person=1	3	parataxis	_	_
6	peut-être	peut-être	ADV	_	_	5	advmod	_	_
7	à	à	ADP	_	_	8	case	_	_
8	Vire	Vire	PROPN	_	Gender=Fem|Number=Sing	5	obl:arg	_	_

~~~


~~~ conllu
# visual-style 14	bgColor:blue
# visual-style 14	fgColor:white
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 10 14 parataxis	color:blue
1	vous	il	PRON	_	Number=Plur|Person=2|PronType=Prs	8	nsubj	_	_
2	l'	le	PRON	_	Number=Sing|Person=3|PronType=Prs	8	obj	_	_
3	avez	avoir	AUX	_	Mood=Ind|Number=Plur|Person=2|Tense=Pres|VerbForm=Fin	8	aux	_	_
4	m~	m~	X	_	_	8	obl:mod	_	_
5	peut-être	peut-être	ADV	_	_	6	advmod	_	_
6	mieux	mieux	ADV	_	_	4	reparandum	_	_
7	euh	euh	INTJ	_	_	6	discourse	_	_
8	explicité	expliciter	VERB	_	_	0	root	_	_
9	en	en	ADP	_	_	10	mark	_	_
10	disant	dire	VERB	_	Tense=Pres|VerbForm=Part	8	advcl	_	_
11	c'	ce	PRON	_	Gender=Masc|Number=Sing|Person=3|PronType=Dem	14	nsubj	_	_
12	est	être	AUX	_	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	14	cop	_	_
13	un	un	DET	_	Definite=Ind|Gender=Masc|Number=Sing|PronType=Art	14	det	_	_
14	scénario	scénario	NOUN	_	Gender=Masc|Number=Sing	10	parataxis	_	_

~~~


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 6 parataxis	color:blue
1	il	il	PRON	_	Gender=Masc|Number=Sing|Person=3|PronType=Prs	4	nsubj	_	_
2	m'	lui	PRON	_	_	4	iobj	_	_
3	a	avoir	AUX	_	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	4	aux	_	_
4	dit	dire	VERB	_	_	0	root	_	_
5	mais	mais	CCONJ	_	_	6	cc	_	_
6	qu'	qu'	PRON	_	_	4	parataxis	_	_
7	est	être	AUX	_	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	6	cop	_	_
8	-ce	ce	PRON	_	Gender=Masc|Number=Sing|Person=3|PronType=Dem	6	expl:subj	_	_
9	que	que	PRON	_	_	11	obj	_	_
10	tu	il	PRON	_	Number=Sing|Person=2|PronType=Prs	11	nsubj	_	_
11	fais	faire	VERB	CCOMP	Number=Sing|Person=2	6	advcl:cleft	_	_
12	là	là	ADV	_	_	11	advmod	_	_
13	très	très	ADV	_	_	14	advmod	_	_
14	surpris	surpris	ADJ	_	_	4	advcl	_	_

~~~


