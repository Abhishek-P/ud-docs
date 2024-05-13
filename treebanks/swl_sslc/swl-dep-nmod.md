---
layout: base
title:  'Statistics of nmod in UD_Swedish_Sign_Language'
udver: '2'
---

## Treebank Statistics: UD_Swedish_Sign_Language: Relations: `nmod`

This relation is universal.
There are 1 language-specific subtypes of `nmod`: <tt><a href="swl-dep-nmod-poss.html">nmod:poss</a></tt>.

13 nodes (1%) are attached to their parents as `nmod`.

7 instances of `nmod` (54%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.84615384615385.

The following 4 pairs of parts of speech are connected with `nmod`: <tt><a href="swl-pos-NOUN.html">NOUN</a></tt>-<tt><a href="swl-pos-PRON.html">PRON</a></tt> (6; 46% instances), <tt><a href="swl-pos-NOUN.html">NOUN</a></tt>-<tt><a href="swl-pos-NOUN.html">NOUN</a></tt> (4; 31% instances), <tt><a href="swl-pos-VERB.html">VERB</a></tt>-<tt><a href="swl-pos-NOUN.html">NOUN</a></tt> (2; 15% instances), <tt><a href="swl-pos-NOUN.html">NOUN</a></tt>-<tt><a href="swl-pos-VERB.html">VERB</a></tt> (1; 8% instances).


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 1 nmod	color:blue
1	POSS1	_	PRON	PN	_	2	nmod	_	_
2	DRÖM	_	NOUN	NN	_	0	root	_	_
3	PRO1	_	PRON	PN	_	2	nmod	_	_

~~~


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 6 nmod	color:blue
1	PRO1	_	PRON	PN	_	2	nsubj	_	_
2	BESTÄMMA-SIG	_	VERB	VB	_	0	root	_	_
3	TA	_	VERB	VB	_	2	conj	_	_
4	MEDIA^PROGRAM	_	NOUN	NN	_	3	obj	_	_
5	I@b	_	ADP	PP	_	6	case	_	_
6	ÖREBRO@en	_	NOUN	NN	_	4	nmod	_	_

~~~


~~~ conllu
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 10 nmod	color:blue
1	VARA	_	VERB	VB	_	3	cop	_	_
2	POSS1	_	PRON	PN	_	3	nmod:poss	_	_
3	MÅLSÄTTNING	_	NOUN	NN	_	0	root	_	_
4	FORTSÄTTA	_	VERB	VB	_	3	csubj	_	_
5	TID-FRAMÅT	_	ADV	AB	_	4	advmod	_	_
6	MED	_	ADP	PP	_	7	case	_	_
7	BASKETBOLL	_	NOUN	NN	_	4	obl	_	_
8	PRO1	_	PRON	PN	_	10	nmod:poss	_	_
9	STOR	_	ADJ	JJ	_	10	amod	_	_
10	INTRESSE	_	NOUN	NN	_	4	nmod	_	_

~~~


