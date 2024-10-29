---
layout: base
title:  'Statistics of nsubj:cop in UD_Moksha-JR'
udver: '2'
---

## Treebank Statistics: UD_Moksha-JR: Relations: `nsubj:cop`

This relation is a language-specific subtype of <tt><a href="mdf_jr-dep-nsubj.html">nsubj</a></tt>.
There are also 1 other language-specific subtypes of `nsubj`: <tt><a href="mdf_jr-dep-nsubj-pass.html">nsubj:pass</a></tt>.

61 nodes (1%) are attached to their parents as `nsubj:cop`.

47 instances of `nsubj:cop` (77%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.98360655737705.

The following 12 pairs of parts of speech are connected with `nsubj:cop`: <tt><a href="mdf_jr-pos-ADJ.html">ADJ</a></tt>-<tt><a href="mdf_jr-pos-NOUN.html">NOUN</a></tt> (29; 48% instances), <tt><a href="mdf_jr-pos-NOUN.html">NOUN</a></tt>-<tt><a href="mdf_jr-pos-NOUN.html">NOUN</a></tt> (6; 10% instances), <tt><a href="mdf_jr-pos-PRON.html">PRON</a></tt>-<tt><a href="mdf_jr-pos-NOUN.html">NOUN</a></tt> (6; 10% instances), <tt><a href="mdf_jr-pos-ADJ.html">ADJ</a></tt>-<tt><a href="mdf_jr-pos-PROPN.html">PROPN</a></tt> (5; 8% instances), <tt><a href="mdf_jr-pos-ADV.html">ADV</a></tt>-<tt><a href="mdf_jr-pos-NOUN.html">NOUN</a></tt> (3; 5% instances), <tt><a href="mdf_jr-pos-NOUN.html">NOUN</a></tt>-<tt><a href="mdf_jr-pos-PRON.html">PRON</a></tt> (3; 5% instances), <tt><a href="mdf_jr-pos-VERB.html">VERB</a></tt>-<tt><a href="mdf_jr-pos-NOUN.html">NOUN</a></tt> (3; 5% instances), <tt><a href="mdf_jr-pos-ADJ.html">ADJ</a></tt>-<tt><a href="mdf_jr-pos-PRON.html">PRON</a></tt> (2; 3% instances), <tt><a href="mdf_jr-pos-ADJ.html">ADJ</a></tt>-<tt><a href="mdf_jr-pos-NUM.html">NUM</a></tt> (1; 2% instances), <tt><a href="mdf_jr-pos-NOUN.html">NOUN</a></tt>-<tt><a href="mdf_jr-pos-ADJ.html">ADJ</a></tt> (1; 2% instances), <tt><a href="mdf_jr-pos-NOUN.html">NOUN</a></tt>-<tt><a href="mdf_jr-pos-PROPN.html">PROPN</a></tt> (1; 2% instances), <tt><a href="mdf_jr-pos-VERB.html">VERB</a></tt>-<tt><a href="mdf_jr-pos-PRON.html">PRON</a></tt> (1; 2% instances).


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 2 nsubj:cop	color:blue
1	Ня	ня	PRON	Pron	_	2	det	_	_
2	стирнятне	стирь	NOUN	N	Case=Nom|Definite=Def|Degree=Dim|Number=Plur	3	nsubj:cop	_	GTtags=Pl,Nom,Def
3	малат	мала	ADJ	A	Case=Nom|Definite=Ind|Number=Plur	0	root	_	GTtags=Pl,Nom,Indef
4	Веряскинонди	Веряскин	PROPN	N	Case=Dat|Definite=Ind|NameType=Sur|Number=Plur,Sing	3	nmod	_	GTtags=Prop,SP,Dat,Indef|SpaceAfter=No
5	,	,	PUNCT	CLB	_	8	punct	_	_
6	сяс	сяс	ADV	Adv	_	8	mark	_	_
7	самозост	самс	VERB	V	Case=Ill|Number=Plur,Sing|Number[psor]=Plur|Person[psor]=3|VerbForm=Vnoun	8	advcl	_	GTtags=IV,Der/NomAct,SP,Ill,PxPl3
8	кенярдсь	кенярдемс	VERB	V	Mood=Ind|Number[subj]=Sing|Person[subj]=3|Tense=Past	3	advcl	_	GTtags=IV,Ind,Prt1,ScSg3|SpaceAfter=No
9	.	.	PUNCT	CLB	_	3	punct	_	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 1 nsubj:cop	color:blue
1	Янгаев	Янгаев	NOUN	N	Case=Nom|Definite=Ind|Number=Sing	4	nsubj:cop	_	GTtags=Prop,Sg,Nom,Indef
2	цёрась	цёра	NOUN	N	Case=Nom|Definite=Def|Number=Sing	1	nmod	_	GTtags=Sg,Nom,Def
3	ульсь	улемс	AUX	V	Mood=Ind|Number[subj]=Sing|Person[subj]=3|Tense=Past|VerbForm=Fin	4	cop	_	GTtags=Ind,Prt1,ScSg3
4	мокша	мокша	NOUN	N	Case=Nom|Definite=Ind|Number=Sing	0	root	_	GTtags=Sg,Nom,Indef
5	и	и	CCONJ	CC	_	7	cc	_	_
6	рузкс	руз	NOUN	N	Case=Tra|Definite=Ind|Number=Sing	7	obl	_	GTtags=Sg,Tra,Indef,Clt/Add
7	корхтась	корхтамс	VERB	V	Mood=Ind|Number[subj]=Sing|Person[subj]=3|Tense=Past|VerbForm=Fin	4	conj	_	GTtags=Ind,Prt1,ScSg3
8	ёфси	ёфси	ADV	Adv	_	9	advmod:deg	_	_
9	кальдявста	кальдявста	ADV	Adv	_	7	advmod:mmod	_	SpaceAfter=No
10	.	.	PUNCT	CLB	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 1 nsubj:cop	color:blue
1	Волясь	воля	NOUN	N	Case=Nom|Definite=Def|Number=Sing	2	nsubj:cop	_	GTtags=Sg,Nom,Def
2	тинь	тон	PRON	Pron	Case=Gen|Number=Plur|Person=2|PronType=Prs	0	root	_	GTtags=Pers,Pl2,Gen|SpaceAfter=No
3	,	,	PUNCT	PUNCT	_	4	punct	_	_
4	тиеда-арада	тиемс-арамс	VERB	V	Mood=Imp|Number[subj]=Plur|Person[subj]=2	2	conj	_	GTtags=Imprt,ScPl2|SpaceAfter=No
5	,	,	PUNCT	PUNCT	_	9	punct	_	_
6	кода	кода	ADV	Adv	_	9	mark	_	_
7	сяда	сяда	ADV	Adv	AdvType=Deg	8	advmod:deg	_	GTtags=Deg
8	лад	лад	NOUN	N	Case=Nom|Definite=Ind|Number=Sing	9	nsubj:cop	_	GTtags=Sg,Nom,Indef
9	тейнть	тон	PRON	Pron	Case=Dat|Number=Plur|Person=2|PronType=Prs|Variant=Short	4	conj	_	GTtags=Pers,Pl2,Dat,Short|SpaceAfter=No
10	..	..	PUNCT	PUNCT	_	2	punct	_	_

~~~


