---
layout: base
title:  'Statistics of fixed in UD_Turkish-Atis'
udver: '2'
---

## Treebank Statistics: UD_Turkish-Atis: Relations: `fixed`

This relation is universal.

21 nodes (0%) are attached to their parents as `fixed`.

21 instances of `fixed` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.

The following 10 pairs of parts of speech are connected with `fixed`: <tt><a href="tr_atis-pos-ADJ.html">ADJ</a></tt>-<tt><a href="tr_atis-pos-DET.html">DET</a></tt> (5; 24% instances), <tt><a href="tr_atis-pos-ADJ.html">ADJ</a></tt>-<tt><a href="tr_atis-pos-ADJ.html">ADJ</a></tt> (4; 19% instances), <tt><a href="tr_atis-pos-ADV.html">ADV</a></tt>-<tt><a href="tr_atis-pos-INTJ.html">INTJ</a></tt> (4; 19% instances), <tt><a href="tr_atis-pos-NUM.html">NUM</a></tt>-<tt><a href="tr_atis-pos-NOUN.html">NOUN</a></tt> (2; 10% instances), <tt><a href="tr_atis-pos-ADJ.html">ADJ</a></tt>-<tt><a href="tr_atis-pos-NOUN.html">NOUN</a></tt> (1; 5% instances), <tt><a href="tr_atis-pos-DET.html">DET</a></tt>-<tt><a href="tr_atis-pos-NOUN.html">NOUN</a></tt> (1; 5% instances), <tt><a href="tr_atis-pos-DET.html">DET</a></tt>-<tt><a href="tr_atis-pos-PRON.html">PRON</a></tt> (1; 5% instances), <tt><a href="tr_atis-pos-NOUN.html">NOUN</a></tt>-<tt><a href="tr_atis-pos-NOUN.html">NOUN</a></tt> (1; 5% instances), <tt><a href="tr_atis-pos-NOUN.html">NOUN</a></tt>-<tt><a href="tr_atis-pos-VERB.html">VERB</a></tt> (1; 5% instances), <tt><a href="tr_atis-pos-PRON.html">PRON</a></tt>-<tt><a href="tr_atis-pos-NOUN.html">NOUN</a></tt> (1; 5% instances).


~~~ conllu
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 9 fixed	color:blue
1	LA'dan	la	PROPN	_	Case=Abl|Number=Sing	2	nmod	_	_
2	Charlotte'ye	charlotte	PROPN	_	Case=Dat|Number=Sing	11	obl	_	_
3	oradan	oradan	ADV	_	_	4	advmod	_	_
4	Newark'a	newark	PROPN	_	Case=Dat|Number=Sing	2	conj	_	_
5	sonra	sonra	ADV	_	_	7	advmod	_	_
6	yeniden	yeniden	ADV	_	_	7	advmod	_	_
7	La'ya	la	PROPN	_	Case=Dat|Number=Sing	4	conj	_	_
8	tek	tek	ADJ	_	_	10	amod	_	_
9	bir	bir	DET	_	Definite=Ind|PronType=Art	8	fixed	_	_
10	havayoluyla	havayol	NOUN	_	Case=Ins|Number=Sing|Number[psor]=Sing|Person=3|Person[psor]=3	11	obl	_	_
11	gidebilir	git	VERB	_	Aspect=Hab|Mood=GenPot|Number=Sing|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin	0	root	_	_
12	miyim	mi	AUX	_	PronType=Int	11	aux:q	_	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 5 fixed	color:blue
1	lütfen	lütfen	ADV	_	_	9	discourse	_	_
2	Boston'dan	boston	PROPN	_	Case=Abl|Number=Sing	3	nmod	_	_
3	Denver'e	denver	PROPN	_	Case=Dat|Number=Sing	8	nmod	_	_
4	mümkün	mümkün	ADJ	_	_	6	advmod	_	_
5	olan	ol	ADJ	_	_	4	fixed	_	_
6	en	en	ADV	_	Degree=Sup	7	advmod	_	_
7	erken	erken	ADJ	_	_	8	amod	_	_
8	uçuşu	uç	NOUN	_	Case=Nom|Number=Sing|Number[psor]=Sing|Person=3|Person[psor]=3	9	obj	_	_
9	bulun	bulun	VERB	_	Mood=Imp|Number=Sing|Person=2|Polarity=Pos|Tense=Pres|VerbForm=Fin	0	root	_	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 2 fixed	color:blue
1	Peki	peki	ADV	_	_	5	discourse	_	_
2	ya	ya	INTJ	_	_	1	fixed	_	_
3	Denver'de	denver	PROPN	_	Case=Loc|Number=Sing	5	nmod	_	_
4	araba	araba	NOUN	_	Case=Nom|Number=Sing|Person=3	5	nmod	_	_
5	kiralama	kiralama	NOUN	_	Case=Nom|Number=Sing|Person=3	0	root	_	_

~~~


