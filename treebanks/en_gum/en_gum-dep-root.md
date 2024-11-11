---
layout: base
title:  'Statistics of root in UD_English-GUM'
udver: '2'
---

## Treebank Statistics: UD_English-GUM: Relations: `root`

This relation is universal.

12146 nodes (6%) are attached to their parents as `root`.

12146 instances of `root` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 5.51053844887206.

The following 15 pairs of parts of speech are connected with `root`: -<tt><a href="en_gum-pos-VERB.html">VERB</a></tt> (7729; 64% instances), -<tt><a href="en_gum-pos-NOUN.html">NOUN</a></tt> (1730; 14% instances), -<tt><a href="en_gum-pos-ADJ.html">ADJ</a></tt> (939; 8% instances), -<tt><a href="en_gum-pos-PROPN.html">PROPN</a></tt> (565; 5% instances), -<tt><a href="en_gum-pos-INTJ.html">INTJ</a></tt> (476; 4% instances), -<tt><a href="en_gum-pos-ADV.html">ADV</a></tt> (224; 2% instances), -<tt><a href="en_gum-pos-PRON.html">PRON</a></tt> (170; 1% instances), -<tt><a href="en_gum-pos-NUM.html">NUM</a></tt> (135; 1% instances), -<tt><a href="en_gum-pos-AUX.html">AUX</a></tt> (109; 1% instances), -<tt><a href="en_gum-pos-X.html">X</a></tt> (20; 0% instances), -<tt><a href="en_gum-pos-DET.html">DET</a></tt> (16; 0% instances), -<tt><a href="en_gum-pos-PART.html">PART</a></tt> (10; 0% instances), -<tt><a href="en_gum-pos-ADP.html">ADP</a></tt> (9; 0% instances), -<tt><a href="en_gum-pos-CCONJ.html">CCONJ</a></tt> (8; 0% instances), -<tt><a href="en_gum-pos-SYM.html">SYM</a></tt> (6; 0% instances).


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 0	bgColor:blue
# visual-style 0	fgColor:white
# visual-style 0 1 root	color:blue
1	Leading	lead	VERB	VBG	Tense=Pres|VerbForm=Part	0	root	0:root	Discourse=elaboration-additional:2->1:0:sem-synym-1-2,9|MSeg=Lead-ing
2	Dutch	Dutch	ADJ	JJ	Degree=Pos	3	amod	3:amod	Entity=(3-person-new-cf2-2-sgl
3	Librarians	librarian	NOUN	NNS	Number=Plur	1	obj	1:obj	Entity=3)|MSeg=Librari-an-s
4	into	into	ADP	IN	_	5	case	5:case	MSeg=in-to
5	DH	DH	PROPN	NNP	Abbr=Yes|Number=Sing	1	obl	1:obl:into	Entity=(2-abstract-giv:act-cf1*-1-coref-Digital_humanities)

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 0	bgColor:blue
# visual-style 0	fgColor:white
# visual-style 0 1 root	color:blue
1	Introduction	introduction	NOUN	NN	Number=Sing	0	root	0:root	Discourse=organization-heading:1->29:3:grf-ly-|Entity=(1-abstract-new-cf1-1-sgl)|MSeg=Introduc-tion

~~~


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 0	bgColor:blue
# visual-style 0	fgColor:white
# visual-style 0 6 root	color:blue
1	However	however	ADV	RB	_	6	advmod	6:advmod	Discourse=evaluation-comment:13->8:3:lex-indwd-78;adversative-contrast:13->8:0:2:orp-however-73|MSeg=How-ever|PDTB=Explicit:Comparison.Contrast:however:73:36-72:74-87|SpaceAfter=No
2	,	,	PUNCT	,	_	1	punct	1:punct	_
3	it	it	PRON	PRP	Case=Nom|Gender=Neut|Number=Sing|Person=3|PronType=Prs	6	expl	6:expl	Entity=(18-event-new-cf2-1-cata)
4	is	be	AUX	VBZ	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	6	cop	6:cop	_
5	not	not	PART	RB	Polarity=Neg	6	advmod	6:advmod	Negation=Yes
6	enough	enough	ADJ	JJ	Degree=Pos	0	root	0:root	_
7	to	to	PART	TO	_	9	mark	9:mark	Entity=(18-event-acc:com-cf2-3-coref
8	have	have	AUX	VB	VerbForm=Inf	9	aux	9:aux	_
9	attained	attain	VERB	VBN	Tense=Past|VerbForm=Part	6	csubj	6:csubj	MSeg=attain-ed
10	such	such	ADJ	JJ	_	14	amod	14:amod	Entity=(13-abstract-giv:act-cf1*-5-coref
11	native	native	ADJ	JJ	Degree=Pos	13	compound	13:compound	SpaceAfter=No|XML=<w>
12	-	-	PUNCT	HYPH	_	11	punct	11:punct	SpaceAfter=No
13	like	like	ADJ	JJ	Degree=Pos	14	amod	14:amod	XML=</w>
14	levels	level	NOUN	NNS	Number=Plur	9	obj	9:obj	Entity=13)18)|MSeg=level-s|SpaceAfter=No
15	.	.	PUNCT	.	_	6	punct	6:punct	_

~~~


