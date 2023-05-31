---
layout: base
title:  'Statistics of dep in UD_Akkadian-RIAO'
udver: '2'
---

## Treebank Statistics: UD_Akkadian-RIAO: Relations: `dep`

This relation is universal.

267 nodes (1%) are attached to their parents as `dep`.

177 instances of `dep` (66%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.26966292134831.

The following 13 pairs of parts of speech are connected with `dep`: <tt><a href="akk_riao-pos-PRON.html">PRON</a></tt>-<tt><a href="akk_riao-pos-ADP.html">ADP</a></tt> (88; 33% instances), <tt><a href="akk_riao-pos-PROPN.html">PROPN</a></tt>-<tt><a href="akk_riao-pos-PART.html">PART</a></tt> (80; 30% instances), <tt><a href="akk_riao-pos-NOUN.html">NOUN</a></tt>-<tt><a href="akk_riao-pos-PART.html">PART</a></tt> (48; 18% instances), <tt><a href="akk_riao-pos-VERB.html">VERB</a></tt>-<tt><a href="akk_riao-pos-PART.html">PART</a></tt> (25; 9% instances), <tt><a href="akk_riao-pos-DET.html">DET</a></tt>-<tt><a href="akk_riao-pos-PART.html">PART</a></tt> (9; 3% instances), <tt><a href="akk_riao-pos-NOUN.html">NOUN</a></tt>-<tt><a href="akk_riao-pos-PRON.html">PRON</a></tt> (6; 2% instances), <tt><a href="akk_riao-pos-VERB.html">VERB</a></tt>-<tt><a href="akk_riao-pos-CCONJ.html">CCONJ</a></tt> (4; 1% instances), <tt><a href="akk_riao-pos-ADJ.html">ADJ</a></tt>-<tt><a href="akk_riao-pos-PART.html">PART</a></tt> (2; 1% instances), <tt><a href="akk_riao-pos-NOUN.html">NOUN</a></tt>-<tt><a href="akk_riao-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="akk_riao-pos-PRON.html">PRON</a></tt>-<tt><a href="akk_riao-pos-PART.html">PART</a></tt> (1; 0% instances), <tt><a href="akk_riao-pos-PROPN.html">PROPN</a></tt>-<tt><a href="akk_riao-pos-X.html">X</a></tt> (1; 0% instances), <tt><a href="akk_riao-pos-VERB.html">VERB</a></tt>-<tt><a href="akk_riao-pos-PRON.html">PRON</a></tt> (1; 0% instances), <tt><a href="akk_riao-pos-VERB.html">VERB</a></tt>-<tt><a href="akk_riao-pos-X.html">X</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 5 dep	color:blue
1	biltu	biltu	NOUN	N	Case=Nom|Gender=Fem|NounBase=Free|Number=Sing	4	obj	_	_
2	maddattu	maddattu	NOUN	N	Case=Nom|Gender=Fem|NounBase=Free|Number=Sing	1	conj	_	_
3	urāsī	urāsu	NOUN	N	Gender=Masc|Number=Plur	1	conj	_	_
4	udannini	danānu	VERB	V	Gender=Com|Mood=Ind|Number=Sing|Person=1|Tense=Past|VerbForm=Fin|VerbStem=D	0	root	_	_
5	eli	eli	ADP	PRP	_	6	dep	_	_
6	šunu	_	PRON	_	Gender=Masc|Number=Plur|Person=3	7	obl	_	_
7	aškun	šakānu	VERB	V	Gender=Com|Mood=Ind|Number=Sing|Person=1|Tense=Past|VerbForm=Fin|VerbStem=G	4	conj	_	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 8 dep	color:blue
1	Aššur-naṣir-apli	Aššur-naṣir-apli_II	PROPN	RN	Gender=Masc	0	root	_	{m}AŠ-PAP-A
2	iššak	iššiakku	NOUN	N	Gender=Masc|NounBase=Bound|Number=Sing	1	appos	_	ŠID
3	Aššur	Aššur	PROPN	DN	Gender=Masc	2	nmod:poss	_	AŠ
4	mār	māru	NOUN	N	Gender=Masc|NounBase=Bound|Number=Sing	1	appos	_	A
5	Tukulti-Ninurta	Tukulti-Ninurta_II	PROPN	RN	Gender=Masc	4	nmod:poss	_	TUKUL-MAŠ
6	iššak	iššiakku	NOUN	N	Gender=Masc|NounBase=Bound|Number=Sing	5	appos	_	ŠID
7	Aššur	Aššur	PROPN	DN	Gender=Masc	6	nmod:poss	_	AŠ-ma
8	ma	_	PART	_	_	7	dep	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 4 dep	color:blue
1	ina	ina	ADP	PRP	_	2	case	_	ina
2	ūme	ūmu	NOUN	N	Case=Gen|Gender=Masc|NounBase=Suffixal|Number=Sing	13	obl	_	UD.MEŠ-šu-ma
3	šu	_	PRON	_	Gender=Masc|Number=Sing|Person=3	2	det	_	_
4	ma	_	PART	_	_	2	dep	_	_
5	ina	ina	ADP	PRP	_	6	case	_	ina
6	pî	pû	NOUN	N	Case=Gen|Gender=Masc|NounBase=Free|Number=Sing	13	obl	_	pi-i
7	ilāni	ilu	NOUN	N	Gender=Masc|Number=Plur	6	nmod:poss	_	DINGIR.MEŠ
8	rabûti	rabû	ADJ	AJ	Gender=Masc|Number=Plur	7	amod	_	GAL.MEŠ
9	šarrūt	_	NOUN	_	Gender=Fem|NounBase=Suffixal|Number=Sing	13	nsubj	_	_
10	ī	_	PRON	_	Number=Sing|Person=1	9	det:poss	_	_
11	bēlūt	_	NOUN	_	Gender=Fem|NounBase=Suffixal|Number=Sing	9	conj	_	_
12	ī	_	PRON	_	Number=Sing|Person=1	11	det:poss	_	_
13	ūṣâ	waṣû	VERB	V	Gender=Fem|Mood=Ind|Number=Plur|Person=3|Tense=Past|Ventive=Yes|VerbForm=Fin|VerbStem=G	0	root	_	_

~~~


