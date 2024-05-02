---
layout: base
title:  'Statistics of nmod in UD_English-Pronouns'
udver: '2'
---

## Treebank Statistics: UD_English-Pronouns: Relations: `nmod`

This relation is universal.

30 nodes (2%) are attached to their parents as `nmod`.

25 instances of `nmod` (83%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.83333333333333.

The following 3 pairs of parts of speech are connected with `nmod`: <tt><a href="en_pronouns-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_pronouns-pos-PRON.html">PRON</a></tt> (20; 67% instances), <tt><a href="en_pronouns-pos-NUM.html">NUM</a></tt>-<tt><a href="en_pronouns-pos-PRON.html">PRON</a></tt> (5; 17% instances), <tt><a href="en_pronouns-pos-PRON.html">PRON</a></tt>-<tt><a href="en_pronouns-pos-DET.html">DET</a></tt> (5; 17% instances).


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 4 nmod	color:blue
1	Any	any	DET	DT	PronType=Ind	2	det	_	_
2	car	car	NOUN	NN	Number=Sing	5	nsubj	_	_
3	of	of	ADP	IN	_	4	case	_	_
4	hers	hers	PRON	PRP	Gender=Fem|Number=Sing|Person=3|Poss=Yes|PronType=Prs	2	nmod	_	_
5	sells	sell	VERB	VBZ	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
6	quickly	quickly	ADV	RB	_	5	advmod	_	SpaceAfter=No
7	.	.	PUNCT	.	_	5	punct	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 3 nmod	color:blue
1	One	one	NUM	CD	NumType=Card	5	nsubj	_	_
2	of	of	ADP	IN	_	3	case	_	_
3	hers	hers	PRON	PRP	Gender=Fem|Number=Sing|Person=3|Poss=Yes|PronType=Prs	1	nmod	_	_
4	was	be	AUX	VBD	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin	5	aux:pass	_	_
5	cleaned	clean	VERB	VBN	Tense=Past|VerbForm=Part	0	root	_	SpaceAfter=No
6	.	.	PUNCT	.	_	5	punct	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 4 nmod	color:blue
1	The	the	DET	DT	Definite=Def|PronType=Art	2	det	_	_
2	car	car	NOUN	NN	Number=Sing	5	nsubj	_	_
3	's	be	AUX	VBZ	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	5	cop	_	_
4	all	all	DET	DT	PronType=Tot	5	nmod	_	_
5	hers	hers	PRON	PRP	Gender=Fem|Number=Sing|Person=3|Poss=Yes|PronType=Prs	0	root	_	SpaceAfter=No
6	!	!	PUNCT	.	_	5	punct	_	_

~~~


