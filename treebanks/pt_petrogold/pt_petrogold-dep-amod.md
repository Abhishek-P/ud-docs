---
layout: base
title:  'Statistics of amod in UD_Portuguese-PetroGold'
udver: '2'
---

## Treebank Statistics: UD_Portuguese-PetroGold: Relations: `amod`

This relation is universal.

14828 nodes (6%) are attached to their parents as `amod`.

12057 instances of `amod` (81%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.21149177232263.

The following 16 pairs of parts of speech are connected with `amod`: <tt><a href="pt_petrogold-pos-NOUN.html">NOUN</a></tt>-<tt><a href="pt_petrogold-pos-ADJ.html">ADJ</a></tt> (14606; 99% instances), <tt><a href="pt_petrogold-pos-PROPN.html">PROPN</a></tt>-<tt><a href="pt_petrogold-pos-ADJ.html">ADJ</a></tt> (144; 1% instances), <tt><a href="pt_petrogold-pos-PRON.html">PRON</a></tt>-<tt><a href="pt_petrogold-pos-ADJ.html">ADJ</a></tt> (30; 0% instances), <tt><a href="pt_petrogold-pos-ADJ.html">ADJ</a></tt>-<tt><a href="pt_petrogold-pos-ADJ.html">ADJ</a></tt> (20; 0% instances), <tt><a href="pt_petrogold-pos-VERB.html">VERB</a></tt>-<tt><a href="pt_petrogold-pos-ADJ.html">ADJ</a></tt> (8; 0% instances), <tt><a href="pt_petrogold-pos-NOUN.html">NOUN</a></tt>-<tt><a href="pt_petrogold-pos-NOUN.html">NOUN</a></tt> (5; 0% instances), <tt><a href="pt_petrogold-pos-SYM.html">SYM</a></tt>-<tt><a href="pt_petrogold-pos-ADJ.html">ADJ</a></tt> (3; 0% instances), <tt><a href="pt_petrogold-pos-X.html">X</a></tt>-<tt><a href="pt_petrogold-pos-ADJ.html">ADJ</a></tt> (3; 0% instances), <tt><a href="pt_petrogold-pos-NOUN.html">NOUN</a></tt>-<tt><a href="pt_petrogold-pos-X.html">X</a></tt> (2; 0% instances), <tt><a href="pt_petrogold-pos-ADV.html">ADV</a></tt>-<tt><a href="pt_petrogold-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="pt_petrogold-pos-NOUN.html">NOUN</a></tt>-<tt><a href="pt_petrogold-pos-DET.html">DET</a></tt> (1; 0% instances), <tt><a href="pt_petrogold-pos-NOUN.html">NOUN</a></tt>-<tt><a href="pt_petrogold-pos-NUM.html">NUM</a></tt> (1; 0% instances), <tt><a href="pt_petrogold-pos-NOUN.html">NOUN</a></tt>-<tt><a href="pt_petrogold-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="pt_petrogold-pos-NUM.html">NUM</a></tt>-<tt><a href="pt_petrogold-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="pt_petrogold-pos-NUM.html">NUM</a></tt>-<tt><a href="pt_petrogold-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="pt_petrogold-pos-PRON.html">PRON</a></tt>-<tt><a href="pt_petrogold-pos-NOUN.html">NOUN</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 2 amod	color:blue
1	REFERENCIAL	referencial	NOUN	_	Gender=Masc|Number=Sing	0	root	_	_
2	TEÓRICO	teórico	ADJ	_	Gender=Masc|Number=Sing	1	amod	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 3 amod	color:blue
1	1.2	1.2	NUM	_	NumType=Card	2	nummod	_	_
2	Objetivo	Objetivo	PROPN	_	Gender=Masc|Number=Sing	0	root	_	_
3	Geral	geral	ADJ	_	Gender=Masc|Number=Sing	2	amod	_	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 8 amod	color:blue
1	Uma	um	DET	_	Definite=Ind|Gender=Fem|Number=Sing|PronType=Art	2	det	_	_
2	corrente	corrente	NOUN	_	Gender=Fem|Number=Sing	11	nsubj	_	_
3	rica	rico	ADJ	_	Gender=Fem|Number=Sing	2	amod	_	_
4	em	em	ADP	_	_	5	case	_	_
5	gás	gás	NOUN	_	Gender=Masc|Number=Sing	2	obl	_	_
6	e	e	CCONJ	_	_	8	cc	_	_
7	uma	um	PRON	_	Gender=Fem|Number=Sing|PronType=Ind	2	conj	_	_
8	rica	rico	ADJ	_	Gender=Fem|Number=Sing	7	amod	_	_
9	em	em	ADP	_	_	10	case	_	_
10	óleo	óleo	NOUN	_	Gender=Masc|Number=Sing	8	obl	_	_
11	deixam	deixar	VERB	_	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
12	este	este	DET	_	Gender=Masc|Number=Sing|PronType=Dem	14	det	_	_
13	primeiro	primeiro	ADJ	_	Gender=Masc|Number=Sing|NumType=Ord	14	amod	_	_
14	separador	separador	NOUN	_	Gender=Masc|Number=Sing	11	obj	_	SpaceAfter=No
15	.	.	PUNCT	_	_	11	punct	_	_

~~~


