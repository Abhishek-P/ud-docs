---
layout: base
title:  'Statistics of vocative in UD_Indonesian-GSD'
udver: '2'
---

## Treebank Statistics: UD_Indonesian-GSD: Relations: `vocative`

This relation is universal.

9 nodes (0%) are attached to their parents as `vocative`.

9 instances of `vocative` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 5.44444444444444.

The following 3 pairs of parts of speech are connected with `vocative`: <tt><a href="id_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="id_gsd-pos-PROPN.html">PROPN</a></tt> (7; 78% instances), <tt><a href="id_gsd-pos-PRON.html">PRON</a></tt>-<tt><a href="id_gsd-pos-PROPN.html">PROPN</a></tt> (1; 11% instances), <tt><a href="id_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="id_gsd-pos-PRON.html">PRON</a></tt> (1; 11% instances).


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 1 vocative	color:blue
1	Allah	allah	PROPN	NSD	_	9	vocative	_	Morf=^allah<n>_NSD$
2	ku	aku	PRON	PS1	Number=Sing|Person=1|Polite=Infm|PronType=Prs	1	nmod:poss	_	Morf=^aku<p>_PS1$
3	,	,	PUNCT	Z--	_	1	punct	_	Morf=^,<z>_Z--$
4	Allah	allah	PROPN	NSD	_	9	vocative	_	Morf=^allah<n>_NSD$
5	ku	aku	PRON	PS1	Number=Sing|Person=1|Polite=Infm|PronType=Prs	4	nmod:poss	_	Morf=^aku<p>_PS1$
6	,	,	PUNCT	Z--	_	4	punct	_	Morf=^,<z>_Z--$
7	mengapa	mengapa	ADV	W--	PronType=Int	9	advmod	_	Morf=^mengapa<w>_W--$
8	Engkau	engkau	PRON	PS2	Number=Sing|Person=2|Polite=Infm|PronType=Prs	9	nsubj	_	Morf=^engkau<p>_PS2$
9	meninggalkan	tinggal	VERB	VSA	Mood=Ind|Voice=Act	0	root	_	Morf=^meN+tinggal<v>+kan_VSA$
10	aku	aku	PRON	PS1	Number=Sing|Person=1|Polite=Infm|PronType=Prs	9	obj	_	SpaceAfter=No|Morf=^aku<p>_PS1$
11	?	?	PUNCT	Z--	_	9	punct	_	Morf=^?<z>_Z--$

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 3 vocative	color:blue
1	``	``	PUNCT	Z--	_	2	punct	_	SpaceAfter=No|Morf=^``<z>_Z--$
2	Wahai	wahai	PROPN	X--	_	6	discourse	_	Morf=^wahai<x>_X--$
3	Gajah	gajah	PROPN	F--	_	6	vocative	_	Morf=^gajah<f>_F--$
4	Mada	mada	PROPN	F--	_	3	flat:name	_	SpaceAfter=No|Morf=^mada<f>_F--$
5	,	,	PUNCT	Z--	_	6	punct	_	Morf=^,<z>_Z--$
6	apa	apa	PRON	W--	PronType=Int	0	root	_	Morf=^apa<w>_W--$
7	maksud	maksud	NOUN	NSD	Number=Sing	6	acl	_	Morf=^maksud<n>_NSD$
8	nya	dia	PRON	PS3	Number=Sing|Person=3|PronType=Prs	7	nmod:poss	_	Morf=^dia<p>_PS3$
9	engkau	engkau	PRON	PS2	Number=Sing|Person=2|Polite=Infm|PronType=Prs	7	nmod:poss	_	Morf=^engkau<p>_PS2$
10	bermulut	mulut	VERB	VSA	Mood=Ind|Voice=Act	9	acl	_	Morf=^ber+mulut<n>_VSA$
11	besar	besar	ADJ	ASP	_	10	amod	_	Morf=^besar<a>_ASP$
12	terhadap	terhadap	ADP	R--	_	13	case	_	Morf=^terhadap<r>_R--$
13	kami	kami	PRON	PP1	Clusivity=Ex|Number=Plur|Person=1|PronType=Prs	10	obl	_	SpaceAfter=No|Morf=^kami<p>_PP1$
14	?	?	PUNCT	Z--	_	6	punct	_	Morf=^?<z>_Z--$

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 11	bgColor:blue
# visual-style 11	fgColor:white
# visual-style 11 5 vocative	color:blue
1	MBC	mbc	PROPN	X--	_	2	nsubj	_	Morf=^mbc<x>_X--$
2	berkata	kata	VERB	VSA	Mood=Ind|Voice=Act	0	root	_	SpaceAfter=No|Morf=^ber+kata<n>_VSA$
3	,	,	PUNCT	Z--	_	11	punct	_	Morf=^,<z>_Z--$
4	``	``	PUNCT	Z--	_	11	punct	_	SpaceAfter=No|Morf=^``<z>_Z--$
5	Anda	anda	PRON	PS2	Number=Sing|Person=2|Polite=Form|PronType=Prs	11	vocative	_	SpaceAfter=No|Morf=^anda<p>_PS2$
6	,	,	PUNCT	Z--	_	5	punct	_	Morf=^,<z>_Z--$
7	apa	apa	ADV	W--	PronType=Int	11	advmod	_	Morf=^apa<w>_W--$
8	kah	kah	PART	T--	_	7	advmod:emph	_	Morf=^kah<t>_T--$
9	Anda	anda	PRON	PS2	Number=Sing|Person=2|Polite=Form|PronType=Prs	11	nsubj	_	Morf=^anda<p>_PS2$
10	akan	akan	AUX	M--	_	11	aux	_	Morf=^akan<m>_M--$
11	menonton	tonton	VERB	VSA	Mood=Ind|Voice=Act	2	advcl	_	Morf=^meN+tonton<v>_VSA$
12	'	'	PUNCT	Z--	_	13	punct	_	SpaceAfter=No
13	Home	home	PROPN	F--	_	11	obj	_	Morf=^home<f>_F--$
14	Alone	alone	PROPN	X--	_	13	flat:name	_	SpaceAfter=No|Morf=^alone<x>_X--$
15	'	'	PUNCT	Z--	_	13	punct	_	_
16	di	di	ADP	R--	_	17	case	_	Morf=^di<r>_R--$
17	rumah	rumah	NOUN	NSD	Number=Sing	11	obl	_	Morf=^rumah<n>_NSD$
18	lagi	lagi	ADV	D--	_	17	advmod	_	SpaceAfter=No|Morf=^lagi<d>_D--$
19	?	?	PUNCT	Z--	_	2	punct	_	Morf=^?<z>_Z--$

~~~


