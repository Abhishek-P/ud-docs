---
layout: base
title:  'Statistics of acl in UD_English-EWT'
udver: '2'
---

## Treebank Statistics: UD_English-EWT: Relations: `acl`

This relation is universal.
There are 1 language-specific subtypes of `acl`: <tt><a href="en_ewt-dep-acl-relcl.html">acl:relcl</a></tt>.

1827 nodes (1%) are attached to their parents as `acl`.

1815 instances of `acl` (99%) are left-to-right (parent precedes child).
Average distance between parent and child is 2.89545703338807.

The following 15 pairs of parts of speech are connected with `acl`: <tt><a href="en_ewt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_ewt-pos-VERB.html">VERB</a></tt> (1608; 88% instances), <tt><a href="en_ewt-pos-PRON.html">PRON</a></tt>-<tt><a href="en_ewt-pos-VERB.html">VERB</a></tt> (67; 4% instances), <tt><a href="en_ewt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="en_ewt-pos-VERB.html">VERB</a></tt> (43; 2% instances), <tt><a href="en_ewt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_ewt-pos-NOUN.html">NOUN</a></tt> (29; 2% instances), <tt><a href="en_ewt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_ewt-pos-ADJ.html">ADJ</a></tt> (28; 2% instances), <tt><a href="en_ewt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="en_ewt-pos-VERB.html">VERB</a></tt> (10; 1% instances), <tt><a href="en_ewt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_ewt-pos-ADV.html">ADV</a></tt> (9; 0% instances), <tt><a href="en_ewt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_ewt-pos-PRON.html">PRON</a></tt> (7; 0% instances), <tt><a href="en_ewt-pos-NUM.html">NUM</a></tt>-<tt><a href="en_ewt-pos-VERB.html">VERB</a></tt> (7; 0% instances), <tt><a href="en_ewt-pos-SYM.html">SYM</a></tt>-<tt><a href="en_ewt-pos-VERB.html">VERB</a></tt> (7; 0% instances), <tt><a href="en_ewt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_ewt-pos-AUX.html">AUX</a></tt> (4; 0% instances), <tt><a href="en_ewt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_ewt-pos-PROPN.html">PROPN</a></tt> (4; 0% instances), <tt><a href="en_ewt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="en_ewt-pos-NOUN.html">NOUN</a></tt> (2; 0% instances), <tt><a href="en_ewt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_ewt-pos-ADP.html">ADP</a></tt> (1; 0% instances), <tt><a href="en_ewt-pos-VERB.html">VERB</a></tt>-<tt><a href="en_ewt-pos-VERB.html">VERB</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 3 acl	color:blue
1	Any	any	DET	DT	PronType=Ind	2	det	2:det	_
2	opinions	opinion	NOUN	NNS	Number=Plur	7	nsubj	7:nsubj	_
3	expressed	express	VERB	VBN	Tense=Past|VerbForm=Part|Voice=Pass	2	acl	2:acl	_
4	herein	herein	ADV	RB	_	3	advmod	3:advmod	_
5	are	be	AUX	VBP	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	7	cop	7:cop	_
6	solely	solely	ADV	RB	_	7	advmod	7:advmod	_
7	those	that	PRON	DT	Number=Plur|PronType=Dem	0	root	0:root	_
8	of	of	ADP	IN	_	10	case	10:case	_
9	the	the	DET	DT	Definite=Def|PronType=Art	10	det	10:det	_
10	author	author	NOUN	NN	Number=Sing	7	nmod	7:nmod:of	SpaceAfter=No
11	.	.	PUNCT	.	_	7	punct	7:punct	_

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 7 acl	color:blue
1	Thanks	thanks	NOUN	NN	Number=Sing	0	root	0:root	_
2	for	for	SCONJ	IN	_	3	mark	3:mark	_
3	thinking	think	VERB	VBG	VerbForm=Ger	1	acl	1:acl:for	_
4	of	of	ADP	IN	_	5	case	5:case	_
5	me	I	PRON	PRP	Case=Acc|Number=Sing|Person=1|PronType=Prs	3	obl	3:obl:of	_
6	to	to	PART	TO	_	7	mark	7:mark	_
7	send	send	VERB	VB	VerbForm=Inf	5	acl	5:acl:to	_
8	it	it	PRON	PRP	Case=Acc|Gender=Neut|Number=Sing|Person=3|PronType=Prs	7	obj	7:obj	_
9	to	to	ADP	IN	_	7	obl	7:obl	Promoted=Yes|SpaceAfter=No
10	.	.	PUNCT	.	_	1	punct	1:punct	_

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 7 acl	color:blue
1	Umar	Umar	PROPN	NNP	Number=Sing	2	compound	2:compound	_
2	Islam	Islam	PROPN	NNP	Number=Sing	0	root	0:root	SpaceAfter=No
3	,	,	PUNCT	,	_	4	punct	4:punct	_
4	28	28	NUM	CD	NumForm=Digit|NumType=Card	2	list	2:list	SpaceAfter=No
5	,	,	PUNCT	,	_	7	punct	7:punct	_
6	(	(	PUNCT	-LRB-	_	7	punct	7:punct	SpaceAfter=No
7	born	bear	VERB	VBN	Tense=Past|VerbForm=Part|Voice=Pass	2	acl	2:acl	_
8	Brian	Brian	PROPN	NNP	Number=Sing	7	xcomp	7:xcomp	_
9	Young	Young	PROPN	NNP	Number=Sing	8	flat	8:flat	SpaceAfter=No
10	)	)	PUNCT	-RRB-	_	7	punct	7:punct	_
11	High	High	ADJ	NNP	Degree=Pos	12	amod	12:amod	_
12	Wycombe	Wycombe	PROPN	NNP	Number=Sing	2	list	2:list	_

~~~


