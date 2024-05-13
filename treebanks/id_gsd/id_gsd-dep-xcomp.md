---
layout: base
title:  'Statistics of xcomp in UD_Indonesian-GSD'
udver: '2'
---

## Treebank Statistics: UD_Indonesian-GSD: Relations: `xcomp`

This relation is universal.

1386 nodes (1%) are attached to their parents as `xcomp`.

1252 instances of `xcomp` (90%) are left-to-right (parent precedes child).
Average distance between parent and child is 3.94805194805195.

The following 19 pairs of parts of speech are connected with `xcomp`: <tt><a href="id_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="id_gsd-pos-VERB.html">VERB</a></tt> (1175; 85% instances), <tt><a href="id_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="id_gsd-pos-ADJ.html">ADJ</a></tt> (110; 8% instances), <tt><a href="id_gsd-pos-NOUN.html">NOUN</a></tt>-<tt><a href="id_gsd-pos-VERB.html">VERB</a></tt> (27; 2% instances), <tt><a href="id_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="id_gsd-pos-NOUN.html">NOUN</a></tt> (16; 1% instances), <tt><a href="id_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="id_gsd-pos-ADV.html">ADV</a></tt> (15; 1% instances), <tt><a href="id_gsd-pos-ADJ.html">ADJ</a></tt>-<tt><a href="id_gsd-pos-VERB.html">VERB</a></tt> (9; 1% instances), <tt><a href="id_gsd-pos-NOUN.html">NOUN</a></tt>-<tt><a href="id_gsd-pos-ADJ.html">ADJ</a></tt> (8; 1% instances), <tt><a href="id_gsd-pos-PROPN.html">PROPN</a></tt>-<tt><a href="id_gsd-pos-ADJ.html">ADJ</a></tt> (5; 0% instances), <tt><a href="id_gsd-pos-PROPN.html">PROPN</a></tt>-<tt><a href="id_gsd-pos-VERB.html">VERB</a></tt> (5; 0% instances), <tt><a href="id_gsd-pos-NOUN.html">NOUN</a></tt>-<tt><a href="id_gsd-pos-NOUN.html">NOUN</a></tt> (4; 0% instances), <tt><a href="id_gsd-pos-ADV.html">ADV</a></tt>-<tt><a href="id_gsd-pos-VERB.html">VERB</a></tt> (3; 0% instances), <tt><a href="id_gsd-pos-ADJ.html">ADJ</a></tt>-<tt><a href="id_gsd-pos-ADJ.html">ADJ</a></tt> (2; 0% instances), <tt><a href="id_gsd-pos-NUM.html">NUM</a></tt>-<tt><a href="id_gsd-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="id_gsd-pos-PROPN.html">PROPN</a></tt>-<tt><a href="id_gsd-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="id_gsd-pos-PROPN.html">PROPN</a></tt>-<tt><a href="id_gsd-pos-PROPN.html">PROPN</a></tt> (1; 0% instances), <tt><a href="id_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="id_gsd-pos-DET.html">DET</a></tt> (1; 0% instances), <tt><a href="id_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="id_gsd-pos-PART.html">PART</a></tt> (1; 0% instances), <tt><a href="id_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="id_gsd-pos-PRON.html">PRON</a></tt> (1; 0% instances), <tt><a href="id_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="id_gsd-pos-PROPN.html">PROPN</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 5 xcomp	color:blue
1	Liburan	libur	NOUN	NSD	Number=Sing	4	nsubj	_	Morf=^libur<n>+an_NSD$
2	yang	yang	PRON	S--	PronType=Rel	3	nsubj	_	Morf=^yang<s>_S--$
3	indah	indah	ADJ	ASP	_	1	acl:relcl	_	Morf=^indah<a>_ASP$
4	mendadak	mendadak	VERB	ASP	_	0	root	_	Morf=^mendadak<a>_ASP$
5	menjadi	jadi	VERB	VSA	Mood=Ind|Voice=Act	4	xcomp	_	Morf=^meN+jadi<a>_VSA$
6	penuh	penuh	ADJ	ASP	_	5	obj	_	Morf=^penuh<a>_ASP$
7	darah	darah	NOUN	NSD	Number=Sing	6	compound	_	SpaceAfter=No|Morf=^darah<n>_NSD$
8	.	.	PUNCT	Z--	_	4	punct	_	Morf=^.<z>_Z--$

~~~


~~~ conllu
# visual-style 11	bgColor:blue
# visual-style 11	fgColor:white
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 10 11 xcomp	color:blue
1	Semakin	semakin	ADV	D--	_	2	advmod	_	Morf=^semakin<d>_D--$
2	jauh	jauh	ADJ	ASP	_	0	root	_	SpaceAfter=No|Morf=^jauh<a>_ASP$
3	,	,	PUNCT	Z--	_	2	punct	_	Morf=^,<z>_Z--$
4	maka	maka	SCONJ	S--	_	7	mark	_	Morf=^maka<s>_S--$
5	warna	warna	NOUN	NSD	Number=Sing	7	nsubj	_	Morf=^warna<n>_NSD$
6	nya	dia	PRON	PS3	Number=Sing|Person=3|PronType=Prs	5	nmod:poss	_	Morf=^dia<p>_PS3$
7	berubah	ubah	VERB	VSA	Mood=Ind|Voice=Act	2	advcl	_	Morf=^ber+ubah<v>_VSA$
8	dari	dari	ADP	R--	_	9	case	_	Morf=^dari<r>_R--$
9	jingga	jingga	ADJ	X--	_	7	obl	_	Morf=^jingga<x>_X--$
10	menjadi	jadi	VERB	VSA	Mood=Ind|Voice=Act	7	xcomp	_	Morf=^meN+jadi<a>_VSA$
11	biru	biru	ADJ	ASP	_	10	xcomp	_	SpaceAfter=No|Morf=^biru<a>_ASP$
12	.	.	PUNCT	Z--	_	2	punct	_	Morf=^.<z>_Z--$

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 5 xcomp	color:blue
1	Yang	yang	PRON	S--	PronType=Rel	8	nsubj	_	Morf=^yang<s>_S--$
2	tidak	tidak	PART	G--	Polarity=Neg	3	advmod	_	Morf=^tidak<g>_G--$
3	mendapat	dapat	VERB	VSA	Mood=Ind|Voice=Act	1	acl	_	Morf=^meN+dapat<v>_VSA$
4	giliran	gilir	NOUN	NSD	Number=Sing	3	obj	_	Morf=^gilir<v>+an_NSD$
5	mengelola	kelola	VERB	VSA	Mood=Ind|Voice=Act	4	xcomp	_	Morf=^meN+kelola<v>_VSA$
6	warung	warung	NOUN	NSD	Number=Sing	5	obj	_	Morf=^warung<n>_NSD$
7	biasanya	biasanya	ADV	D--	_	8	advmod	_	Morf=^biasanya<d>_D--$
8	bertani	tani	VERB	VSA	Mood=Ind|Voice=Act	0	root	_	Morf=^ber+tani<n>_VSA$
9	di	di	ADP	R--	_	10	case	_	Morf=^di<r>_R--$
10	kampung	kampung	NOUN	NSD	Number=Sing	8	obl	_	Morf=^kampung<n>_NSD$
11	halaman	halaman	NOUN	NSD	Number=Sing	10	compound	_	Morf=^halaman<n>_NSD$
12	nya	dia	PRON	PS3	Number=Sing|Person=3|PronType=Prs	11	nmod:poss	_	Morf=^dia<p>_PS3$
13	.	.	PUNCT	Z--	_	8	punct	_	Morf=^.<z>_Z--$

~~~


