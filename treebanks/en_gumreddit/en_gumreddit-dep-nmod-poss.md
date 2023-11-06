---
layout: base
title:  'Statistics of nmod:poss in UD_English-GUMReddit'
udver: '2'
---

## Treebank Statistics: UD_English-GUMReddit: Relations: `nmod:poss`

This relation is a language-specific subtype of <tt><a href="en_gumreddit-dep-nmod.html">nmod</a></tt>.
There are also 2 other language-specific subtypes of `nmod`: <tt><a href="en_gumreddit-dep-nmod-npmod.html">nmod:npmod</a></tt>, <tt><a href="en_gumreddit-dep-nmod-tmod.html">nmod:tmod</a></tt>.

301 nodes (2%) are attached to their parents as `nmod:poss`.

301 instances of `nmod:poss` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.48837209302326.

The following 7 pairs of parts of speech are connected with `nmod:poss`: <tt><a href="en_gumreddit-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_gumreddit-pos-PRON.html">PRON</a></tt> (261; 87% instances), <tt><a href="en_gumreddit-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_gumreddit-pos-NOUN.html">NOUN</a></tt> (20; 7% instances), <tt><a href="en_gumreddit-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_gumreddit-pos-PROPN.html">PROPN</a></tt> (11; 4% instances), <tt><a href="en_gumreddit-pos-PROPN.html">PROPN</a></tt>-<tt><a href="en_gumreddit-pos-PRON.html">PRON</a></tt> (4; 1% instances), <tt><a href="en_gumreddit-pos-ADJ.html">ADJ</a></tt>-<tt><a href="en_gumreddit-pos-PRON.html">PRON</a></tt> (3; 1% instances), <tt><a href="en_gumreddit-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_gumreddit-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="en_gumreddit-pos-PROPN.html">PROPN</a></tt>-<tt><a href="en_gumreddit-pos-PROPN.html">PROPN</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 5 nmod:poss	color:blue
1	_	_	PRON	PRP	Case=Nom|Number=Sing|Person=2|PronType=Prs	3	nsubj	3:nsubj	Discourse=ROOT:6:0|Entity=(5-person-acc:com-cf1-1-ana)|Lem=*LOWER*|Len=3
2	_	_	AUX	MD	VerbForm=Fin	3	aux	3:aux	Lem=_|Len=3
3	_	_	VERB	VB	VerbForm=Inf	0	root	0:root	Lem=_|Len=6
4	_	_	ADP	IN	_	7	case	7:case	Lem=_|Len=4
5	_	_	PRON	PRP$	Case=Gen|Number=Sing|Person=2|Poss=Yes|PronType=Prs	7	nmod:poss	7:nmod:poss	Entity=(6-person-new-cf2-3-sgl(5-person-giv:act-cf1-1-ana)|Lem=_|Len=4
6	_	_	ADJ	JJ	Degree=Pos	7	amod	7:amod	Lem=_|Len=3
7	_	_	NOUN	NNS	Number=Plur	3	obl	3:obl:from	Entity=6)|Lem=person|Len=6|SpaceAfter=No
8	_	_	PUNCT	.	_	3	punct	3:punct	Lem=_|Len=1

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 5 nmod:poss	color:blue
1	_	_	PRON	PRP	Case=Nom|Gender=Fem|Number=Sing|Person=3|PronType=Prs	3	nsubj	3:nsubj	Discourse=joint-sequence_m:16->13:1:dm-then-87|Entity=(7-person-giv:act-cf1*-1-ana)|Lem=*LOWER*|Len=3
2	_	_	ADV	RB	PronType=Dem	3	advmod	3:advmod	Lem=_|Len=4
3	_	_	VERB	VBD	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin	0	root	0:root	Lem=give|Len=4
4	_	_	DET	DT	Definite=Def|PronType=Art	5	det	5:det	Entity=(15-time-new-cf3-5-sgl(14-object-giv:act-cf2-2-coref|Lem=_|Len=3
5	_	_	NOUN	NN	Number=Sing	8	nmod:poss	8:nmod:poss	Lem=_|Len=4
6	_	_	PART	POS	_	5	case	5:case	Entity=14)|Lem='s|Len=2
7	_	_	NOUN	NN	Number=Sing	8	compound	8:compound	Entity=(16-event-new-cf6-1-sgl)|Lem=_|Len=10|MSeg=expir-ation
8	_	_	NOUN	NN	Number=Sing	3	obj	3:obj	Entity=15)|Lem=_|Len=4|SpaceAfter=No
9	_	_	PUNCT	,	_	11	punct	11:punct	Lem=_|Len=1
10	_	_	NOUN	NN	Number=Sing	11	compound	11:compound	Entity=(17-abstract-new-cf4-2-sgl|Lem=_|Len=8|MSeg=secur-ity
11	_	_	NOUN	NN	Number=Sing	8	conj	3:obj|8:conj:and	Entity=17)|Lem=_|Len=4|SpaceAfter=No
12	_	_	PUNCT	,	_	16	punct	16:punct	Lem=_|Len=1
13	_	_	CCONJ	CC	_	16	cc	16:cc	Lem=_|Len=3
14	_	_	PRON	PRP$	Case=Gen|Gender=Fem|Number=Sing|Person=3|Poss=Yes|PronType=Prs	16	nmod:poss	16:nmod:poss	Entity=(18-abstract-new-cf5-3-sgl(7-person-giv:act-cf1*-1-ana)|Lem=_|Len=3
15	_	_	NOUN	NN	Number=Sing	16	compound	16:compound	Lem=_|Len=3
16	_	_	NOUN	NN	Number=Sing	8	conj	3:obj|8:conj:and	Entity=18)|Lem=_|Len=4|SpaceAfter=No
17	_	_	PUNCT	.	_	3	punct	3:punct	Lem=_|Len=1

~~~


~~~ conllu
# visual-style 26	bgColor:blue
# visual-style 26	fgColor:white
# visual-style 28	bgColor:blue
# visual-style 28	fgColor:white
# visual-style 28 26 nmod:poss	color:blue
1	_	_	PRON	PRP	Case=Nom|Number=Sing|Person=1|PronType=Prs	2	nsubj	2:nsubj	Discourse=causal-cause:102->104:0:_|Entity=(72-person-giv:act-cf1*-1-ana)|Lem=_|Len=1
2	_	_	VERB	VBP	Mood=Ind|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin	0	root	0:root	Lem=_|Len=4
3	_	_	SCONJ	IN	_	6	mark	6:mark	Lem=_|Len=4
4	_	_	PRON	PRP	Case=Nom|Number=Plur|Person=3|PronType=Prs	6	nsubj	6:nsubj	Entity=(29-person-giv:act-cf2-1-ana)|Lem=_|Len=4
5	_	_	ADV	RB	_	6	advmod	6:advmod	Lem=_|Len=6
6	_	_	VERB	VBP	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	2	advcl	2:advcl:like	Lem=_|Len=2
7	_	_	ADV	RB	Degree=Pos	6	advmod	6:advmod	Lem=_|Len=9|MSeg=over-board
8	_	_	ADP	IN	_	10	case	10:case	Lem=_|Len=4
9	_	_	PRON	PRP$	Case=Gen|Number=Plur|Person=3|Poss=Yes|PronType=Prs	10	nmod:poss	10:nmod:poss	Entity=(43-object-giv:inact-cf6-2-coref(29-person-giv:act-cf2-1-ana)|Lem=_|Len=5
10	_	_	NOUN	NN	Number=Sing	6	obl	6:obl:with	Entity=43)|Lem=_|Len=4
11	_	_	PART	TO	_	12	mark	12:mark	Discourse=purpose-goal:103->102:0:syn-inf-757|Lem=_|Len=2
12	_	_	VERB	VB	VerbForm=Inf	6	advcl	6:advcl:to	Lem=_|Len=3
13	_	_	CCONJ	CC	_	14	cc	14:cc	Lem=_|Len=3
14	_	_	VERB	VB	VerbForm=Inf	12	conj	6:advcl:to|12:conj:and	Lem=_|Len=3
15	_	_	DET	DT	Definite=Def|PronType=Art	16	det	16:det	Entity=(54-person-giv:inact-cf4-2-coref|Lem=_|Len=3
16	_	_	NOUN	NNS	Number=Plur	14	obj	14:obj	Entity=54)|Lem=judge|Len=6|MSeg=judge-s
17	_	_	SCONJ	IN	_	19	mark	19:mark	Discourse=attribution-positive:104->105:0:sem-atsrc-747,764+lex-indwd-748+lex-indwd-765|Lem=_|Len=4
18	_	_	PRON	PRP	Case=Nom|Number=Plur|Person=3|PronType=Prs	19	nsubj	19:nsubj	Entity=(29-person-giv:act-cf2-1-ana)|Lem=_|Len=4
19	_	_	VERB	VBP	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	6	advcl	6:advcl:that	Lem=_|Len=6|MSeg=for-get
20	_	_	PRON	PRP	Case=Nom|Number=Plur|Person=3|PronType=Prs	23	nsubj	23:nsubj|25:nsubj:xsubj	Discourse=elaboration-additional:105->101:1:ref-prs-731,737-738,747,750|Entity=(29-person-giv:act-cf2-1-ana)|Lem=_|Len=4
21	_	_	ADV	RB	Degree=Pos	23	advmod	23:advmod	Lem=_|Len=6|MSeg=simp-ly
22	_	_	ADV	RB	_	23	advmod	23:advmod	Lem=_|Len=4
23	_	_	VERB	VBP	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	19	ccomp	19:ccomp	Lem=_|Len=4
24	_	_	PART	TO	_	25	mark	25:mark	Lem=_|Len=2
25	_	_	VERB	VB	VerbForm=Inf	23	xcomp	23:xcomp	Lem=_|Len=4
26	_	_	PROPN	NNP	Number=Sing	28	nmod:poss	28:nmod:poss	Entity=(37-object-giv:inact-cf5-3-coref(2-person-giv:act-cf3-1-coref-Bobby_Flay|Lem=_|Len=5|MSeg=Bobb-y
27	_	_	PART	POS	_	26	case	26:case	Entity=2)|Lem='s|Len=2
28	_	_	NOUN	NN	Number=Sing	25	obj	25:obj	Entity=37)|Lem=_|Len=4|SpaceAfter=No
29	_	_	PUNCT	.	_	2	punct	2:punct	Lem=_|Len=1

~~~


