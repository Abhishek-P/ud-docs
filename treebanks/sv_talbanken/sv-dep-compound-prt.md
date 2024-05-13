---
layout: base
title:  'Statistics of compound:prt in UD_Swedish'
udver: '2'
---

## Treebank Statistics: UD_Swedish: Relations: `compound:prt`

This relation is a language-specific subtype of <tt><a href="sv-dep-compound.html">compound</a></tt>.

855 nodes (1%) are attached to their parents as `compound:prt`.

854 instances of `compound:prt` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.35438596491228.

The following 5 pairs of parts of speech are connected with `compound:prt`: <tt><a href="sv-pos-VERB.html">VERB</a></tt>-<tt><a href="sv-pos-ADV.html">ADV</a></tt> (530; 62% instances), <tt><a href="sv-pos-VERB.html">VERB</a></tt>-<tt><a href="sv-pos-ADP.html">ADP</a></tt> (279; 33% instances), <tt><a href="sv-pos-VERB.html">VERB</a></tt>-<tt><a href="sv-pos-NOUN.html">NOUN</a></tt> (40; 5% instances), <tt><a href="sv-pos-VERB.html">VERB</a></tt>-<tt><a href="sv-pos-ADJ.html">ADJ</a></tt> (5; 1% instances), <tt><a href="sv-pos-NOUN.html">NOUN</a></tt>-<tt><a href="sv-pos-ADV.html">ADV</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 3 compound:prt	color:blue
1	Industrialiseringen	industrialisering	NOUN	NN|UTR|SIN|DEF|NOM	Case=Nom|Definite=Def|Gender=Com|Number=Sing	2	nsubj	_	_
2	gick	gå	VERB	VB|PRT|AKT	Mood=Ind|Tense=Past|VerbForm=Fin|Voice=Act	0	root	_	_
3	ut	ut	ADV	PL	_	2	compound:prt	_	_
4	över	över	ADP	PP	_	5	case	_	_
5	kvinnorna	kvinna	NOUN	NN|UTR|PLU|DEF|NOM	Case=Nom|Definite=Def|Gender=Com|Number=Plur	2	obl	_	SpaceAfter=No
6	.	.	PUNCT	MAD	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 2 compound:prt	color:blue
1	Undra	undra	VERB	VB|INF|AKT	VerbForm=Inf|Voice=Act	0	root	_	_
2	på	på	ADP	PL	_	1	compound:prt	_	_
3	att	att	SCONJ	SN	_	7	mark	_	_
4	vi	vi	PRON	PN|UTR|PLU|DEF|SUB	Case=Nom|Definite=Def|Gender=Com|Number=Plur|PronType=Prs	7	nsubj:pass	_	_
5	blev	bli	AUX	VB|PRT|AKT	Mood=Ind|Tense=Past|VerbForm=Fin|Voice=Act	7	aux:pass	_	_
6	lite	lite	ADV	AB|POS	Degree=Pos	7	advmod	_	_
7	undandragna	undandragen	VERB	PC|PRF|UTR/NEU|PLU|IND/DEF|NOM	Case=Nom|Number=Plur|Tense=Past|VerbForm=Part	1	ccomp	_	SpaceAfter=No
8	.	.	PUNCT	MAD	_	1	punct	_	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 5 compound:prt	color:blue
1	Så	så	ADV	AB	_	4	mark	_	_
2	länge	länge	ADV	AB|POS	Degree=Pos	1	fixed	_	_
3	mamma	mamma	NOUN	NN|UTR|SIN|IND|NOM	Case=Nom|Definite=Ind|Gender=Com|Number=Sing	4	nsubj	_	_
4	har	ha	VERB	VB|PRS|AKT	Mood=Ind|Tense=Pres|VerbForm=Fin|Voice=Act	11	advcl	_	_
5	hand	hand	NOUN	NN|UTR|SIN|IND|NOM	Case=Nom|Definite=Ind|Gender=Com|Number=Sing	4	compound:prt	_	_
6	om	om	ADP	PP	_	7	case	_	_
7	barnen	barn	NOUN	NN|NEU|PLU|DEF|NOM	Case=Nom|Definite=Def|Gender=Neut|Number=Plur	4	obl	_	_
8	kan	kunna	AUX	VB|PRS|AKT	Mood=Ind|Tense=Pres|VerbForm=Fin|Voice=Act	11	aux	_	_
9	hon	hon	PRON	PN|UTR|SIN|DEF|SUB	Case=Nom|Definite=Def|Gender=Com|Number=Sing|PronType=Prs	11	nsubj	_	_
10	inte	inte	ADV	AB	Polarity=Neg	11	advmod	_	_
11	välja	välja	VERB	VB|INF|AKT	VerbForm=Inf|Voice=Act	0	root	_	_
12	...	...	PUNCT	MAD	_	11	punct	_	_

~~~


