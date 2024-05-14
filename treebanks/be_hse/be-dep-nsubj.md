---
layout: base
title:  'Statistics of nsubj in UD_Belarusian'
udver: '2'
---

## Treebank Statistics: UD_Belarusian: Relations: `nsubj`

This relation is universal.
There are 1 language-specific subtypes of `nsubj`: <tt><a href="be-dep-nsubj-pass.html">nsubj:pass</a></tt>.

575 nodes (7%) are attached to their parents as `nsubj`.

432 instances of `nsubj` (75%) are right-to-left (child precedes parent).
Average distance between parent and child is 2.72869565217391.

The following 20 pairs of parts of speech are connected with `nsubj`: <tt><a href="be-pos-VERB.html">VERB</a></tt>-<tt><a href="be-pos-NOUN.html">NOUN</a></tt> (273; 47% instances), <tt><a href="be-pos-VERB.html">VERB</a></tt>-<tt><a href="be-pos-PRON.html">PRON</a></tt> (130; 23% instances), <tt><a href="be-pos-VERB.html">VERB</a></tt>-<tt><a href="be-pos-PROPN.html">PROPN</a></tt> (84; 15% instances), <tt><a href="be-pos-ADJ.html">ADJ</a></tt>-<tt><a href="be-pos-NOUN.html">NOUN</a></tt> (20; 3% instances), <tt><a href="be-pos-ADJ.html">ADJ</a></tt>-<tt><a href="be-pos-PRON.html">PRON</a></tt> (20; 3% instances), <tt><a href="be-pos-NOUN.html">NOUN</a></tt>-<tt><a href="be-pos-NOUN.html">NOUN</a></tt> (19; 3% instances), <tt><a href="be-pos-NOUN.html">NOUN</a></tt>-<tt><a href="be-pos-PRON.html">PRON</a></tt> (9; 2% instances), <tt><a href="be-pos-PRON.html">PRON</a></tt>-<tt><a href="be-pos-ADJ.html">ADJ</a></tt> (3; 1% instances), <tt><a href="be-pos-VERB.html">VERB</a></tt>-<tt><a href="be-pos-ADJ.html">ADJ</a></tt> (3; 1% instances), <tt><a href="be-pos-ADJ.html">ADJ</a></tt>-<tt><a href="be-pos-PROPN.html">PROPN</a></tt> (2; 0% instances), <tt><a href="be-pos-ADV.html">ADV</a></tt>-<tt><a href="be-pos-PRON.html">PRON</a></tt> (2; 0% instances), <tt><a href="be-pos-VERB.html">VERB</a></tt>-<tt><a href="be-pos-X.html">X</a></tt> (2; 0% instances), <tt><a href="be-pos-ADJ.html">ADJ</a></tt>-<tt><a href="be-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="be-pos-ADJ.html">ADJ</a></tt>-<tt><a href="be-pos-NUM.html">NUM</a></tt> (1; 0% instances), <tt><a href="be-pos-ADV.html">ADV</a></tt>-<tt><a href="be-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="be-pos-CCONJ.html">CCONJ</a></tt>-<tt><a href="be-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="be-pos-PART.html">PART</a></tt>-<tt><a href="be-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="be-pos-PRON.html">PRON</a></tt>-<tt><a href="be-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="be-pos-VERB.html">VERB</a></tt>-<tt><a href="be-pos-NUM.html">NUM</a></tt> (1; 0% instances), <tt><a href="be-pos-X.html">X</a></tt>-<tt><a href="be-pos-NOUN.html">NOUN</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 3 nsubj	color:blue
1	У	у	ADP	IN	_	2	case	_	_
2	лютым	люты	NOUN	NN	Animacy=Inan|Case=Loc|Gender=Masc|Number=Sing	6	obl	_	_
3	беларусы	беларус	NOUN	NN	Animacy=Anim|Case=Nom|Gender=Masc|Number=Plur	6	nsubj	_	_
4	ў	ў	ADP	IN	_	5	case	_	_
5	сярэднім	сярэдняе	NOUN	NN	Animacy=Inan|Case=Loc|Gender=Neut|Number=Sing	6	obl	_	_
6	атрымлівалі	атрымліваць	VERB	VBC	Aspect=Imp|Mood=Ind|Number=Plur|Tense=Past|VerbForm=Fin|Voice=Act	0	root	_	_
7	370	370	NUM	CD	Case=Acc|NumType=Card	8	nummod:gov	_	_
8	даляраў	даляр	NOUN	NN	Animacy=Inan|Case=Gen|Gender=Masc|Number=Plur	6	obj	_	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 2 nsubj	color:blue
1	"	"	PUNCT	PUNCT	_	4	punct	_	SpaceAfter=No
2	Мы	мы	PRON	PRP	Case=Nom|Number=Plur|Person=1|PronType=Prs	4	nsubj	_	_
3	часта	часта	ADV	RB	Degree=Pos	4	advmod	_	_
4	рухаемся	рухацца	VERB	VBC	Aspect=Imp|Mood=Ind|Number=Plur|Person=1|Tense=Pres|VerbForm=Fin|Voice=Mid	0	root	_	_
5	дзесьці	дзесьці	ADV	RB	Degree=Pos	9	advmod	_	_
6	паміж	паміж	ADP	IN	_	9	case	_	_
7	гэтымі	гэты	DET	DT	Case=Ins|Number=Plur|PronType=Dem	9	det	_	_
8	двума	два	NUM	CD	Case=Ins|Gender=Masc|NumType=Card	9	nummod	_	_
9	падыходамі	падыход	NOUN	NN	Animacy=Inan|Case=Ins|Gender=Masc|Number=Plur	4	obl	_	SpaceAfter=No
10	.	.	PUNCT	PUNCT	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 3 nsubj	color:blue
1	Эштан	эштан	PROPN	NNP	Animacy=Anim|Case=Nom|Gender=Fem|Number=Sing	0	root	_	SpaceAfter=No
2	:	:	PUNCT	PUNCT	_	4	punct	_	_
3	ЕС	ес	PROPN	NNP	Animacy=Inan|Case=Nom|Gender=Masc|Number=Sing	4	nsubj	_	_
4	пасылае	пасылаць	VERB	VBC	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	1	parataxis	_	_
5	ясны	ясны	ADJ	JJL	Animacy=Inan|Case=Acc|Degree=Pos|Gender=Masc|Number=Sing	6	amod	_	_
6	сігнал	сігнал	NOUN	NN	Animacy=Inan|Case=Acc|Gender=Masc|Number=Sing	4	obj	_	_
7	Беларусі	беларусь	PROPN	NNP	Animacy=Inan|Case=Dat|Gender=Fem|Number=Sing	4	iobj	_	_

~~~


