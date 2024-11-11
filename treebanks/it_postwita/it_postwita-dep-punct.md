---
layout: base
title:  'Statistics of punct in UD_Italian-PoSTWITA'
udver: '2'
---

## Treebank Statistics: UD_Italian-PoSTWITA: Relations: `punct`

This relation is universal.

15246 nodes (12%) are attached to their parents as `punct`.

12184 instances of `punct` (80%) are left-to-right (parent precedes child).
Average distance between parent and child is 3.83602256329529.

The following 15 pairs of parts of speech are connected with `punct`: <tt><a href="it_postwita-pos-VERB.html">VERB</a></tt>-<tt><a href="it_postwita-pos-PUNCT.html">PUNCT</a></tt> (5394; 35% instances), <tt><a href="it_postwita-pos-NOUN.html">NOUN</a></tt>-<tt><a href="it_postwita-pos-PUNCT.html">PUNCT</a></tt> (4069; 27% instances), <tt><a href="it_postwita-pos-PROPN.html">PROPN</a></tt>-<tt><a href="it_postwita-pos-PUNCT.html">PUNCT</a></tt> (2025; 13% instances), <tt><a href="it_postwita-pos-SYM.html">SYM</a></tt>-<tt><a href="it_postwita-pos-PUNCT.html">PUNCT</a></tt> (1099; 7% instances), <tt><a href="it_postwita-pos-ADJ.html">ADJ</a></tt>-<tt><a href="it_postwita-pos-PUNCT.html">PUNCT</a></tt> (832; 5% instances), <tt><a href="it_postwita-pos-INTJ.html">INTJ</a></tt>-<tt><a href="it_postwita-pos-PUNCT.html">PUNCT</a></tt> (456; 3% instances), <tt><a href="it_postwita-pos-PRON.html">PRON</a></tt>-<tt><a href="it_postwita-pos-PUNCT.html">PUNCT</a></tt> (388; 3% instances), <tt><a href="it_postwita-pos-NUM.html">NUM</a></tt>-<tt><a href="it_postwita-pos-PUNCT.html">PUNCT</a></tt> (379; 2% instances), <tt><a href="it_postwita-pos-ADV.html">ADV</a></tt>-<tt><a href="it_postwita-pos-PUNCT.html">PUNCT</a></tt> (309; 2% instances), <tt><a href="it_postwita-pos-X.html">X</a></tt>-<tt><a href="it_postwita-pos-PUNCT.html">PUNCT</a></tt> (194; 1% instances), <tt><a href="it_postwita-pos-PUNCT.html">PUNCT</a></tt>-<tt><a href="it_postwita-pos-PUNCT.html">PUNCT</a></tt> (37; 0% instances), <tt><a href="it_postwita-pos-DET.html">DET</a></tt>-<tt><a href="it_postwita-pos-PUNCT.html">PUNCT</a></tt> (32; 0% instances), <tt><a href="it_postwita-pos-AUX.html">AUX</a></tt>-<tt><a href="it_postwita-pos-PUNCT.html">PUNCT</a></tt> (15; 0% instances), <tt><a href="it_postwita-pos-ADP.html">ADP</a></tt>-<tt><a href="it_postwita-pos-PUNCT.html">PUNCT</a></tt> (11; 0% instances), <tt><a href="it_postwita-pos-CCONJ.html">CCONJ</a></tt>-<tt><a href="it_postwita-pos-PUNCT.html">PUNCT</a></tt> (6; 0% instances).


~~~ conllu
# visual-style 14	bgColor:blue
# visual-style 14	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 14 punct	color:blue
1	@user	@user	SYM	SYM	_	8	vocative	_	_
2	si	sì	INTJ	I	_	8	discourse	_	CorrectForm=sì
3	cazzo	cazzo	INTJ	I	_	8	discourse	_	_
4	c'	ce	PRON	PC	Clitic=Yes|Number=Plur|Person=1|PronType=Prs|Typo=Yes	8	expl	_	CorrectForm=ce|SpaceAfter=No
5	è	_	X	X	_	4	dep	_	_
6	la	la	PRON	PC	Clitic=Yes|Gender=Fem|Number=Sing|Person=3|PronType=Prs	8	obj	_	_
7	devo	dovere	AUX	VM	Mood=Ind|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin	8	aux	_	_
8	fare	fare	VERB	V	VerbForm=Inf	0	root	_	_
9	c'	ce	PRON	PC	Clitic=Yes|Number=Plur|Person=1|PronType=Prs|Typo=Yes	13	expl	_	CorrectForm=ce|SpaceAfter=No
10	è	_	X	X	_	9	dep	_	_
11	la	la	PRON	PC	Clitic=Yes|Gender=Fem|Number=Sing|Person=3|PronType=Prs	13	obj	_	_
12	posso	potere	AUX	VM	Mood=Ind|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin	13	aux	_	_
13	fare	fare	VERB	V	VerbForm=Inf	8	conj	_	SpaceAfter=No
14	!	!	PUNCT	FS	_	8	punct	_	_

~~~


~~~ conllu
# visual-style 11	bgColor:blue
# visual-style 11	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 11 punct	color:blue
1	a	a	ADP	E	_	3	case	_	_
2	il	il	DET	RD	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	3	det	_	_
3	via	via	NOUN	S	Gender=Fem|Number=Sing	0	root	_	_
4	la	il	DET	RD	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	5	det	_	_
5	fase	fase	NOUN	S	Gender=Fem|Number=Sing	3	nsubj	_	_
6	due	due	NUM	N	NumType=Card	5	nummod	_	_
7	di	di	ADP	E	_	9	case	_	_
8	il	il	DET	RD	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	9	det	_	_
9	governo	governo	NOUN	S	Gender=Masc|Number=Sing	5	nmod	_	_
10	#Monti	#Monti	SYM	SYM	_	9	nmod	_	SpaceAfter=No
11	:	:	PUNCT	FC	_	3	punct	_	_
12	la	il	DET	RD	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	13	det	_	_
13	risata	risata	NOUN	S	Gender=Fem|Number=Sing	3	parataxis	_	_
14	satanica	satanico	ADJ	A	Gender=Fem|Number=Sing	13	amod	_	SpaceAfter=No
15	.	.	PUNCT	FS	_	13	punct	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 3 punct	color:blue
1	Mario	mario	PROPN	SP	_	0	root	_	_
2	Monti	Monti	PROPN	SP	_	1	flat:name	_	SpaceAfter=No
3	,	,	PUNCT	FF	_	5	punct	_	_
4	la	il	DET	RD	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	5	det	_	_
5	Rai	rai	PROPN	SP	_	1	conj	_	_
6	e	e	CCONJ	CC	_	8	cc	_	_
7	la	il	DET	RD	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	8	det	_	_
8	democrazia	democrazia	NOUN	S	Gender=Fem|Number=Sing	1	conj	_	_
9	http://t.co/mwe3kJAe	http://t.co/mwe3kJAe	SYM	X	_	1	parataxis	_	_

~~~


