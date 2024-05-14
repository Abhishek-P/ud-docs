---
layout: base
title:  'Statistics of orphan in UD_Komi_Zyrian-Lattice'
udver: '2'
---

## Treebank Statistics: UD_Komi_Zyrian-Lattice: Relations: `orphan`

This relation is universal.

15 nodes (0%) are attached to their parents as `orphan`.

12 instances of `orphan` (80%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.8.

The following 9 pairs of parts of speech are connected with `orphan`: <tt><a href="kpv_lattice-pos-NOUN.html">NOUN</a></tt>-<tt><a href="kpv_lattice-pos-NOUN.html">NOUN</a></tt> (5; 33% instances), <tt><a href="kpv_lattice-pos-DET.html">DET</a></tt>-<tt><a href="kpv_lattice-pos-NOUN.html">NOUN</a></tt> (2; 13% instances), <tt><a href="kpv_lattice-pos-NOUN.html">NOUN</a></tt>-<tt><a href="kpv_lattice-pos-ADV.html">ADV</a></tt> (2; 13% instances), <tt><a href="kpv_lattice-pos-DET.html">DET</a></tt>-<tt><a href="kpv_lattice-pos-ADV.html">ADV</a></tt> (1; 7% instances), <tt><a href="kpv_lattice-pos-NOUN.html">NOUN</a></tt>-<tt><a href="kpv_lattice-pos-VERB.html">VERB</a></tt> (1; 7% instances), <tt><a href="kpv_lattice-pos-PRON.html">PRON</a></tt>-<tt><a href="kpv_lattice-pos-NOUN.html">NOUN</a></tt> (1; 7% instances), <tt><a href="kpv_lattice-pos-PRON.html">PRON</a></tt>-<tt><a href="kpv_lattice-pos-PRON.html">PRON</a></tt> (1; 7% instances), <tt><a href="kpv_lattice-pos-VERB.html">VERB</a></tt>-<tt><a href="kpv_lattice-pos-ADV.html">ADV</a></tt> (1; 7% instances), <tt><a href="kpv_lattice-pos-VERB.html">VERB</a></tt>-<tt><a href="kpv_lattice-pos-VERB.html">VERB</a></tt> (1; 7% instances).


~~~ conllu
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 9 orphan	color:blue
1	Озырлун	озырлун	NOUN	N	Case=Nom|Number=Sing	2	nsubj	_	GTtags=Sg,Nom
2	кыссьӧ	кыссьыны	VERB	V	Mood=Ind|Number=Sing|Person=3|Tense=Pres	0	root	_	GTtags=IV,Ind,Prs,Sg3
3	озырлун	озырлун	NOUN	N	Case=Nom|Number=Sing	2	obl:lmod	_	GTtags=Sg,Nom
4	дінӧ	дінӧ	ADP	Adp	AdpType=Post|Case=Ill|Number=Sing	3	case	_	GTtags=Po,Sg,Ill|SpaceAfter=No
5	,	,	PUNCT	CLB	_	7	punct	_	_
6	a	а	CCONJ	CC	_	7	cc	_	_
7	зарни	зарни	NOUN	N	Case=Nom|Number=Sing	2	conj	_	GTtags=Sg,Nom
8	—	—	PUNCT	PUNCT	_	9	punct	_	_
9	зарни	зарни	NOUN	N	Case=Nom|Number=Sing	7	orphan	_	GTtags=Sg,Nom
10	дінӧ	дінӧ	ADP	Adp	AdpType=Post|Case=Ill|Number=Sing	9	case	_	GTtags=Po,Sg,Ill|SpaceAfter=No
11	.	.	PUNCT	CLB	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 12	bgColor:blue
# visual-style 12	fgColor:white
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 10 12 orphan	color:blue
1	Ми	ме	PRON	Pron	Case=Nom|Number=Plur|Person=1|PronType=Prs	14	nsubj	_	GTtags=Pers,Pl1,Nom|SpaceAfter=No
2	,	,	PUNCT	CLB	_	4	punct	_	_
3	кык	кык	NUM	Num	Case=Nom|Number=Sing|NumType=Card	4	nummod	_	GTtags=Card,Sg,Nom
4	чой	чой	NOUN	N	Case=Nom|Number=Sing	1	appos	_	GTtags=Sg,Nom|SpaceAfter=No
5	,	,	PUNCT	CLB	_	6	punct	_	_
6	ӧтиным	ӧти	DET	Det	Case=Nom|Number=Sing|Number[psor]=Plur|NumType=Card|Person[psor]=1	4	conj	_	GTtags=Card,Sg,Nom,PxPl1
7	ва	ва	NOUN	N	Case=Nom|Number=Sing	8	nmod	_	GTtags=Sg,Nom
8	дозйӧн	доз	NOUN	N	Case=Ins|Number=Sing	6	orphan	_	GTtags=Sg,Ins|SpaceAfter=No
9	,	,	PUNCT	CLB	_	10	punct	_	_
10	мӧдным	мӧд	DET	Det	Case=Nom|Number=Sing|Number[psor]=Plur|NumType=Ord|Person[psor]=1	4	conj	_	GTtags=Ord,Sg,Nom,PxPl1
11	пес	пес	NOUN	N	Case=Nom|Number=Sing	12	nmod	_	GTtags=Sg,Nom
12	моздорӧн	моздор	NOUN	N	Case=Ins|Number=Sing	10	orphan	_	GTtags=Sg,Ins|SpaceAfter=No
13	,	,	PUNCT	CLB	_	10	punct	_	_
14	мӧдӧдчим	мӧдӧдчыны	VERB	V	Mood=Ind|Number=Plur|Person=1|Tense=Past	0	root	_	GTtags=Refl,Ind,Prt1,Pl1
15	пывсян	пывсян	NOUN	N	Case=Nom|Number=Sing	16	obj	_	GTtags=Sg,Nom
16	ломтыны	ломтыны	VERB	V	VerbForm=Inf	14	xcomp	_	GTtags=TV,Inf|SpaceAfter=No
17	.	.	PUNCT	CLB	_	14	punct	_	_

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 7 orphan	color:blue
1	Сійӧ	сійӧ	PRON	Pron	Case=Nom|Number=Sing|Person=3|PronType=Prs	2	nsubj	_	_
2	ньӧбис	ньӧбны	VERB	V	Mood=Ind|Number=Sing|Person=3|Tense=Past	0	root	_	_
3	машина	машина	NOUN	N	Case=Nom|Number=Sing	2	obj	_	OrigLang=ru|SpaceAfter=No
4	,	,	PUNCT	CLB	_	6	punct	_	_
5	а	а	CCONJ	CC	_	6	cc	_	OrigLang=ru
6	вокыс	вок	NOUN	N	Case=Nom|Number=Sing|Number[psor]=Sing|Person[psor]=3	2	conj	_	_
7	сӧмын	сӧмын	ADV	Adv	_	6	orphan	_	_
8	велосипед	велосипед	NOUN	N	Case=Nom|Number=Sing	6	orphan	_	OrigLang=ru|SpaceAfter=No
9	.	.	PUNCT	CLB	_	2	punct	_	_

~~~


