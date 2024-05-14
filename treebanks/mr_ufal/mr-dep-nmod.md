---
layout: base
title:  'Statistics of nmod in UD_Marathi'
udver: '2'
---

## Treebank Statistics: UD_Marathi: Relations: `nmod`

This relation is universal.
There are 1 language-specific subtypes of `nmod`: <tt><a href="mr-dep-nmod-poss.html">nmod:poss</a></tt>.

5 nodes (0%) are attached to their parents as `nmod`.

5 instances of `nmod` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 2.6.

The following 3 pairs of parts of speech are connected with `nmod`: <tt><a href="mr-pos-NOUN.html">NOUN</a></tt>-<tt><a href="mr-pos-NOUN.html">NOUN</a></tt> (3; 60% instances), <tt><a href="mr-pos-VERB.html">VERB</a></tt>-<tt><a href="mr-pos-NOUN.html">NOUN</a></tt> (1; 20% instances), <tt><a href="mr-pos-VERB.html">VERB</a></tt>-<tt><a href="mr-pos-PRON.html">PRON</a></tt> (1; 20% instances).


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 1 nmod	color:blue
1	चांदी	चांदी	NOUN	_	Case=Nom|Gender=Fem|Number=Sing	5	nmod	_	_
2	-	-	PUNCT	_	_	1	punct	_	_
3	_	सोने	NOUN	_	Case=Obl|Gender=Neut|Number=Sing	1	conj	_	_
4	_	चा	ADP	_	Gender=Neut|Number=Plur	3	case	_	_
5	भांडी	भांडे	NOUN	_	Case=Nom|Gender=Neut|Number=Plur	6	nsubj	_	_
6	होती	असणे	AUX	_	Gender=Neut|Number=Plur|Person=3|Tense=Past|VerbForm=Fin	0	root	_	_
7	.	.	PUNCT	_	_	6	punct	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 4 nmod	color:blue
1	तो	तो	PRON	_	Case=Nom|Distance=Dist|Gender=Masc|Number=Sing|Person=3	5	nsubj	_	_
2	_	आई	NOUN	_	Case=Obl|Gender=Fem|Number=Sing	4	nmod:poss	_	_
3	_	चा	ADP	_	Case=Obl	2	case	_	_
4	पाया	पाय	NOUN	_	Case=Loc|Gender=Masc|Number=Sing	5	nmod	_	_
5	पडला	पडणे	VERB	_	Aspect=Perf|Gender=Masc|Number=Sing|Person=3|VerbForm=Fin	0	root	_	_
6	.	.	PUNCT	_	_	5	punct	_	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 1 nmod	color:blue
1	_	तो	PRON	_	Distance=Dist|Gender=Neut|Number=Sing|Person=3	5	nmod	_	_
2	_	च्या	PART	_	_	1	case	_	_
3	_	वर	ADP	_	_	1	case	_	_
4	अंबारी	अंबारी	NOUN	_	Case=Nom|Gender=Fem|Number=Sing	5	nsubj:pass	_	_
5	ठेवण्यात	ठेवणे	VERB	_	Case=Loc|InfForm=Dict|VerbForm=Inf	0	root	_	_
6	आली	येणे	AUX	_	Aspect=Perf|Gender=Fem|Number=Sing|Person=3|VerbForm=Fin	5	aux:pass	_	_
7	.	.	PUNCT	_	_	5	punct	_	_

~~~


