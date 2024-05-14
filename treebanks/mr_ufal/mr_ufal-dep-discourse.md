---
layout: base
title:  'Statistics of discourse in UD_Marathi-UFAL'
udver: '2'
---

## Treebank Statistics: UD_Marathi-UFAL: Relations: `discourse`

This relation is universal.

57 nodes (1%) are attached to their parents as `discourse`.

40 instances of `discourse` (70%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.70175438596491.

The following 17 pairs of parts of speech are connected with `discourse`: <tt><a href="mr_ufal-pos-PRON.html">PRON</a></tt>-<tt><a href="mr_ufal-pos-PART.html">PART</a></tt> (12; 21% instances), <tt><a href="mr_ufal-pos-NOUN.html">NOUN</a></tt>-<tt><a href="mr_ufal-pos-PART.html">PART</a></tt> (11; 19% instances), <tt><a href="mr_ufal-pos-ADJ.html">ADJ</a></tt>-<tt><a href="mr_ufal-pos-PART.html">PART</a></tt> (4; 7% instances), <tt><a href="mr_ufal-pos-DET.html">DET</a></tt>-<tt><a href="mr_ufal-pos-PART.html">PART</a></tt> (4; 7% instances), <tt><a href="mr_ufal-pos-VERB.html">VERB</a></tt>-<tt><a href="mr_ufal-pos-ADV.html">ADV</a></tt> (4; 7% instances), <tt><a href="mr_ufal-pos-VERB.html">VERB</a></tt>-<tt><a href="mr_ufal-pos-INTJ.html">INTJ</a></tt> (4; 7% instances), <tt><a href="mr_ufal-pos-VERB.html">VERB</a></tt>-<tt><a href="mr_ufal-pos-NOUN.html">NOUN</a></tt> (3; 5% instances), <tt><a href="mr_ufal-pos-VERB.html">VERB</a></tt>-<tt><a href="mr_ufal-pos-PART.html">PART</a></tt> (3; 5% instances), <tt><a href="mr_ufal-pos-ADJ.html">ADJ</a></tt>-<tt><a href="mr_ufal-pos-NOUN.html">NOUN</a></tt> (2; 4% instances), <tt><a href="mr_ufal-pos-PRON.html">PRON</a></tt>-<tt><a href="mr_ufal-pos-INTJ.html">INTJ</a></tt> (2; 4% instances), <tt><a href="mr_ufal-pos-PROPN.html">PROPN</a></tt>-<tt><a href="mr_ufal-pos-PART.html">PART</a></tt> (2; 4% instances), <tt><a href="mr_ufal-pos-ADV.html">ADV</a></tt>-<tt><a href="mr_ufal-pos-ADV.html">ADV</a></tt> (1; 2% instances), <tt><a href="mr_ufal-pos-NOUN.html">NOUN</a></tt>-<tt><a href="mr_ufal-pos-ADV.html">ADV</a></tt> (1; 2% instances), <tt><a href="mr_ufal-pos-NOUN.html">NOUN</a></tt>-<tt><a href="mr_ufal-pos-INTJ.html">INTJ</a></tt> (1; 2% instances), <tt><a href="mr_ufal-pos-NOUN.html">NOUN</a></tt>-<tt><a href="mr_ufal-pos-PRON.html">PRON</a></tt> (1; 2% instances), <tt><a href="mr_ufal-pos-VERB.html">VERB</a></tt>-<tt><a href="mr_ufal-pos-PRON.html">PRON</a></tt> (1; 2% instances), <tt><a href="mr_ufal-pos-VERB.html">VERB</a></tt>-<tt><a href="mr_ufal-pos-SCONJ.html">SCONJ</a></tt> (1; 2% instances).


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 2 discourse	color:blue
1	तो	तो	PRON	_	Case=Nom|Deixis=Remt|Gender=Masc|Number=Sing|Person=3|PronType=Dem	3	nsubj	_	Translit=to|LTranslit=to
2	ही	ही	PART	_	_	1	discourse	_	Translit=hī|LTranslit=hī
3	म्हणाला	म्हणणे	VERB	_	Aspect=Perf|Gender=Masc|Number=Sing|Person=3|VerbForm=Fin	0	root	_	SpaceAfter=No|Translit=mhaṇālā|LTranslit=mhaṇaṇe
4	.	.	PUNCT	_	_	3	punct	_	Translit=.|LTranslit=.

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 3 discourse	color:blue
1	"	"	PUNCT	_	_	6	punct	_	SpaceAfter=No|Translit="|LTranslit="
2	खरे	खरा	NOUN	_	Case=Nom|Gender=Masc|Number=Plur	6	discourse	_	Translit=khare|LTranslit=kharā
3	च	च	PART	_	_	2	discourse	_	Translit=ca|LTranslit=ca
4	,	,	PUNCT	_	_	2	punct	_	Translit=,|LTranslit=,
5	न्याय	न्याय	NOUN	_	Case=Nom|Gender=Masc|Number=Sing	6	nsubj	_	Translit=nyāya|LTranslit=nyāya
6	उरला	उरणे	VERB	_	Aspect=Perf|Gender=Masc|Number=Sing|Person=3|VerbForm=Fin	0	root	_	Translit=uralā|LTranslit=uraṇe
7	नाही	असणे	AUX	_	Number=Sing|Person=3|Polarity=Neg|VerbForm=Fin	6	aux	_	SpaceAfter=No|Translit=nāhī|LTranslit=asaṇe
8	.	.	PUNCT	_	_	6	punct	_	SpaceAfter=No|Translit=.|LTranslit=.
9	"	"	PUNCT	_	_	6	punct	_	Translit="|LTranslit="
10	देवी	देवी	NOUN	_	Case=Abs|Gender=Fem|Number=Sing	13	nmod:poss	_	Translit=devī|LTranslit=devī
11	चा	चा	ADP	_	Gender=Masc|Number=Sing	10	case	_	Translit=cā|LTranslit=cā
12	तो	तो	DET	_	Deixis=Remt|Gender=Masc|Number=Sing|PronType=Dem	13	det	_	Translit=to|LTranslit=to
13	पुजारी	पुजारी	NOUN	_	Case=Nom|Gender=Masc|Number=Sing	14	nsubj	_	Translit=pujārī|LTranslit=pujārī
14	म्हणाला	म्हणणे	VERB	_	Aspect=Perf|Gender=Masc|Number=Sing|Person=3|VerbForm=Fin	6	parataxis	_	SpaceAfter=No|Translit=mhaṇālā|LTranslit=mhaṇaṇe
15	.	.	PUNCT	_	_	14	punct	_	Translit=.|LTranslit=.

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 2 discourse	color:blue
1	जवळ	जवळ	ADJ	_	Case=Nom	4	amod	_	Translit=javaḷa|LTranslit=javaḷa
2	च	च	PART	_	_	1	discourse	_	Translit=ca|LTranslit=ca
3	एक	एक	DET	_	Number=Sing|PronType=Ind	4	det	_	Translit=eka|LTranslit=eka
4	शहर	शहर	NOUN	_	Case=Acc|Gender=Neut|Number=Sing	5	obj	_	Translit=śahara|LTranslit=śahara
5	दिसत	दिसणे	VERB	_	Aspect=Imp|VerbForm=Part	0	root	_	Translit=disata|LTranslit=disaṇe
6	होते	असणे	AUX	_	Gender=Neut|Number=Sing|Person=3|Polarity=Pos|Tense=Past|VerbForm=Fin	5	aux	_	SpaceAfter=No|Translit=hote|LTranslit=asaṇe
7	.	.	PUNCT	_	_	5	punct	_	Translit=.|LTranslit=.

~~~


