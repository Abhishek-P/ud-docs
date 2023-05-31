---
layout: base
title:  'Statistics of cop in UD_Slovak-SNK'
udver: '2'
---

## Treebank Statistics: UD_Slovak-SNK: Relations: `cop`

This relation is universal.

1583 nodes (1%) are attached to their parents as `cop`.

1333 instances of `cop` (84%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.95388502842704.

The following 9 pairs of parts of speech are connected with `cop`: <tt><a href="sk_snk-pos-NOUN.html">NOUN</a></tt>-<tt><a href="sk_snk-pos-AUX.html">AUX</a></tt> (740; 47% instances), <tt><a href="sk_snk-pos-ADJ.html">ADJ</a></tt>-<tt><a href="sk_snk-pos-AUX.html">AUX</a></tt> (722; 46% instances), <tt><a href="sk_snk-pos-NUM.html">NUM</a></tt>-<tt><a href="sk_snk-pos-AUX.html">AUX</a></tt> (37; 2% instances), <tt><a href="sk_snk-pos-DET.html">DET</a></tt>-<tt><a href="sk_snk-pos-AUX.html">AUX</a></tt> (31; 2% instances), <tt><a href="sk_snk-pos-PRON.html">PRON</a></tt>-<tt><a href="sk_snk-pos-AUX.html">AUX</a></tt> (25; 2% instances), <tt><a href="sk_snk-pos-PROPN.html">PROPN</a></tt>-<tt><a href="sk_snk-pos-AUX.html">AUX</a></tt> (19; 1% instances), <tt><a href="sk_snk-pos-ADV.html">ADV</a></tt>-<tt><a href="sk_snk-pos-AUX.html">AUX</a></tt> (7; 0% instances), <tt><a href="sk_snk-pos-PART.html">PART</a></tt>-<tt><a href="sk_snk-pos-AUX.html">AUX</a></tt> (1; 0% instances), <tt><a href="sk_snk-pos-X.html">X</a></tt>-<tt><a href="sk_snk-pos-AUX.html">AUX</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 4 cop	color:blue
1	Prvou	prvý	ADJ	NAfs7	Case=Ins|Gender=Fem|Number=Sing|NumType=Ord	3	amod	3:amod	_
2	Kimovou	kimov	ADJ	AFfs7x:r	Case=Ins|Degree=Pos|Gender=Fem|Number=Sing	3	amod	3:amod	_
3	zástavkou	zástavka	NOUN	SSfs7	Case=Ins|Gender=Fem|Number=Sing	0	root	0:root	_
4	je	byť	AUX	VKesc+	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin	3	cop	3:cop	_
5	centrum	centrum	NOUN	SSns1	Case=Nom|Gender=Neut|Number=Sing	3	nsubj	3:nsubj	_
6	čínskeho	čínsky	ADJ	AAis2x	Animacy=Inan|Case=Gen|Degree=Pos|Gender=Masc|Number=Sing	7	amod	7:amod	_
7	biznisu	biznis	NOUN	SSis2	Animacy=Inan|Case=Gen|Gender=Masc|Number=Sing	5	nmod	5:nmod:gen	_
8	-	-	PUNCT	ZIP	_	9	punct	9:punct	_
9	Šanghaj	šanghaj	PROPN	SSis1:r	Animacy=Inan|Case=Nom|Gender=Masc|Number=Sing	5	appos	5:appos	SpaceAfter=No
10	.	.	PUNCT	ZIP	_	3	punct	3:punct	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 3 cop	color:blue
1	Po	po	ADP	Eu6	AdpType=Prep|Case=Loc	2	case	2:case	_
2	Silvestri	silvester	PROPN	SSis6:r	Animacy=Inan|Case=Loc|Gender=Masc|Number=Sing	4	obl	4:obl:po:loc	_
3	sú	byť	AUX	VKepc+	Aspect=Imp|Mood=Ind|Number=Plur|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin	4	cop	4:cop	_
4	zničení	zničený	ADJ	AAmp1x	Animacy=Anim|Case=Nom|Degree=Pos|Gender=Masc|Number=Plur	0	root	0:root	_
5	aj	aj	CCONJ	O	_	6	cc	6:cc	_
6	ľudia	človek	NOUN	SSmp1	Animacy=Anim|Case=Nom|Gender=Masc|Number=Plur	4	nsubj	4:nsubj	SpaceAfter=No
7	,	,	PUNCT	ZIP	_	9	punct	9:punct	_
8	aj	aj	CCONJ	O	_	9	cc	9:cc	_
9	zvieratá	zviera	NOUN	SSnp1	Case=Nom|Gender=Neut|Number=Plur	6	conj	4:nsubj|6:conj	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 4 cop	color:blue
1	Spôsob	spôsob	NOUN	SSis1	Animacy=Inan|Case=Nom|Gender=Masc|Number=Sing	5	nsubj	5:nsubj	_
2	jej	jej	DET	PUfs2	Case=Gen|Gender=Fem|Gender[psor]=Fem|Number=Sing|Number[psor]=Sing|Person=3|Poss=Yes|PronType=Prs	3	det	3:det	_
3	domestikácie	domestikácia	NOUN	SSfs2	Case=Gen|Gender=Fem|Number=Sing	1	nmod	1:nmod:gen	_
4	je	byť	AUX	VKesc+	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin	5	cop	5:cop	_
5	jednou	jeden	NUM	NFfs7	Case=Ins|Gender=Fem|Number=Sing	0	root	0:root	_
6	z	z	ADP	Eu2	AdpType=Prep|Case=Gen	8	case	8:case	_
7	najväčších	veľký	ADJ	AAfp2z	Case=Gen|Degree=Sup|Gender=Fem|Number=Plur	8	amod	8:amod	_
8	záhad	záhada	NOUN	SSfp2	Case=Gen|Gender=Fem|Number=Plur	5	nmod	5:nmod:z:gen	_
9	genetiky	genetika	NOUN	SSfs2	Case=Gen|Gender=Fem|Number=Sing	8	nmod	8:nmod:gen	SpaceAfter=No
10	.	.	PUNCT	Z	_	5	punct	5:punct	_

~~~


