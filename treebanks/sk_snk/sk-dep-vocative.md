---
layout: base
title:  'Statistics of vocative in UD_Slovak'
udver: '2'
---

## Treebank Statistics: UD_Slovak: Relations: `vocative`

This relation is universal.

34 nodes (0%) are attached to their parents as `vocative`.

24 instances of `vocative` (71%) are left-to-right (parent precedes child).
Average distance between parent and child is 3.32352941176471.

The following 6 pairs of parts of speech are connected with `vocative`: <tt><a href="sk-pos-VERB.html">VERB</a></tt>-<tt><a href="sk-pos-PROPN.html">PROPN</a></tt> (16; 47% instances), <tt><a href="sk-pos-VERB.html">VERB</a></tt>-<tt><a href="sk-pos-NOUN.html">NOUN</a></tt> (12; 35% instances), <tt><a href="sk-pos-NOUN.html">NOUN</a></tt>-<tt><a href="sk-pos-PROPN.html">PROPN</a></tt> (2; 6% instances), <tt><a href="sk-pos-PRON.html">PRON</a></tt>-<tt><a href="sk-pos-NOUN.html">NOUN</a></tt> (2; 6% instances), <tt><a href="sk-pos-NOUN.html">NOUN</a></tt>-<tt><a href="sk-pos-NOUN.html">NOUN</a></tt> (1; 3% instances), <tt><a href="sk-pos-PROPN.html">PROPN</a></tt>-<tt><a href="sk-pos-NOUN.html">NOUN</a></tt> (1; 3% instances).


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 6 vocative	color:blue
1	"	"	PUNCT	ZIP	_	4	punct	_	SpaceAfter=No
2	Koľko	koľko	DET	PUns4	Case=Acc|Gender=Neut|Number=Sing|NumType=Card|PronType=Int,Rel	3	det:numgov	_	_
3	prstov	prst	NOUN	SSip2	Animacy=Inan|Case=Gen|Gender=Masc|Number=Plur	4	obj	_	_
4	zdvíham	zdvíhať	VERB	VKesa+	Aspect=Imp|Mood=Ind|Number=Sing|Person=1|Polarity=Pos|Tense=Pres|VerbForm=Fin	0	root	_	SpaceAfter=No
5	,	,	PUNCT	ZIP	_	4	punct	_	_
6	Winston	winston	PROPN	SSms5:r	Animacy=Anim|Case=Voc|Gender=Masc|Number=Sing	4	vocative	_	SpaceAfter=No
7	?	?	PUNCT	ZIP	_	4	punct	_	SpaceAfter=No
8	"	"	PUNCT	ZIP	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 6 vocative	color:blue
1	Krásne	krásny	ADJ	AAfp4x	Case=Acc|Degree=Pos|Gender=Fem|Number=Plur	2	amod	_	_
2	Vianoce	vianoce	PROPN	SSfp4:r	Case=Acc|Gender=Fem|Number=Plur	4	obj	_	_
3	Vám	vy	PRON	PPhp3	Case=Dat|Number=Plur|Person=2|PronType=Prs	4	iobj	_	_
4	prajem	priať	VERB	VKesa+	Aspect=Imp|Mood=Ind|Number=Sing|Person=1|Polarity=Pos|Tense=Pres|VerbForm=Fin	0	root	_	SpaceAfter=No
5	,	,	PUNCT	Z	_	6	punct	_	_
6	priatelia	priateľ	NOUN	SSmp5	Animacy=Anim|Case=Voc|Gender=Masc|Number=Plur	4	vocative	_	SpaceAfter=No
7	.	.	PUNCT	Z	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 8 vocative	color:blue
1	"	"	PUNCT	ZIP	_	6	punct	_	SpaceAfter=No
2	Koľko	koľko	DET	PUns1	Case=Nom|Gender=Neut|Number=Sing|NumType=Card|PronType=Int,Rel	6	nsubj	_	_
3	je	byť	AUX	VKesc+	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin	6	cop	_	_
4	teda	teda	PART	T	_	6	advmod	_	_
5	tých	ten	DET	PFip2	Animacy=Inan|Case=Gen|Gender=Masc|Number=Plur|PronType=Dem	6	det	_	_
6	prstov	prst	NOUN	SSip2	Animacy=Inan|Case=Gen|Gender=Masc|Number=Plur	0	root	_	SpaceAfter=No
7	,	,	PUNCT	ZIP	_	6	punct	_	_
8	Winston	winston	PROPN	SSms5:r	Animacy=Anim|Case=Voc|Gender=Masc|Number=Sing	6	vocative	_	SpaceAfter=No
9	?	?	PUNCT	ZIP	_	6	punct	_	SpaceAfter=No
10	"	"	PUNCT	ZIP	_	6	punct	_	_

~~~


