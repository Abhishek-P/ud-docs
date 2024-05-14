---
layout: base
title:  'Statistics of discourse in UD_Moksha-JR'
udver: '2'
---

## Treebank Statistics: UD_Moksha-JR: Relations: `discourse`

This relation is universal.

15 nodes (0%) are attached to their parents as `discourse`.

14 instances of `discourse` (93%) are right-to-left (child precedes parent).
Average distance between parent and child is 3.46666666666667.

The following 7 pairs of parts of speech are connected with `discourse`: <tt><a href="mdf_jr-pos-VERB.html">VERB</a></tt>-<tt><a href="mdf_jr-pos-INTJ.html">INTJ</a></tt> (5; 33% instances), <tt><a href="mdf_jr-pos-ADV.html">ADV</a></tt>-<tt><a href="mdf_jr-pos-INTJ.html">INTJ</a></tt> (3; 20% instances), <tt><a href="mdf_jr-pos-ADJ.html">ADJ</a></tt>-<tt><a href="mdf_jr-pos-INTJ.html">INTJ</a></tt> (2; 13% instances), <tt><a href="mdf_jr-pos-NOUN.html">NOUN</a></tt>-<tt><a href="mdf_jr-pos-INTJ.html">INTJ</a></tt> (2; 13% instances), <tt><a href="mdf_jr-pos-ADJ.html">ADJ</a></tt>-<tt><a href="mdf_jr-pos-PART.html">PART</a></tt> (1; 7% instances), <tt><a href="mdf_jr-pos-PRON.html">PRON</a></tt>-<tt><a href="mdf_jr-pos-ADJ.html">ADJ</a></tt> (1; 7% instances), <tt><a href="mdf_jr-pos-VERB.html">VERB</a></tt>-<tt><a href="mdf_jr-pos-PART.html">PART</a></tt> (1; 7% instances).


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 1 discourse	color:blue
1	Вов	вов	INTJ	Interj	_	2	discourse	_	_
2	раман	рамамс	VERB	V	Mood=Ind|Number[subj]=Sing|Person[subj]=1|Tense=Pres|VerbForm=Fin	0	root	_	GTtags=Ind,Prs,ScSg1
3	хромовай	хромовай	ADJ	A	Case=Nom|Definite=Ind|Number=Sing	4	amod	_	GTtags=Sg,Nom,Indef
4	кямот	кяме	NOUN	N	Case=Nom|Definite=Ind|Number=Plur	2	obj	_	GTtags=Pl,Nom,Indef
5	—	—	PUNCT	PUNCT	_	7	punct	_	_
6	эста	эста	ADV	Adv	AdvType=Tim	7	advmod:tmod	_	GTtags=Sem/Time
7	няйсак	няемс	VERB	V	Mood=Ind|Number[obj]=Sing|Number[subj]=Sing|Person[obj]=3|Person[subj]=2|Tense=Pres|VerbForm=Fin	2	parataxis	_	GTtags=Ind,Prs,ScSg2,OcSg3|SpaceAfter=No
8	!	!	PUNCT	PUNCT	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 1 discourse	color:blue
1	Вай	вай	INTJ	Interj	_	3	discourse	_	_
2	конашкава	конашкава	ADV	Adv	_	3	advmod:deg	_	_
3	ужяль	ужяль	ADV	Adv	_	0	root	_	_
4	вазнясь	вазня	NOUN	N	Case=Nom|Definite=Def|Number=Sing	3	nsubj:cop	_	GTtags=Sg,Nom,Def|SpaceAfter=No
5	!	!	PUNCT	CLB	_	3	punct	_	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 1 discourse	color:blue
1	Ну	ну	INTJ	Interj	_	6	discourse	_	SpaceAfter=No
2	,	,	PUNCT	CLB	_	6	punct	_	_
3	кли	кли	ADV	Adv	_	4	advmod	_	_
4	онцтон	он	NOUN	N	Case=Ela|Number=Plur,Sing|Number[psor]=Sing|Person[psor]=1	6	obl	_	SpaceAfter=No
5	,	,	PUNCT	CLB	_	4	punct	_	_
6	пара	пара	ADJ	A	Case=Nom|Definite=Ind|Number=Sing	0	root	_	SpaceAfter=No
7	:	:	PUNCT	CLB	_	11	punct	_	_
8	гулянять	гуляня	NOUN	N	Case=Gen|Definite=Def|Number=Sing	9	nmod	_	_
9	пацяняц	паця	NOUN	N	Case=Nom|Degree=Dim|Number=Sing|Number[psor]=Sing|Person[psor]=3	11	obj	_	_
10	апак	аф	AUX	Aux	PartForm=NegConvPrc|Polarity=Neg|VerbForm=Conv,Part	11	aux:neg	_	_
11	синтть	синдемс	VERB	V	Connegative=Yes	6	csubj	_	SpaceAfter=No
12	.	.	PUNCT	CLB	_	6	punct	_	_

~~~


