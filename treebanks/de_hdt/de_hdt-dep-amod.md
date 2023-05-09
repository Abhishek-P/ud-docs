---
layout: base
title:  'Statistics of amod in UD_German-HDT'
udver: '2'
---

## Treebank Statistics: UD_German-HDT: Relations: `amod`

This relation is universal.

182338 nodes (5%) are attached to their parents as `amod`.

182309 instances of `amod` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.09441257444965.

The following 19 pairs of parts of speech are connected with `amod`: <tt><a href="de_hdt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="de_hdt-pos-ADJ.html">ADJ</a></tt> (175556; 96% instances), <tt><a href="de_hdt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="de_hdt-pos-ADJ.html">ADJ</a></tt> (4317; 2% instances), <tt><a href="de_hdt-pos-X.html">X</a></tt>-<tt><a href="de_hdt-pos-ADJ.html">ADJ</a></tt> (1766; 1% instances), <tt><a href="de_hdt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="de_hdt-pos-NOUN.html">NOUN</a></tt> (345; 0% instances), <tt><a href="de_hdt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="de_hdt-pos-ADJ.html">ADJ</a></tt> (180; 0% instances), <tt><a href="de_hdt-pos-NUM.html">NUM</a></tt>-<tt><a href="de_hdt-pos-ADJ.html">ADJ</a></tt> (122; 0% instances), <tt><a href="de_hdt-pos-DET.html">DET</a></tt>-<tt><a href="de_hdt-pos-ADJ.html">ADJ</a></tt> (13; 0% instances), <tt><a href="de_hdt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="de_hdt-pos-X.html">X</a></tt> (11; 0% instances), <tt><a href="de_hdt-pos-X.html">X</a></tt>-<tt><a href="de_hdt-pos-NOUN.html">NOUN</a></tt> (5; 0% instances), <tt><a href="de_hdt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="de_hdt-pos-PROPN.html">PROPN</a></tt> (4; 0% instances), <tt><a href="de_hdt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="de_hdt-pos-NOUN.html">NOUN</a></tt> (4; 0% instances), <tt><a href="de_hdt-pos-VERB.html">VERB</a></tt>-<tt><a href="de_hdt-pos-ADJ.html">ADJ</a></tt> (4; 0% instances), <tt><a href="de_hdt-pos-NUM.html">NUM</a></tt>-<tt><a href="de_hdt-pos-NOUN.html">NOUN</a></tt> (3; 0% instances), <tt><a href="de_hdt-pos-ADV.html">ADV</a></tt>-<tt><a href="de_hdt-pos-ADJ.html">ADJ</a></tt> (2; 0% instances), <tt><a href="de_hdt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="de_hdt-pos-PRON.html">PRON</a></tt> (2; 0% instances), <tt><a href="de_hdt-pos-ADP.html">ADP</a></tt>-<tt><a href="de_hdt-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="de_hdt-pos-INTJ.html">INTJ</a></tt>-<tt><a href="de_hdt-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="de_hdt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="de_hdt-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="de_hdt-pos-PRON.html">PRON</a></tt>-<tt><a href="de_hdt-pos-ADJ.html">ADJ</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 6 amod	color:blue
1	"	"	PUNCT	$(	PunctType=Brck	4	punct	_	_
2	Diesen	dieser	DET	PDAT	Case=Dat|Number=Plur|PronType=Dem	3	det	_	_
3	Gerüchten	Gerücht	NOUN	NN	Case=Dat|Gender=Neut|Number=Plur	4	obj	_	_
4	liegt	liegen	VERB	VVFIN	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
5	eine	ein	DET	ART	Case=Nom|Definite=Ind|Gender=Fem|Number=Sing|NumType=Card|PronType=Art	7	det	_	_
6	unseriöse	unseriöse	ADJ	ADJA	Gender=Fem|Number=Sing	7	amod	_	_
7	Recherche	Recherche	NOUN	NN	Case=Nom|Gender=Fem|Number=Sing	4	nsubj	_	_
8	zugrunde	zugrunde	ADP	PTKVZ	PartType=Vbp	4	compound:prt	_	_
9	.	.	PUNCT	$.	PunctType=Peri	4	punct	_	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 8 amod	color:blue
1	Die	der	DET	ART	Case=Nom|Definite=Def|Gender=Fem|Number=Sing|PronType=Art	2	det	_	_
2	max.mobil	max.mobil	PROPN	NE	Case=Nom|Number=Sing	3	nsubj	_	_
3	gehört	gehören	VERB	VVFIN	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
4	zu	zu	ADP	APPR	AdpType=Prep|Case=Dat	6	case	_	_
5	81	81	NUM	CARD	Number=Plur|NumType=Card	6	nummod	_	_
6	Prozent	Prozent	NOUN	NN	Case=Dat|Gender=Neut|Number=Plur	3	obl	_	_
7	der	der	DET	ART	Case=Dat|Definite=Def|Gender=Fem|Number=Sing|PronType=Art	9	det	_	_
8	Deutschen	deutsch	ADJ	ADJA	Case=Dat|Degree=Pos|Gender=Fem|Number=Sing	9	amod	_	_
9	Telekom	Telekom	PROPN	NE	Case=Dat|Gender=Fem|Number=Sing	3	obj	_	_
10	.	.	PUNCT	$.	PunctType=Peri	3	punct	_	_

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 7 amod	color:blue
1	Als	Als	CCONJ	KOKOM	ConjType=Comp	2	case	_	_
2	Zielgruppe	Zielgruppe	NOUN	NN	Gender=Fem|Number=Sing	3	obl	_	_
3	sieht	sehen	VERB	VVFIN	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
4	Meister	Meister	NOUN	NN	Case=Nom|Gender=Masc|Number=Sing	3	nsubj	_	_
5	15	15	NUM	CARD	Number=Plur|NumType=Card	3	obj	_	_
6	bis	bis	ADP	APPR	AdpType=Prep	8	case	_	_
7	25-jährige	jährig	ADJ	ADJA	Degree=Pos|Number=Plur	8	amod	_	_
8	Surfer	Surfer	X	FM	Foreign=Yes	5	nmod	_	_
9	.	.	PUNCT	$.	PunctType=Peri	3	punct	_	_

~~~


