---
layout: base
title:  'Statistics of expl:subj in UD_French-GSD'
udver: '2'
---

## Treebank Statistics: UD_French-GSD: Relations: `expl:subj`

This relation is a language-specific subtype of .
There are also 3 other language-specific subtypes of `expl`: <tt><a href="fr_gsd-dep-expl-comp.html">expl:comp</a></tt>, <tt><a href="fr_gsd-dep-expl-pass.html">expl:pass</a></tt>, <tt><a href="fr_gsd-dep-expl-pv.html">expl:pv</a></tt>.

931 nodes (0%) are attached to their parents as `expl:subj`.

872 instances of `expl:subj` (94%) are right-to-left (child precedes parent).
Average distance between parent and child is 2.26530612244898.

The following 10 pairs of parts of speech are connected with `expl:subj`: <tt><a href="fr_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="fr_gsd-pos-PRON.html">PRON</a></tt> (599; 64% instances), <tt><a href="fr_gsd-pos-NOUN.html">NOUN</a></tt>-<tt><a href="fr_gsd-pos-PRON.html">PRON</a></tt> (142; 15% instances), <tt><a href="fr_gsd-pos-ADJ.html">ADJ</a></tt>-<tt><a href="fr_gsd-pos-PRON.html">PRON</a></tt> (100; 11% instances), <tt><a href="fr_gsd-pos-ADV.html">ADV</a></tt>-<tt><a href="fr_gsd-pos-PRON.html">PRON</a></tt> (28; 3% instances), <tt><a href="fr_gsd-pos-PRON.html">PRON</a></tt>-<tt><a href="fr_gsd-pos-PRON.html">PRON</a></tt> (26; 3% instances), <tt><a href="fr_gsd-pos-PROPN.html">PROPN</a></tt>-<tt><a href="fr_gsd-pos-PRON.html">PRON</a></tt> (26; 3% instances), <tt><a href="fr_gsd-pos-NUM.html">NUM</a></tt>-<tt><a href="fr_gsd-pos-PRON.html">PRON</a></tt> (5; 1% instances), <tt><a href="fr_gsd-pos-ADP.html">ADP</a></tt>-<tt><a href="fr_gsd-pos-PRON.html">PRON</a></tt> (3; 0% instances), <tt><a href="fr_gsd-pos-SYM.html">SYM</a></tt>-<tt><a href="fr_gsd-pos-PRON.html">PRON</a></tt> (1; 0% instances), <tt><a href="fr_gsd-pos-X.html">X</a></tt>-<tt><a href="fr_gsd-pos-PRON.html">PRON</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 10 8 expl:subj	color:blue
1	Il	lui	PRON	_	Emph=No|Gender=Masc|Number=Sing|Person=3|PronType=Prs	6	nsubj	_	wordform=il
2	n'	ne	ADV	_	Polarity=Neg	6	advmod	_	SpaceAfter=No
3	est	être	AUX	_	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	6	cop	_	_
4	pas	pas	ADV	_	Polarity=Neg	6	advmod	_	_
5	aussi	aussi	ADV	_	_	6	advmod	_	_
6	anxieux	anxieux	ADJ	_	Gender=Masc	0	root	_	_
7	qu'	que	SCONJ	_	_	10	mark	_	SpaceAfter=No
8	il	lui	PRON	_	Emph=No|Gender=Masc|Number=Sing|Person=3|PronType=Prs	10	expl:subj	_	_
9	y	y	PRON	_	Emph=No|Person=3|PronType=Prs	10	expl:comp	_	_
10	paraît	paraître	VERB	_	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	5	ccomp	_	SpaceAfter=No
11	.	.	PUNCT	_	_	10	punct	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 4 expl:subj	color:blue
1	Elle	lui	PRON	_	Emph=No|Gender=Fem|Number=Sing|Person=3|PronType=Prs	2	nsubj	_	wordform=elle
2	fonce	foncer	VERB	_	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
3	et	et	CCONJ	_	_	7	cc	_	_
4	c'	ce	PRON	_	Gender=Masc|Number=Sing|Person=3|PronType=Dem	7	expl:subj	_	SpaceAfter=No
5	est	être	AUX	_	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	7	cop	_	_
6	cette	ce	DET	_	Gender=Fem|Number=Sing|PronType=Dem	7	det	_	_
7	audace	audace	NOUN	_	Gender=Fem|Number=Sing	2	conj	_	_
8	qui	qui	PRON	_	PronType=Rel	10	nsubj:pass	_	_
9	est	être	AUX	_	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	10	aux:pass	_	_
10	récompensée	récompenser	VERB	_	Gender=Fem|Number=Sing|Tense=Past|VerbForm=Part|Voice=Pass	7	advcl:cleft	_	SpaceAfter=No
11	.	.	PUNCT	_	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 1 expl:subj	color:blue
1	C'	ce	PRON	_	Gender=Masc|Number=Sing|Person=3|PronType=Dem	4	expl:subj	_	SpaceAfter=No|wordform=c'
2	est	être	AUX	_	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	4	cop	_	_
3	tellement	tellement	ADV	_	_	4	advmod	_	_
4	rare	rare	ADJ	_	Gender=Masc|Number=Sing	0	root	_	_
5	de	de	ADP	_	_	6	mark	_	_
6	pouvoir	pouvoir	VERB	_	VerbForm=Inf	4	csubj	_	Subject=Generic
7	dîner	dîner	VERB	_	VerbForm=Inf	6	xcomp	_	Subject=SubjRaising
8	à	à	ADP	_	_	10	case	_	_
9	le	le	DET	_	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	10	det	_	_
10	coin	coin	NOUN	_	Gender=Masc|Number=Sing	7	obl:mod	_	_
11	de	de	ADP	_	_	13	case	_	_
12	le	le	DET	_	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	13	det	_	_
13	feu	feu	NOUN	_	Gender=Masc|Number=Sing	10	nmod	_	_
14	!	!	PUNCT	_	_	4	punct	_	_

~~~


