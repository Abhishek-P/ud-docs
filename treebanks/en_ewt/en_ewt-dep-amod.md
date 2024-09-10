---
layout: base
title:  'Statistics of amod in UD_English-EWT'
udver: '2'
---

## Treebank Statistics: UD_English-EWT: Relations: `amod`

This relation is universal.

12236 nodes (5%) are attached to their parents as `amod`.

11873 instances of `amod` (97%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.37757437070938.

The following 22 pairs of parts of speech are connected with `amod`: <tt><a href="en_ewt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_ewt-pos-ADJ.html">ADJ</a></tt> (10045; 82% instances), <tt><a href="en_ewt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="en_ewt-pos-ADJ.html">ADJ</a></tt> (1067; 9% instances), <tt><a href="en_ewt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_ewt-pos-VERB.html">VERB</a></tt> (759; 6% instances), <tt><a href="en_ewt-pos-PRON.html">PRON</a></tt>-<tt><a href="en_ewt-pos-ADJ.html">ADJ</a></tt> (142; 1% instances), <tt><a href="en_ewt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="en_ewt-pos-ADJ.html">ADJ</a></tt> (102; 1% instances), <tt><a href="en_ewt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="en_ewt-pos-VERB.html">VERB</a></tt> (51; 0% instances), <tt><a href="en_ewt-pos-NUM.html">NUM</a></tt>-<tt><a href="en_ewt-pos-ADJ.html">ADJ</a></tt> (24; 0% instances), <tt><a href="en_ewt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="en_ewt-pos-NUM.html">NUM</a></tt> (10; 0% instances), <tt><a href="en_ewt-pos-SYM.html">SYM</a></tt>-<tt><a href="en_ewt-pos-ADJ.html">ADJ</a></tt> (8; 0% instances), <tt><a href="en_ewt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="en_ewt-pos-VERB.html">VERB</a></tt> (5; 0% instances), <tt><a href="en_ewt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_ewt-pos-X.html">X</a></tt> (5; 0% instances), <tt><a href="en_ewt-pos-VERB.html">VERB</a></tt>-<tt><a href="en_ewt-pos-ADJ.html">ADJ</a></tt> (5; 0% instances), <tt><a href="en_ewt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="en_ewt-pos-X.html">X</a></tt> (2; 0% instances), <tt><a href="en_ewt-pos-DET.html">DET</a></tt>-<tt><a href="en_ewt-pos-ADJ.html">ADJ</a></tt> (2; 0% instances), <tt><a href="en_ewt-pos-SYM.html">SYM</a></tt>-<tt><a href="en_ewt-pos-SYM.html">SYM</a></tt> (2; 0% instances), <tt><a href="en_ewt-pos-ADV.html">ADV</a></tt>-<tt><a href="en_ewt-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="en_ewt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_ewt-pos-NUM.html">NUM</a></tt> (1; 0% instances), <tt><a href="en_ewt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_ewt-pos-SYM.html">SYM</a></tt> (1; 0% instances), <tt><a href="en_ewt-pos-NUM.html">NUM</a></tt>-<tt><a href="en_ewt-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="en_ewt-pos-PRON.html">PRON</a></tt>-<tt><a href="en_ewt-pos-PART.html">PART</a></tt> (1; 0% instances), <tt><a href="en_ewt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="en_ewt-pos-SYM.html">SYM</a></tt> (1; 0% instances), <tt><a href="en_ewt-pos-SYM.html">SYM</a></tt>-<tt><a href="en_ewt-pos-VERB.html">VERB</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 7 amod	color:blue
1	The	the	DET	DT	Definite=Def|PronType=Art	3	det	3:det	_
2	US	US	PROPN	NNP	Number=Sing	3	compound	3:compound	_
3	troops	troops	NOUN	NNS	Number=Ptan	4	nsubj	4:nsubj	_
4	fired	fire	VERB	VBD	Mood=Ind|Number=Plur|Person=3|Tense=Past|VerbForm=Fin	0	root	0:root	_
5	into	into	ADP	IN	_	8	case	8:case	_
6	the	the	DET	DT	Definite=Def|PronType=Art	8	det	8:det	_
7	hostile	hostile	ADJ	JJ	Degree=Pos	8	amod	8:amod	_
8	crowd	crowd	NOUN	NN	Number=Sing	4	obl	4:obl:into	SpaceAfter=No
9	,	,	PUNCT	,	_	10	punct	10:punct	_
10	killing	kill	VERB	VBG	Tense=Pres|VerbForm=Part	4	advcl	4:advcl	_
11	4	4	NUM	CD	NumForm=Digit|NumType=Card	10	obj	10:obj	SpaceAfter=No
12	.	.	PUNCT	.	_	4	punct	4:punct	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 1 amod	color:blue
1	Dear	dear	ADJ	JJ	Degree=Pos	2	amod	2:amod	_
2	Nina	Nina	PROPN	NNP	Number=Sing	0	root	0:root	SpaceAfter=No
3	,	,	PUNCT	,	_	2	punct	2:punct	_

~~~


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 6 amod	color:blue
1	This	this	PRON	DT	Number=Sing|PronType=Dem	7	nsubj	7:nsubj	_
2	is	be	AUX	VBZ	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	7	cop	7:cop	_
3	one	one	NUM	CD	NumForm=Word|NumType=Card	7	nummod	7:nummod	_
4	thought	thought	NOUN	NN	Number=Sing	6	compound	6:compound	SpaceAfter=No
5	-	-	PUNCT	HYPH	_	4	punct	4:punct	SpaceAfter=No
6	provoking	provoke	VERB	VBG	VerbForm=Ger	7	amod	7:amod	_
7	film	film	NOUN	NN	Number=Sing	0	root	0:root	SpaceAfter=No
8	.	.	PUNCT	.	_	7	punct	7:punct	_

~~~


