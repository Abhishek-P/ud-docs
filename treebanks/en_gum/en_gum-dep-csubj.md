---
layout: base
title:  'Statistics of csubj in UD_English-GUM'
udver: '2'
---

## Treebank Statistics: UD_English-GUM: Relations: `csubj`

This relation is universal.
There are 2 language-specific subtypes of `csubj`: <tt><a href="en_gum-dep-csubj-outer.html">csubj:outer</a></tt>, <tt><a href="en_gum-dep-csubj-pass.html">csubj:pass</a></tt>.

264 nodes (0%) are attached to their parents as `csubj`.

142 instances of `csubj` (54%) are left-to-right (parent precedes child).
Average distance between parent and child is 5.68939393939394.

The following 19 pairs of parts of speech are connected with `csubj`: <tt><a href="en_gum-pos-ADJ.html">ADJ</a></tt>-<tt><a href="en_gum-pos-VERB.html">VERB</a></tt> (107; 41% instances), <tt><a href="en_gum-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gum-pos-VERB.html">VERB</a></tt> (74; 28% instances), <tt><a href="en_gum-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_gum-pos-VERB.html">VERB</a></tt> (43; 16% instances), <tt><a href="en_gum-pos-ADJ.html">ADJ</a></tt>-<tt><a href="en_gum-pos-ADJ.html">ADJ</a></tt> (7; 3% instances), <tt><a href="en_gum-pos-PRON.html">PRON</a></tt>-<tt><a href="en_gum-pos-VERB.html">VERB</a></tt> (6; 2% instances), <tt><a href="en_gum-pos-ADJ.html">ADJ</a></tt>-<tt><a href="en_gum-pos-NOUN.html">NOUN</a></tt> (4; 2% instances), <tt><a href="en_gum-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gum-pos-NOUN.html">NOUN</a></tt> (4; 2% instances), <tt><a href="en_gum-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_gum-pos-ADJ.html">ADJ</a></tt> (3; 1% instances), <tt><a href="en_gum-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gum-pos-ADV.html">ADV</a></tt> (3; 1% instances), <tt><a href="en_gum-pos-ADJ.html">ADJ</a></tt>-<tt><a href="en_gum-pos-PRON.html">PRON</a></tt> (2; 1% instances), <tt><a href="en_gum-pos-AUX.html">AUX</a></tt>-<tt><a href="en_gum-pos-VERB.html">VERB</a></tt> (2; 1% instances), <tt><a href="en_gum-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gum-pos-ADJ.html">ADJ</a></tt> (2; 1% instances), <tt><a href="en_gum-pos-ADJ.html">ADJ</a></tt>-<tt><a href="en_gum-pos-PROPN.html">PROPN</a></tt> (1; 0% instances), <tt><a href="en_gum-pos-DET.html">DET</a></tt>-<tt><a href="en_gum-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="en_gum-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_gum-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="en_gum-pos-NUM.html">NUM</a></tt>-<tt><a href="en_gum-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="en_gum-pos-PROPN.html">PROPN</a></tt>-<tt><a href="en_gum-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="en_gum-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gum-pos-AUX.html">AUX</a></tt> (1; 0% instances), <tt><a href="en_gum-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gum-pos-PRON.html">PRON</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 1 csubj	color:blue
1	Practicing	practice	VERB	VBG	VerbForm=Ger	5	csubj	5:csubj	Discourse=joint-other_m:110->24:4:_|MSeg=Practic-ing
2	your	your	PRON	PRP$	Case=Gen|Number=Sing|Person=2|Poss=Yes|PronType=Prs	3	nmod:poss	3:nmod:poss	Entity=(66-abstract-giv:inact-cf2-2-coref(9-person-giv:act-cf1*-1-ana)
3	joke	joke	NOUN	NN	Number=Sing	1	obj	1:obj	Entity=66)
4	is	be	AUX	VBZ	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	5	cop	5:cop	_
5	crucial	crucial	ADJ	JJ	Degree=Pos	0	root	0:root	SpaceAfter=No
6	.	.	PUNCT	.	_	5	punct	5:punct	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 1 csubj	color:blue
1	Moving	move	VERB	VBG	VerbForm=Ger	3	csubj	3:csubj	Discourse=causal-cause:61->55:3:_|Entity=(70-event-new-cf3-3-disc|MSeg=Mov-ing
2	them	they	PRON	PRP	Case=Acc|Number=Plur|Person=3|PronType=Prs	1	obj	1:obj	Entity=(65-object-giv:act-cf1*-1-ana)
3	distributes	distribute	VERB	VBZ	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	0	root	0:root	MSeg=distribute-s
4	the	the	DET	DT	Definite=Def|PronType=Art	5	det	5:det	Entity=(71-event-new-cf2-2,4-sgl
5	wear	wear	NOUN	NN	Number=Sing	3	obj	3:obj	_
6	and	and	CCONJ	CC	_	7	cc	7:cc	_
7	tear	tear	NOUN	NN	Number=Sing	5	conj	3:obj|5:conj:and	_
8	of	of	SCONJ	IN	_	9	mark	9:mark	_
9	washing	wash	VERB	VBG	VerbForm=Ger	5	acl	5:acl:of	Entity=71)|MSeg=wash-ing|SpaceAfter=No
10	.	.	PUNCT	.	_	3	punct	3:punct	Entity=70)

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 3 csubj	color:blue
1	All	all	DET	DT	PronType=Tot	3	obl:npmod	3:obl:npmod	Discourse=explanation-motivation:41->33:3:_
2	it	it	PRON	PRP	Case=Nom|Gender=Neut|Number=Sing|Person=3|PronType=Prs	3	nsubj	3:nsubj	_
3	takes	take	VERB	VBZ	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	7	csubj	7:csubj|11:csubj	MSeg=take-s
4	is	be	AUX	VBZ	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	7	cop	7:cop	_
5	two	two	NUM	CD	NumForm=Word|NumType=Card	7	nummod	7:nummod	Entity=(40-object-giv:inact-cf1-3-pred
6	twist	twist	NOUN	NN	Number=Sing	7	compound	7:compound	_
7	ties	tie	NOUN	NNS	Number=Plur	0	root	0:root	Entity=40)|MSeg=tie-s
8	and	and	CCONJ	CC	_	11	cc	11:cc	_
9	a	a	DET	DT	Definite=Ind|PronType=Art	11	det	11:det	Entity=(43-time-giv:inact-cf2-3-coref
10	few	few	ADJ	JJ	Degree=Pos	11	amod	11:amod	_
11	seconds	second	NOUN	NNS	Number=Plur	7	conj	7:conj:and	MSeg=second-s
12	of	of	ADP	IN	_	13	case	13:case	_
13	patience	patience	NOUN	NN	Number=Sing	11	nmod	11:nmod:of	Entity=(49-abstract-new-cf3-1-sgl)43)|MSeg=pati-ence|SpaceAfter=No
14	.	.	PUNCT	.	_	7	punct	7:punct	_

~~~


