---
layout: base
title:  'Statistics of xcomp in UD_Scottish_Gaelic-ARCOSG'
udver: '2'
---

## Treebank Statistics: UD_Scottish_Gaelic-ARCOSG: Relations: `xcomp`

This relation is universal.
There are 1 language-specific subtypes of `xcomp`: <tt><a href="gd_arcosg-dep-xcomp-pred.html">xcomp:pred</a></tt>.

1324 nodes (1%) are attached to their parents as `xcomp`.

1302 instances of `xcomp` (98%) are left-to-right (parent precedes child).
Average distance between parent and child is 5.06722054380665.

The following 17 pairs of parts of speech are connected with `xcomp`: <tt><a href="gd_arcosg-pos-VERB.html">VERB</a></tt>-<tt><a href="gd_arcosg-pos-NOUN.html">NOUN</a></tt> (601; 45% instances), <tt><a href="gd_arcosg-pos-NOUN.html">NOUN</a></tt>-<tt><a href="gd_arcosg-pos-NOUN.html">NOUN</a></tt> (586; 44% instances), <tt><a href="gd_arcosg-pos-ADJ.html">ADJ</a></tt>-<tt><a href="gd_arcosg-pos-NOUN.html">NOUN</a></tt> (80; 6% instances), <tt><a href="gd_arcosg-pos-PROPN.html">PROPN</a></tt>-<tt><a href="gd_arcosg-pos-NOUN.html">NOUN</a></tt> (16; 1% instances), <tt><a href="gd_arcosg-pos-NOUN.html">NOUN</a></tt>-<tt><a href="gd_arcosg-pos-VERB.html">VERB</a></tt> (9; 1% instances), <tt><a href="gd_arcosg-pos-PRON.html">PRON</a></tt>-<tt><a href="gd_arcosg-pos-NOUN.html">NOUN</a></tt> (9; 1% instances), <tt><a href="gd_arcosg-pos-NOUN.html">NOUN</a></tt>-<tt><a href="gd_arcosg-pos-ADJ.html">ADJ</a></tt> (5; 0% instances), <tt><a href="gd_arcosg-pos-VERB.html">VERB</a></tt>-<tt><a href="gd_arcosg-pos-ADJ.html">ADJ</a></tt> (4; 0% instances), <tt><a href="gd_arcosg-pos-ADV.html">ADV</a></tt>-<tt><a href="gd_arcosg-pos-NOUN.html">NOUN</a></tt> (3; 0% instances), <tt><a href="gd_arcosg-pos-VERB.html">VERB</a></tt>-<tt><a href="gd_arcosg-pos-VERB.html">VERB</a></tt> (3; 0% instances), <tt><a href="gd_arcosg-pos-X.html">X</a></tt>-<tt><a href="gd_arcosg-pos-NOUN.html">NOUN</a></tt> (2; 0% instances), <tt><a href="gd_arcosg-pos-ADJ.html">ADJ</a></tt>-<tt><a href="gd_arcosg-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="gd_arcosg-pos-ADP.html">ADP</a></tt>-<tt><a href="gd_arcosg-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="gd_arcosg-pos-ADV.html">ADV</a></tt>-<tt><a href="gd_arcosg-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="gd_arcosg-pos-PRON.html">PRON</a></tt>-<tt><a href="gd_arcosg-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="gd_arcosg-pos-VERB.html">VERB</a></tt>-<tt><a href="gd_arcosg-pos-NUM.html">NUM</a></tt> (1; 0% instances), <tt><a href="gd_arcosg-pos-VERB.html">VERB</a></tt>-<tt><a href="gd_arcosg-pos-PROPN.html">PROPN</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 5 xcomp	color:blue
1	am	am	PART	Qq	PartType=Vb|PronType=Int	2	mark:prt	_	_
2	faod	faod	VERB	V-f--d	Mood=Ind|Tense=Fut|VerbForm=Fin	0	root	_	_
3	mise	mi	PRON	Pp1s--e	Form=Emp|Number=Sing|Person=1|PronType=Prs	2	nsubj	_	_
4	am	an	DET	Dp3p	Number=Plur|Person=3|Poss=Yes|PronType=Prs	5	obj	_	_
5	faighinn	faigh	NOUN	Nv	VerbForm=Inf	2	xcomp	_	SpaceAfter=No
6	?	?	PUNCT	Fg	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 7 xcomp	color:blue
1	chan	cha	PART	Qn	PartType=Vb|Polarity=Neg	2	mark:prt	_	_
2	eil	bi	VERB	V-p--d	Mood=Ind|Tense=Pres|VerbForm=Fin	0	root	_	_
3	sibh	sibh	PRON	Pp2p	Number=Plur|Person=2|PronType=Prs	2	nsubj	_	_
4	a’	ag	PART	Sa	_	5	case	_	_
5	dol	rach	NOUN	Nv	VerbForm=Vnoun	2	xcomp:pred	_	_
6	a	a	PART	Ug	PartType=Inf	7	mark:prt	_	_
7	dh’fhosgail	fosg	NOUN	Nv	VerbForm=Inf	5	xcomp	_	_
8	sin	sin	PRON	Pd	PronType=Dem	7	obl	_	_
9	an-dràsda	an-dràsda	ADV	Rt	_	7	advmod	_	_
10	idir	idir	ADV	Rg	_	7	advmod	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 4 xcomp	color:blue
1	bhiodh	bi	VERB	V-h	Mood=Ind|VerbForm=Fin	0	root	_	_
2	e	e	PRON	Pp3sm	Gender=Masc|Number=Sing|Person=3|PronType=Prs	1	nsubj	_	_
3	toilichte	toilichte	ADJ	Ap	_	1	xcomp:pred	_	_
4	faighinn	faigh	NOUN	Nv	VerbForm=Vnoun	3	xcomp	_	_
5	beothaichean	beothach	NOUN	Ncpmg	Case=Gen|Gender=Masc|Number=Plur	4	obj	_	_
6	saor	saor	ADJ	Aq-pmg	Case=Gen|Gender=Masc|Number=Plur	5	amod	_	_

~~~


