---
layout: base
title:  'Statistics of nsubj:pass in UD_Spanish'
udver: '2'
---

## Treebank Statistics: UD_Spanish: Relations: `nsubj:pass`

This relation is a language-specific subtype of <tt><a href="es-dep-nsubj.html">nsubj</a></tt>.

1182 nodes (0%) are attached to their parents as `nsubj:pass`.

1123 instances of `nsubj:pass` (95%) are right-to-left (child precedes parent).
Average distance between parent and child is 4.60998307952623.

The following 26 pairs of parts of speech are connected with `nsubj:pass`: <tt><a href="es-pos-VERB.html">VERB</a></tt>-<tt><a href="es-pos-NOUN.html">NOUN</a></tt> (787; 67% instances), <tt><a href="es-pos-VERB.html">VERB</a></tt>-<tt><a href="es-pos-PRON.html">PRON</a></tt> (178; 15% instances), <tt><a href="es-pos-VERB.html">VERB</a></tt>-<tt><a href="es-pos-PROPN.html">PROPN</a></tt> (151; 13% instances), <tt><a href="es-pos-NOUN.html">NOUN</a></tt>-<tt><a href="es-pos-PROPN.html">PROPN</a></tt> (12; 1% instances), <tt><a href="es-pos-NOUN.html">NOUN</a></tt>-<tt><a href="es-pos-NOUN.html">NOUN</a></tt> (11; 1% instances), <tt><a href="es-pos-ADJ.html">ADJ</a></tt>-<tt><a href="es-pos-NOUN.html">NOUN</a></tt> (9; 1% instances), <tt><a href="es-pos-PROPN.html">PROPN</a></tt>-<tt><a href="es-pos-NOUN.html">NOUN</a></tt> (4; 0% instances), <tt><a href="es-pos-VERB.html">VERB</a></tt>-<tt><a href="es-pos-NUM.html">NUM</a></tt> (4; 0% instances), <tt><a href="es-pos-VERB.html">VERB</a></tt>-<tt><a href="es-pos-SYM.html">SYM</a></tt> (4; 0% instances), <tt><a href="es-pos-PROPN.html">PROPN</a></tt>-<tt><a href="es-pos-PRON.html">PRON</a></tt> (3; 0% instances), <tt><a href="es-pos-PROPN.html">PROPN</a></tt>-<tt><a href="es-pos-PROPN.html">PROPN</a></tt> (2; 0% instances), <tt><a href="es-pos-VERB.html">VERB</a></tt>-<tt><a href="es-pos-ADJ.html">ADJ</a></tt> (2; 0% instances), <tt><a href="es-pos-VERB.html">VERB</a></tt>-<tt><a href="es-pos-DET.html">DET</a></tt> (2; 0% instances), <tt><a href="es-pos-ADJ.html">ADJ</a></tt>-<tt><a href="es-pos-NUM.html">NUM</a></tt> (1; 0% instances), <tt><a href="es-pos-ADJ.html">ADJ</a></tt>-<tt><a href="es-pos-PRON.html">PRON</a></tt> (1; 0% instances), <tt><a href="es-pos-ADJ.html">ADJ</a></tt>-<tt><a href="es-pos-PROPN.html">PROPN</a></tt> (1; 0% instances), <tt><a href="es-pos-ADP.html">ADP</a></tt>-<tt><a href="es-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="es-pos-NOUN.html">NOUN</a></tt>-<tt><a href="es-pos-PRON.html">PRON</a></tt> (1; 0% instances), <tt><a href="es-pos-NOUN.html">NOUN</a></tt>-<tt><a href="es-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="es-pos-PRON.html">PRON</a></tt>-<tt><a href="es-pos-PROPN.html">PROPN</a></tt> (1; 0% instances), <tt><a href="es-pos-VERB.html">VERB</a></tt>-<tt><a href="es-pos-ADV.html">ADV</a></tt> (1; 0% instances), <tt><a href="es-pos-VERB.html">VERB</a></tt>-<tt><a href="es-pos-AUX.html">AUX</a></tt> (1; 0% instances), <tt><a href="es-pos-VERB.html">VERB</a></tt>-<tt><a href="es-pos-CCONJ.html">CCONJ</a></tt> (1; 0% instances), <tt><a href="es-pos-VERB.html">VERB</a></tt>-<tt><a href="es-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="es-pos-VERB.html">VERB</a></tt>-<tt><a href="es-pos-X.html">X</a></tt> (1; 0% instances), <tt><a href="es-pos-X.html">X</a></tt>-<tt><a href="es-pos-NOUN.html">NOUN</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 10 8 nsubj:pass	color:blue
1	Según	según	ADP	_	_	2	case	_	_
2	figura	figurar	NOUN	_	Gender=Fem|Number=Sing	10	obl	_	_
3	en	en	ADP	_	_	5	case	_	_
4	la	el	DET	_	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	5	det	_	_
5	portada	portada	NOUN	_	Gender=Fem|Number=Sing	2	nmod	_	SpaceAfter=No
6	,	,	PUNCT	_	_	2	punct	_	_
7	el	el	DET	_	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	8	det	_	_
8	libro	libro	NOUN	_	Gender=Masc|Number=Sing	10	nsubj:pass	_	_
9	fue	ser	AUX	_	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin	10	aux:pass	_	_
10	publicado	publicar	VERB	_	Gender=Masc|Number=Sing|Tense=Past|VerbForm=Part	0	root	_	_
11	en	en	ADP	_	_	12	case	_	_
12	1535	1535	NUM	_	NumType=Card	10	obl	_	SpaceAfter=No
13	;	;	PUNCT	_	_	10	punct	_	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 1 nsubj:pass	color:blue
1	Éstas	ésta	PRON	_	Gender=Fem|Number=Plur|PronType=Dem	3	nsubj:pass	_	_
2	son	ser	AUX	_	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	3	aux:pass	_	_
3	vendidas	vender	VERB	_	Gender=Fem|Number=Plur|Tense=Past|VerbForm=Part	0	root	_	_
4	con	con	ADP	_	_	5	case	_	_
5	Windows	windows	PROPN	_	_	3	obl	_	_
6	Mobile	mobile	PROPN	_	_	5	appos	_	_
7	2003	2003	NUM	_	NumType=Card	5	nummod	_	_
8	como	como	ADP	_	_	9	case	_	_
9	estándar	estándar	NOUN	_	Number=Sing	3	obl	_	SpaceAfter=No
10	.	.	PUNCT	_	_	3	punct	_	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 1 nsubj:pass	color:blue
1	Trudón	trudón	PROPN	_	_	3	nsubj:pass	_	_
2	fue	ser	AUX	_	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin	3	aux:pass	_	_
3	enterrado	enterrar	VERB	_	Gender=Masc|Number=Sing|Tense=Past|VerbForm=Part	0	root	_	_
4	en	en	ADP	_	_	6	case	_	_
5	la	el	DET	_	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	6	det	_	_
6	iglesia	iglesia	NOUN	_	Gender=Fem|Number=Sing	3	obl	_	_
7	de	de	ADP	_	_	9	case	_	_
8	su	su	DET	_	Number=Sing|Person=3|Poss=Yes|PronType=Prs	9	det	_	_
9	monasterio	monasterio	NOUN	_	Gender=Masc|Number=Sing	6	nmod	_	SpaceAfter=No
10	.	.	PUNCT	_	_	3	punct	_	_

~~~


