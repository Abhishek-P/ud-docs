---
layout: base
title:  'Statistics of det in UD_Estonian-EWT'
udver: '2'
---

## Treebank Statistics: UD_Estonian-EWT: Relations: `det`

This relation is universal.

2230 nodes (2%) are attached to their parents as `det`.

2204 instances of `det` (99%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.36053811659193.

The following 13 pairs of parts of speech are connected with `det`: <tt><a href="et_ewt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="et_ewt-pos-DET.html">DET</a></tt> (2028; 91% instances), <tt><a href="et_ewt-pos-PRON.html">PRON</a></tt>-<tt><a href="et_ewt-pos-DET.html">DET</a></tt> (51; 2% instances), <tt><a href="et_ewt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="et_ewt-pos-DET.html">DET</a></tt> (49; 2% instances), <tt><a href="et_ewt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="et_ewt-pos-DET.html">DET</a></tt> (44; 2% instances), <tt><a href="et_ewt-pos-NUM.html">NUM</a></tt>-<tt><a href="et_ewt-pos-DET.html">DET</a></tt> (31; 1% instances), <tt><a href="et_ewt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="et_ewt-pos-PRON.html">PRON</a></tt> (10; 0% instances), <tt><a href="et_ewt-pos-ADV.html">ADV</a></tt>-<tt><a href="et_ewt-pos-DET.html">DET</a></tt> (5; 0% instances), <tt><a href="et_ewt-pos-VERB.html">VERB</a></tt>-<tt><a href="et_ewt-pos-DET.html">DET</a></tt> (4; 0% instances), <tt><a href="et_ewt-pos-SYM.html">SYM</a></tt>-<tt><a href="et_ewt-pos-DET.html">DET</a></tt> (3; 0% instances), <tt><a href="et_ewt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="et_ewt-pos-PRON.html">PRON</a></tt> (2; 0% instances), <tt><a href="et_ewt-pos-DET.html">DET</a></tt>-<tt><a href="et_ewt-pos-DET.html">DET</a></tt> (1; 0% instances), <tt><a href="et_ewt-pos-PRON.html">PRON</a></tt>-<tt><a href="et_ewt-pos-PRON.html">PRON</a></tt> (1; 0% instances), <tt><a href="et_ewt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="et_ewt-pos-PRON.html">PRON</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 6 det	color:blue
1	onia	Onia	PROPN	S	Case=Gen|Number=Sing	2	nmod	2:nmod	NE=B-Loc
2	fotopoe	foto_pood	NOUN	S	Case=Gen|Number=Sing	3	nmod	3:nmod	_
3	peded	pede	NOUN	S	Case=Nom|Number=Plur	4	nsubj	4:nsubj	_
4	korrutavad	korrutama	VERB	V	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	0:root	_
5	nagunii	nagu_nii	ADV	D	_	4	advmod	4:advmod	_
6	selle	see	DET	P	Case=Gen|Number=Sing|PronType=Dem	7	det	7:det	_
7	hinna	hind	NOUN	S	Case=Gen|Number=Sing	4	obj	4:obj	_
8	2X	2X	NOUN	Y	Abbr=Yes	4	obl	4:obl	SpaceAfter=No
9	.	.	PUNCT	Z	_	4	punct	4:punct	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 1 det	color:blue
1	paljudel	palju	DET	P	Case=Ade|Number=Plur|PronType=Ind	2	det	2:det	_
2	tesitel	teine	PRON	P	Case=Ade|Number=Plur|PronType=Dem|Typo=Yes	6	obl	6:obl	CorrectForm=teistel
3	pead	pidama	AUX	V	Mood=Ind|Number=Sing|Person=2|Tense=Pres|VerbForm=Fin|Voice=Act	6	aux	6:aux	_
4	seda	see	PRON	P	Case=Par|Number=Sing|PronType=Dem	6	obj	6:obj	_
5	menüüst	menüü	NOUN	S	Case=Ela|Number=Sing	6	obl	6:obl	_
6	tegema	tegema	VERB	V	Case=Ill|VerbForm=Sup|Voice=Act	0	root	0:root	SpaceAfter=No
7	.	.	PUNCT	Z	_	6	punct	6:punct	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 2 det	color:blue
1	Näiteks	näiteks	ADV	D	_	3	advmod	3:advmod	_
2	mingile	mingi	DET	P	Case=All|Number=Sing|PronType=Ind	3	det	3:det	_
3	Raivo	Raivo	PROPN	S	Case=Nom|Number=Sing	0	root	0:root|11:nsubj	NE=B-Per
4	Rannamäele	Ranna_mägi	PROPN	S	Case=All|Number=Sing	3	flat	3:flat	NE=I-Per|SpaceAfter=No
5	,	,	PUNCT	Z	_	11	punct	11:punct	_
6	kes	kes	PRON	P	Case=Nom|Number=Sing|PronType=Int,Rel	11	nsubj	3:ref	_
7	on	olema	AUX	V	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	11	aux	11:aux	_
8	poole	pool	NUM	N	Case=Gen|Number=Sing|NumForm=Word|NumType=Card	9	nummod	9:nummod	CorrectForm=pool|CorrectCase=Nom
9	elu	elu	NOUN	S	Case=Gen|Number=Sing	11	obj	11:obj	_
10	maha	maha	ADV	D	_	11	compound:prt	11:compound	_
11	joonud	jooma	VERB	V	Tense=Past|VerbForm=Part|Voice=Act	3	acl:relcl	3:acl	SpaceAfter=No
12	?	?	PUNCT	Z	_	3	punct	3:punct	_

~~~


