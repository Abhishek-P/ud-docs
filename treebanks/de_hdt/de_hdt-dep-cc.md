---
layout: base
title:  'Statistics of cc in UD_German-HDT'
udver: '2'
---

## Treebank Statistics: UD_German-HDT: Relations: `cc`

This relation is universal.

75304 nodes (2%) are attached to their parents as `cc`.

75303 instances of `cc` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 2.81554764687135.

The following 16 pairs of parts of speech are connected with `cc`: <tt><a href="de_hdt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="de_hdt-pos-CCONJ.html">CCONJ</a></tt> (37785; 50% instances), <tt><a href="de_hdt-pos-VERB.html">VERB</a></tt>-<tt><a href="de_hdt-pos-CCONJ.html">CCONJ</a></tt> (20172; 27% instances), <tt><a href="de_hdt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="de_hdt-pos-CCONJ.html">CCONJ</a></tt> (8923; 12% instances), <tt><a href="de_hdt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="de_hdt-pos-CCONJ.html">CCONJ</a></tt> (4366; 6% instances), <tt><a href="de_hdt-pos-X.html">X</a></tt>-<tt><a href="de_hdt-pos-CCONJ.html">CCONJ</a></tt> (1450; 2% instances), <tt><a href="de_hdt-pos-AUX.html">AUX</a></tt>-<tt><a href="de_hdt-pos-CCONJ.html">CCONJ</a></tt> (766; 1% instances), <tt><a href="de_hdt-pos-NUM.html">NUM</a></tt>-<tt><a href="de_hdt-pos-CCONJ.html">CCONJ</a></tt> (542; 1% instances), <tt><a href="de_hdt-pos-ADV.html">ADV</a></tt>-<tt><a href="de_hdt-pos-CCONJ.html">CCONJ</a></tt> (516; 1% instances), <tt><a href="de_hdt-pos-DET.html">DET</a></tt>-<tt><a href="de_hdt-pos-CCONJ.html">CCONJ</a></tt> (410; 1% instances), <tt><a href="de_hdt-pos-PRON.html">PRON</a></tt>-<tt><a href="de_hdt-pos-CCONJ.html">CCONJ</a></tt> (231; 0% instances), <tt><a href="de_hdt-pos-PART.html">PART</a></tt>-<tt><a href="de_hdt-pos-CCONJ.html">CCONJ</a></tt> (102; 0% instances), <tt><a href="de_hdt-pos-ADP.html">ADP</a></tt>-<tt><a href="de_hdt-pos-CCONJ.html">CCONJ</a></tt> (23; 0% instances), <tt><a href="de_hdt-pos-SCONJ.html">SCONJ</a></tt>-<tt><a href="de_hdt-pos-CCONJ.html">CCONJ</a></tt> (12; 0% instances), <tt><a href="de_hdt-pos-INTJ.html">INTJ</a></tt>-<tt><a href="de_hdt-pos-CCONJ.html">CCONJ</a></tt> (4; 0% instances), <tt><a href="de_hdt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="de_hdt-pos-ADV.html">ADV</a></tt> (1; 0% instances), <tt><a href="de_hdt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="de_hdt-pos-X.html">X</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 5 cc	color:blue
1	Anleitung	Anleitung	NOUN	NN	Gender=Fem|Number=Sing	0	root	_	_
2	zu	zu	ADP	APPR	AdpType=Prep|Case=Dat	4	case	_	_
3	dem	der	DET	ART	Case=Dat|Definite=Def|Gender=Masc,Neut|Number=Sing|PronType=Art	4	det	_	_
4	Kindesmißbrauch	Mißbrauch	NOUN	NN	Case=Dat|Gender=Masc|Number=Sing	1	nmod	_	_
5	und	und	CCONJ	KON	_	6	cc	_	_
6	Mord	Mord	NOUN	NN	Gender=Masc|Number=Sing	4	conj	_	_
7	in	in	ADP	APPR	AdpType=Prep|Case=Dat	9	case	_	_
8	dem	der	DET	ART	Case=Dat|Definite=Def|Gender=Masc,Neut|Number=Sing|PronType=Art	9	det	_	_
9	Internet	Internet	NOUN	NN	Case=Dat|Gender=Neut|Number=Sing	1	nmod	_	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 1 cc	color:blue
1	Doch	Doch	CCONJ	KON	_	7	cc	_	_
2	die	der	DET	ART	Case=Nom|Definite=Def|Gender=Fem|Number=Sing|PronType=Art	3	det	_	_
3	Sache	Sache	NOUN	NN	Case=Nom|Gender=Fem|Number=Sing	7	nsubj:pass	_	_
4	dürfte	dürfen	AUX	VMFIN	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|VerbType=Mod	7	aux	_	_
5	noch	noch	ADV	ADV	_	7	advmod	_	_
6	nicht	nicht	PART	PTKNEG	Polarity=Neg	7	advmod	_	_
7	ausgestanden	ausstehen	VERB	VVPP	Aspect=Perf|VerbForm=Part	0	root	_	_
8	sein	sein	AUX	VAINF	VerbForm=Inf	7	aux:pass	_	_
9	.	.	PUNCT	$.	PunctType=Peri	7	punct	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 4 cc	color:blue
1	Deutsche	deutsch	ADJ	ADJA	Degree=Pos|Gender=Fem|Number=Sing	2	amod	_	_
2	Bank	Bank	NOUN	NN	Case=Nom|Gender=Fem|Number=Sing	6	nsubj	_	_
3	24	24	NUM	CARD	Number=Plur|NumType=Card	2	flat	_	_
4	und	und	CCONJ	KON	_	5	cc	_	_
5	Yahoo	Yahoo	PROPN	NE	Case=Nom|Number=Sing	2	conj	_	_
6	kooperieren	kooperieren	VERB	VVFIN	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_

~~~


