---
layout: base
title:  'Statistics of obl:tmod in UD_Indonesian-GSD'
udver: '2'
---

## Treebank Statistics: UD_Indonesian-GSD: Relations: `obl:tmod`

This relation is a language-specific subtype of <tt><a href="id_gsd-dep-obl.html">obl</a></tt>.
There are also 1 other language-specific subtypes of `obl`: <tt><a href="id_gsd-dep-obl-agent.html">obl:agent</a></tt>.

660 nodes (1%) are attached to their parents as `obl:tmod`.

396 instances of `obl:tmod` (60%) are left-to-right (parent precedes child).
Average distance between parent and child is 5.52727272727273.

The following 7 pairs of parts of speech are connected with `obl:tmod`: <tt><a href="id_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="id_gsd-pos-NOUN.html">NOUN</a></tt> (490; 74% instances), <tt><a href="id_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="id_gsd-pos-NUM.html">NUM</a></tt> (135; 20% instances), <tt><a href="id_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="id_gsd-pos-PROPN.html">PROPN</a></tt> (21; 3% instances), <tt><a href="id_gsd-pos-ADJ.html">ADJ</a></tt>-<tt><a href="id_gsd-pos-NOUN.html">NOUN</a></tt> (11; 2% instances), <tt><a href="id_gsd-pos-NOUN.html">NOUN</a></tt>-<tt><a href="id_gsd-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="id_gsd-pos-NOUN.html">NOUN</a></tt>-<tt><a href="id_gsd-pos-NUM.html">NUM</a></tt> (1; 0% instances), <tt><a href="id_gsd-pos-NUM.html">NUM</a></tt>-<tt><a href="id_gsd-pos-NOUN.html">NOUN</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 2 obl:tmod	color:blue
1	Pada	pada	ADP	R--	_	2	case	_	Morf=^pada<r>_R--$
2	zaman	zaman	NOUN	NSD	Number=Sing	4	obl:tmod	_	Morf=^zaman<n>_NSD$
3	dulu	dulu	ADV	D--	_	2	advmod	_	Morf=^dulu<d>_D--$
4	disebut	sebut	VERB	VSP	Mood=Ind|Voice=Pass	0	root	_	Morf=^di+sebut<v>_VSP$
5	atau	atau	CCONJ	H--	_	6	cc	_	Morf=^atau<h>_H--$
6	cha	cha	NOUN	X--	_	4	conj	_	Morf=^cha<x>_X--$
7	no	no	PROPN	F--	_	6	nmod	_	Morf=^no<f>_F--$
8	yu	yu	PROPN	F--	_	7	flat:name	_	SpaceAfter=No|Morf=^yu<f>_F--$
9	.	.	PUNCT	Z--	_	4	punct	_	Morf=^.<z>_Z--$

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 2 obl:tmod	color:blue
1	Pada	pada	ADP	R--	_	2	case	_	Morf=^pada<r>_R--$
2	16	16	NUM	CC-	NumType=Card	7	obl:tmod	_	Morf=^16<c>_CC-$
3	Juli	juli	NOUN	NSD	Number=Sing	2	flat	_	Morf=^juli<n>_NSD$
4	berita	berita	NOUN	NSD	Number=Sing	5	nsubj	_	Morf=^berita<n>_NSD$
5	adanya	adanya	VERB	B--	Voice=Act	8	csubj	_	Morf=^adanya<b>_B--$
6	pembantaian	bantai	NOUN	NSD	Number=Sing	5	obj	_	Morf=^peN+bantai<v>+an_NSD$
7	mulai	mulai	VERB	VSA	Mood=Ind|Voice=Act	0	root	_	Morf=^mulai<v>_VSA$
8	tersebar	sebar	VERB	VSP	Mood=Ind|Voice=Pass	7	xcomp	_	SpaceAfter=No|Morf=^ter+sebar<v>_VSP$
9	.	.	PUNCT	Z--	_	8	punct	_	Morf=^.<z>_Z--$

~~~


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 6 obl:tmod	color:blue
1	Kedua	kedua	NUM	CO-	NumType=Card|PronType=Tot	2	nummod	_	Morf=^ke+dua<c>_CO-$
2	atap	atap	NOUN	NSD	Number=Sing	4	nsubj:pass	_	Morf=^atap<n>_NSD$
3	menara	menara	NOUN	NSD	Number=Sing	2	compound	_	Morf=^menara<n>_NSD$
4	dibuat	buat	VERB	VSP	Mood=Ind|Voice=Pass	0	root	_	Morf=^di+buat<v>_VSP$
5	pada	pada	ADP	R--	_	6	case	_	Morf=^pada<r>_R--$
6	November	november	PROPN	NSD	_	4	obl:tmod	_	Morf=^november<n>_NSD$
7	2007	2007	NUM	CC-	NumType=Card	6	nummod	_	SpaceAfter=No|Morf=^2007<c>_CC-$
8	.	.	PUNCT	Z--	_	4	punct	_	Morf=^.<z>_Z--$

~~~


