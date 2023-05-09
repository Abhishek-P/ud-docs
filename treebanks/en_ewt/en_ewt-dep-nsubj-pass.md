---
layout: base
title:  'Statistics of nsubj:pass in UD_English-EWT'
udver: '2'
---

## Treebank Statistics: UD_English-EWT: Relations: `nsubj:pass`

This relation is a language-specific subtype of <tt><a href="en_ewt-dep-nsubj.html">nsubj</a></tt>.
There are also 1 other language-specific subtypes of `nsubj`: <tt><a href="en_ewt-dep-nsubj-outer.html">nsubj:outer</a></tt>.

1389 nodes (1%) are attached to their parents as `nsubj:pass`.

1352 instances of `nsubj:pass` (97%) are right-to-left (child precedes parent).
Average distance between parent and child is 3.87329013678906.

The following 7 pairs of parts of speech are connected with `nsubj:pass`: <tt><a href="en_ewt-pos-VERB.html">VERB</a></tt>-<tt><a href="en_ewt-pos-NOUN.html">NOUN</a></tt> (696; 50% instances), <tt><a href="en_ewt-pos-VERB.html">VERB</a></tt>-<tt><a href="en_ewt-pos-PRON.html">PRON</a></tt> (547; 39% instances), <tt><a href="en_ewt-pos-VERB.html">VERB</a></tt>-<tt><a href="en_ewt-pos-PROPN.html">PROPN</a></tt> (114; 8% instances), <tt><a href="en_ewt-pos-VERB.html">VERB</a></tt>-<tt><a href="en_ewt-pos-DET.html">DET</a></tt> (12; 1% instances), <tt><a href="en_ewt-pos-VERB.html">VERB</a></tt>-<tt><a href="en_ewt-pos-ADJ.html">ADJ</a></tt> (10; 1% instances), <tt><a href="en_ewt-pos-VERB.html">VERB</a></tt>-<tt><a href="en_ewt-pos-SYM.html">SYM</a></tt> (6; 0% instances), <tt><a href="en_ewt-pos-VERB.html">VERB</a></tt>-<tt><a href="en_ewt-pos-NUM.html">NUM</a></tt> (4; 0% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 5 nsubj:pass	color:blue
1	In	in	ADP	IN	_	3	case	3:case	_
2	other	other	ADJ	JJ	Degree=Pos	3	amod	3:amod	_
3	words	word	NOUN	NNS	Number=Plur	7	obl	7:obl:in	_
4	the	the	DET	DT	Definite=Def|PronType=Art	5	det	5:det	_
5	table	table	NOUN	NN	Number=Sing	7	nsubj:pass	7:nsubj:pass	_
6	is	be	AUX	VBZ	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	7	aux:pass	7:aux:pass	_
7	set	set	VERB	VBN	Tense=Past|VerbForm=Part|Voice=Pass	0	root	0:root	SpaceAfter=No
8	.	.	PUNCT	.	_	7	punct	7:punct	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 5 nsubj:pass	color:blue
1	Four	four	NUM	CD	NumForm=Word|NumType=Card	2	nummod	2:nummod	_
2	months	month	NOUN	NNS	Number=Plur	3	obl:npmod	3:obl:npmod	_
3	later	late	ADV	RBR	Degree=Cmp	7	advmod	7:advmod	SpaceAfter=No
4	,	,	PUNCT	,	_	7	punct	7:punct	_
5	we	we	PRON	PRP	Case=Nom|Number=Plur|Person=1|PronType=Prs	7	nsubj:pass	7:nsubj:pass	_
6	were	be	AUX	VBD	Mood=Ind|Number=Plur|Person=1|Tense=Past|VerbForm=Fin	7	aux:pass	7:aux:pass	_
7	married	marry	VERB	VBN	Tense=Past|VerbForm=Part|Voice=Pass	0	root	0:root	SpaceAfter=No
8	.	.	PUNCT	.	_	7	punct	7:punct	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 5 nsubj:pass	color:blue
1	Capt.	Capt.	PROPN	NNP	Number=Sing	2	compound	2:compound	_
2	Spastic	Spastic	PROPN	NNP	Number=Sing	5	nmod:poss	5:nmod:poss	_
3	's	's	PART	POS	_	2	case	2:case	_
4	Demented	Demented	ADJ	NNP	Degree=Pos	5	amod	5:amod	_
5	World	World	PROPN	NNP	Number=Sing	7	nsubj:pass	7:nsubj:pass	_
6	is	be	AUX	VBZ	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	7	aux:pass	7:aux:pass	_
7	located	locate	VERB	VBN	Tense=Past|VerbForm=Part|Voice=Pass	0	root	0:root	_
8	at	at	ADP	IN	_	7	obl	7:obl	SpaceAfter=No
9	:	:	PUNCT	:	_	7	punct	7:punct	_
10	<	<	PUNCT	-LRB-	_	7	punct	7:punct	SpaceAfter=No
11	>	>	PUNCT	-RRB-	_	7	punct	7:punct	_

~~~


