---
layout: base
title:  'Statistics of mark in UD_Estonian-EWT'
udver: '2'
---

## Treebank Statistics: UD_Estonian-EWT: Relations: `mark`

This relation is universal.

3045 nodes (3%) are attached to their parents as `mark`.

3037 instances of `mark` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 3.32545155993432.

The following 19 pairs of parts of speech are connected with `mark`: <tt><a href="et_ewt-pos-VERB.html">VERB</a></tt>-<tt><a href="et_ewt-pos-SCONJ.html">SCONJ</a></tt> (1733; 57% instances), <tt><a href="et_ewt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="et_ewt-pos-SCONJ.html">SCONJ</a></tt> (400; 13% instances), <tt><a href="et_ewt-pos-VERB.html">VERB</a></tt>-<tt><a href="et_ewt-pos-ADV.html">ADV</a></tt> (319; 10% instances), <tt><a href="et_ewt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="et_ewt-pos-SCONJ.html">SCONJ</a></tt> (214; 7% instances), <tt><a href="et_ewt-pos-ADV.html">ADV</a></tt>-<tt><a href="et_ewt-pos-SCONJ.html">SCONJ</a></tt> (111; 4% instances), <tt><a href="et_ewt-pos-PRON.html">PRON</a></tt>-<tt><a href="et_ewt-pos-SCONJ.html">SCONJ</a></tt> (84; 3% instances), <tt><a href="et_ewt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="et_ewt-pos-SCONJ.html">SCONJ</a></tt> (49; 2% instances), <tt><a href="et_ewt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="et_ewt-pos-ADV.html">ADV</a></tt> (43; 1% instances), <tt><a href="et_ewt-pos-ADV.html">ADV</a></tt>-<tt><a href="et_ewt-pos-ADV.html">ADV</a></tt> (31; 1% instances), <tt><a href="et_ewt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="et_ewt-pos-ADV.html">ADV</a></tt> (22; 1% instances), <tt><a href="et_ewt-pos-NUM.html">NUM</a></tt>-<tt><a href="et_ewt-pos-SCONJ.html">SCONJ</a></tt> (13; 0% instances), <tt><a href="et_ewt-pos-PRON.html">PRON</a></tt>-<tt><a href="et_ewt-pos-ADV.html">ADV</a></tt> (6; 0% instances), <tt><a href="et_ewt-pos-SYM.html">SYM</a></tt>-<tt><a href="et_ewt-pos-SCONJ.html">SCONJ</a></tt> (6; 0% instances), <tt><a href="et_ewt-pos-AUX.html">AUX</a></tt>-<tt><a href="et_ewt-pos-SCONJ.html">SCONJ</a></tt> (4; 0% instances), <tt><a href="et_ewt-pos-INTJ.html">INTJ</a></tt>-<tt><a href="et_ewt-pos-SCONJ.html">SCONJ</a></tt> (3; 0% instances), <tt><a href="et_ewt-pos-NUM.html">NUM</a></tt>-<tt><a href="et_ewt-pos-ADV.html">ADV</a></tt> (2; 0% instances), <tt><a href="et_ewt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="et_ewt-pos-ADV.html">ADV</a></tt> (2; 0% instances), <tt><a href="et_ewt-pos-X.html">X</a></tt>-<tt><a href="et_ewt-pos-SCONJ.html">SCONJ</a></tt> (2; 0% instances), <tt><a href="et_ewt-pos-AUX.html">AUX</a></tt>-<tt><a href="et_ewt-pos-ADV.html">ADV</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 4 mark	color:blue
1	On	olema	VERB	V	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	0:root	_
2	ja	ja	CCONJ	J	_	3	cc	3:cc	_
3	elavad	elama	VERB	V	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	1	conj	0:root|1:conj	_
4	nagu	nagu	SCONJ	J	_	5	mark	5:mark	_
5	elaksid	elama	VERB	V	Mood=Cnd|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	3	advcl	3:advcl	_
6	nad	tema	PRON	P	Case=Nom|Number=Plur|Person=3|PronType=Prs	5	nsubj	5:nsubj	_
7	igavesti	igavesti	ADV	D	_	5	advmod	5:advmod	SpaceAfter=No
8	.	.	PUNCT	Z	_	1	punct	1:punct	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 1 mark	color:blue
1	Nagu	nagu	SCONJ	J	_	2	mark	2:mark	_
2	filmis	film	NOUN	S	Case=Ine|Number=Sing	0	root	0:root	NE=B-Prod
3	"	"	PUNCT	Z	_	6	punct	6:punct	NE=I-Prod|SpaceAfter=No
4	Madissoni	Madisson	PROPN	S	Case=Gen|Number=Sing	5	nmod	5:nmod	NE=I-Prod
5	maakonna	maakond	NOUN	S	Case=Gen|Number=Sing	6	nmod	6:nmod	NE=I-Prod
6	sillad	sild	NOUN	S	Case=Nom|Number=Plur	2	appos	2:appos	NE=I-Prod|SpaceAfter=No
7	"	"	PUNCT	Z	_	6	punct	6:punct	NE=I-Prod
8	...	...	PUNCT	Z	_	2	punct	2:punct	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 1 mark	color:blue
1	Kas	kas	ADV	D	_	5	mark	5:mark	_
2	sa	sina	PRON	P	Case=Nom|Number=Sing|Person=2|PronType=Prs	5	nsubj	5:nsubj	_
3	pead	pidama	AUX	V	Mood=Ind|Number=Sing|Person=2|Tense=Pres|VerbForm=Fin|Voice=Act	5	aux	5:aux	_
4	sellest	see	PRON	P	Case=Ela|Number=Sing|PronType=Dem	5	obl	5:obl	_
5	kirjutama	kirjutama	VERB	V	Case=Ill|VerbForm=Sup|Voice=Act	0	root	0:root	SpaceAfter=No
6	.	.	PUNCT	Z	_	5	punct	5:punct	_

~~~


