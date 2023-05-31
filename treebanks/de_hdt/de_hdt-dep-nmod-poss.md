---
layout: base
title:  'Statistics of nmod:poss in UD_German-HDT'
udver: '2'
---

## Treebank Statistics: UD_German-HDT: Relations: `nmod:poss`

This relation is a language-specific subtype of <tt><a href="de_hdt-dep-nmod.html">nmod</a></tt>.

10 nodes (0%) are attached to their parents as `nmod:poss`.

10 instances of `nmod:poss` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 2.2.

The following 3 pairs of parts of speech are connected with `nmod:poss`: <tt><a href="de_hdt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="de_hdt-pos-NOUN.html">NOUN</a></tt> (8; 80% instances), <tt><a href="de_hdt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="de_hdt-pos-PROPN.html">PROPN</a></tt> (1; 10% instances), <tt><a href="de_hdt-pos-PRON.html">PRON</a></tt>-<tt><a href="de_hdt-pos-NOUN.html">NOUN</a></tt> (1; 10% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 5 nmod:poss	color:blue
1	Konkursgerüchte	Gerücht	NOUN	NN	Case=Nom|Gender=Neut|Number=Plur	2	nsubj	_	_
2	drücken	drücken	VERB	VVFIN	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
3	Kurs	Kurs	NOUN	NN	Case=Acc|Gender=Masc|Number=Sing	2	obj	_	_
4	der	der	DET	ART	Case=Gen|Definite=Def|Gender=Fem|Number=Sing|PronType=Art	5	det:poss	_	_
5	Amazon-Aktie	Aktie	NOUN	NN	Case=Gen|Gender=Fem|Number=Sing	3	nmod:poss	_	_

~~~


~~~ conllu
# visual-style 24	bgColor:blue
# visual-style 24	fgColor:white
# visual-style 22	bgColor:blue
# visual-style 22	fgColor:white
# visual-style 22 24 nmod:poss	color:blue
1	Formac	unknown	NOUN	NN	_	13	nsubj	_	_
2	aus	aus	ADP	APPR	AdpType=Prep|Case=Dat	3	case	_	_
3	Blankenfelde	Feld	NOUN	NN	Case=Dat|Gender=Neut|Number=Sing	1	nmod	_	_
4	,	,	PUNCT	$,	PunctType=Comm	11	punct	_	_
5	Mac-Usern	User	NOUN	NN	Case=Dat|Gender=Masc|Number=Plur	11	nsubj	_	_
6	durch	durch	ADP	APPR	AdpType=Prep|Case=Acc	7	case	_	_
7	Grafikkarten	Karte	NOUN	NN	Gender=Fem|Number=Plur	11	nmod	_	_
8	und	und	CCONJ	KON	_	9	cc	_	_
9	Monitore	Tor	NOUN	NN	Gender=Neut|Number=Plur	7	conj	_	_
10	ein	ein	DET	ART	Case=Nom|Definite=Ind|Gender=Masc|Number=Sing|NumType=Card|PronType=Art	11	det	_	_
11	Begriff	Begriff	NOUN	NN	Gender=Masc|Number=Sing	1	appos	_	_
12	,	,	PUNCT	$,	PunctType=Comm	11	punct	_	_
13	zeigt	zeigen	VERB	VVFIN	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
14	auf	auf	ADP	APPR	AdpType=Prep|Case=Dat	16	case	_	_
15	der	der	DET	ART	Case=Dat|Definite=Def|Gender=Fem|Number=Sing|PronType=Art	16	det	_	_
16	Macworld	unknown	NOUN	NN	_	13	obl	_	_
17	zwei	zwei	NUM	CARD	Number=Plur|NumType=Card	18	nummod	_	_
18	Erweiterungskarten	Karte	NOUN	NN	Gender=Fem|Number=Plur	13	obj	_	_
19	für	für	ADP	APPR	AdpType=Prep|Case=Acc	22	case	_	_
20	den	der	DET	ART	Case=Acc|Definite=Def|Gender=Masc|Number=Sing|PronType=Art	22	det	_	_
21	internen	intern	ADJ	ADJA	Case=Acc|Degree=Pos|Gender=Masc|Number=Sing	22	amod	_	_
22	Mezzanine-Slot	Slot	NOUN	NN	Gender=Masc|Number=Sing	18	nmod	_	_
23	des	der	DET	ART	Case=Gen|Definite=Def|Gender=Neut|Number=Sing|PronType=Art	24	det:poss	_	_
24	iMac	iMac	PROPN	NE	Case=Nom|Number=Sing	22	nmod:poss	_	_
25	.	.	PUNCT	$.	PunctType=Peri	13	punct	_	_

~~~


~~~ conllu
# visual-style 17	bgColor:blue
# visual-style 17	fgColor:white
# visual-style 15	bgColor:blue
# visual-style 15	fgColor:white
# visual-style 15 17 nmod:poss	color:blue
1	"	"	PUNCT	$(	PunctType=Brck	5	punct	_	_
2	Die	der	DET	ART	Case=Nom|Definite=Def|Number=Plur|PronType=Art	4	det	_	_
3	amerikanischen	amerikanisch	ADJ	ADJA	Degree=Pos|Number=Plur	4	amod	_	_
4	Geheimdienste	Dienst	NOUN	NN	Gender=Masc|Number=Plur	5	nsubj	_	_
5	handeln	handeln	VERB	VVFIN	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
6	nicht	nicht	PART	PTKNEG	Polarity=Neg	9	advmod	_	_
7	in	in	ADP	APPR	AdpType=Prep|Case=Dat	9	case	_	_
8	dem	der	DET	ART	Case=Dat|Definite=Def|Gender=Masc,Neut|Number=Sing|PronType=Art	9	det	_	_
9	Auftrag	Auftrag	NOUN	NN	Gender=Masc|Number=Sing	5	obl	_	_
10	von	von	ADP	APPR	AdpType=Prep|Case=Dat	11	case	_	_
11	US-Unternehmen	Unternehmen	NOUN	NN	Gender=Neut|Number=Plur	9	nmod	_	_
12	,	,	PUNCT	$,	PunctType=Comm	15	punct	_	_
13	sondern	sondern	CCONJ	KON	_	15	cc	_	_
14	in	in	ADP	APPR	AdpType=Prep|Case=Dat	15	case	_	_
15	dem	der	PRON	PDS	Case=Dat|Gender=Neut|Number=Sing|PronType=Dem,Rel	9	conj	_	_
16	der	der	DET	ART	Case=Gen|Definite=Def|Gender=Fem|Number=Sing|PronType=Art	17	det:poss	_	_
17	Regierung	Regierung	NOUN	NN	Gender=Fem|Number=Sing	15	nmod:poss	_	_
18	.	.	PUNCT	$.	PunctType=Peri	5	punct	_	_

~~~


