---
layout: base
title:  'Statistics of obl:tmod in UD_Skolt_Sami-Giellagas'
udver: '2'
---

## Treebank Statistics: UD_Skolt_Sami-Giellagas: Relations: `obl:tmod`

This relation is a language-specific subtype of <tt><a href="sms_giellagas-dep-obl.html">obl</a></tt>.
There are also 2 other language-specific subtypes of `obl`: <tt><a href="sms_giellagas-dep-obl-agent.html">obl:agent</a></tt>, <tt><a href="sms_giellagas-dep-obl-lmod.html">obl:lmod</a></tt>.

15 nodes (1%) are attached to their parents as `obl:tmod`.

10 instances of `obl:tmod` (67%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.93333333333333.

The following 3 pairs of parts of speech are connected with `obl:tmod`: <tt><a href="sms_giellagas-pos-VERB.html">VERB</a></tt>-<tt><a href="sms_giellagas-pos-NOUN.html">NOUN</a></tt> (13; 87% instances), <tt><a href="sms_giellagas-pos-AUX.html">AUX</a></tt>-<tt><a href="sms_giellagas-pos-NOUN.html">NOUN</a></tt> (1; 7% instances), <tt><a href="sms_giellagas-pos-NOUN.html">NOUN</a></tt>-<tt><a href="sms_giellagas-pos-NOUN.html">NOUN</a></tt> (1; 7% instances).


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 4 obl:tmod	color:blue
1	teʹl	teʹl	ADV	Adv	_	2	advmod:tmod	_	_
2	piʹjje	piijjâd	VERB	V	Mood=Ind|Number=Plur|Person=3|Tense=Past	0	root	_	GTtags=Ind,Prt,Pl3
3	čiččâm	čiččâm	NUM	Num	Case=Nom|Number=Sing|NumType=Card	4	nummod	_	GTtags=Sg,Nom
4	ekka	eeʹǩǩ	NOUN	N	Case=Ill|Number=Sing	2	obl:tmod	_	GTtags=Sg,Ill
5	sluužba	sluuʹžb	NOUN	N	Case=Ill|Number=Sing	2	obl	_	GTtags=Sg,Ill|SpaceAfter=No
6	.	.	PUNCT	CLB	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 6 obl:tmod	color:blue
1	Suʹst	son	PRON	Pron	Case=Loc|Number=Sing|Person=3|PronType=Prs	4	obl:agent	_	GTtags=Pers,Sg3,Loc
2	leäi	leeʹd	AUX	V	Mood=Ind|Number=Sing|Person=3|Tense=Past	4	aux	_	GTtags=IV,Ind,Prt,Sg3
3	õlggâm	õlggâd	AUX	Aux	Aspect=Perf|VerbForm=Part	4	aux	_	GTtags=Act,PrfPrc
4	leeʹd	leeʹd	AUX	V	VerbForm=Inf	0	root	_	GTtags=IV,Inf
5	tõn	tõt	DET	Det	Case=Gen|Number=Sing|PronType=Dem	6	det	_	GTtags=Dem,Sg,Gen
6	peeiʹv	peiʹvv	NOUN	N	Case=Gen|Number=Sing	4	obl:tmod	_	GTtags=Sg,Gen
7	čååǥǥâʹttmen	čååǥǥâʹttmen	VERB	V	_	4	xcomp	_	_
8	vuõptees	vuõptt	NOUN	N	Case=Acc|Number=Plur|Number[psor]=Sing|Person[psor]=3	7	obj	_	GTtags=Pl,Acc,PxSg3|SpaceAfter=No
9	,	,	PUNCT	CLB	_	13	punct	_	_
10	leša	leša	CCONJ	CC	_	13	mark	_	_
11	mii	mii	PRON	Pron	Case=Nom|Number=Sing|PronType=Rel	13	nsubj	_	GTtags=Rel,Sg,Nom
12	leežž	leeʹd	AUX	Aux	Mood=Pot|Number=Sing|Person=3	13	aux	_	GTtags=IV,Pot,Sg3
13	šõddâm	šõddâd	VERB	V	Aspect=Perf|VerbForm=Part	4	advcl	_	GTtags=Act,PrfPrc
14	ǥu	ǥu	SCONJ	CS	_	18	mark	_	_
15	ij	ij	AUX	Aux	Mood=Ind|Number=Sing|Person=3|Polarity=Neg	18	aux	_	GTtags=Neg,Ind,Sg3
16	tâʹl	tâʹl	ADV	Adv	AdvType=Tim	18	advmod:tmod	_	GTtags=Sem/Time
17	ni	ni	PART	Pcle	_	18	advmod:neg	_	_
18	vuäittam	vueiʹtted	VERB	V	Aspect=Perf|VerbForm=Part	13	advcl	_	GTtags=Act,PrfPrc|SpaceAfter=No
19	.	.	PUNCT	CLB	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 5 obl:tmod	color:blue
1	Na	na	INTJ	Interj	_	8	discourse	_	GTtags=Interj
2	teʹl	teʹl	ADV	Adv	_	8	advmod:tmod	_	_
3	âʹtte	âʹtte	ADV	Adv	AdvType=Tim	2	advmod:tmod	_	GTtags=Sem/Time
4	čiččâm	čiččâm	NUM	Num	Case=Nom|Number=Sing|NumType=Card	5	nummod	_	GTtags=Sg,Nom
5	eeʹjj	eeʹǩǩ	NOUN	N	Case=Acc|Number=Sing	8	obl:tmod	_	GTtags=Sg,Acc
6	feʹrttji	feʹrttjed	AUX	Aux	Mood=Ind|Number=Sing|Person=3|Tense=Past	8	aux	_	GTtags=Ind,Prt,Sg3
7	leeʹd	leeʹd	AUX	V	VerbForm=Inf	8	cop	_	GTtags=IV,Inf
8	säldten	säldten	NOUN	N	Case=Ess	0	root	_	GTtags=Ess
9	ja	ja	CCONJ	CC	_	11	cc	_	_
10	vasta	vasta	ADV	Adv	_	11	advmod:tmod	_	_
11	puätt	pueʹtted	VERB	V	Mood=Ind|Number=Sing|Person=3|Tense=Pres	8	conj	_	GTtags=Ind,Prs,Sg3
12	mååust	mååust	ADV	Adv	_	11	advmod:lmod	_	SpaceAfter=No
13	.	.	PUNCT	CLB	_	8	punct	_	_

~~~


