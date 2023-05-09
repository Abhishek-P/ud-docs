---
layout: base
title:  'Statistics of csubj:cop in UD_Estonian-EWT'
udver: '2'
---

## Treebank Statistics: UD_Estonian-EWT: Relations: `csubj:cop`

This relation is a language-specific subtype of <tt><a href="et_ewt-dep-csubj.html">csubj</a></tt>.

267 nodes (0%) are attached to their parents as `csubj:cop`.

250 instances of `csubj:cop` (94%) are left-to-right (parent precedes child).
Average distance between parent and child is 3.41198501872659.

The following 18 pairs of parts of speech are connected with `csubj:cop`: <tt><a href="et_ewt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="et_ewt-pos-VERB.html">VERB</a></tt> (167; 63% instances), <tt><a href="et_ewt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="et_ewt-pos-VERB.html">VERB</a></tt> (53; 20% instances), <tt><a href="et_ewt-pos-PRON.html">PRON</a></tt>-<tt><a href="et_ewt-pos-VERB.html">VERB</a></tt> (16; 6% instances), <tt><a href="et_ewt-pos-ADV.html">ADV</a></tt>-<tt><a href="et_ewt-pos-VERB.html">VERB</a></tt> (8; 3% instances), <tt><a href="et_ewt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="et_ewt-pos-ADJ.html">ADJ</a></tt> (4; 1% instances), <tt><a href="et_ewt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="et_ewt-pos-ADV.html">ADV</a></tt> (3; 1% instances), <tt><a href="et_ewt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="et_ewt-pos-VERB.html">VERB</a></tt> (3; 1% instances), <tt><a href="et_ewt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="et_ewt-pos-ADJ.html">ADJ</a></tt> (2; 1% instances), <tt><a href="et_ewt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="et_ewt-pos-NOUN.html">NOUN</a></tt> (2; 1% instances), <tt><a href="et_ewt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="et_ewt-pos-ADV.html">ADV</a></tt> (1; 0% instances), <tt><a href="et_ewt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="et_ewt-pos-AUX.html">AUX</a></tt> (1; 0% instances), <tt><a href="et_ewt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="et_ewt-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="et_ewt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="et_ewt-pos-PROPN.html">PROPN</a></tt> (1; 0% instances), <tt><a href="et_ewt-pos-ADV.html">ADV</a></tt>-<tt><a href="et_ewt-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="et_ewt-pos-ADV.html">ADV</a></tt>-<tt><a href="et_ewt-pos-ADV.html">ADV</a></tt> (1; 0% instances), <tt><a href="et_ewt-pos-ADV.html">ADV</a></tt>-<tt><a href="et_ewt-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="et_ewt-pos-PRON.html">PRON</a></tt>-<tt><a href="et_ewt-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="et_ewt-pos-VERB.html">VERB</a></tt>-<tt><a href="et_ewt-pos-VERB.html">VERB</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 6 csubj:cop	color:blue
1	aga	aga	CCONJ	J	_	2	cc	2:cc	_
2	viisakas	viisakas	ADJ	A	Case=Nom|Degree=Pos|Number=Sing	0	root	0:root	_
3	oleks	olema	AUX	V	Mood=Cnd|Tense=Pres|VerbForm=Fin|Voice=Act	2	cop	2:cop	_
4	enne	enne	ADV	D	_	2	advmod	2:advmod	_
5	Daamilt	daam	NOUN	S	Case=Abl|Number=Sing	6	obl	6:obl	_
6	küsida	küsima	VERB	V	VerbForm=Inf	2	csubj:cop	2:csubj	SpaceAfter=No
7	,	,	PUNCT	Z	_	11	punct	11:punct	_
8	kas	kas	ADV	D	_	11	advmod	11:advmod	_
9	ta	tema	PRON	P	Case=Nom|Number=Sing|Person=3|PronType=Prs	11	nsubj	11:nsubj	_
10	tohib	tohtima	AUX	V	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	11	aux	11:aux	_
11	maksta	maksma	VERB	V	VerbForm=Inf	6	ccomp	6:ccomp	_
12	!!!	!!!	PUNCT	Z	_	2	punct	2:punct	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 4 csubj:cop	color:blue
1	mida	mis	PRON	P	Case=Par|Number=Sing|PronType=Int,Rel	4	obj	4:obj	_
2	keegi	keegi	PRON	P	Case=Nom|Number=Sing|PronType=Ind	4	nsubj	4:nsubj	_
3	autox	auto	NOUN	S	Case=Tra|Number=Sing|Typo=Yes	2	obl	2:obl	CorrectForm=autoks
4	loeb	lugema	VERB	V	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	7	csubj:cop	7:csubj	_
5	on	olema	AUX	V	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	7	cop	7:cop	_
6	isiklik	isiklik	ADJ	A	Case=Nom|Degree=Pos|Number=Sing	7	amod	7:amod	_
7	arvamus	arvamus	NOUN	S	Case=Nom|Number=Sing	0	root	0:root	SpaceAfter=No
8	...	...	PUNCT	Z	_	7	punct	7:punct	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 3 csubj:cop	color:blue
1	Mida	mis	PRON	P	Case=Par|Number=Sing|PronType=Int,Rel	3	obj	3:obj	_
2	neil	tema	PRON	P	Case=Ade|Number=Plur|Person=3|PronType=Prs	0	root	0:root	_
3	varjata	varjama	VERB	V	VerbForm=Inf	2	csubj:cop	2:csubj	_
4	on	olema	AUX	V	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	2	cop	2:cop	_
5	või	või	CCONJ	J	_	6	cc	6:cc	_
6	kardavad	kartma	VERB	V	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	2	conj	2:conj	SpaceAfter=No
7	,	,	PUNCT	Z	_	10	punct	10:punct	_
8	et	et	SCONJ	J	_	10	mark	10:mark	_
9	keegi	keegi	PRON	P	Case=Nom|Number=Sing|PronType=Ind	10	nsubj	10:nsubj	_
10	tuleb	tulema	VERB	V	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	6	ccomp	6:ccomp	_
11	vargile	vargile	ADV	D	_	10	advmod	10:advmod	SpaceAfter=No
12	?	?	PUNCT	Z	_	2	punct	2:punct	_

~~~


