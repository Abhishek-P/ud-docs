---
layout: base
title:  'Statistics of nmod:poss in UD_Moksha-JR'
udver: '2'
---

## Treebank Statistics: UD_Moksha-JR: Relations: `nmod:poss`

This relation is a language-specific subtype of <tt><a href="mdf_jr-dep-nmod.html">nmod</a></tt>.
There are also 4 other language-specific subtypes of `nmod`: <tt><a href="mdf_jr-dep-nmod-bahuv.html">nmod:bahuv</a></tt>, <tt><a href="mdf_jr-dep-nmod-gobj.html">nmod:gobj</a></tt>, <tt><a href="mdf_jr-dep-nmod-lmod.html">nmod:lmod</a></tt>, <tt><a href="mdf_jr-dep-nmod-tmod.html">nmod:tmod</a></tt>.

42 nodes (1%) are attached to their parents as `nmod:poss`.

41 instances of `nmod:poss` (98%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.11904761904762.

The following 3 pairs of parts of speech are connected with `nmod:poss`: <tt><a href="mdf_jr-pos-NOUN.html">NOUN</a></tt>-<tt><a href="mdf_jr-pos-NOUN.html">NOUN</a></tt> (27; 64% instances), <tt><a href="mdf_jr-pos-NOUN.html">NOUN</a></tt>-<tt><a href="mdf_jr-pos-PRON.html">PRON</a></tt> (10; 24% instances), <tt><a href="mdf_jr-pos-NOUN.html">NOUN</a></tt>-<tt><a href="mdf_jr-pos-PROPN.html">PROPN</a></tt> (5; 12% instances).


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 1 nmod:poss	color:blue
1	Елена	Елена	NOUN	N	Case=Nom|Definite=Ind|Number=Sing	3	nmod:poss	_	GTtags=Prop,Sem/Fem,Sg,Nom,Indef
2	Васильевнань	Васильевна	NOUN	N	Case=Gen|Definite=Ind|Number=Plur,Sing	1	flat:name	_	GTtags=Prop,Sem/Patr,Sem/Fem,SP,Gen,Indef
3	эряфса	эряф	NOUN	N	Case=Ine|Definite=Ind|Number=Plur,Sing	8	obl	_	GTtags=SP,Ine,Indef
4	тя	тя	PRON	Pron	Case=Nom|Number=Sing|PronType=Dem	8	nsubj	_	GTtags=Dem,Sg,Nom
5	ульсь	улемс	AUX	V	Mood=Ind|Number[subj]=Sing|Person[subj]=3|Tense=Past	8	cop	_	GTtags=IV,Ind,Prt1,ScSg3
6	омбоце	омбоце	ADJ	A	Case=Nom|Definite=Ind|Number=Sing|NumType=Ord	8	amod	_	GTtags=Der/Ord,A,Ord,Sg,Nom,Indef
7	оцю	оцю	ADJ	A	Case=Nom|Definite=Ind|Number=Sing	8	amod	_	GTtags=Sg,Nom,Indef
8	ризфсь-пичефкссь	ризф-пичефкс	NOUN	N	Case=Nom|Definite=Def|Number=Sing	0	root	_	GTtags=Sg,Nom,Def|SpaceAfter=No
9	.	.	PUNCT	CLB	_	8	punct	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 4 nmod:poss	color:blue
1	Кальдявста	кальдявста	ADV	Adv	_	2	advmod:mmod	_	_
2	тиень	тиемс	VERB	V	Mood=Ind|Number[subj]=Sing|Person[subj]=1|Tense=Past	0	root	_	GTtags=TV,Ind,Prt1,ScSg1|SpaceAfter=No
3	,	,	PUNCT	CLB	_	6	punct	_	_
4	тонь	тон	PRON	Pron	Case=Gen|Number=Sing|Person=2|PronType=Prs	5	nmod:poss	_	GTtags=Pers,Sg2,Gen
5	тевцень	тев	NOUN	N	Case=Gen|Number=Sing|Number[psor]=Sing|Person[psor]=2	6	obj	_	GTtags=Sg,Gen,PxSg2
6	юкстань	юкстамс	VERB	V	Mood=Ind|Number[subj]=Sing|Person[subj]=1|Tense=Past	2	appos	_	GTtags=TV,Ind,Prt1,ScSg1|SpaceAfter=No
7	.	.	PUNCT	CLB	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 7 nmod:poss	color:blue
1	Михаил	Михаил	PROPN	N	Animacy=Hum|Case=Nom|Definite=Ind|Gender=Masc|NameType=Sur|Number=Sing	6	nsubj	_	GTtags=Prop,Sg,Nom,Indef
2	Девятаев	Девятаев	PROPN	N	Animacy=Hum|Case=Nom|Definite=Ind|Gender=Masc|NameType=Sur|Number=Sing	1	flat:name	_	GTtags=Prop,Sem/Mal-Sur,Sg,Nom,Indef
3	ялга	ялга	NOUN	N	Case=Nom|Definite=Ind|Number=Sing	6	obl	_	GTtags=Sg,Nom,Indef
4	мархта	мархта	ADP	Adp	_	3	case	_	_
5	марса	марса	ADV	Adv	_	3	advmod	_	_
6	служась	служамс	VERB	V	Mood=Ind|Number[subj]=Sing|Person[subj]=3|Tense=Past|VerbForm=Fin	0	root	_	GTtags=Ind,Prt1,ScSg3
7	Покрышкинонь	Покрышкин	PROPN	N	Animacy=Hum|Case=Gen|Definite=Ind|Gender=Masc|NameType=Sur|Number=Plur,Sing	8	nmod:poss	_	GTtags=Prop,Sem/Mal-Sur,SP,Gen,Indef
8	дивизияса	дивизия	NOUN	N	Case=Ine|Definite=Ind|Number=Plur,Sing	6	obl:lmod	_	GTtags=SP,Ine,Indef|SpaceAfter=No
9	.	.	PUNCT	PUNCT	_	6	punct	_	_

~~~


