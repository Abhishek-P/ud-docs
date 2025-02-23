---
layout: base
title:  'Statistics of vocative in UD_Cappadocian-AMGiC'
udver: '2'
---

## Treebank Statistics: UD_Cappadocian-AMGiC: Relations: `vocative`

This relation is universal.

5 nodes (1%) are attached to their parents as `vocative`.

5 instances of `vocative` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 4.

The following 4 pairs of parts of speech are connected with `vocative`: <tt><a href="cpg_amgic-pos-VERB.html">VERB</a></tt>-<tt><a href="cpg_amgic-pos-NOUN.html">NOUN</a></tt> (2; 40% instances), <tt><a href="cpg_amgic-pos-ADV.html">ADV</a></tt>-<tt><a href="cpg_amgic-pos-NOUN.html">NOUN</a></tt> (1; 20% instances), <tt><a href="cpg_amgic-pos-PROPN.html">PROPN</a></tt>-<tt><a href="cpg_amgic-pos-NOUN.html">NOUN</a></tt> (1; 20% instances), <tt><a href="cpg_amgic-pos-VERB.html">VERB</a></tt>-<tt><a href="cpg_amgic-pos-PROPN.html">PROPN</a></tt> (1; 20% instances).


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 3 vocative	color:blue
1	fikirsúzis	fikirsúzis	ADJ	ADJ	Case=Voc|Gender=Masc|Number=Sing	3	amod	_	OrigLang=tr|#Turkish_fikirsiz_derivative_morph_copied?
2	mu	(e)γó	PRON	PRON	Case=Gen|Clitic=Yes|Number=Sing|Person=1|Poss=Yes|PronType=Prs	3	nmod	_	_
3	ádras	ádras	NOUN	NOUN	Case=Voc|Gender=Masc|Number=Sing	8	vocative	_	_
4	tiyá	tiás	DET	DET	Case=Acc|Gender=Neut|Number=Sing	5	det	_	_
5	kalaǰí	kalaǰí	NOUN	NOUN	Case=Acc|Gender=Neut|Number=Sing	8	obj	_	_
6	ne	ne	PRON	Ques	_	7	obl	_	Foreign=Yes|Lang=tr
7	deyí	deyí	ADP	_	_	8	case	_	Foreign=Yes|Lang=tr
8	ípis	léghu	VERB	VERB	Aspect=Perf|Mood=Ind|Number=Sing|Person=2|Tense=Past|VerbForm=Fin|Voice=Act	0	root	_	_
9	ta	(e)γó	PRON	PRON	Case=Acc|Gender=Neut|Number=Sing|Person=3|PronType=Prs	8	obj	_	#weak_clitic_form_double_cliting
10	mi	mi	AUX	_	_	8	aux:q	_	LC=YES|MorphSynC=Part,FrGrEl,QPart|Orig=mI|OrigLang=tr|SpaceAfter=No
11	?	?	PUNCT	PUNCT	_	8	punct	_	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 1 vocative	color:blue
1	mána	mána	NOUN	NOUN	Case=Voc|Gender=Fem|Number=Sing	7	vocative	_	_
2	deyí	deyí	SCONJ	_	_	7	mark	_	LC=YES|MorphSynC=FrGrEl|MorphSynSC=ConjSub|Orig=diye(<deyü)|OrigLang=tr|SpaceAfter=No
3	,	,	PUNCT	PUNCT	_	4	punct	_	_
4	baγərdά	baγərdó	VERB	VERB	_	0	root	_	Orig=bağırmak|OrigLang=tr
5	či	(e)γó	PRON	PRON	Case=Acc|Clitic=Yes|Gender=Fem|Number=Sing|Person=3|PronType=Prs	4	obj	_	SpaceAfter=No
6	,	,	PUNCT	PUNCT	_	4	punct	_	_
7	put'	put'	ADV	_	_	4	advcl	_	_
8	ísu	ímu	AUX	_	Mood=Ind|Number=Sing|Person=2|Tense=Pres|VerbForm=Fin	7	cop	_	SpaceAfter=No
9	.	.	PUNCT	PUNCT	_	7	punct	_	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 12	bgColor:blue
# visual-style 12	fgColor:white
# visual-style 12 8 vocative	color:blue
1	ítan	ímu	VERB	VERB	_	0	root	_	#existential_meaning_"there_was"
2	éna	ís	DET	DET	Case=Nom|Definite=Ind|Gender=Neut|Number=Sing|PronType=Art	4	det	_	_#Differential_Subject_Marking?
3	yerasméni	yerasménos	ADJ	ADJ	Case=Nom|Gender=Fem|Number=Sing	4	amod	_	_
4	néka	(e)néka	NOUN	NOUN	Case=Nom|Gender=Fem|Number=Sing	1	nsubj	_	SpaceAfter=No
5	,	,	PUNCT	_	_	1	punct	_	_
6	léi	léghu	VERB	VERB	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	1	parataxis	_	SpaceAfter=No
7	,	,	PUNCT	PUNCT	_	6	punct	_	_
8	ǰaním	ǰaním	NOUN	_	Case=Voc|Number=Sing	12	vocative	_	Orig=canım|OrigLang=tr|SpaceAfter=No
9	,	,	PUNCT	PUNCT	_	8	punct	_	_
10	A	ághius	ADJ	ADJ	Case=Voc|Gender=Masc|Number=Sing	12	amod	_	SpaceAfter=No
11	-	-	PUNCT	PUNCT	_	12	punct	_	SpaceAfter=No
12	Yóryis	Yóryis	PROPN	PROPN	Case=Voc|Gender=Masc|Number=Sing	15	vocative	_	_
13	mu	(e)γó	PRON	PRON	Case=Gen|Clitic=Yes|Number=Sing|Person=1|Poss=Yes|PronType=Prs	12	nmod	_	SpaceAfter=No
14	,	,	PUNCT	PUNCT	_	12	punct	_	_
15	írtis	érkhumu	VERB	VERB	Aspect=Perf|Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin|Voice=Pass	6	parataxis	_	#non_embedded
16	ro	ro	ADV	ADV	_	15	advmod	_	_
17	m'	mi	AUX	_	_	15	aux:q	_	LC=YES|MorphSynC=FrGrM|MorphSynSC=QPart|Orig=mI|OrigLang=tr
18	ki	ki	ADV	_	_	15	advmod:emph	_	LC=YES|MorphSynC=FrGrM|MorphSynSC=EmphPart|SpaceAfter=No
19	?	?	PUNCT	PUNCT	_	15	punct	_	_

~~~


