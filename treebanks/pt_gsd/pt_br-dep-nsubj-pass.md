---
layout: base
title:  'Statistics of nsubj:pass in UD_Portuguese-BR'
udver: '2'
---

## Treebank Statistics: UD_Portuguese-BR: Relations: `nsubj:pass`

This relation is a language-specific subtype of <tt><a href="pt_br-dep-nsubj.html">nsubj</a></tt>.

2011 nodes (1%) are attached to their parents as `nsubj:pass`.

1750 instances of `nsubj:pass` (87%) are right-to-left (child precedes parent).
Average distance between parent and child is 4.47289905519642.

The following 16 pairs of parts of speech are connected with `nsubj:pass`: <tt><a href="pt_br-pos-VERB.html">VERB</a></tt>-<tt><a href="pt_br-pos-NOUN.html">NOUN</a></tt> (1455; 72% instances), <tt><a href="pt_br-pos-VERB.html">VERB</a></tt>-<tt><a href="pt_br-pos-PRON.html">PRON</a></tt> (309; 15% instances), <tt><a href="pt_br-pos-VERB.html">VERB</a></tt>-<tt><a href="pt_br-pos-PROPN.html">PROPN</a></tt> (186; 9% instances), <tt><a href="pt_br-pos-VERB.html">VERB</a></tt>-<tt><a href="pt_br-pos-NUM.html">NUM</a></tt> (26; 1% instances), <tt><a href="pt_br-pos-NOUN.html">NOUN</a></tt>-<tt><a href="pt_br-pos-NOUN.html">NOUN</a></tt> (9; 0% instances), <tt><a href="pt_br-pos-NOUN.html">NOUN</a></tt>-<tt><a href="pt_br-pos-PROPN.html">PROPN</a></tt> (8; 0% instances), <tt><a href="pt_br-pos-VERB.html">VERB</a></tt>-<tt><a href="pt_br-pos-PART.html">PART</a></tt> (6; 0% instances), <tt><a href="pt_br-pos-PROPN.html">PROPN</a></tt>-<tt><a href="pt_br-pos-NOUN.html">NOUN</a></tt> (3; 0% instances), <tt><a href="pt_br-pos-NOUN.html">NOUN</a></tt>-<tt><a href="pt_br-pos-PRON.html">PRON</a></tt> (2; 0% instances), <tt><a href="pt_br-pos-PRON.html">PRON</a></tt>-<tt><a href="pt_br-pos-PRON.html">PRON</a></tt> (1; 0% instances), <tt><a href="pt_br-pos-PRON.html">PRON</a></tt>-<tt><a href="pt_br-pos-PROPN.html">PROPN</a></tt> (1; 0% instances), <tt><a href="pt_br-pos-PROPN.html">PROPN</a></tt>-<tt><a href="pt_br-pos-NUM.html">NUM</a></tt> (1; 0% instances), <tt><a href="pt_br-pos-PROPN.html">PROPN</a></tt>-<tt><a href="pt_br-pos-PROPN.html">PROPN</a></tt> (1; 0% instances), <tt><a href="pt_br-pos-VERB.html">VERB</a></tt>-<tt><a href="pt_br-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="pt_br-pos-VERB.html">VERB</a></tt>-<tt><a href="pt_br-pos-AUX.html">AUX</a></tt> (1; 0% instances), <tt><a href="pt_br-pos-VERB.html">VERB</a></tt>-<tt><a href="pt_br-pos-CCONJ.html">CCONJ</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 2 nsubj:pass	color:blue
1	Os	_	DET	DET	_	2	det	_	_
2	cuidados	_	NOUN	NOUN	_	7	nsubj:pass	_	_
3	de	_	ADP	ADP	_	4	mark	_	_
4	sempre	_	ADV	ADV	_	2	nmod	_	_
5	estão	_	AUX	AUX	_	7	aux	_	_
6	sendo	_	AUX	AUX	_	7	aux:pass	_	_
7	tomados	_	VERB	VERB	_	0	root	_	_
8	por	por	ADP	ADP	_	10	case	_	_
9	o	o	DET	DET	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	10	det	_	_
10	consumidor	_	NOUN	NOUN	_	7	nmod	_	SpaceAfter=No
11	.	_	PUNCT	.	_	7	punct	_	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 5 nsubj:pass	color:blue
1	Dois	_	NUM	NUM	NumType=Card	2	nummod	_	_
2	anos	_	NOUN	NOUN	_	3	nmod	_	_
3	depois	_	ADV	ADV	_	7	advmod	_	SpaceAfter=No
4	,	_	PUNCT	.	_	3	punct	_	_
5	ele	_	PRON	PRON	_	7	nsubj:pass	_	_
6	foi	_	AUX	AUX	_	7	aux:pass	_	_
7	preso	_	VERB	VERB	_	0	root	_	_
8	--	_	PUNCT	.	_	13	punct	_	_
9	e	_	CCONJ	CONJ	_	13	cc	_	_
10	eu	_	PRON	PRON	_	13	nsubj	_	_
11	nunca	_	ADV	ADV	_	13	advmod	_	_
12	o	_	PRON	PRON	_	13	obj	_	_
13	vi	_	VERB	VERB	_	7	conj	_	_
14	novamente	_	ADV	ADV	_	13	advmod	_	SpaceAfter=No
15	.	_	PUNCT	.	_	7	punct	_	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 5 nsubj:pass	color:blue
1	En	en	ADP	ADP	_	3	case	_	_
2	o	o	DET	DET	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	3	det	_	_
3	hospital	_	NOUN	NOUN	_	7	nmod	_	SpaceAfter=No
4	,	_	PUNCT	.	_	3	punct	_	_
5	Carmen	_	PROPN	PNOUN	_	7	nsubj:pass	_	_
6	será	_	AUX	AUX	_	7	aux:pass	_	_
7	levada	_	VERB	VERB	_	0	root	_	_
8	para	_	ADP	ADP	_	10	case	_	_
9	a	_	DET	DET	_	10	det	_	_
10	mesa	_	NOUN	NOUN	_	7	nmod	_	_
11	de	_	ADP	ADP	_	12	case	_	_
12	cirurgia	_	NOUN	NOUN	_	10	nmod	_	SpaceAfter=No
13	.	_	PUNCT	.	_	7	punct	_	_

~~~


