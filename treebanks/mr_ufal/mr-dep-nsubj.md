---
layout: base
title:  'Statistics of nsubj in UD_Marathi'
udver: '2'
---

## Treebank Statistics: UD_Marathi: Relations: `nsubj`

This relation is universal.
There are 2 language-specific subtypes of `nsubj`: <tt><a href="mr-dep-nsubj-own.html">nsubj:own</a></tt>, <tt><a href="mr-dep-nsubj-pass.html">nsubj:pass</a></tt>.

480 nodes (12%) are attached to their parents as `nsubj`.

467 instances of `nsubj` (97%) are right-to-left (child precedes parent).
Average distance between parent and child is 2.4125.

The following 20 pairs of parts of speech are connected with `nsubj`: <tt><a href="mr-pos-VERB.html">VERB</a></tt>-<tt><a href="mr-pos-NOUN.html">NOUN</a></tt> (205; 43% instances), <tt><a href="mr-pos-VERB.html">VERB</a></tt>-<tt><a href="mr-pos-PRON.html">PRON</a></tt> (170; 35% instances), <tt><a href="mr-pos-VERB.html">VERB</a></tt>-<tt><a href="mr-pos-PROPN.html">PROPN</a></tt> (22; 5% instances), <tt><a href="mr-pos-NOUN.html">NOUN</a></tt>-<tt><a href="mr-pos-PRON.html">PRON</a></tt> (19; 4% instances), <tt><a href="mr-pos-NOUN.html">NOUN</a></tt>-<tt><a href="mr-pos-NOUN.html">NOUN</a></tt> (16; 3% instances), <tt><a href="mr-pos-ADJ.html">ADJ</a></tt>-<tt><a href="mr-pos-NOUN.html">NOUN</a></tt> (12; 3% instances), <tt><a href="mr-pos-AUX.html">AUX</a></tt>-<tt><a href="mr-pos-NOUN.html">NOUN</a></tt> (8; 2% instances), <tt><a href="mr-pos-ADV.html">ADV</a></tt>-<tt><a href="mr-pos-PRON.html">PRON</a></tt> (6; 1% instances), <tt><a href="mr-pos-ADV.html">ADV</a></tt>-<tt><a href="mr-pos-PROPN.html">PROPN</a></tt> (3; 1% instances), <tt><a href="mr-pos-NOUN.html">NOUN</a></tt>-<tt><a href="mr-pos-PROPN.html">PROPN</a></tt> (3; 1% instances), <tt><a href="mr-pos-PRON.html">PRON</a></tt>-<tt><a href="mr-pos-PRON.html">PRON</a></tt> (3; 1% instances), <tt><a href="mr-pos-ADJ.html">ADJ</a></tt>-<tt><a href="mr-pos-PRON.html">PRON</a></tt> (2; 0% instances), <tt><a href="mr-pos-ADV.html">ADV</a></tt>-<tt><a href="mr-pos-NOUN.html">NOUN</a></tt> (2; 0% instances), <tt><a href="mr-pos-AUX.html">AUX</a></tt>-<tt><a href="mr-pos-PRON.html">PRON</a></tt> (2; 0% instances), <tt><a href="mr-pos-PROPN.html">PROPN</a></tt>-<tt><a href="mr-pos-PRON.html">PRON</a></tt> (2; 0% instances), <tt><a href="mr-pos-ADP.html">ADP</a></tt>-<tt><a href="mr-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="mr-pos-NOUN.html">NOUN</a></tt>-<tt><a href="mr-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="mr-pos-PRON.html">PRON</a></tt>-<tt><a href="mr-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="mr-pos-VERB.html">VERB</a></tt>-<tt><a href="mr-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="mr-pos-VERB.html">VERB</a></tt>-<tt><a href="mr-pos-VERB.html">VERB</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 1 nsubj	color:blue
1	कागदपत्रं	कागदपत्र	NOUN	_	Case=Nom|Gender=Masc|Number=Plur	3	nsubj	_	_
2	काय	काय	PRON	_	Case=Acc|PronType=Int	3	obj	_	_
3	सांगतात	सांगणे	VERB	_	Aspect=Imp|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
4	?	?	PUNCT	_	_	3	punct	_	_

~~~


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 6 nsubj	color:blue
1	"	"	PUNCT	_	_	9	punct	_	_
2	त्या	तो	DET	_	Case=Obl|Distance=Dist|PronType=Dem	3	det	_	_
3	_	तुकडा	NOUN	_	Case=Obl|Gender=Masc|Number=Sing	9	obl	_	_
4	_	चा	ADP	_	Gender=Neut|Number=Sing	3	case	_	_
5	का	का	ADV	_	_	9	advmod	_	_
6	कोणी	कोण	PRON	_	Case=Erg|PronType=Int	9	nsubj	_	_
7	हजार	हजार	NUM	_	_	8	nummod	_	_
8	रुपये	रुपय	NOUN	_	Case=Acc|Gender=Masc|Number=Plur	9	obj	_	_
9	देईल	देणे	VERB	_	Number=Sing|Person=3|Tense=Fut|VerbForm=Fin	0	root	_	_
10	?	?	PUNCT	_	_	9	punct	_	_
11	"	"	PUNCT	_	_	9	punct	_	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 1 nsubj	color:blue
1	भीमा	भीमा	PROPN	_	Case=Nom|Gender=Masc|Number=Sing	4	nsubj	_	_
2	दुःखाने	दुःख	NOUN	_	Case=Ins|Gender=Neut|Number=Sing	4	obl	_	_
3	घरी	घरी	ADV	_	_	4	obl	_	_
4	गेला	जाणे	VERB	_	Aspect=Perf|Gender=Masc|Number=Sing|Person=3|VerbForm=Fin	0	root	_	_
5	.	.	PUNCT	_	_	4	punct	_	_

~~~


