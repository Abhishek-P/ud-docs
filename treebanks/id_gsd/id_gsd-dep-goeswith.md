---
layout: base
title:  'Statistics of goeswith in UD_Indonesian-GSD'
udver: '2'
---

## Treebank Statistics: UD_Indonesian-GSD: Relations: `goeswith`

This relation is universal.

20 nodes (0%) are attached to their parents as `goeswith`.

20 instances of `goeswith` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.

The following 3 pairs of parts of speech are connected with `goeswith`: <tt><a href="id_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="id_gsd-pos-X.html">X</a></tt> (18; 90% instances), <tt><a href="id_gsd-pos-NUM.html">NUM</a></tt>-<tt><a href="id_gsd-pos-X.html">X</a></tt> (1; 5% instances), <tt><a href="id_gsd-pos-PROPN.html">PROPN</a></tt>-<tt><a href="id_gsd-pos-X.html">X</a></tt> (1; 5% instances).


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 4 goeswith	color:blue
1	Kisah	kisah	NOUN	NSD	Number=Sing	3	nsubj:pass	_	Morf=^kisah<n>_NSD$
2	ini	ini	DET	B--	PronType=Dem	1	det	_	Morf=^ini<b>_B--$
3	di	di	VERB	R--	Typo=Yes	0	root	_	CorrectForm=diakhiri|Morf=^di<r>_R--$
4	akhiri	_	X	VSA	_	3	goeswith	_	Morf=^akhir<n>+i_VSA$
5	dengan	dengan	ADP	R--	_	6	case	_	Morf=^dengan<r>_R--$
6	hilang	hilang	NOUN	ASP	_	3	obl	_	Morf=^hilang<a>_ASP$
7	nya	nya	DET	PS3	Definite=Def|PronType=Art	6	det	_	Morf=^dia<p>_PS3$
8	Superman	superman	PROPN	X--	_	6	nmod	_	SpaceAfter=No|Morf=^superman<x>_X--$
9	?	?	PUNCT	Z--	_	3	punct	_	Morf=^?<z>_Z--$

~~~


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 6 goeswith	color:blue
1	SMP	smp	PROPN	NSD	_	4	nsubj	_	Morf=^smp<n>_NSD$
2	PGRI	pgri	PROPN	X--	_	1	flat:name	_	Morf=^pgri<x>_X--$
3	Wongkai	wongkai	PROPN	X--	_	2	flat:name	_	Morf=^wongkai<x>_X--$
4	merupakan	merupakan	VERB	O--	_	0	root	_	Morf=^merupakan<o>_O--$
5	satu	satu	NUM	CC-	NumType=Card|Typo=Yes	8	nummod	_	CorrectForm=satu-satu|Morf=^satu<c>_CC-$|CorrectForm=satu-
6	satu	_	X	CC-	_	5	goeswith	_	Morf=^satu<c>_CC-$
7	nya	nya	DET	PS3	Definite=Def|PronType=Art	5	det	_	Morf=^dia<p>_PS3$
8	SMP	smp	NOUN	NSD	Number=Sing	4	obj	_	Morf=^smp<n>_NSD$
9	yang	yang	PRON	S--	PronType=Rel	10	nsubj	_	Morf=^yang<s>_S--$
10	ada	ada	VERB	ASP	_	8	acl:relcl	_	Morf=^ada<a>_ASP$
11	di	di	ADP	R--	_	12	case	_	Morf=^di<r>_R--$
12	Wongkai	wongkai	PROPN	X--	_	10	obl	_	Morf=^wongkai<x>_X--$
13	yang	yang	PRON	S--	PronType=Rel	17	nsubj:pass	_	Morf=^yang<s>_S--$
14	belum	belum	PART	G--	Polarity=Neg	15	advmod	_	Morf=^belum<g>_G--$
15	lama	lama	ADJ	ASP	_	17	advmod	_	Morf=^lama<a>_ASP$
16	ini	ini	DET	B--	PronType=Dem	15	det	_	Morf=^ini<b>_B--$
17	di	di	VERB	R--	Typo=Yes|Voice=Pass	8	acl:relcl	_	CorrectForm=disahkan|Morf=^di<r>_R--$
18	sahkan	_	X	VSA	_	17	goeswith	_	Morf=^sah<a>+kan_VSA$
19	menjadi	jadi	VERB	VSA	Mood=Ind|Voice=Act	17	xcomp	_	Morf=^meN+jadi<a>_VSA$
20	SMP	smp	PROPN	NSD	_	19	obj	_	Morf=^smp<n>_NSD$
21	Negeri	negeri	PROPN	NSD	_	20	flat:name	_	Morf=^negeri<n>_NSD$
22	7	7	NUM	CC-	NumType=Card	21	nummod	_	Morf=^7<c>_CC-$
23	Ratahan	ratahan	PROPN	X--	_	20	flat:name	_	SpaceAfter=No|Morf=^ratahan<x>_X--$
24	,	,	PUNCT	Z--	_	26	punct	_	Morf=^,<z>_Z--$
25	telah	telah	AUX	D--	_	26	aux	_	Morf=^telah<d>_D--$
26	memiliki	milik	VERB	VSA	Mood=Ind|Voice=Act	10	advcl	_	Morf=^meN+milik<v>+i_VSA$
27	gedung	gedung	NOUN	NSD	Number=Sing	26	obj	_	Morf=^gedung<n>_NSD$
28	dan	dan	CCONJ	H--	_	29	cc	_	Morf=^dan<h>_H--$
29	fasilitas	fasilitas	NOUN	NSD	Number=Sing	27	conj	_	Morf=^fasilitas<n>_NSD$
30	yang	yang	PRON	S--	PronType=Rel	31	nsubj:pass	_	Morf=^yang<s>_S--$
31	diharapkan	harap	VERB	VSP	Mood=Ind|Voice=Pass	27	acl:relcl	_	Morf=^di+harap<v>+kan_VSP$
32	dapat	dapat	AUX	VSA	_	33	aux	_	Morf=^dapat<v>_VSA$
33	menunjang	tunjang	VERB	VSA	Mood=Ind|Voice=Act	31	xcomp	_	Morf=^meN+tunjang<v>_VSA$
34	proses	proses	NOUN	NSD	Number=Sing	33	obj	_	Morf=^proses<n>_NSD$
35	kegiatan	giat	NOUN	NSD	Number=Sing	34	compound	_	Morf=^ke+giat<n>+an_NSD$
36	belajar	belajar	VERB	NSD	_	35	acl	_	Morf=^belajar<n>_NSD$
37	mengajar	ajar	VERB	VSA	Mood=Ind|Voice=Act	36	fixed	_	SpaceAfter=No|Morf=^meN+ajar<v>_VSA$
38	,	,	PUNCT	Z--	_	40	punct	_	Morf=^,<z>_Z--$
39	yang	yang	PRON	S--	PronType=Rel	40	nsubj	_	Morf=^yang<s>_S--$
40	berlokasi	lokasi	VERB	VSA	Mood=Ind|Voice=Act	34	acl:relcl	_	Morf=^ber+lokasi<n>_VSA$
41	di	di	ADP	R--	_	42	case	_	Morf=^di<r>_R--$
42	desa	desa	NOUN	NSD	Number=Sing	40	obl	_	Morf=^desa<n>_NSD$
43	Wongkai	wongkai	PROPN	X--	_	42	nmod	_	SpaceAfter=No|Morf=^wongkai<x>_X--$
44	.	.	PUNCT	Z--	_	4	punct	_	Morf=^.<z>_Z--$

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 7 goeswith	color:blue
1	Bekerja	bekerja	VERB	VSA	Mood=Ind|Voice=Act	12	advcl	_	Morf=^bekerja<v>_VSA$
2	dengan	dengan	ADP	R--	_	3	case	_	Morf=^dengan<r>_R--$
3	JB	jb	PROPN	F--	_	1	obl	_	Morf=^jb<f>_F--$
4	Lippincott	lippincott	PROPN	X--	_	3	flat:name	_	Morf=^lippincott<x>_X--$
5	&	&	PUNCT	X--	_	6	punct	_	Morf=^&<x>_X--$
6	Co	co	PROPN	F--	Typo=Yes	3	flat:name	_	CorrectForm=Coeditor|Morf=^co<f>_F--$
7	editor	_	X	F--	_	6	goeswith	_	Morf=^editor<f>_F--$
8	Tay	tay	PROPN	X--	_	6	appos	_	Morf=^tay<x>_X--$
9	Hohoff	hohoff	PROPN	X--	_	8	flat:name	_	SpaceAfter=No|Morf=^hohoff<x>_X--$
10	,	,	PUNCT	Z--	_	1	punct	_	Morf=^,<z>_Z--$
11	ia	dia	PRON	PS3	Number=Sing|Person=3|PronType=Prs	12	nsubj	_	Morf=^ia<p>_PS3$
12	menyelesaikan	selesai	VERB	VSA	Mood=Ind|Voice=Act	0	root	_	Morf=^meN+selesai<a>+kan_VSA$
13	To	to	PROPN	F--	_	12	obj	_	Morf=^to<f>_F--$
14	Kill	kill	PROPN	X--	_	13	flat:name	_	Morf=^kill<x>_X--$
15	a	a	PROPN	F--	_	13	flat:name	_	Morf=^a<f>_F--$
16	Mockingbird	mockingbird	PROPN	X--	_	13	flat:name	_	Morf=^mockingbird<x>_X--$
17	pada	pada	ADP	R--	_	18	case	_	Morf=^pada<r>_R--$
18	musim	musim	NOUN	NSD	Number=Sing	12	obl:tmod	_	Morf=^musim<n>_NSD$
19	panas	panas	ADJ	NSD	_	18	amod	_	Morf=^panas<n>_NSD$
20	tahun	tahun	NOUN	NSD	Number=Sing	18	compound	_	Morf=^tahun<n>_NSD$
21	1959	1959	NUM	CC-	NumType=Card	20	nummod	_	SpaceAfter=No|Morf=^1959<c>_CC-$
22	.	.	PUNCT	Z--	_	12	punct	_	Morf=^.<z>_Z--$

~~~


