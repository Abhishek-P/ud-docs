---
layout: base
title:  'Statistics of obj in UD_German-LIT'
udver: '2'
---

## Treebank Statistics: UD_German-LIT: Relations: `obj`

This relation is universal.

1629 nodes (4%) are attached to their parents as `obj`.

1147 instances of `obj` (70%) are right-to-left (child precedes parent).
Average distance between parent and child is 3.75260896255371.

The following 20 pairs of parts of speech are connected with `obj`: <tt><a href="de_lit-pos-VERB.html">VERB</a></tt>-<tt><a href="de_lit-pos-NOUN.html">NOUN</a></tt> (785; 48% instances), <tt><a href="de_lit-pos-VERB.html">VERB</a></tt>-<tt><a href="de_lit-pos-PRON.html">PRON</a></tt> (542; 33% instances), <tt><a href="de_lit-pos-AUX.html">AUX</a></tt>-<tt><a href="de_lit-pos-NOUN.html">NOUN</a></tt> (132; 8% instances), <tt><a href="de_lit-pos-VERB.html">VERB</a></tt>-<tt><a href="de_lit-pos-DET.html">DET</a></tt> (88; 5% instances), <tt><a href="de_lit-pos-AUX.html">AUX</a></tt>-<tt><a href="de_lit-pos-PRON.html">PRON</a></tt> (27; 2% instances), <tt><a href="de_lit-pos-ADJ.html">ADJ</a></tt>-<tt><a href="de_lit-pos-PRON.html">PRON</a></tt> (12; 1% instances), <tt><a href="de_lit-pos-VERB.html">VERB</a></tt>-<tt><a href="de_lit-pos-PROPN.html">PROPN</a></tt> (10; 1% instances), <tt><a href="de_lit-pos-ADJ.html">ADJ</a></tt>-<tt><a href="de_lit-pos-NOUN.html">NOUN</a></tt> (9; 1% instances), <tt><a href="de_lit-pos-VERB.html">VERB</a></tt>-<tt><a href="de_lit-pos-ADJ.html">ADJ</a></tt> (6; 0% instances), <tt><a href="de_lit-pos-ADV.html">ADV</a></tt>-<tt><a href="de_lit-pos-NOUN.html">NOUN</a></tt> (4; 0% instances), <tt><a href="de_lit-pos-ADJ.html">ADJ</a></tt>-<tt><a href="de_lit-pos-DET.html">DET</a></tt> (3; 0% instances), <tt><a href="de_lit-pos-AUX.html">AUX</a></tt>-<tt><a href="de_lit-pos-DET.html">DET</a></tt> (2; 0% instances), <tt><a href="de_lit-pos-VERB.html">VERB</a></tt>-<tt><a href="de_lit-pos-X.html">X</a></tt> (2; 0% instances), <tt><a href="de_lit-pos-ADP.html">ADP</a></tt>-<tt><a href="de_lit-pos-PRON.html">PRON</a></tt> (1; 0% instances), <tt><a href="de_lit-pos-AUX.html">AUX</a></tt>-<tt><a href="de_lit-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="de_lit-pos-AUX.html">AUX</a></tt>-<tt><a href="de_lit-pos-PROPN.html">PROPN</a></tt> (1; 0% instances), <tt><a href="de_lit-pos-AUX.html">AUX</a></tt>-<tt><a href="de_lit-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="de_lit-pos-DET.html">DET</a></tt>-<tt><a href="de_lit-pos-PRON.html">PRON</a></tt> (1; 0% instances), <tt><a href="de_lit-pos-VERB.html">VERB</a></tt>-<tt><a href="de_lit-pos-ADV.html">ADV</a></tt> (1; 0% instances), <tt><a href="de_lit-pos-VERB.html">VERB</a></tt>-<tt><a href="de_lit-pos-NUM.html">NUM</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 12	bgColor:blue
# visual-style 12	fgColor:white
# visual-style 12 5 obj	color:blue
1	man	man	PRON	PIS	Case=Nom|Number=Sing|PronType=Ind	12	nsubj	_	_
2	müßte	müssen	AUX	VMFIN	_	12	aux	_	_
3	ihm	er	PRON	PPER	Case=Dat|Gender=Masc|Number=Sing|Person=3|PronType=Prs	12	obl:arg	_	_
4	denn	denn	ADV	ADV	_	12	advmod	_	_
5	Helden	Held	NOUN	NN	Case=Acc	12	obj	_	SpaceAfter=No
6	,	,	PUNCT	$,	_	7	punct	_	_
7	Musik	Musik	NOUN	NN	_	5	conj	_	_
8	oder	oder	CCONJ	KON	_	9	cc	_	_
9	Narren	Narr	NOUN	NN	_	5	conj	_	_
10	zum	zu	ADP	APPRART	_	11	case	_	_
11	besten	gut	ADJ	ADJA	_	12	advmod	_	_
12	geben	geben	VERB	VVINF	_	0	root	_	SpaceAfter=No
13	.	.	PUNCT	$.	_	12	punct	_	_

~~~


~~~ conllu
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 12	bgColor:blue
# visual-style 12	fgColor:white
# visual-style 12 10 obj	color:blue
1	Man	man	PRON	PIS	Case=Nom|Number=Sing|PronType=Ind	6	nsubj	_	_
2	soll	sollen	AUX	VMFIN	_	6	aux	_	_
3	von	von	ADP	APPR	_	4	case	_	_
4	jedermann	jedermann	PRON	PIAT	Case=Dat|Number=Sing|PronType=Tot	6	det	_	_
5	Genie	Genie	NOUN	NN	Case=Acc	6	obj	_	_
6	fordern	fordern	VERB	VVFIN	_	0	root	_	SpaceAfter=No
7	,	,	PUNCT	$,	_	6	punct	_	_
8	aber	aber	ADV	ADV	_	12	advmod	_	_
9	ohne	ohne	SCONJ	KOUI	_	12	mark	_	_
10	es	es	PRON	PPER	Case=Acc|Gender=Neut|Number=Sing|Person=3|PronType=Prs	12	obj	_	_
11	zu	zu	PART	PTKZU	_	12	mark	_	_
12	erwarten	erwarten	VERB	VVINF	_	6	xcomp	_	SpaceAfter=No
13	.	.	PUNCT	$.	_	6	punct	_	_

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 7 obj	color:blue
1	Er	er	PRON	PPER	Case=Nom|Gender=Masc|Number=Sing|Person=3|PronType=Prs	8	nsubj	_	_
2	sollte	sollen	AUX	VMFIN	_	8	aux	_	_
3	also	also	ADV	ADV	_	8	advmod	_	_
4	mehr	mehr	ADV	PIS	_	7	advmod	_	_
5	als	als	CCONJ	KOKOM	_	7	case	_	_
6	einen	ein	DET	ART	Definite=Ind|NumType=Card|PronType=Art	7	det	_	_
7	Magen	Magen	NOUN	NN	Case=Acc	8	obj	_	_
8	haben	haben	AUX	VAINF	_	0	root	_	SpaceAfter=No
9	.	.	PUNCT	$.	_	8	punct	_	_

~~~


