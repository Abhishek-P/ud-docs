---
layout: base
title:  'Statistics of xcomp in UD_Portuguese-GSD'
udver: '2'
---

## Treebank Statistics: UD_Portuguese-GSD: Relations: `xcomp`

This relation is universal.

2597 nodes (1%) are attached to their parents as `xcomp`.

2569 instances of `xcomp` (99%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.54909510974201.

The following 19 pairs of parts of speech are connected with `xcomp`: <tt><a href="pt_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="pt_gsd-pos-ADJ.html">ADJ</a></tt> (1770; 68% instances), <tt><a href="pt_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="pt_gsd-pos-VERB.html">VERB</a></tt> (766; 29% instances), <tt><a href="pt_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="pt_gsd-pos-NOUN.html">NOUN</a></tt> (37; 1% instances), <tt><a href="pt_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="pt_gsd-pos-PROPN.html">PROPN</a></tt> (4; 0% instances), <tt><a href="pt_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="pt_gsd-pos-ADV.html">ADV</a></tt> (3; 0% instances), <tt><a href="pt_gsd-pos-PRON.html">PRON</a></tt>-<tt><a href="pt_gsd-pos-ADJ.html">ADJ</a></tt> (2; 0% instances), <tt><a href="pt_gsd-pos-PROPN.html">PROPN</a></tt>-<tt><a href="pt_gsd-pos-PROPN.html">PROPN</a></tt> (2; 0% instances), <tt><a href="pt_gsd-pos-PROPN.html">PROPN</a></tt>-<tt><a href="pt_gsd-pos-VERB.html">VERB</a></tt> (2; 0% instances), <tt><a href="pt_gsd-pos-ADJ.html">ADJ</a></tt>-<tt><a href="pt_gsd-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="pt_gsd-pos-ADJ.html">ADJ</a></tt>-<tt><a href="pt_gsd-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="pt_gsd-pos-ADV.html">ADV</a></tt>-<tt><a href="pt_gsd-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="pt_gsd-pos-AUX.html">AUX</a></tt>-<tt><a href="pt_gsd-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="pt_gsd-pos-AUX.html">AUX</a></tt>-<tt><a href="pt_gsd-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="pt_gsd-pos-NOUN.html">NOUN</a></tt>-<tt><a href="pt_gsd-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="pt_gsd-pos-PART.html">PART</a></tt>-<tt><a href="pt_gsd-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="pt_gsd-pos-PROPN.html">PROPN</a></tt>-<tt><a href="pt_gsd-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="pt_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="pt_gsd-pos-PRON.html">PRON</a></tt> (1; 0% instances), <tt><a href="pt_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="pt_gsd-pos-SYM.html">SYM</a></tt> (1; 0% instances), <tt><a href="pt_gsd-pos-X.html">X</a></tt>-<tt><a href="pt_gsd-pos-VERB.html">VERB</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 9 xcomp	color:blue
1	A	o	DET	DET	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	2	det	_	_
2	Nina	_	PROPN	PNOUN	_	5	nsubj	_	_
3	é	ser	AUX	AUX	_	5	cop	_	_
4	a	o	DET	DET	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	5	det	_	_
5	chance	chance	NOUN	NOUN	_	0	root	_	_
6	de	_	ADP	ADP	_	8	mark	_	_
7	ele	_	PRON	PRON	_	8	nsubj	_	_
8	ser	ser	VERB	VERB	_	5	nmod	_	_
9	feliz	feliz	ADJ	ADJ	_	8	xcomp	_	SpaceAfter=No
10	.	.	PUNCT	.	_	5	punct	_	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 2 xcomp	color:blue
1	Quero	querer	VERB	VERB	_	10	ccomp	_	_
2	dar	dar	VERB	VERB	_	1	xcomp	_	_
3	o	o	DET	DET	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	4	det	_	_
4	máximo	máximo	NOUN	NOUN	_	2	obj	_	_
5	e	e	CCONJ	CONJ	_	6	cc	_	_
6	sair	sair	VERB	VERB	_	2	conj	_	_
7	satisfeito	satisfeito	ADJ	ADJ	_	6	xcomp	_	_
8	'	_	PUNCT	.	_	1	punct	_	SpaceAfter=No
9	,	,	PUNCT	.	_	10	punct	_	_
10	afirmou	afirmar	VERB	VERB	_	0	root	_	SpaceAfter=No
11	.	.	PUNCT	.	_	10	punct	_	_

~~~


~~~ conllu
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 9 xcomp	color:blue
1	Por	_	ADP	ADP	_	2	case	_	_
2	isso	_	PRON	PRON	_	7	nmod	_	SpaceAfter=No
3	,	,	PUNCT	.	_	2	punct	_	_
4	administrar	administrar	VERB	VERB	_	7	csubj	_	_
5	nem	_	ADV	ADV	_	7	advmod	_	_
6	sempre	sempre	ADV	ADV	_	7	advmod	_	_
7	significa	significar	VERB	VERB	_	0	root	_	_
8	ser	ser	AUX	AUX	_	9	cop	_	_
9	estadista	estadista	NOUN	NOUN	_	7	xcomp	_	SpaceAfter=No
10	.	.	PUNCT	.	_	7	punct	_	_

~~~


