---
layout: base
title:  'Statistics of nummod in UD_Erzya-JR'
udver: '2'
---

## Treebank Statistics: UD_Erzya-JR: Relations: `nummod`

This relation is universal.

135 nodes (1%) are attached to their parents as `nummod`.

135 instances of `nummod` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.17777777777778.

The following 6 pairs of parts of speech are connected with `nummod`: <tt><a href="myv_jr-pos-NOUN.html">NOUN</a></tt>-<tt><a href="myv_jr-pos-NUM.html">NUM</a></tt> (129; 96% instances), <tt><a href="myv_jr-pos-VERB.html">VERB</a></tt>-<tt><a href="myv_jr-pos-NUM.html">NUM</a></tt> (2; 1% instances), <tt><a href="myv_jr-pos-ADP.html">ADP</a></tt>-<tt><a href="myv_jr-pos-NUM.html">NUM</a></tt> (1; 1% instances), <tt><a href="myv_jr-pos-ADV.html">ADV</a></tt>-<tt><a href="myv_jr-pos-NUM.html">NUM</a></tt> (1; 1% instances), <tt><a href="myv_jr-pos-NOUN.html">NOUN</a></tt>-<tt><a href="myv_jr-pos-NOUN.html">NOUN</a></tt> (1; 1% instances), <tt><a href="myv_jr-pos-PRON.html">PRON</a></tt>-<tt><a href="myv_jr-pos-NUM.html">NUM</a></tt> (1; 1% instances).


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 4 nummod	color:blue
1	―	―	PUNCT	PUNCT	_	6	punct	_	_
2	Колчаконь	Колчак	PROPN	N	Case=Gen|Definite=Ind|NameType=Sur|Number=Plur,Sing	3	nmod:poss	_	GTtags=Prop,Sem/Sur,SP,Gen,Indef
3	армиясто	армия	NOUN	N	Case=Ela|Definite=Ind|Number=Plur,Sing	6	obl	_	GTtags=SP,Ela,Indef
4	кавто	кавто	NUM	Num	Case=Nom|Definite=Ind|Number=Sing|NumType=Card	5	nummod	_	GTtags=Card,Sg,Nom,Indef
5	полкт	полк	NOUN	N	Case=Nom|Definite=Ind|Number=Plur	6	nsubj	_	GTtags=Sem/Plc,Pl,Nom,Indef
6	калавтсть	калавтомс	VERB	V	Mood=Ind|Number[subj]=Plur|Person[subj]=3|Tense=Past	0	root	_	GTtags=TV,Ind,Prt1,ScPl3|SpaceAfter=No
7	.	.	PUNCT	CLB	_	6	punct	_	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 1 nummod	color:blue
1	Кавонстонь-кавонстонь	кавонстонь-кавонстонь	NUM	_	_	4	nummod	_	CGdephead=#1-&gt;1|CGdeprel=@X|GTtags=?
2	лембе	лембе	ADJ	A	Case=Nom|Definite=Ind|Number=Sing	3	amod	_	CGdephead=#2-&gt;3|CGdeprel=@&gt;N|GTtags=Sg,Nom,Indef
3	пракстат	пракста	NOUN	N	Case=Nom|Definite=Ind|Number=Plur	4	nsubj	_	CGdephead=#3-&gt;3|CGdeprel=@SUBJ&gt;|GTtags=Pl,Nom,Indef
4	эрявольть	эрявомс	VERB	V	Mood=Sub|Number[subj]=Plur|Person[subj]=3	0	root	_	CGdephead=#4-&gt;4|CGdeprel=@FMV|GTtags=IV,Conj,ScPl3
5	бу	бу	AUX	Pcle	Mood=Sub|VerbType=Aux	4	aux:cnd	_	CGdephead=#5-&gt;5|CGdeprel=@X|GTtags=Aux,Conj|SpaceAfter=No
6	.	.	PUNCT	CLB	_	4	punct	_	CGdephead=#6-&gt;6|CGdeprel=@CLB|GTtags=CLB

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 5 nummod	color:blue
1	—	—	PUNCT	PUNCT	_	3	punct	_	_
2	Бандитнэнь	бандит	NOUN	N	Case=Gen|Definite=Def|Number=Plur	3	obj	_	GTtags=Pl,Gen,Def
3	пекстынк	пекстамс	VERB	V	Mood=Imp|Number[obj]=Sing|Number[subj]=Plur|Person[obj]=3|Person[subj]=2	0	root	_	GTtags=TV,Imprt,ScPl2,OcSg3
4	весе	весе	PRON	Pron	Case=Nom|Definite=Ind|Number=Sing|PronType=Tot	3	advcl	_	GTtags=Tot,Sg,Nom,Indef
5	ве	ве	NUM	Num	NumType=Card	6	nummod	_	GTtags=Card,Adn
6	таркас	таркас	ADP	Adp	AdvType=Loc|Case=Ill	3	obl	_	GTtags=Spat,Ill|SpaceAfter=No
7	!	!	PUNCT	CLB	_	3	punct	_	_
8	—	—	PUNCT	PUNCT	_	9	punct	_	_
9	мерсь	меремс	VERB	V	Mood=Ind|Number[subj]=Sing|Person[subj]=3|Tense=Past	3	parataxis	_	GTtags=TV,Ind,Prt1,ScSg3
10	камандирэсь	командир	NOUN	N	Case=Nom|Definite=Def|Number=Sing	9	nsubj	_	GTtags=Dial,Sg,Nom,Def|SpaceAfter=No
11	.	.	PUNCT	CLB	_	3	punct	_	_

~~~


