---
layout: base
title:  'Statistics of case in UD_Estonian-EDT'
udver: '2'
---

## Treebank Statistics: UD_Estonian-EDT: Relations: `case`

This relation is universal.

9277 nodes (2%) are attached to their parents as `case`.

7275 instances of `case` (78%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.37921741942438.

The following 15 pairs of parts of speech are connected with `case`: <tt><a href="et_edt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="et_edt-pos-ADP.html">ADP</a></tt> (7482; 81% instances), <tt><a href="et_edt-pos-PRON.html">PRON</a></tt>-<tt><a href="et_edt-pos-ADP.html">ADP</a></tt> (970; 10% instances), <tt><a href="et_edt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="et_edt-pos-ADP.html">ADP</a></tt> (511; 6% instances), <tt><a href="et_edt-pos-NUM.html">NUM</a></tt>-<tt><a href="et_edt-pos-ADP.html">ADP</a></tt> (189; 2% instances), <tt><a href="et_edt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="et_edt-pos-ADP.html">ADP</a></tt> (88; 1% instances), <tt><a href="et_edt-pos-SYM.html">SYM</a></tt>-<tt><a href="et_edt-pos-ADP.html">ADP</a></tt> (13; 0% instances), <tt><a href="et_edt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="et_edt-pos-PRON.html">PRON</a></tt> (8; 0% instances), <tt><a href="et_edt-pos-VERB.html">VERB</a></tt>-<tt><a href="et_edt-pos-ADP.html">ADP</a></tt> (7; 0% instances), <tt><a href="et_edt-pos-ADV.html">ADV</a></tt>-<tt><a href="et_edt-pos-ADP.html">ADP</a></tt> (3; 0% instances), <tt><a href="et_edt-pos-INTJ.html">INTJ</a></tt>-<tt><a href="et_edt-pos-ADP.html">ADP</a></tt> (1; 0% instances), <tt><a href="et_edt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="et_edt-pos-ADV.html">ADV</a></tt> (1; 0% instances), <tt><a href="et_edt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="et_edt-pos-CCONJ.html">CCONJ</a></tt> (1; 0% instances), <tt><a href="et_edt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="et_edt-pos-ADV.html">ADV</a></tt> (1; 0% instances), <tt><a href="et_edt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="et_edt-pos-PRON.html">PRON</a></tt> (1; 0% instances), <tt><a href="et_edt-pos-X.html">X</a></tt>-<tt><a href="et_edt-pos-ADP.html">ADP</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 7 case	color:blue
1	Kahjuks	kahjuks	ADV	D	_	2	advmod	2:advmod	_
2	teatakse	teadma	VERB	V	Mood=Ind|Tense=Pres|VerbForm=Fin|Voice=Pass	0	root	0:root	Verb=teadma
3	ajaloos	aja_lugu	NOUN	S	Case=Ine|Number=Sing	2	obl	2:obl	_
4	oopereid	ooper	NOUN	S	Case=Par|Number=Plur	2	obj	2:obj	Arg=teadma_Arg_1
5	peamiselt	peamiselt	ADV	D	_	6	advmod	6:advmod	_
6	heliloojate	heli_looja	NOUN	S	Case=Gen|Number=Plur	2	obl	2:obl	_
7	järgi	järgi	ADP	K	AdpType=Post	6	case	6:case	SpaceAfter=No
8	.	.	PUNCT	Z	_	2	punct	2:punct	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 4 case	color:blue
1	Tegelikult	tegelikult	ADV	D	_	2	advmod	2:advmod	_
2	esimesed	esimene	ADJ	N	Case=Nom|Number=Plur|NumForm=Word|NumType=Ord	0	root	0:root	SpaceAfter=No
3	,	,	PUNCT	Z	_	7	punct	7:punct	_
4	tänu	tänu	ADP	K	AdpType=Prep	5	case	5:case	_
5	kellele	kes	PRON	P	Case=All|Number=Plur|PronType=Int,Rel	7	obl	2:ref|10:ref	_
6	etnofutu	etnofutu	NOUN	S	Case=Nom|Number=Sing|Tense=Past|VerbForm=Part|Voice=Pass	7	nsubj	7:nsubj	Arg=sündima_Arg_1
7	sündis	sündima	VERB	V	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin|Voice=Act	2	acl:relcl	2:acl:relcl	SpaceAfter=No|Verb=sündima
8	,	,	PUNCT	Z	_	7	punct	7:punct	_
9	olid	olema	AUX	V	Mood=Ind|Number=Plur|Person=3|Tense=Past|VerbForm=Fin|Voice=Act	2	cop	2:cop	_
10	setod	seto	NOUN	S	Case=Nom|Number=Plur	2	nsubj:cop	2:nsubj|7:obl	SpaceAfter=No
11	.	.	PUNCT	Z	_	2	punct	2:punct	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 3 case	color:blue
1	Nagu	nagu	SCONJ	J	_	2	mark	2:mark	_
2	Wagneri	Wagner	PROPN	S	Case=Gen|Number=Sing	0	root	0:root	NE=B-Per
3	puhul	puhul	ADP	K	AdpType=Post	2	case	2:case	SpaceAfter=No
4	.	.	PUNCT	Z	_	2	punct	2:punct	_

~~~


