---
layout: base
title:  'Statistics of punct in UD_Turkish-Penn'
udver: '2'
---

## Treebank Statistics: UD_Turkish-Penn: Relations: `punct`

This relation is universal.

27427 nodes (15%) are attached to their parents as `punct`.

19543 instances of `punct` (71%) are left-to-right (parent precedes child).
Average distance between parent and child is 2.91927662522332.

The following 13 pairs of parts of speech are connected with `punct`: <tt><a href="tr_penn-pos-VERB.html">VERB</a></tt>-<tt><a href="tr_penn-pos-PUNCT.html">PUNCT</a></tt> (20623; 75% instances), <tt><a href="tr_penn-pos-NOUN.html">NOUN</a></tt>-<tt><a href="tr_penn-pos-PUNCT.html">PUNCT</a></tt> (3380; 12% instances), <tt><a href="tr_penn-pos-ADJ.html">ADJ</a></tt>-<tt><a href="tr_penn-pos-PUNCT.html">PUNCT</a></tt> (1489; 5% instances), <tt><a href="tr_penn-pos-PROPN.html">PROPN</a></tt>-<tt><a href="tr_penn-pos-PUNCT.html">PUNCT</a></tt> (1265; 5% instances), <tt><a href="tr_penn-pos-NUM.html">NUM</a></tt>-<tt><a href="tr_penn-pos-PUNCT.html">PUNCT</a></tt> (295; 1% instances), <tt><a href="tr_penn-pos-ADV.html">ADV</a></tt>-<tt><a href="tr_penn-pos-PUNCT.html">PUNCT</a></tt> (203; 1% instances), <tt><a href="tr_penn-pos-PRON.html">PRON</a></tt>-<tt><a href="tr_penn-pos-PUNCT.html">PUNCT</a></tt> (63; 0% instances), <tt><a href="tr_penn-pos-INTJ.html">INTJ</a></tt>-<tt><a href="tr_penn-pos-PUNCT.html">PUNCT</a></tt> (25; 0% instances), <tt><a href="tr_penn-pos-AUX.html">AUX</a></tt>-<tt><a href="tr_penn-pos-PUNCT.html">PUNCT</a></tt> (23; 0% instances), <tt><a href="tr_penn-pos-ADP.html">ADP</a></tt>-<tt><a href="tr_penn-pos-PUNCT.html">PUNCT</a></tt> (18; 0% instances), <tt><a href="tr_penn-pos-DET.html">DET</a></tt>-<tt><a href="tr_penn-pos-PUNCT.html">PUNCT</a></tt> (18; 0% instances), <tt><a href="tr_penn-pos-X.html">X</a></tt>-<tt><a href="tr_penn-pos-PUNCT.html">PUNCT</a></tt> (15; 0% instances), <tt><a href="tr_penn-pos-CCONJ.html">CCONJ</a></tt>-<tt><a href="tr_penn-pos-PUNCT.html">PUNCT</a></tt> (10; 0% instances).


~~~ conllu
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 9 punct	color:blue
1	Reklam	reklam	NOUN	_	Case=Nom|Number=Sing|Person=3	6	nsubj	_	_
2	ve	ve	CCONJ	_	_	3	cc	_	_
3	tanıtımın	tanıtım	NOUN	_	Case=Gen|Number=Sing|Person=3	1	conj	_	_
4	işe	iş	NOUN	_	Case=Dat|Number=Sing|Person=3	6	compound	_	_
5	yarayıp	yara	ADV	_	_	6	compound	_	_
6	yaramadığını	yara	NOUN	_	Case=Acc|Number=Sing|Number[psor]=Sing|Person=3|Person[psor]=3	7	ccomp	_	_
7	görmek	gör	NOUN	_	Case=Nom|Number=Sing|Person=3	8	xcomp	_	_
8	üzereyiz	üzere	VERB	_	Mood=Gen|Number=Plur|Person=1|Tense=Pres|VerbForm=Fin	0	root	_	_
9	.	.	PUNCT	_	_	8	punct	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 3 punct	color:blue
1	Bu	bu	DET	_	Definite=Def|PronType=Art	2	det	_	_
2	defa	defa	NOUN	_	Case=Nom|Number=Sing|Person=3	8	obl	_	_
3	,	,	PUNCT	_	_	2	punct	_	_
4	daha	daha	ADV	_	Degree=Cmp	6	advmod	_	_
5	da	da	CCONJ	_	_	4	cc	_	_
6	hızlı	hız	ADJ	_	_	8	advmod	_	_
7	hareket	hareket	NOUN	_	Case=Nom|Number=Sing|Person=3	8	compound	_	_
8	ediyorlar	et	VERB	_	Aspect=Prog|Mood=Ind|Number=Plur|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin	0	root	_	_
9	.	.	PUNCT	_	_	8	punct	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 3 punct	color:blue
1	Ekledi	ekle	VERB	_	Aspect=Perf|Mood=Ind|Number=Sing|Person=3|Polarity=Pos|Tense=Past|VerbForm=Fin	8	parataxis	_	_
2	,	,	PUNCT	_	_	1	punct	_	_
3	"	"	PUNCT	_	_	8	punct	_	_
4	Bu	bu	PRON	_	PronType=Dem	8	nsubj	_	_
5	1987'nin	1987	NOUN	_	Case=Gen|Number=Sing|Person=3	8	nmod	_	_
6	yeniden	yeniden	ADV	_	_	8	advmod	_	_
7	ziyaret	ziyaret	NOUN	_	Case=Nom|Number=Sing|Person=3	8	compound	_	_
8	edilmesi	et	ADJ	_	_	0	root	_	_
9	değil	değil	AUX	_	_	8	aux	_	_
10	.	.	PUNCT	_	_	8	punct	_	_
11	"	"	PUNCT	_	_	8	punct	_	_

~~~


