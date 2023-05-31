---
layout: base
title:  'Statistics of vocative in UD_Russian'
udver: '2'
---

## Treebank Statistics: UD_Russian: Relations: `vocative`

This relation is universal.

7 nodes (0%) are attached to their parents as `vocative`.

5 instances of `vocative` (71%) are left-to-right (parent precedes child).
Average distance between parent and child is 2.71428571428571.

The following 4 pairs of parts of speech are connected with `vocative`: <tt><a href="ru-pos-VERB.html">VERB</a></tt>-<tt><a href="ru-pos-NOUN.html">NOUN</a></tt> (2; 29% instances), <tt><a href="ru-pos-VERB.html">VERB</a></tt>-<tt><a href="ru-pos-PRON.html">PRON</a></tt> (2; 29% instances), <tt><a href="ru-pos-VERB.html">VERB</a></tt>-<tt><a href="ru-pos-PROPN.html">PROPN</a></tt> (2; 29% instances), <tt><a href="ru-pos-NOUN.html">NOUN</a></tt>-<tt><a href="ru-pos-PROPN.html">PROPN</a></tt> (1; 14% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 5 vocative	color:blue
1	``	``	PUNCT	``	_	3	punct	_	SpaceAfter=No
2	Не	НЕ	PART	NEG	Polarity=Neg	3	advmod	_	_
3	думайте	ДУМАТЬ	VERB	VBC	Aspect=Imp|Mood=Imp|Number=Plur|Person=2|VerbForm=Fin	0	root	_	SpaceAfter=No
4	,	,	PUNCT	,	_	5	punct	_	_
5	товарищи	ТОВАРИЩ	NOUN	NN	Animacy=Anim|Case=Nom|Gender=Masc|Number=Plur	3	vocative	_	SpaceAfter=No
6	,	,	PUNCT	,	_	5	punct	_	_
7	я	Я	PRON	PRP	Case=Nom|Number=Sing|Person=1	8	nsubj	_	_
8	бросаю	БРОСАТЬ	VERB	VBC	Aspect=Imp|Mood=Ind|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin	3	ccomp	_	_
9	слова	СЛОВО	NOUN	NN	Animacy=Inan|Case=Acc|Gender=Neut|Number=Plur	8	obj	_	_
10	на	НА	ADP	IN	_	11	case	_	_
11	ветер	ВЕТЕР	NOUN	NN	Animacy=Inan|Case=Acc|Gender=Masc|Number=Sing	9	nmod	_	SpaceAfter=No
12	.	.	PUNCT	.	_	3	punct	_	_

~~~


~~~ conllu
# visual-style 25	bgColor:blue
# visual-style 25	fgColor:white
# visual-style 23	bgColor:blue
# visual-style 23	fgColor:white
# visual-style 23 25 vocative	color:blue
1	В	В	ADP	IN	_	2	case	_	_
2	ней	ОНА	PRON	PRP	Case=Loc|Gender=Fem|Number=Sing|Person=3	6	obl	_	SpaceAfter=No
3	,	,	PUNCT	,	_	4	punct	_	_
4	конечно	КОНЕЧНО	ADV	UH	_	6	discourse	_	SpaceAfter=No
5	,	,	PUNCT	,	_	4	punct	_	_
6	было	БЫТЬ	VERB	VBC	Aspect=Imp|Gender=Neut|Mood=Ind|Number=Sing|Tense=Past|VerbForm=Fin	0	root	_	_
7	влияние	ВЛИЯНИЕ	NOUN	NN	Animacy=Inan|Case=Nom|Gender=Neut|Number=Sing	6	nsubj	_	_
8	ирландских	ИРЛАНДСКИЙ	ADJ	JJL	Animacy=Inan|Case=Gen|Number=Plur	11	amod	_	_
9	и	И	CCONJ	CC	_	10	cc	_	_
10	шотландских	ШОТЛАНДСКИЙ	ADJ	JJL	Animacy=Inan|Case=Gen|Number=Plur	8	conj	_	_
11	баллад	БАЛЛАДА	NOUN	NN	Animacy=Inan|Case=Gen|Gender=Fem|Number=Plur	7	nmod	_	SpaceAfter=No
12	...	...	PUNCT	:	_	11	punct	_	_
13	&#39;&#39;	&#39;&#39;	PUNCT	``	_	14	punct	_	_
14	Come	COME	VERB	VBC	Aspect=Perf|Mood=Imp|Number=Plur|Person=2|VerbForm=Fin	11	appos	_	_
15	All	ALL	DET	DT	Animacy=Anim|Case=Nom|Number=Plur	16	det	_	_
16	Ye	YE	PRON	PRP	Case=Voc|Number=Plur|Person=2	14	vocative	_	_
17	Bold	BOLD	ADJ	JJL	Animacy=Anim|Case=Nom|Gender=Masc|Number=Sing	19	amod	_	_
18	Highway	HIGHWAY	ADJ	JJL	Animacy=Anim|Case=Nom|Number=Plur	19	compound	_	_
19	Men	MAN	NOUN	NN	Animacy=Anim|Case=Nom|Gender=Masc|Number=Plur	16	appos	_	_
20	&#39;&#39;	&#39;&#39;	PUNCT	&#39;&#39;	_	14	conj	_	SpaceAfter=No
21	,	,	PUNCT	,	_	23	punct	_	_
22	&#39;&#39;	&#39;&#39;	PUNCT	``	_	23	punct	_	_
23	Come	COME	VERB	VBC	Aspect=Perf|Mood=Imp|Number=Plur|Person=2|VerbForm=Fin	14	conj	_	_
24	All	ALL	DET	DT	Animacy=Anim|Case=Voc|Number=Plur	25	det	_	_
25	Ye	YE	PRON	PRP	Case=Voc|Number=Plur|Person=2	23	vocative	_	_
26	Tender	TENDER	ADV	RB	_	27	advmod	_	_
27	Hearted	HEARTED	ADJ	JJL	Animacy=Anim|Case=Nom|Number=Plur	28	amod	_	_
28	Maidens	MAIDEN	NOUN	NN	Animacy=Anim|Case=Nom|Gender=Fem|Number=Plur	25	appos	_	_
29	&#39;&#39;	&#39;&#39;	PUNCT	&#39;&#39;	_	23	punct	_	SpaceAfter=No
30	.	.	PUNCT	.	_	6	punct	_	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 2 vocative	color:blue
1	``	``	PUNCT	``	_	4	punct	_	SpaceAfter=No
2	Адад	АДАД	PROPN	NNP	Animacy=Anim|Case=Nom|Gender=Masc|Number=Sing	4	vocative	_	_
3	потомство	ПОТОМСТВО	NOUN	NN	Animacy=Inan|Case=Acc|Gender=Neut|Number=Sing	4	obj	_	_
4	храни	ХРАНИТЬ	VERB	VBC	Aspect=Imp|Mood=Imp|Number=Sing|Person=2|VerbForm=Fin	21	parataxis	_	_
5	&#39;&#39;	&#39;&#39;	PUNCT	.	_	4	punct	_	SpaceAfter=No
6	;	;	PUNCT	:	_	4	punct	_	_
7	dIM	DIM	ADV	FW	_	4	list	_	SpaceAfter=No
8	,	,	PUNCT	,	_	9	punct	_	_
9	MU	MU	ADV	FW	_	7	list	_	SpaceAfter=No
10	,	,	PUNCT	,	_	11	punct	_	_
11	ŠEŠ	ŠEŠ	ADV	FW	_	7	list	_	_
12	или	ИЛИ	CCONJ	CC	_	13	cc	_	_
13	mdIM	MDIM	ADV	FW	_	7	conj	_	SpaceAfter=No
14	,	,	PUNCT	,	_	15	punct	_	_
15	MU	MU	ADV	FW	_	13	list	_	SpaceAfter=No
16	,	,	PUNCT	,	_	17	punct	_	_
17	ŠEŠ	ŠEŠ	ADV	FW	_	13	list	_	SpaceAfter=No
18	)	)	PUNCT	)	_	4	punct	_	_
19	--	--	PUNCT	--	_	21	punct	_	_
20	касситский	КАССИТСКИЙ	ADJ	JJL	Animacy=Anim|Case=Nom|Gender=Masc|Number=Sing	21	amod	_	_
21	царь	ЦАРЬ	NOUN	NN	Animacy=Anim|Case=Nom|Gender=Masc|Number=Sing	0	root	_	_
22	Вавилонии	ВАВИЛОНИЯ	PROPN	NNP	Animacy=Inan|Case=Gen|Gender=Fem|Number=Sing	21	nmod	_	SpaceAfter=No
23	,	,	PUNCT	,	_	21	punct	_	_
24	правил	ПРАВИТЬ	VERB	VBC	Aspect=Imp|Gender=Masc|Mood=Ind|Number=Sing|Tense=Past|VerbForm=Fin	21	parataxis	_	_
25	приблизительно	ПРИБЛИЗИТЕЛЬНО	ADV	RB	_	26	advmod	_	_
26	в	В	ADP	IN	_	30	case	_	_
27	1219	1219	ADJ	ORD	Animacy=Inan|Case=Loc|Gender=Masc|Number=Sing	30	amod	_	_
28	--	--	PUNCT	--	_	29	punct	_	_
29	1188	1188	ADJ	ORD	Animacy=Inan|Case=Loc|Gender=Masc|Number=Sing	27	list	_	_
30	годах	ГОД	NOUN	NN	Animacy=Inan|Case=Loc|Gender=Masc|Number=Plur	24	obl	_	_
31	до	ДО	ADP	IN	_	33	case	_	_
32	н.	Н.	DET	PRP$	Animacy=Inan|Case=Gen|Gender=Fem|Number=Sing|Person=1	33	det	_	_
33	э	Э	NOUN	NN	Animacy=Inan|Case=Gen|Gender=Fem|Number=Sing	30	nmod	_	SpaceAfter=No
34	.	.	PUNCT	.	_	21	punct	_	_

~~~


