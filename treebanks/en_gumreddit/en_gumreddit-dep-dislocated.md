---
layout: base
title:  'Statistics of dislocated in UD_English-GUMReddit'
udver: '2'
---

## Treebank Statistics: UD_English-GUMReddit: Relations: `dislocated`

This relation is universal.

4 nodes (0%) are attached to their parents as `dislocated`.

3 instances of `dislocated` (75%) are left-to-right (parent precedes child).
Average distance between parent and child is 3.5.

The following 4 pairs of parts of speech are connected with `dislocated`: <tt><a href="en_gumreddit-pos-ADJ.html">ADJ</a></tt>-<tt><a href="en_gumreddit-pos-NOUN.html">NOUN</a></tt> (1; 25% instances), <tt><a href="en_gumreddit-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_gumreddit-pos-NOUN.html">NOUN</a></tt> (1; 25% instances), <tt><a href="en_gumreddit-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gumreddit-pos-NOUN.html">NOUN</a></tt> (1; 25% instances), <tt><a href="en_gumreddit-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gumreddit-pos-PRON.html">PRON</a></tt> (1; 25% instances).


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 2 dislocated	color:blue
1	_	_	NOUN	NN	Number=Sing	2	compound	2:compound	Discourse=organization-preparation:1->2:4:ref-prs-1-2,9+grf-col-3|Entity=(1-person-new-cf1-2-coref(2-event-new-cf2-1-coref)|Lem=*LOWER*|Len=6
2	_	_	NOUN	NNS	Number=Plur	6	dislocated	6:dislocated	Entity=1)|Lem=survivor|Len=9|MSeg=Surviv-or-s|SpaceAfter=No
3	_	_	PUNCT	:	_	2	punct	2:punct	Lem=_|Len=1
4	_	_	ADV	WRB	PronType=Int	6	advmod	6:advmod	Discourse=topic-question:2->16:4:lex-indwd-4+grf-qst-19|Lem=_|Len=3
5	_	_	PUNCT	``	_	6	punct	6:punct	Lem=''|Len=1|SpaceAfter=No|XML=<q>
6	_	_	ADJ	JJ	Degree=Pos	0	root	0:root	Cxn=Interrogative-WHInfo-Direct|Lem=_|Len=5|MSeg=a-ware|SpaceAfter=No
7	_	_	PUNCT	''	_	6	punct	6:punct	Lem=''|Len=1|XML=</q>
8	_	_	AUX	VBD	Mood=Ind|Number=Sing|Person=2|Tense=Past|VerbForm=Fin	6	cop	6:cop	Lem=be|Len=4
9	_	_	PRON	PRP	Case=Nom|Number=Sing|Person=2|PronType=Prs	6	nsubj	6:nsubj	Entity=(1-person-giv:act-cf1-1-ana)|Lem=_|Len=3
10	_	_	ADV	RB	_	13	advmod	13:advmod	Discourse=context-circumstance:3->2:0:dm-after-11|Lem=_|Len=4
11	_	_	SCONJ	IN	_	13	mark	13:mark	Lem=_|Len=5
12	_	_	PRON	PRP	Case=Nom|Number=Sing|Person=2|PronType=Prs	13	nsubj	13:nsubj|18:nsubj:xsubj	Entity=(1-person-giv:act-cf1-1-ana)|Lem=_|Len=3
13	_	_	VERB	VBD	Mood=Ind|Number=Sing|Person=2|Tense=Past|VerbForm=Fin	6	advcl	6:advcl:after	Lem=stabilize|Len=10|MSeg=stabil-iz-ed
14	_	_	CCONJ	CC	_	16	cc	16:cc	Discourse=joint-list_m:4->3:0:dm-and-14|Lem=_|Len=3
15	_	_	AUX	VBD	Mood=Ind|Number=Plur|Person=3|Tense=Past|VerbForm=Fin	16	cop	16:cop	Lem=be|Len=4
16	_	_	ADJ	JJ	Degree=Pos|Polarity=Neg	13	conj	6:advcl:after|13:conj:and	Lem=_|Len=6|MSeg=un-able
17	_	_	PART	TO	_	18	mark	18:mark	Lem=_|Len=2
18	_	_	VERB	VB	VerbForm=Inf	16	xcomp	16:xcomp	Lem=_|Len=5|SpaceAfter=No
19	_	_	PUNCT	.	_	6	punct	6:punct	Lem=_|Len=1

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 8 dislocated	color:blue
1	_	_	NOUN	NN	Number=Sing	2	compound	2:compound	Discourse=organization-preparation:53->54:1:sem-synym-326-327,329-347+grf-col-328|Entity=(65-abstract-new-cf3-2-coref(66-abstract-new-cf5-1-sgl)|Lem=*LOWER*|Len=4
2	_	_	NOUN	NN	Number=Sing	0	root	0:root	Entity=65)|Lem=_|Len=5|SpaceAfter=No
3	_	_	PUNCT	:	_	8	punct	8:punct	Lem=_|Len=1
4	_	_	NOUN	NNS	Number=Plur	8	nsubj	8:nsubj|13:nsubj	Discourse=adversative-contrast_m:54->49:3:_|Entity=(65-abstract-giv:act-cf3-5,10-coref(67-animal-new-cf2-1-coref)|Lem=cat|Len=4|MSeg=cat-s
5	_	_	AUX	VBP	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	8	cop	8:cop	Lem=be|Len=3
6	_	_	DET	DT	Definite=Def|PronType=Art	8	det	8:det	Entity=(67-animal-giv:act-cf2-3-coref|Lem=_|Len=3
7	_	_	ADJ	JJS	Degree=Sup	8	amod	8:amod	Lem=smart|Len=8
8	_	_	NOUN	NN	Number=Sing	2	dislocated	2:dislocated	Lem=_|Len=7
9	_	_	ADP	IN	_	10	case	10:case	Lem=_|Len=2
10	_	_	NOUN	NN	Number=Sing	8	nmod	8:nmod:on	Entity=(68-place-new-cf4-1-sgl)67)|Lem=_|Len=5
11	_	_	CCONJ	CC	_	13	cc	13:cc	Discourse=joint-list_m:55->54:0:sem-lxchn-333,339+dm-and-336|Lem=_|Len=3
12	_	_	AUX	MD	VerbForm=Fin	13	aux	13:aux	Lem=_|Len=4
13	_	_	VERB	VB	VerbForm=Inf	8	conj	2:dislocated|8:conj:and	Lem=_|Len=9|MSeg=over-throw
14	_	_	NOUN	NNS	Number=Plur	13	obj	13:obj	Entity=(2-person-giv:act-cf1*-1-coref)|Lem=human|Len=6|MSeg=human-s
15	_	_	ADV	WRB	PronType=Int	17	advmod	17:advmod	Discourse=context-circumstance:56->55:0:dm-when-340;attribution-positive:56->57:0:0:lex-indwd-342+sem-atsrc-341+syn-rpr-343|Lem=_|Len=4
16	_	_	PRON	PRP	Case=Nom|Number=Plur|Person=1|PronType=Prs	17	nsubj	17:nsubj	Entity=(2-person-giv:act-cf1*-1-ana)|Lem=_|Len=2
17	_	_	VERB	VBP	Mood=Ind|Number=Plur|Person=1|Tense=Pres|VerbForm=Fin	13	advcl	13:advcl:when	Lem=_|Len=7|MSeg=real-ize
18	_	_	SCONJ	IN	_	22	mark	22:mark	Discourse=elaboration-additional:57->56:0:ref-prs-341,344|Lem=_|Len=4
19	_	_	PRON	PRP	Case=Nom|Number=Plur|Person=1|PronType=Prs	22	nsubj	22:nsubj	Entity=(2-person-giv:act-cf1*-1-ana)|Lem=_|Len=2
20	_	_	AUX	VBP	Mood=Ind|Number=Plur|Person=1|Tense=Pres|VerbForm=Fin	22	cop	22:cop	Lem=be|Len=3
21	_	_	PRON	PRP$	Case=Gen|Number=Plur|Person=3|Poss=Yes|PronType=Prs	22	nmod:poss	22:nmod:poss	Entity=(2-person-giv:act-cf1*-2-coref(67-animal-giv:act-cf2-1-ana)|Lem=_|Len=5
22	_	_	NOUN	NNS	Number=Plur	17	ccomp	17:ccomp	Entity=2)65)|Lem=servant|Len=8|MSeg=serv-ant-s|SpaceAfter=No
23	_	_	PUNCT	.	_	2	punct	2:punct	Lem=_|Len=1

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 5 dislocated	color:blue
1	_	_	PRON	PRP	Case=Nom|Gender=Neut|Number=Sing|Person=3|PronType=Prs	2	nsubj	2:nsubj	Discourse=evaluation-comment:41->38:3:lex-indwd-271|Entity=(43-abstract-new-cf3-1-cata)|Lem=*LOWER*|Len=2
2	_	_	VERB	VBZ	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	0	root	0:root	Lem=amaze|Len=6|MSeg=a-maze-s
3	_	_	PRON	PRP	Case=Acc|Number=Sing|Person=1|PronType=Prs	2	obj	2:obj	Entity=(44-person-acc:com-cf1-1-sgl)|Lem=I|Len=2
4	_	_	DET	DT	Definite=Def|PronType=Art	5	det	5:det	Entity=(43-abstract-acc:com-cf3-2-coref(45-object-new-cf5-2-sgl|Lem=_|Len=3
5	_	_	NOUN	NNS	Number=Plur	2	dislocated	2:dislocated	Lem=chunk|Len=6|MSeg=chunk-s
6	_	_	ADP	IN	_	7	case	7:case	Lem=_|Len=2
7	_	_	NOUN	NN	Number=Sing	5	nmod	5:nmod:of	Entity=(46-time-new-cf7-1-sgl)45)|Lem=_|Len=4
8	_	_	PRON	PRP	Case=Nom|Gender=Neut|Number=Sing|Person=3|PronType=Prs	9	expl	9:expl	Discourse=elaboration-additional:42->41:0:sem-gnrl-270,273-285|Entity=(47-abstract-new-cf2-1-cata)|Lem=_|Len=2
9	_	_	VERB	VBZ	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	7	acl:relcl	7:acl:relcl	Lem=take|Len=5|MSeg=take-s
10	_	_	SCONJ	IN	_	13	mark	13:mark	Entity=(47-abstract-acc:com-cf2-4-coref|Lem=_|Len=3
11	_	_	NOUN	NNS	Number=Plur	13	nsubj	13:nsubj	Entity=(48-person-new-cf4-1-sgl)|Lem=person|Len=6
12	_	_	PART	TO	_	13	mark	13:mark	Lem=_|Len=2
13	_	_	VERB	VB	VerbForm=Inf	9	csubj	9:csubj	Lem=_|Len=7
14	_	_	ADP	IN	_	16	case	16:case	Lem=_|Len=2
15	_	_	DET	DT	Number=Plur|PronType=Dem	16	det	16:det	Entity=(49-abstract-new-cf6-2-sgl|Lem=this|Len=5
16	_	_	NOUN	NNS	Number=Plur	13	obl	13:obl:to	Entity=49)47)43)|Lem=thing|Len=6|MSeg=thing-s
17	_	_	SYM	SYM	_	2	discourse	2:discourse	Lem=_|Len=3|XML=<w></w>

~~~


