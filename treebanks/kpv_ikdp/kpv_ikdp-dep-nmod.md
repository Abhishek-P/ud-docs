---
layout: base
title:  'Statistics of nmod in UD_Komi_Zyrian-IKDP'
udver: '2'
---

## Treebank Statistics: UD_Komi_Zyrian-IKDP: Relations: `nmod`

This relation is universal.
There are 2 language-specific subtypes of `nmod`: <tt><a href="kpv_ikdp-dep-nmod-poss.html">nmod:poss</a></tt>, <tt><a href="kpv_ikdp-dep-nmod-prp.html">nmod:prp</a></tt>.

89 nodes (4%) are attached to their parents as `nmod`.

70 instances of `nmod` (79%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.85393258426966.

The following 12 pairs of parts of speech are connected with `nmod`: <tt><a href="kpv_ikdp-pos-NOUN.html">NOUN</a></tt>-<tt><a href="kpv_ikdp-pos-NOUN.html">NOUN</a></tt> (44; 49% instances), <tt><a href="kpv_ikdp-pos-NOUN.html">NOUN</a></tt>-<tt><a href="kpv_ikdp-pos-PRON.html">PRON</a></tt> (18; 20% instances), <tt><a href="kpv_ikdp-pos-ADJ.html">ADJ</a></tt>-<tt><a href="kpv_ikdp-pos-NOUN.html">NOUN</a></tt> (5; 6% instances), <tt><a href="kpv_ikdp-pos-VERB.html">VERB</a></tt>-<tt><a href="kpv_ikdp-pos-NOUN.html">NOUN</a></tt> (5; 6% instances), <tt><a href="kpv_ikdp-pos-NOUN.html">NOUN</a></tt>-<tt><a href="kpv_ikdp-pos-ADJ.html">ADJ</a></tt> (4; 4% instances), <tt><a href="kpv_ikdp-pos-NOUN.html">NOUN</a></tt>-<tt><a href="kpv_ikdp-pos-PROPN.html">PROPN</a></tt> (4; 4% instances), <tt><a href="kpv_ikdp-pos-VERB.html">VERB</a></tt>-<tt><a href="kpv_ikdp-pos-PRON.html">PRON</a></tt> (3; 3% instances), <tt><a href="kpv_ikdp-pos-PROPN.html">PROPN</a></tt>-<tt><a href="kpv_ikdp-pos-NOUN.html">NOUN</a></tt> (2; 2% instances), <tt><a href="kpv_ikdp-pos-ADJ.html">ADJ</a></tt>-<tt><a href="kpv_ikdp-pos-NUM.html">NUM</a></tt> (1; 1% instances), <tt><a href="kpv_ikdp-pos-NOUN.html">NOUN</a></tt>-<tt><a href="kpv_ikdp-pos-NUM.html">NUM</a></tt> (1; 1% instances), <tt><a href="kpv_ikdp-pos-PRON.html">PRON</a></tt>-<tt><a href="kpv_ikdp-pos-NOUN.html">NOUN</a></tt> (1; 1% instances), <tt><a href="kpv_ikdp-pos-PROPN.html">PROPN</a></tt>-<tt><a href="kpv_ikdp-pos-PRON.html">PRON</a></tt> (1; 1% instances).


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 6 nmod	color:blue
1	Рӧдитчи	рӧдитчыны	VERB	V	Mood=Ind|Number=Sing|Person=1|Tense=Past	0	root	_	OrigLang=ru
2	ме	ме	PRON	Pron	Case=Nom|Number=Sing|Person=1|PronType=Prs	1	nsubj	_	_
3	шейсят	шейсят	NUM	Num	Case=Nom|Number=Sing|NumType=Card	4	nummod	_	OrigLang=ru
4	четвёртэй	четвёртэй	NUM	Num	Case=Nom|Number=Sing|NumType=Ord	5	nummod	_	OrigLang=ru
5	годын	год	NOUN	N	Case=Ine|Number=Sing	1	obl	_	OrigLang=ru
6	октяб	октяб	NOUN	N	Case=Nom|Number=Sing	7	nmod	_	OrigLang=ru
7	тӧлысе	тӧлысь	NOUN	N	Case=Ill|Number=Sing	1	obl	_	_
8	тундраын	тундра	NOUN	N	Case=Ine|Number=Sing	1	obl	_	OrigLang=ru|SpaceAfter=No
9	.	.	PUNCT	CLB	_	1	punct	_	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 1 nmod	color:blue
1	Миян	ми	PRON	Pron	Case=Gen|Number=Plur|Person=1|PronType=Prs	2	nmod	_	_
2	семяын	семя	NOUN	N	Case=Ine|Number=Sing	0	root	_	OrigLang=ru
3	дас	дас	NUM	Num	Case=Nom|Number=Sing|NumType=Card	4	nummod	_	_
4	морт	морт	NOUN	N	Case=Nom|Number=Sing	2	nsubj	_	SpaceAfter=No
5	.	.	PUNCT	CLB	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 10 nmod	color:blue
1	А	а	CCONJ	CC	_	3	cc	_	OrigLang=ru
2	храмыс	храм	NOUN	N	Case=Nom|Number=Sing|Number[psor]=Sing|Person[psor]=3	3	nsubj	_	_
3	восьса	восьса	ADJ	A	Case=Nom|Number=Sing	0	root	_	_
4	дзик	дзик	ADV	Adv	_	6	advmod:deg	_	_
5	быд	быд	PRON	Pron	PronType=Tot	6	det	_	_
6	лун	лун	NOUN	N	Case=Nom|Number=Sing	3	obl	_	_
7	с	с	ADP	Pr	_	8	case	_	Lang=ru
8	десяти	десять	NUM	Num	NumType=Card	3	nmod	_	Lang=ru
9	до	до	ADP	Pr	_	10	case	_	Lang=ru
10	часу	час	NOUN	N	Case=Dat|Number=Sing	3	nmod	_	Lang=ru|SpaceAfter=No
11	.	.	PUNCT	CLB	_	3	punct	_	_

~~~


