---
layout: base
title:  'Statistics of obl:agent in UD_Indonesian-GSD'
udver: '2'
---

## Treebank Statistics: UD_Indonesian-GSD: Relations: `obl:agent`

This relation is a language-specific subtype of <tt><a href="id_gsd-dep-obl.html">obl</a></tt>.
There are also 1 other language-specific subtypes of `obl`: <tt><a href="id_gsd-dep-obl-tmod.html">obl:tmod</a></tt>.

65 nodes (0%) are attached to their parents as `obl:agent`.

65 instances of `obl:agent` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.03076923076923.

The following 3 pairs of parts of speech are connected with `obl:agent`: <tt><a href="id_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="id_gsd-pos-PRON.html">PRON</a></tt> (59; 91% instances), <tt><a href="id_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="id_gsd-pos-PROPN.html">PROPN</a></tt> (4; 6% instances), <tt><a href="id_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="id_gsd-pos-NOUN.html">NOUN</a></tt> (2; 3% instances).


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 8 obl:agent	color:blue
1	Kesempatan	kesempatan	PROPN	NSD	_	7	nsubj:pass	_	Morf=^kesempatan<n>_NSD$
2	Kubica	kubica	PROPN	F--	_	1	flat:name	_	Morf=^kubica<f>_F--$
3	untuk	untuk	SCONJ	R--	_	4	mark	_	Morf=^untuk<r>_R--$
4	mengetes	tes	VERB	VSA	Mood=Ind|Voice=Act	1	acl	_	Morf=^meN+tes<n>_VSA$
5	mobil	mobil	NOUN	NSD	Number=Sing	4	obj	_	Morf=^mobil<n>_NSD$
6	F1	f1	PROPN	F--	_	5	nmod	_	Morf=^f1<f>_F--$
7	digunakan	guna	VERB	VSP	Mood=Ind|Voice=Pass	0	root	_	Morf=^di+guna<n>+kan_VSP$
8	nya	dia	PRON	PS3	Number=Sing|Person=3|PronType=Prs	7	obl:agent	_	Morf=^dia<p>_PS3$
9	dengan	dengan	ADP	R--	_	10	case	_	Morf=^dengan<r>_R--$
10	baik	baik	ADJ	ASP	_	7	xcomp	_	SpaceAfter=No|Morf=^baik<a>_ASP$
11	.	.	PUNCT	Z--	_	7	punct	_	Morf=^.<z>_Z--$

~~~


~~~ conllu
# visual-style 16	bgColor:blue
# visual-style 16	fgColor:white
# visual-style 15	bgColor:blue
# visual-style 15	fgColor:white
# visual-style 15 16 obl:agent	color:blue
1	Apa	apa	ADV	W--	PronType=Int	9	advmod	_	Morf=^apa<w>_W--$
2	kah	kah	PART	T--	_	1	advmod:emph	_	Morf=^kah<t>_T--$
3	pada	pada	ADP	R--	_	4	case	_	Morf=^pada<r>_R--$
4	akhirnya	akhirnya	ADV	B--	_	9	xcomp	_	SpaceAfter=No|Morf=^akhirnya<b>_B--$
5	,	,	PUNCT	Z--	_	4	punct	_	Morf=^,<z>_Z--$
6	ia	dia	PRON	PS3	Number=Sing|Person=3|PronType=Prs	9	nsubj	_	Morf=^ia<p>_PS3$
7	betul-betul	betul	ADV	APP	_	6	advmod	_	Morf=^betul<a>_APP$
8	bisa	bisa	AUX	M--	_	9	aux	_	Morf=^bisa<m>_M--$
9	mengeluarkan	keluar	VERB	VSA	Mood=Ind|Voice=Act	0	root	_	Morf=^meN+keluar<v>+kan_VSA$
10	tenaga	tenaga	NOUN	NSD	Number=Sing	9	obj	_	Morf=^tenaga<n>_NSD$
11	dalam	dalam	ADJ	NSD	_	10	amod	_	Morf=^dalam<n>_NSD$
12	nya	nya	PRON	PS3	Number=Sing|Person=3|PronType=Prs	10	nmod:poss	_	Morf=^dia<p>_PS3$
13	seperti	seperti	ADP	R--	_	10	case	_	Morf=^seperti<r>_R--$
14	yang	yang	PRON	S--	PronType=Rel	15	nsubj:pass	_	Morf=^yang<s>_S--$
15	diajarkan	ajar	VERB	VSP	Mood=Ind|Voice=Pass	10	acl:relcl	_	Morf=^di+ajar<v>+kan_VSP$
16	Sam	sam	PROPN	F--	_	15	obl:agent	_	Morf=^sam<f>_F--$
17	selama	selama	ADP	R--	_	18	case	_	Morf=^selama<r>_R--$
18	ini	ini	PRON	B--	PronType=Dem	15	obl	_	SpaceAfter=No|Morf=^ini<b>_B--$
19	?	?	PUNCT	Z--	_	9	punct	_	Morf=^?<z>_Z--$

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 8 obl:agent	color:blue
1	Ini	ini	DET	B--	PronType=Dem	3	nsubj	_	Morf=^ini<b>_B--$
2	adalah	adalah	AUX	O--	_	3	cop	_	Morf=^adalah<o>_O--$
3	gelar	gelar	NOUN	VSA	_	0	root	_	Morf=^gelar<v>_VSA$
4	internasional	internasional	ADJ	ASP	_	3	amod	_	Morf=^internasional<a>_ASP$
5	pertama	pertama	ADJ	CO-	NumType=Ord	3	amod	_	Morf=^pertama<c>_CO-$
6	yang	yang	PRON	S--	PronType=Rel	7	nsubj	_	Morf=^yang<s>_S--$
7	dimenangkan	menang	VERB	VSP	Mood=Ind|Voice=Pass	3	acl:relcl	_	Morf=^di+menang<a>+kan_VSP$
8	pelatih	latih	NOUN	NSD	Number=Sing	7	obl:agent	_	Morf=^peN+latih<v>_NSD$
9	Monterrey	monterrey	PROPN	X--	_	8	nmod	_	SpaceAfter=No|Morf=^monterrey<x>_X--$
10	,	,	PUNCT	Z--	_	8	punct	_	Morf=^,<z>_Z--$
11	Víctor	víctor	PROPN	X--	_	13	obj	_	Morf=^víctor<x>_X--$
12	Manuel	manuel	PROPN	F--	_	11	flat:name	_	Morf=^manuel<f>_F--$
13	Vucetich	vucetich	PROPN	X--	_	7	obj	_	Morf=^vucetich<x>_X--$
14	setelah	setelah	ADP	R--	_	15	case	_	Morf=^setelah<r>_R--$
15	serangkaian	rangkai	NOUN	NSD	Number=Plur	7	obl	_	Morf=^serangkaian<x>_X--$
16	panjang	panjang	ADJ	ASP	_	15	amod	_	Morf=^panjang<a>_ASP$
17	gelar	gelar	NOUN	VSA	_	15	nmod	_	Morf=^gelar<v>_VSA$
18	liga	liga	NOUN	NSD	Number=Sing	17	compound	_	SpaceAfter=No|Morf=^liga<n>_NSD$
19	.	.	PUNCT	Z--	_	3	punct	_	Morf=^.<z>_Z--$

~~~


