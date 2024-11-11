---
layout: base
title:  'Statistics of amod in UD_German-LIT'
udver: '2'
---

## Treebank Statistics: UD_German-LIT: Relations: `amod`

This relation is universal.

2280 nodes (6%) are attached to their parents as `amod`.

2267 instances of `amod` (99%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.20350877192982.

The following 18 pairs of parts of speech are connected with `amod`: <tt><a href="de_lit-pos-NOUN.html">NOUN</a></tt>-<tt><a href="de_lit-pos-ADJ.html">ADJ</a></tt> (2235; 98% instances), <tt><a href="de_lit-pos-ADJ.html">ADJ</a></tt>-<tt><a href="de_lit-pos-ADJ.html">ADJ</a></tt> (13; 1% instances), <tt><a href="de_lit-pos-PROPN.html">PROPN</a></tt>-<tt><a href="de_lit-pos-ADJ.html">ADJ</a></tt> (7; 0% instances), <tt><a href="de_lit-pos-VERB.html">VERB</a></tt>-<tt><a href="de_lit-pos-ADJ.html">ADJ</a></tt> (7; 0% instances), <tt><a href="de_lit-pos-PROPN.html">PROPN</a></tt>-<tt><a href="de_lit-pos-ADP.html">ADP</a></tt> (3; 0% instances), <tt><a href="de_lit-pos-NOUN.html">NOUN</a></tt>-<tt><a href="de_lit-pos-ADP.html">ADP</a></tt> (2; 0% instances), <tt><a href="de_lit-pos-PRON.html">PRON</a></tt>-<tt><a href="de_lit-pos-ADJ.html">ADJ</a></tt> (2; 0% instances), <tt><a href="de_lit-pos-ADV.html">ADV</a></tt>-<tt><a href="de_lit-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="de_lit-pos-AUX.html">AUX</a></tt>-<tt><a href="de_lit-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="de_lit-pos-DET.html">DET</a></tt>-<tt><a href="de_lit-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="de_lit-pos-DET.html">DET</a></tt>-<tt><a href="de_lit-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="de_lit-pos-DET.html">DET</a></tt>-<tt><a href="de_lit-pos-NUM.html">NUM</a></tt> (1; 0% instances), <tt><a href="de_lit-pos-NOUN.html">NOUN</a></tt>-<tt><a href="de_lit-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="de_lit-pos-NOUN.html">NOUN</a></tt>-<tt><a href="de_lit-pos-PRON.html">PRON</a></tt> (1; 0% instances), <tt><a href="de_lit-pos-NOUN.html">NOUN</a></tt>-<tt><a href="de_lit-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="de_lit-pos-NOUN.html">NOUN</a></tt>-<tt><a href="de_lit-pos-X.html">X</a></tt> (1; 0% instances), <tt><a href="de_lit-pos-PROPN.html">PROPN</a></tt>-<tt><a href="de_lit-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="de_lit-pos-VERB.html">VERB</a></tt>-<tt><a href="de_lit-pos-X.html">X</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 4 amod	color:blue
1	Man	man	PRON	PIS	Case=Nom|Number=Sing|PronType=Ind	2	nsubj	_	_
2	tadelt	tadeln	VERB	VVFIN	_	0	root	_	_
3	die	der	DET	ART	Definite=Def|PronType=Art	5	det	_	_
4	metrische	metrisch	ADJ	ADJA	_	5	amod	_	_
5	Sorglosigkeit	Sorglosigkeit	NOUN	NN	Case=Acc	2	obj	_	_
6	der	der	DET	ART	Definite=Def|PronType=Art	8	det	_	_
7	Goetheschen	goethesch	ADJ	ADJA	_	8	amod	_	_
8	Gedichte	Gedicht	NOUN	NN	_	5	nmod	_	SpaceAfter=No
9	.	.	PUNCT	$.	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 4 amod	color:blue
1	Gewisse	gewiß	ADJ	ADJA	_	2	amod	_	_
2	Stimmungen	Stimmung	NOUN	NN	Case=Nom	7	nsubj	_	_
3	sind	sein	AUX	VAFIN	_	7	cop	_	_
4	vorzüglich	vorzüglich	ADJ	ADJD	_	7	amod	_	_
5	solchen	solcher	DET	PIAT	PronType=Dem	6	det	_	_
6	Offenbarungen	Offenbarung	NOUN	NN	_	7	nmod	_	_
7	günstig	günstig	ADJ	ADJD	_	0	root	_	SpaceAfter=No
8	.	.	PUNCT	$.	_	7	punct	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 3 amod	color:blue
1	Auch	auch	ADV	ADV	_	4	advmod	_	_
2	die	der	DET	ART	Definite=Def|PronType=Art	4	det	_	_
3	moderne	modern	ADJ	ADJA	_	4	amod	_	_
4	Madonna	Madonna	PROPN	NE	Case=Nom	8	nsubj	_	_
5	ist	sein	AUX	VAFIN	_	8	cop	_	_
6	ein	ein	DET	ART	Definite=Ind|NumType=Card|PronType=Art	8	det	_	_
7	solcher	solcher	DET	PIAT	PronType=Dem	8	det	_	_
8	Mythus	Mythus	NOUN	NN	Case=Nom	0	root	_	SpaceAfter=No
9	.	.	PUNCT	$.	_	8	punct	_	_

~~~


