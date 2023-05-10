---
layout: base
title:  'Statistics of aux:pass in UD_German-HDT'
udver: '2'
---

## Treebank Statistics: UD_German-HDT: Relations: `aux:pass`

This relation is a language-specific subtype of <tt><a href="de_hdt-dep-aux.html">aux</a></tt>.

32895 nodes (1%) are attached to their parents as `aux:pass`.

18049 instances of `aux:pass` (55%) are left-to-right (parent precedes child).
Average distance between parent and child is 3.86858185134519.

The following 2 pairs of parts of speech are connected with `aux:pass`: <tt><a href="de_hdt-pos-VERB.html">VERB</a></tt>-<tt><a href="de_hdt-pos-AUX.html">AUX</a></tt> (32894; 100% instances), <tt><a href="de_hdt-pos-AUX.html">AUX</a></tt>-<tt><a href="de_hdt-pos-AUX.html">AUX</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 3 aux:pass	color:blue
1	Alte	alt	ADJ	ADJA	Degree=Pos|Number=Plur	2	amod	_	_
2	EMails	EMails	NOUN	NN	Case=Nom	8	nsubj:pass	_	_
3	wurden	werden	AUX	VAFIN	Mood=Ind|Number=Plur|Person=3|Tense=Past|VerbForm=Fin	8	aux:pass	_	_
4	nicht	nicht	PART	PTKNEG	Polarity=Neg	8	advmod	_	_
5	von	von	ADP	APPR	AdpType=Prep|Case=Dat	7	case	_	_
6	dem	der	DET	ART	Case=Dat|Definite=Def|Gender=Masc,Neut|Number=Sing|PronType=Art	7	det	_	_
7	Server	Server	NOUN	NN	Case=Dat|Gender=Masc|Number=Sing	8	obl	_	_
8	gelöscht	löschen	VERB	VVPP	Aspect=Perf|VerbForm=Part	0	root	_	_
9	.	.	PUNCT	$.	PunctType=Peri	8	punct	_	_

~~~


~~~ conllu
# visual-style 11	bgColor:blue
# visual-style 11	fgColor:white
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 10 11 aux:pass	color:blue
1	Doch	Doch	CCONJ	KON	_	10	cc	_	_
2	billiger	billig	ADJ	ADJD	Degree=Cmp|Variant=Short	10	advmod	_	_
3	sei	sein	AUX	VAFIN	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	10	aux	_	_
4	der	der	DET	ART	Case=Nom|Definite=Def|Gender=Masc|Number=Sing|PronType=Art	5	det	_	_
5	US-Mobilfunker	Funker	NOUN	NN	Gender=Masc|Number=Sing	10	nsubj:pass	_	_
6	wahrscheinlich	wahrscheinlich	ADJ	ADJD	Degree=Pos|Variant=Short	10	advmod	_	_
7	gar	gar	ADV	ADV	_	10	advmod	_	_
8	nicht	nicht	PART	PTKNEG	Polarity=Neg	10	advmod	_	_
9	zu	zu	PART	PTKZU	PartType=Inf	10	mark	_	_
10	haben	haben	AUX	VAINF	VerbForm=Inf	0	root	_	_
11	gewesen	sein	AUX	VAPP	Aspect=Perf|VerbForm=Part	10	aux:pass	_	_
12	,	,	PUNCT	$,	PunctType=Comm	13	punct	_	_
13	sagten	sagen	VERB	VVFIN	Mood=Ind|Number=Plur|Person=3|Tense=Past|VerbForm=Fin	10	parataxis	_	_
14	die	der	DET	ART	Case=Nom|Definite=Def|Number=Plur|PronType=Art	16	det	_	_
15	meisten	meist	DET	PIDAT	Degree=Sup|Number=Plur|PronType=Ind	16	det	_	_
16	Analysten	Analyst	NOUN	NN	Gender=Masc|Number=Plur	13	nsubj	_	_
17	.	.	PUNCT	$.	PunctType=Peri	10	punct	_	_

~~~


