---
layout: base
title:  'Statistics of obl:arg in UD_German-GSD'
udver: '2'
---

## Treebank Statistics: UD_German-GSD: Relations: `obl:arg`

This relation is a language-specific subtype of <tt><a href="de_gsd-dep-obl.html">obl</a></tt>.
There are also 2 other language-specific subtypes of `obl`: <tt><a href="de_gsd-dep-obl-agent.html">obl:agent</a></tt>, <tt><a href="de_gsd-dep-obl-tmod.html">obl:tmod</a></tt>.

1258 nodes (0%) are attached to their parents as `obl:arg`.

769 instances of `obl:arg` (61%) are right-to-left (child precedes parent).
Average distance between parent and child is 4.04531001589825.

The following 13 pairs of parts of speech are connected with `obl:arg`: <tt><a href="de_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="de_gsd-pos-NOUN.html">NOUN</a></tt> (543; 43% instances), <tt><a href="de_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="de_gsd-pos-PRON.html">PRON</a></tt> (425; 34% instances), <tt><a href="de_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="de_gsd-pos-PROPN.html">PROPN</a></tt> (142; 11% instances), <tt><a href="de_gsd-pos-ADJ.html">ADJ</a></tt>-<tt><a href="de_gsd-pos-NOUN.html">NOUN</a></tt> (58; 5% instances), <tt><a href="de_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="de_gsd-pos-DET.html">DET</a></tt> (47; 4% instances), <tt><a href="de_gsd-pos-ADJ.html">ADJ</a></tt>-<tt><a href="de_gsd-pos-PRON.html">PRON</a></tt> (27; 2% instances), <tt><a href="de_gsd-pos-ADJ.html">ADJ</a></tt>-<tt><a href="de_gsd-pos-PROPN.html">PROPN</a></tt> (6; 0% instances), <tt><a href="de_gsd-pos-ADJ.html">ADJ</a></tt>-<tt><a href="de_gsd-pos-DET.html">DET</a></tt> (4; 0% instances), <tt><a href="de_gsd-pos-DET.html">DET</a></tt>-<tt><a href="de_gsd-pos-PRON.html">PRON</a></tt> (2; 0% instances), <tt><a href="de_gsd-pos-ADP.html">ADP</a></tt>-<tt><a href="de_gsd-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="de_gsd-pos-ADV.html">ADV</a></tt>-<tt><a href="de_gsd-pos-PROPN.html">PROPN</a></tt> (1; 0% instances), <tt><a href="de_gsd-pos-INTJ.html">INTJ</a></tt>-<tt><a href="de_gsd-pos-PRON.html">PRON</a></tt> (1; 0% instances), <tt><a href="de_gsd-pos-PART.html">PART</a></tt>-<tt><a href="de_gsd-pos-NOUN.html">NOUN</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 5 obl:arg	color:blue
1	Kann	können	AUX	VMFIN	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	8	aux	_	_
2	mich	ich	PRON	PPER	Case=Acc|Number=Sing|Person=1|PronType=Prs	8	obj	_	_
3	der	der	DET	ART	Case=Dat|Definite=Def|Gender=Fem|Number=Sing|PronType=Art	5	det	_	_
4	ersten	erst	ADJ	ADJA	Case=Dat|Degree=Pos|Gender=Fem|Number=Sing|NumType=Ord	5	amod	_	_
5	Bewertung	Bewertung	NOUN	NN	Case=Dat|Gender=Fem|Number=Sing	8	obl:arg	_	_
6	überhaupt	überhaupt	ADV	ADV	_	7	advmod	_	_
7	nicht	nicht	PART	PTKNEG	Polarity=Neg	8	advmod	_	_
8	anschließen	anschließen	VERB	VVINF	VerbForm=Inf	0	root	_	SpaceAfter=No
9	.	.	PUNCT	$.	_	8	punct	_	_

~~~


~~~ conllu
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 13	bgColor:blue
# visual-style 13	fgColor:white
# visual-style 13 9 obl:arg	color:blue
1	Also	also	ADV	ADV	_	3	advmod	_	_
2	ich	ich	PRON	PPER	Case=Nom|Number=Sing|Person=1|PronType=Prs	3	nsubj	_	_
3	bin	sein	VERB	VAFIN	Mood=Ind|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin	0	root	_	_
4	öfter	öfter	ADV	ADV	_	3	advmod	_	_
5	hier	hier	ADV	ADV	_	3	advmod	_	SpaceAfter=No
6	,	,	PUNCT	$,	_	13	punct	_	_
7	da	da	SCONJ	KOUS	_	13	mark	_	_
8	es	es	PRON	PPER	Case=Nom|Gender=Neut|Number=Sing|Person=3|PronType=Prs	13	nsubj	_	_
9	mir	ich	PRON	PPER	Case=Dat|Number=Sing|Person=1|PronType=Prs	13	obl:arg	_	_
10	hier	hier	ADV	ADV	_	13	advmod	_	_
11	sehr	sehr	ADV	ADV	_	12	advmod	_	_
12	gut	gut	ADV	ADJD	_	13	advmod	_	_
13	gefällt	fällen	VERB	VVFIN	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	3	advcl	_	SpaceAfter=No
14	!	!	PUNCT	$.	_	3	punct	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 4 obl:arg	color:blue
1	Die	der	DET	ART	Case=Nom|Definite=Def|Gender=Fem|Number=Sing|PronType=Art	2	det	_	_
2	SPD	SPD	PROPN	NE	Case=Nom|Gender=Fem|Number=Sing	3	nsubj	_	NamedEntity=Yes
3	begegnet	begegnen	VERB	VVFIN	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
4	Lafontaine	Lafontaine	PROPN	NE	Case=Dat|Gender=Masc|Number=Sing	3	obl:arg	_	NamedEntity=Yes
5	skeptisch	skeptisch	ADV	ADJD	_	3	advmod	_	SpaceAfter=No
6	.	.	PUNCT	$.	_	3	punct	_	_

~~~


