---
layout: base
title:  'Statistics of obl:tmod in UD_English-GUMReddit'
udver: '2'
---

## Treebank Statistics: UD_English-GUMReddit: Relations: `obl:tmod`

This relation is a language-specific subtype of <tt><a href="en_gumreddit-dep-obl.html">obl</a></tt>.
There are also 2 other language-specific subtypes of `obl`: <tt><a href="en_gumreddit-dep-obl-agent.html">obl:agent</a></tt>, <tt><a href="en_gumreddit-dep-obl-npmod.html">obl:npmod</a></tt>.

29 nodes (0%) are attached to their parents as `obl:tmod`.

15 instances of `obl:tmod` (52%) are right-to-left (child precedes parent).
Average distance between parent and child is 4.24137931034483.

The following 4 pairs of parts of speech are connected with `obl:tmod`: <tt><a href="en_gumreddit-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gumreddit-pos-NOUN.html">NOUN</a></tt> (17; 59% instances), <tt><a href="en_gumreddit-pos-ADV.html">ADV</a></tt>-<tt><a href="en_gumreddit-pos-NOUN.html">NOUN</a></tt> (7; 24% instances), <tt><a href="en_gumreddit-pos-ADJ.html">ADJ</a></tt>-<tt><a href="en_gumreddit-pos-NOUN.html">NOUN</a></tt> (3; 10% instances), <tt><a href="en_gumreddit-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_gumreddit-pos-NOUN.html">NOUN</a></tt> (2; 7% instances).


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 2 obl:tmod	color:blue
1	_	_	ADJ	JJ	Degree=Pos	2	amod	2:amod	Discourse=context-circumstance:44->47:1|Entity=(51-time-new-cf1-2-sgl|Lem=*LOWER*|Len=4
2	_	_	NOUN	NN	Number=Sing	4	obl:tmod	4:obl:tmod	Entity=51)|Lem=_|Len=5|SpaceAfter=No
3	_	_	PUNCT	,	_	2	punct	2:punct	Lem=_|Len=1
4	_	_	VERB	VB	Mood=Imp|Person=2|VerbForm=Fin	0	root	0:root	Lem=_|Len=4
5	_	_	ADV	RB	Degree=Pos	4	advmod	4:advmod	Entity=(52-place-new-cf2-1-sgl)|Lem=_|Len=4

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 2 obl:tmod	color:blue
1	_	_	NUM	CD	NumForm=Digit|NumType=Card	2	nummod	2:nummod	Discourse=context-circumstance:43->44:0|Entity=(50-time-new-cf1-2-sgl|Lem=_|Len=1
2	_	_	NOUN	NN	Number=Sing	3	obl:tmod	3:obl:tmod	Entity=50)|Lem=_|Len=4
3	_	_	ADV	RBR	Degree=Cmp	0	root	0:root	Lem=late|Len=5

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 3 obl:tmod	color:blue
1	_	_	DET	DT	Definite=Def|PronType=Art	3	det	3:det	Discourse=context-background:112->117:3|Entity=(126-time-new-cf4-3-sgl|Lem=*LOWER*|Len=3
2	_	_	ADJ	JJ	Degree=Pos	3	amod	3:amod	Lem=_|Len=5
3	_	_	NOUN	NN	Number=Sing	6	obl:tmod	6:obl:tmod	Entity=126)|Lem=_|Len=5
4	_	_	PRON	PRP	Case=Nom|Number=Sing|Person=1|PronType=Prs	6	nsubj	6:nsubj|8:nsubj:xsubj	Entity=(113-person-giv:act-cf1*-1-ana)|Lem=_|Len=1
5	_	_	AUX	VBD	Mood=Ind|Number=Sing|Person=1|Tense=Past|VerbForm=Fin	6	cop	6:cop	Lem=be|Len=3
6	_	_	ADJ	JJ	Degree=Pos	0	root	0:root	Lem=_|Len=4
7	_	_	PART	TO	_	8	mark	8:mark	Lem=_|Len=2
8	_	_	VERB	VB	VerbForm=Inf	6	xcomp	6:xcomp	Lem=_|Len=5
9	_	_	NUM	CD	NumForm=Digit|NumType=Card	10	nummod	10:nummod	Entity=(127-time-new-cf3-2-sgl|Lem=_|Len=1
10	_	_	NOUN	NNS	Number=Plur	8	obj	8:obj	Entity=127)|Lem=hour|Len=3
11	_	_	ADV	RB	_	12	advmod	12:advmod	Discourse=mode-manner:113->112:0|Lem=_|Len=4
12	_	_	VERB	VBG	VerbForm=Ger	8	advcl	8:advcl	Lem=chill|Len=8
13	_	_	CCONJ	CC	_	14	cc	14:cc	Discourse=joint-list_m:114->113:0|Lem=_|Len=3
14	_	_	VERB	VBG	VerbForm=Ger	12	conj	8:advcl|12:conj:and	Lem=talk|Len=7
15	_	_	ADP	IN	_	17	case	17:case	Lem=_|Len=4
16	_	_	DET	DT	Definite=Def|PronType=Art	17	det	17:det	Entity=(117-person-giv:inact-cf2-2-coref|Lem=_|Len=3
17	_	_	NOUN	NNS	Number=Plur	14	obl	14:obl:with	Entity=117)|Lem=roommate|Len=9
18	_	_	CCONJ	CC	_	20	cc	20:cc	Lem=_|Len=3
19	_	_	DET	DT	PronType=Ind	20	det	20:det	Entity=(128-person-new-cf5-2-coref|Lem=_|Len=4
20	_	_	NOUN	NNS	Number=Plur	17	conj	14:obl:with|17:conj:and	Entity=128)|Lem=guest|Len=6
21	_	_	PRON	PRP	Case=Nom|Number=Plur|Person=3|PronType=Prs	22	nsubj	22:nsubj	Discourse=elaboration-attribute:115->114:0|Entity=(117-person-giv:act-cf2-1-ana)|Lem=_|Len=4
22	_	_	VERB	VBD	Mood=Ind|Number=Plur|Person=3|Tense=Past|VerbForm=Fin	20	acl:relcl	20:acl:relcl	Lem=have|Len=3
23	_	_	ADP	RP	_	22	compound:prt	22:compound:prt	Lem=_|Len=4|SpaceAfter=No
24	_	_	PUNCT	,	_	6	punct	6:punct	Lem=_|Len=1

~~~


