---
layout: base
title:  'Statistics of compound in UD_Norwegian-Bokmaal'
udver: '2'
---

## Treebank Statistics: UD_Norwegian-Bokmaal: Relations: `compound`

This relation is universal.

304 nodes (0%) are attached to their parents as `compound`.

304 instances of `compound` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.75986842105263.

The following 21 pairs of parts of speech are connected with `compound`: <tt><a href="no_bokmaal-pos-NOUN.html">NOUN</a></tt>-<tt><a href="no_bokmaal-pos-PROPN.html">PROPN</a></tt> (107; 35% instances), <tt><a href="no_bokmaal-pos-NUM.html">NUM</a></tt>-<tt><a href="no_bokmaal-pos-NUM.html">NUM</a></tt> (53; 17% instances), <tt><a href="no_bokmaal-pos-NOUN.html">NOUN</a></tt>-<tt><a href="no_bokmaal-pos-NOUN.html">NOUN</a></tt> (52; 17% instances), <tt><a href="no_bokmaal-pos-NOUN.html">NOUN</a></tt>-<tt><a href="no_bokmaal-pos-ADJ.html">ADJ</a></tt> (14; 5% instances), <tt><a href="no_bokmaal-pos-NOUN.html">NOUN</a></tt>-<tt><a href="no_bokmaal-pos-ADP.html">ADP</a></tt> (12; 4% instances), <tt><a href="no_bokmaal-pos-NOUN.html">NOUN</a></tt>-<tt><a href="no_bokmaal-pos-NUM.html">NUM</a></tt> (11; 4% instances), <tt><a href="no_bokmaal-pos-NOUN.html">NOUN</a></tt>-<tt><a href="no_bokmaal-pos-PRON.html">PRON</a></tt> (10; 3% instances), <tt><a href="no_bokmaal-pos-NOUN.html">NOUN</a></tt>-<tt><a href="no_bokmaal-pos-SYM.html">SYM</a></tt> (10; 3% instances), <tt><a href="no_bokmaal-pos-NOUN.html">NOUN</a></tt>-<tt><a href="no_bokmaal-pos-VERB.html">VERB</a></tt> (10; 3% instances), <tt><a href="no_bokmaal-pos-NOUN.html">NOUN</a></tt>-<tt><a href="no_bokmaal-pos-X.html">X</a></tt> (7; 2% instances), <tt><a href="no_bokmaal-pos-NOUN.html">NOUN</a></tt>-<tt><a href="no_bokmaal-pos-CCONJ.html">CCONJ</a></tt> (6; 2% instances), <tt><a href="no_bokmaal-pos-ADJ.html">ADJ</a></tt>-<tt><a href="no_bokmaal-pos-PROPN.html">PROPN</a></tt> (2; 1% instances), <tt><a href="no_bokmaal-pos-PROPN.html">PROPN</a></tt>-<tt><a href="no_bokmaal-pos-X.html">X</a></tt> (2; 1% instances), <tt><a href="no_bokmaal-pos-ADJ.html">ADJ</a></tt>-<tt><a href="no_bokmaal-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="no_bokmaal-pos-ADV.html">ADV</a></tt>-<tt><a href="no_bokmaal-pos-ADV.html">ADV</a></tt> (1; 0% instances), <tt><a href="no_bokmaal-pos-NOUN.html">NOUN</a></tt>-<tt><a href="no_bokmaal-pos-ADV.html">ADV</a></tt> (1; 0% instances), <tt><a href="no_bokmaal-pos-NOUN.html">NOUN</a></tt>-<tt><a href="no_bokmaal-pos-DET.html">DET</a></tt> (1; 0% instances), <tt><a href="no_bokmaal-pos-NOUN.html">NOUN</a></tt>-<tt><a href="no_bokmaal-pos-SCONJ.html">SCONJ</a></tt> (1; 0% instances), <tt><a href="no_bokmaal-pos-PROPN.html">PROPN</a></tt>-<tt><a href="no_bokmaal-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="no_bokmaal-pos-PROPN.html">PROPN</a></tt>-<tt><a href="no_bokmaal-pos-PROPN.html">PROPN</a></tt> (1; 0% instances), <tt><a href="no_bokmaal-pos-VERB.html">VERB</a></tt>-<tt><a href="no_bokmaal-pos-NOUN.html">NOUN</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 1 compound	color:blue
1	Jan	Jan	PROPN	subst	Gender=Masc	2	compound	_	_
2	Mayen-lovens	Mayen-lov	NOUN	subst	Case=Gen|Definite=Def|Gender=Masc|Number=Sing	3	nmod	_	_
3	regler	regel	NOUN	subst	Definite=Ind|Gender=Masc|Number=Plur	4	nsubj	_	_
4	gjelder	gjelde	VERB	verb	Mood=Ind|Tense=Pres|VerbForm=Fin	0	root	_	_
5	for	for	ADP	prep	_	7	case	_	_
6	øyas	øy	NOUN	subst	Case=Gen|Definite=Def|Gender=Fem|Number=Sing	7	nmod	_	_
7	land-	land-	NOUN	subst	_	4	obl	_	_
8	og	og	CCONJ	konj	_	9	cc	_	_
9	sjøterritorium	sjøterritorium	NOUN	subst	Definite=Ind|Gender=Neut|Number=Sing	7	conj	_	SpaceAfter=No
10	.	$.	PUNCT	clb	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 7 compound	color:blue
1	-	$-	PUNCT	<strek>	_	2	punct	_	_
2	Bedre	god	ADJ	adj	Degree=Cmp	0	root	_	_
3	å	å	PART	inf-merke	_	4	mark	_	_
4	kjøpe	kjøpe	VERB	verb	VerbForm=Inf	2	csubj	_	_
5	veske	veske	NOUN	subst	Definite=Ind|Gender=Fem|Number=Sing	4	obj	_	_
6	til	til	ADP	prep	_	8	case	_	_
7	33	33	NUM	det	Number=Plur|NumType=Card	8	compound	_	_
8	000	000	NUM	det	Number=Plur|NumType=Card	5	nmod	_	_
9	enn	enn	ADP	prep	_	10	case	_	_
10	aksjer	aksje	NOUN	subst	Definite=Ind|Gender=Masc|Number=Plur	2	obl	_	_

~~~


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 6 compound	color:blue
1	Han	han	PRON	pron	Animacy=Hum|Case=Nom|Gender=Masc|Number=Sing|Person=3|PronType=Prs	4	nsubj	_	_
2	var	være	AUX	verb	Mood=Ind|Tense=Past|VerbForm=Fin	4	cop	_	_
3	selv	selv	ADV	adv	_	4	advmod	_	_
4	med	med	ADP	prep	_	0	root	_	_
5	på	på	ADP	prep	_	7	case	_	_
6	jorden	jord	NOUN	subst	Definite=Def|Gender=Masc|Number=Sing	7	compound	_	_
7	rundt-reisen	rundt-reise	NOUN	subst	Definite=Def|Gender=Masc|Number=Sing	4	obl	_	_
8	før	før	SCONJ	sbu	_	10	mark	_	_
9	dette	dette	PRON	pron	Gender=Neut|Number=Sing|Person=3|PronType=Prs	10	nsubj	_	_
10	skjedde	skje	VERB	verb	Mood=Ind|Tense=Past|VerbForm=Fin	4	advcl	_	SpaceAfter=No
11	.	$.	PUNCT	clb	_	4	punct	_	_

~~~


