---
layout: base
title:  'Statistics of nummod:gov in UD_Russian'
udver: '2'
---

## Treebank Statistics: UD_Russian: Relations: `nummod:gov`

This relation is a language-specific subtype of <tt><a href="ru-dep-nummod.html">nummod</a></tt>.

911 nodes (1%) are attached to their parents as `nummod:gov`.

903 instances of `nummod:gov` (99%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.20746432491767.

The following 10 pairs of parts of speech are connected with `nummod:gov`: <tt><a href="ru-pos-NOUN.html">NOUN</a></tt>-<tt><a href="ru-pos-NUM.html">NUM</a></tt> (796; 87% instances), <tt><a href="ru-pos-NOUN.html">NOUN</a></tt>-<tt><a href="ru-pos-NOUN.html">NOUN</a></tt> (52; 6% instances), <tt><a href="ru-pos-SYM.html">SYM</a></tt>-<tt><a href="ru-pos-NUM.html">NUM</a></tt> (44; 5% instances), <tt><a href="ru-pos-ADJ.html">ADJ</a></tt>-<tt><a href="ru-pos-NUM.html">NUM</a></tt> (9; 1% instances), <tt><a href="ru-pos-NUM.html">NUM</a></tt>-<tt><a href="ru-pos-NUM.html">NUM</a></tt> (3; 0% instances), <tt><a href="ru-pos-PROPN.html">PROPN</a></tt>-<tt><a href="ru-pos-NUM.html">NUM</a></tt> (2; 0% instances), <tt><a href="ru-pos-SYM.html">SYM</a></tt>-<tt><a href="ru-pos-NOUN.html">NOUN</a></tt> (2; 0% instances), <tt><a href="ru-pos-NOUN.html">NOUN</a></tt>-<tt><a href="ru-pos-SYM.html">SYM</a></tt> (1; 0% instances), <tt><a href="ru-pos-PRON.html">PRON</a></tt>-<tt><a href="ru-pos-NUM.html">NUM</a></tt> (1; 0% instances), <tt><a href="ru-pos-PUNCT.html">PUNCT</a></tt>-<tt><a href="ru-pos-NUM.html">NUM</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 5 nummod:gov	color:blue
1	Всего	ВСЕГО	ADV	RB	_	2	advmod	_	_
2	скачано	СКАЧАТЬ	VERB	VBNH	Animacy=Inan|Aspect=Perf|Case=Nom|Gender=Neut|Number=Sing|Tense=Past|Variant=Short|VerbForm=Part|Voice=Pass	0	root	_	_
3	содержания	СОДЕРЖАНИЕ	NOUN	NN	Animacy=Inan|Case=Gen|Gender=Neut|Number=Sing	2	obj	_	SpaceAfter=No
4	:	:	PUNCT	:	_	3	punct	_	_
5	207.022	207,022	NUM	CD	Animacy=Inan|Case=Nom|Gender=Masc|NumType=Card	6	nummod:gov	_	_
6	гигабайт	ГИГАБАЙТ	NOUN	NN	Animacy=Inan|Case=Gen|Gender=Masc|Number=Plur	3	appos	_	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 8 nummod:gov	color:blue
1	По	ПО	ADP	IN	_	3	case	_	_
2	официальным	ОФИЦИАЛЬНЫЙ	ADJ	JJL	Animacy=Inan|Case=Dat|Number=Plur	3	amod	_	_
3	данным	ДАННЫЕ	NOUN	NN	Animacy=Inan|Case=Dat|Gender=Neut|Number=Plur	5	obl	_	SpaceAfter=No
4	,	,	PUNCT	,	_	3	punct	_	_
5	погибло	ПОГИБНУТЬ	VERB	VBC	Aspect=Perf|Gender=Neut|Mood=Ind|Number=Sing|Tense=Past|VerbForm=Fin	0	root	_	_
6	более	БОЛЕЕ	ADV	RBR	Degree=Cmp	8	advmod	_	_
7	двух	ДВА	NUM	CD	Animacy=Inan|Case=Gen|Gender=Fem|NumType=Card	8	compound	_	_
8	тысяч	ТЫСЯЧА	NOUN	NN	Animacy=Inan|Case=Gen|Gender=Fem|Number=Plur	9	nummod:gov	_	_
9	человек	ЧЕЛОВЕК	NOUN	NN	Animacy=Anim|Case=Gen|Gender=Masc|Number=Plur	5	nsubj	_	SpaceAfter=No
10	.	.	PUNCT	.	_	5	punct	_	_

~~~


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 6 nummod:gov	color:blue
1	Преобладающая	ПРЕОБЛАДАЮЩИЙ	ADJ	JJL	Animacy=Inan|Case=Nom|Gender=Fem|Number=Sing	2	amod	_	_
2	национальность	НАЦИОНАЛЬНОСТЬ	NOUN	NN	Animacy=Inan|Case=Nom|Gender=Fem|Number=Sing	4	nsubj	_	_
3	--	--	PUNCT	--	_	4	punct	_	_
4	русские	РУССКИЙ	NOUN	NN	Animacy=Anim|Case=Nom|Gender=Masc|Number=Plur	0	root	_	_
5	(	(	PUNCT	(	_	7	punct	_	SpaceAfter=No
6	99	99	NUM	CD	Case=Nom|NumType=Card	7	nummod:gov	_	_
7	%	%	SYM	SYM	_	4	appos	_	SpaceAfter=No
8	)	)	PUNCT	)	_	7	punct	_	SpaceAfter=No
9	.	.	PUNCT	.	_	4	punct	_	_

~~~


