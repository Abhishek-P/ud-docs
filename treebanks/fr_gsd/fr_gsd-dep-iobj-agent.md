---
layout: base
title:  'Statistics of iobj:agent in UD_French-GSD'
udver: '2'
---

## Treebank Statistics: UD_French-GSD: Relations: `iobj:agent`

This relation is a language-specific subtype of <tt><a href="fr_gsd-dep-iobj.html">iobj</a></tt>.

24 nodes (0%) are attached to their parents as `iobj:agent`.

24 instances of `iobj:agent` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 2.5.

The following 1 pairs of parts of speech are connected with `iobj:agent`: <tt><a href="fr_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="fr_gsd-pos-PRON.html">PRON</a></tt> (24; 100% instances).


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 7 iobj:agent	color:blue
1	Son	son	DET	_	Number=Sing|Number[psor]=Sing|Person[psor]=3|Poss=Yes|PronType=Prs	2	det	_	wordform=son
2	entourage	entourage	NOUN	_	Gender=Masc|Number=Sing	9	nsubj:caus	_	SpaceAfter=No
3	,	,	PUNCT	_	_	5	punct	_	_
4	ses	son	DET	_	Number=Plur|Number[psor]=Sing|Person[psor]=3|Poss=Yes|PronType=Prs	5	det	_	_
5	enfants	enfant	NOUN	_	Number=Plur	2	conj	_	_
6	le	lui	PRON	_	Emph=No|Gender=Masc|Number=Sing|Person=3|PronType=Prs	9	obj	_	_
7	lui	lui	PRON	_	Emph=No|Gender=Masc|Number=Sing|Person=3|PronType=Prs	9	iobj:agent	_	_
8	font	faire	AUX	_	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	9	aux:caus	_	_
9	remarquer	remarquer	VERB	_	VerbForm=Inf	0	root	_	SpaceAfter=No|Subject=Generic
10	.	.	PUNCT	_	_	9	punct	_	_

~~~


