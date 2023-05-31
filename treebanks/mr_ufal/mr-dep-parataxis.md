---
layout: base
title:  'Statistics of parataxis in UD_Marathi'
udver: '2'
---

## Treebank Statistics: UD_Marathi: Relations: `parataxis`

This relation is universal.

75 nodes (2%) are attached to their parents as `parataxis`.

75 instances of `parataxis` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 5.97333333333333.

The following 13 pairs of parts of speech are connected with `parataxis`: <tt><a href="mr-pos-VERB.html">VERB</a></tt>-<tt><a href="mr-pos-VERB.html">VERB</a></tt> (52; 69% instances), <tt><a href="mr-pos-NOUN.html">NOUN</a></tt>-<tt><a href="mr-pos-VERB.html">VERB</a></tt> (7; 9% instances), <tt><a href="mr-pos-ADJ.html">ADJ</a></tt>-<tt><a href="mr-pos-VERB.html">VERB</a></tt> (2; 3% instances), <tt><a href="mr-pos-AUX.html">AUX</a></tt>-<tt><a href="mr-pos-VERB.html">VERB</a></tt> (2; 3% instances), <tt><a href="mr-pos-NOUN.html">NOUN</a></tt>-<tt><a href="mr-pos-NOUN.html">NOUN</a></tt> (2; 3% instances), <tt><a href="mr-pos-VERB.html">VERB</a></tt>-<tt><a href="mr-pos-ADJ.html">ADJ</a></tt> (2; 3% instances), <tt><a href="mr-pos-VERB.html">VERB</a></tt>-<tt><a href="mr-pos-NOUN.html">NOUN</a></tt> (2; 3% instances), <tt><a href="mr-pos-ADV.html">ADV</a></tt>-<tt><a href="mr-pos-ADJ.html">ADJ</a></tt> (1; 1% instances), <tt><a href="mr-pos-ADV.html">ADV</a></tt>-<tt><a href="mr-pos-VERB.html">VERB</a></tt> (1; 1% instances), <tt><a href="mr-pos-CCONJ.html">CCONJ</a></tt>-<tt><a href="mr-pos-VERB.html">VERB</a></tt> (1; 1% instances), <tt><a href="mr-pos-PRON.html">PRON</a></tt>-<tt><a href="mr-pos-VERB.html">VERB</a></tt> (1; 1% instances), <tt><a href="mr-pos-VERB.html">VERB</a></tt>-<tt><a href="mr-pos-ADV.html">ADV</a></tt> (1; 1% instances), <tt><a href="mr-pos-VERB.html">VERB</a></tt>-<tt><a href="mr-pos-PRON.html">PRON</a></tt> (1; 1% instances).


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 8 parataxis	color:blue
1	"	"	PUNCT	_	_	3	punct	_	_
2	काय	काय	PRON	_	Case=Acc|PronType=Int	3	obj	_	_
3	लागला	लागणे	VERB	_	Aspect=Perf|Gender=Masc|Number=Sing|Person=3|VerbForm=Fin	0	root	_	_
4	निकाल	निकाल	NOUN	_	Case=Nom|Gender=Masc|Number=Sing	3	nsubj	_	_
5	?	?	PUNCT	_	_	3	punct	_	_
6	"	"	PUNCT	_	_	3	punct	_	_
7	बायकोने	बायको	NOUN	_	Case=Erg|Gender=Fem|Number=Sing	8	nsubj	_	_
8	विचारले	विचारणे	VERB	_	Aspect=Perf|Gender=Neut|Number=Sing|Person=3|VerbForm=Fin	3	parataxis	_	_
9	.	.	PUNCT	_	_	8	punct	_	_

~~~


~~~ conllu
# visual-style 12	bgColor:blue
# visual-style 12	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 12 parataxis	color:blue
1	"	"	PUNCT	_	_	5	punct	_	_
2	हे	हा	DET	_	Distance=Prox|Gender=Neut|Number=Sing|PronType=Dem	4	det	_	_
3	म्हातारे	म्हातारा	ADJ	_	Case=Nom|Gender=Neut|Number=Sing	4	amod	_	_
4	शेतकरी	शेतकरी	NOUN	_	Case=Nom|Gender=Masc|Number=Plur	5	nsubj	_	_
5	साक्षीदार	साक्षीदार	NOUN	_	Case=Nom|Gender=Masc|Number=Sing	0	root	_	_
6	का	का	CCONJ	_	_	8	cc	_	_
7	खोटे	खोटा	ADJ	_	Case=Nom|Gender=Neut|Number=Sing	8	compound:lvc	_	_
8	सांगतात	सांगसांगणे	VERB	_	Aspect=Imp|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	5	conj	_	_
9	?	?	PUNCT	_	_	8	punct	_	_
10	"	"	PUNCT	_	_	5	punct	_	_
11	वकील	वकील	NOUN	_	Case=Nom|Gender=Masc|Number=Sing	12	nsubj	_	_
12	म्हणाला	म्हणणे	VERB	_	Aspect=Perf|Gender=Masc|Number=Sing|Person=3|VerbForm=Fin	5	parataxis	_	_
13	.	.	PUNCT	_	_	12	punct	_	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 8 parataxis	color:blue
1	"	"	PUNCT	_	_	3	punct	_	_
2	कोण	कोण	PRON	_	Case=Nom|PronType=Int	3	nsubj	_	_
3	मेले	मेला	ADJ	_	Case=Nom|Gender=Neut|Number=Sing	0	root	_	_
4	?	?	PUNCT	_	_	3	punct	_	_
5	"	"	PUNCT	_	_	3	punct	_	_
6	म्हाताऱ्या	म्हातारा	ADJ	_	Case=Obl	7	amod	_	_
7	गुरवाने	गुरव	NOUN	_	Case=Ins|Gender=Masc|Number=Sing	8	nsubj	_	_
8	विचारले	विचारणे	VERB	_	Aspect=Perf|Gender=Masc|Number=Plur|Person=3|VerbForm=Fin	3	parataxis	_	_
9	.	.	PUNCT	_	_	8	punct	_	_

~~~


