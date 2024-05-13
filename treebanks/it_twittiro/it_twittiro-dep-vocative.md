---
layout: base
title:  'Statistics of vocative in UD_Italian-TWITTIRO'
udver: '2'
---

## Treebank Statistics: UD_Italian-TWITTIRO: Relations: `vocative`

This relation is universal.
There are 1 language-specific subtypes of `vocative`: <tt><a href="it_twittiro-dep-vocative-mention.html">vocative:mention</a></tt>.

63 nodes (0%) are attached to their parents as `vocative`.

44 instances of `vocative` (70%) are right-to-left (child precedes parent).
Average distance between parent and child is 3.92063492063492.

The following 15 pairs of parts of speech are connected with `vocative`: <tt><a href="it_twittiro-pos-VERB.html">VERB</a></tt>-<tt><a href="it_twittiro-pos-PROPN.html">PROPN</a></tt> (18; 29% instances), <tt><a href="it_twittiro-pos-VERB.html">VERB</a></tt>-<tt><a href="it_twittiro-pos-NOUN.html">NOUN</a></tt> (17; 27% instances), <tt><a href="it_twittiro-pos-NOUN.html">NOUN</a></tt>-<tt><a href="it_twittiro-pos-NOUN.html">NOUN</a></tt> (5; 8% instances), <tt><a href="it_twittiro-pos-NOUN.html">NOUN</a></tt>-<tt><a href="it_twittiro-pos-PROPN.html">PROPN</a></tt> (4; 6% instances), <tt><a href="it_twittiro-pos-ADJ.html">ADJ</a></tt>-<tt><a href="it_twittiro-pos-PROPN.html">PROPN</a></tt> (3; 5% instances), <tt><a href="it_twittiro-pos-INTJ.html">INTJ</a></tt>-<tt><a href="it_twittiro-pos-NOUN.html">NOUN</a></tt> (3; 5% instances), <tt><a href="it_twittiro-pos-VERB.html">VERB</a></tt>-<tt><a href="it_twittiro-pos-SYM.html">SYM</a></tt> (3; 5% instances), <tt><a href="it_twittiro-pos-ADJ.html">ADJ</a></tt>-<tt><a href="it_twittiro-pos-NOUN.html">NOUN</a></tt> (2; 3% instances), <tt><a href="it_twittiro-pos-NOUN.html">NOUN</a></tt>-<tt><a href="it_twittiro-pos-SYM.html">SYM</a></tt> (2; 3% instances), <tt><a href="it_twittiro-pos-ADJ.html">ADJ</a></tt>-<tt><a href="it_twittiro-pos-SYM.html">SYM</a></tt> (1; 2% instances), <tt><a href="it_twittiro-pos-INTJ.html">INTJ</a></tt>-<tt><a href="it_twittiro-pos-PROPN.html">PROPN</a></tt> (1; 2% instances), <tt><a href="it_twittiro-pos-PRON.html">PRON</a></tt>-<tt><a href="it_twittiro-pos-NOUN.html">NOUN</a></tt> (1; 2% instances), <tt><a href="it_twittiro-pos-PROPN.html">PROPN</a></tt>-<tt><a href="it_twittiro-pos-NOUN.html">NOUN</a></tt> (1; 2% instances), <tt><a href="it_twittiro-pos-SYM.html">SYM</a></tt>-<tt><a href="it_twittiro-pos-SYM.html">SYM</a></tt> (1; 2% instances), <tt><a href="it_twittiro-pos-VERB.html">VERB</a></tt>-<tt><a href="it_twittiro-pos-SCONJ.html">SCONJ</a></tt> (1; 2% instances).


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 1 vocative	color:blue
1	Mario	mario	PROPN	SP	_	4	vocative	_	_
2	Monti	Monti	PROPN	SP	_	1	flat:name	_	_
3	non	non	ADV	BN	PronType=Neg	4	advmod	_	_
4	vuoi	volere	VERB	V	Mood=Ind|Number=Sing|Person=2|Tense=Pres|VerbForm=Fin	0	root	_	_
5	una	uno	DET	RI	Definite=Ind|Gender=Fem|Number=Sing|PronType=Art	6	det	_	_
6	nipotina	nipote	NOUN	S	Gender=Fem|Number=Sing	4	obj	_	SpaceAfter=No
7	?	?	PUNCT	FS	_	4	punct	_	_
8	#ADOTTAMI	#ADOTTAMI	SYM	SYM	_	4	parataxis:hashtag	_	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 1 vocative	color:blue
1	Governo	governo	NOUN	S	Gender=Masc|Number=Sing	6	vocative	_	_
2	Monti	Monti	PROPN	SP	_	1	nmod	_	SpaceAfter=No
3	,	,	PUNCT	FF	_	1	punct	_	_
4	tu	tu	PRON	PE	Number=Sing|Person=2|PronType=Prs	6	nsubj	_	_
5	Ci	ci	PRON	PC	Clitic=Yes|Number=Plur|Person=1|PronType=Prs	6	obj	_	_
6	SMONTI	smontare	VERB	V	Mood=Ind|Number=Sing|Person=2|Tense=Pres|VerbForm=Fin	0	root	_	_
7	!.	!.	PUNCT	FS	_	6	punct	_	_
8	By	By	ADP	E	_	9	case	_	_
9	Luigi	luigi	PROPN	SP	_	6	parataxis	_	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 2 vocative	color:blue
1	@user	@user	SYM	SYM	_	11	vocative:mention	_	_
2	Ragazzi	ragazzo	NOUN	S	Gender=Masc|Number=Plur	3	vocative	_	_
3	calma	calma	NOUN	S	Gender=Fem|Number=Sing	11	discourse	_	SpaceAfter=No
4	,	,	PUNCT	FF	_	3	punct	_	_
5	il	il	DET	RD	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	6	det	_	_
6	Prof.	professore	NOUN	S	Number=Sing	11	nsubj	_	_
7	Mario	mario	PROPN	SP	_	6	appos	_	_
8	Monti	Monti	PROPN	SP	_	7	flat:name	_	_
9	se	se	PRON	PC	Clitic=Yes|Person=3|PronType=Prs	11	expl	_	_
10	la	la	PRON	PC	Clitic=Yes|Gender=Fem|Number=Sing|Person=3|PronType=Prs	11	obj	_	_
11	cava	cavare	VERB	V	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
12	da	da	ADP	E	_	13	case	_	_
13	solo	solo	ADJ	A	Gender=Masc|Number=Sing	11	advmod	_	SpaceAfter=No
14	:	:	PUNCT	FC	_	11	punct	_	_
15	e'	essere	AUX	V	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	16	cop	_	_
16	bocconiano	bocconiano	ADJ	A	Gender=Masc|Number=Sing	11	parataxis	_	SpaceAfter=No
17	,	,	PUNCT	FF	_	19	punct	_	_
18	mica	mica	ADV	B	_	19	advmod	_	_
19	bocchiniano	bocchiniano	ADJ	A	Gender=Masc|Number=Sing	16	conj	_	SpaceAfter=No
20	!	!	PUNCT	FS	_	11	punct	_	_
21	;)	;)	SYM	SYM	_	11	discourse:emo	_	_
22	by	by	ADP	E	_	23	case	_	_
23	rao	rao	PROPN	SP	_	11	parataxis	_	_

~~~


