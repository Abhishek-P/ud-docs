---
layout: base
title:  'Statistics of compound:prt in UD_Finnish'
udver: '2'
---

## Treebank Statistics: UD_Finnish: Relations: `compound:prt`

This relation is a language-specific subtype of <tt><a href="fi-dep-compound.html">compound</a></tt>.
There are also 1 other language-specific subtypes of `compound`: <tt><a href="fi-dep-compound-nn.html">compound:nn</a></tt>.

281 nodes (0%) are attached to their parents as `compound:prt`.

225 instances of `compound:prt` (80%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.40213523131673.

The following 6 pairs of parts of speech are connected with `compound:prt`: <tt><a href="fi-pos-VERB.html">VERB</a></tt>-<tt><a href="fi-pos-ADV.html">ADV</a></tt> (257; 91% instances), <tt><a href="fi-pos-NOUN.html">NOUN</a></tt>-<tt><a href="fi-pos-ADV.html">ADV</a></tt> (11; 4% instances), <tt><a href="fi-pos-VERB.html">VERB</a></tt>-<tt><a href="fi-pos-NOUN.html">NOUN</a></tt> (6; 2% instances), <tt><a href="fi-pos-ADV.html">ADV</a></tt>-<tt><a href="fi-pos-ADV.html">ADV</a></tt> (4; 1% instances), <tt><a href="fi-pos-VERB.html">VERB</a></tt>-<tt><a href="fi-pos-ADJ.html">ADJ</a></tt> (2; 1% instances), <tt><a href="fi-pos-NOUN.html">NOUN</a></tt>-<tt><a href="fi-pos-ADP.html">ADP</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 3 compound:prt	color:blue
1	Ottakaa	ottaa	VERB	V	Mood=Imp|Number=Plur|Person=2|VerbForm=Fin|Voice=Act	0	root	_	_
2	minut	minä	PRON	Pron	Case=Acc|Number=Sing|Person=1|PronType=Prs	1	obj	_	_
3	mukaan	mukaan	ADV	Adv	_	1	compound:prt	_	SpaceAfter=No
4	,	,	PUNCT	Punct	_	6	punct	_	_
5	niin	niin	ADV	Adv	_	6	mark	_	_
6	saatte	saada	VERB	V	Mood=Ind|Number=Plur|Person=2|Tense=Pres|VerbForm=Fin|Voice=Act	1	advcl	_	_
7	luotettavan	luotettava	ADJ	A	Case=Gen|Degree=Pos|Number=Sing	8	amod	_	_
8	turvamiehen	turva#mies	NOUN	N	Case=Gen|Number=Sing	6	obj	_	SpaceAfter=No
9	.	.	PUNCT	Punct	_	1	punct	_	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 8 compound:prt	color:blue
1	Päätimme	päättää	VERB	V	Mood=Ind|Number=Plur|Person=1|Tense=Past|VerbForm=Fin|Voice=Act	0	root	_	_
2	myös	myös	ADV	Adv	_	3	advmod	_	_
3	säilyttää	säilyttää	VERB	V	InfForm=1|Number=Sing|VerbForm=Inf|Voice=Act	1	xcomp	_	_
4	kuuden	kuusi	NUM	Num	Case=Gen|Number=Sing|NumType=Card	5	nummod	_	_
5	kuukauden	kuu#kausi	NOUN	N	Case=Gen|Number=Sing	6	nmod:poss	_	_
6	siirtymäkauden	siirtymä#kausi	NOUN	N	Case=Gen|Number=Sing	3	obj	_	_
7	direktiivin	direktiivi	NOUN	N	Case=Gen|Number=Sing	9	nmod:gsubj	_	_
8	voimaan	voimaan	ADV	Adv	_	9	compound:prt	_	_
9	astumisen	astuminen	NOUN	N	Case=Gen|Derivation=Minen|Number=Sing	3	obl	_	_
10	jälkeen	jälkeen	ADP	Adp	AdpType=Post	9	case	_	SpaceAfter=No
11	.	.	PUNCT	Punct	_	1	punct	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 4 compound:prt	color:blue
1	Moni	moni	PRON	Pron	Case=Nom|Number=Sing|PronType=Ind	2	det	_	_
2	yhtiö	yhtiö	NOUN	N	Case=Nom|Number=Sing	3	nsubj	_	_
3	ottikin	ottaa	VERB	V	Clitic=Kin|Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin|Voice=Act	0	root	_	_
4	vaarin	vaari	NOUN	N	Case=Gen|Number=Sing	3	compound:prt	_	_
5	analyytikkojen	analyytikko	NOUN	N	Case=Gen|Number=Plur	6	nmod:poss	_	_
6	ohjeista	ohje	NOUN	N	Case=Ela|Number=Plur	3	obl	_	SpaceAfter=No
7	.	.	PUNCT	Punct	_	3	punct	_	_

~~~


