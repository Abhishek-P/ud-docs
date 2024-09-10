---
layout: base
title:  'Statistics of mark in UD_Skolt_Sami-Giellagas'
udver: '2'
---

## Treebank Statistics: UD_Skolt_Sami-Giellagas: Relations: `mark`

This relation is universal.

59 nodes (2%) are attached to their parents as `mark`.

58 instances of `mark` (98%) are right-to-left (child precedes parent).
Average distance between parent and child is 2.54237288135593.

The following 10 pairs of parts of speech are connected with `mark`: <tt><a href="sms_giellagas-pos-VERB.html">VERB</a></tt>-<tt><a href="sms_giellagas-pos-SCONJ.html">SCONJ</a></tt> (41; 69% instances), <tt><a href="sms_giellagas-pos-AUX.html">AUX</a></tt>-<tt><a href="sms_giellagas-pos-SCONJ.html">SCONJ</a></tt> (5; 8% instances), <tt><a href="sms_giellagas-pos-ADJ.html">ADJ</a></tt>-<tt><a href="sms_giellagas-pos-SCONJ.html">SCONJ</a></tt> (3; 5% instances), <tt><a href="sms_giellagas-pos-VERB.html">VERB</a></tt>-<tt><a href="sms_giellagas-pos-CCONJ.html">CCONJ</a></tt> (3; 5% instances), <tt><a href="sms_giellagas-pos-PRON.html">PRON</a></tt>-<tt><a href="sms_giellagas-pos-SCONJ.html">SCONJ</a></tt> (2; 3% instances), <tt><a href="sms_giellagas-pos-ADV.html">ADV</a></tt>-<tt><a href="sms_giellagas-pos-SCONJ.html">SCONJ</a></tt> (1; 2% instances), <tt><a href="sms_giellagas-pos-NOUN.html">NOUN</a></tt>-<tt><a href="sms_giellagas-pos-ADV.html">ADV</a></tt> (1; 2% instances), <tt><a href="sms_giellagas-pos-PRON.html">PRON</a></tt>-<tt><a href="sms_giellagas-pos-ADV.html">ADV</a></tt> (1; 2% instances), <tt><a href="sms_giellagas-pos-PROPN.html">PROPN</a></tt>-<tt><a href="sms_giellagas-pos-SCONJ.html">SCONJ</a></tt> (1; 2% instances), <tt><a href="sms_giellagas-pos-VERB.html">VERB</a></tt>-<tt><a href="sms_giellagas-pos-ADV.html">ADV</a></tt> (1; 2% instances).


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 4 mark	color:blue
1	Källsaž	källsaž	NOUN	N	Case=Nom|Number=Sing	2	nsubj	_	GTtags=Sg,Nom
2	ceälkk	ceäʹlǩǩed	VERB	V	Mood=Ind|Number=Sing|Person=3|Tense=Pres	0	root	_	GTtags=Ind,Prs,Sg3
3	tõt	tõt	PRON	Pron	Case=Nom|Number=Sing|PronType=Dem	2	obl	_	GTtags=Dem,Sg,Nom
4	što	što	SCONJ	CS	_	8	mark	_	_
5	”	”	PUNCT	PUNCT	_	8	punct	_	GTtags=RIGHT|SpaceAfter=No
6	ååʹn	ååʹn	ADV	Adv	AdvType=Tim	8	advmod:tmod	_	GTtags=Sem/Time
7	muännaid	mon	PRON	Pron	Case=Acc|Number=Dual|Person=1|PronType=Prs	8	obj	_	GTtags=Pers,Du1,Acc
8	kåʹdde	kåʹdded	VERB	V	Mood=Ind|Number=Plur|Person=3|Tense=Pres	2	ccomp	_	GTtags=Ind,Prs,Pl3|SpaceAfter=No
9	”	”	PUNCT	PUNCT	_	8	punct	_	GTtags=RIGHT|SpaceAfter=No
10	.	.	PUNCT	PUNCT	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 3 mark	color:blue
1	A	a	CCONJ	CC	_	10	cc	_	_
2	kååʹtt	kååʹtt	PRON	Pron	Case=Nom|Number=Sing|PronType=Rel	10	nsubj	_	GTtags=Rel,Sg,Nom
3	ko	ko	SCONJ	CS	_	4	mark	_	GTtags=@CVP
4	lij	leeʹd	AUX	V	Mood=Ind|Number=Sing|Person=3|Tense=Pres	10	reparandum	_	GTtags=Ind,Prs,Sg3,@+FMAINV|SpaceAfter=No
5	...	...	PUNCT	CLB	_	4	punct	_	_
6	nuʹt	nuʹtt	ADV	Adv	_	10	advmod	_	GTtags=Err/Orth,@ADVL>
7	še	še	ADV	Adv	_	6	discourse	_	GTtags=@ADVL>
8	lij	leeʹd	AUX	V	Mood=Ind|Number=Sing|Person=3|Tense=Pres	10	cop	_	GTtags=Ind,Prs,Sg3,@+FMAINV
9	kaađâš	kaađâš	ADJ	A	_	10	amod	_	_
10	ooumaž	ooumaž	NOUN	N	Animacy=Hum|Case=Nom|Number=Sing	0	root	_	GTtags=Sem/Hum,Sg,Nom,@<SUBJ
11	ko	ko	SCONJ	CS	_	17	mark	_	GTtags=@CVP
12	lij	leeʹd	AUX	V	Mood=Ind|Number=Sing|Person=3|Tense=Pres	17	cop	_	GTtags=Ind,Prs,Sg3,@+FMAINV
13	što	što	SCONJ	CS	_	17	mark	_	GTtags=@CVP
14	”	”	PUNCT	PUNCT	_	17	punct	_	GTtags=RIGHT|SpaceAfter=No
15	mon	mon	PRON	Pron	Case=Nom|Number=Sing|Person=1|PronType=Prs	17	nsubj	_	GTtags=Pers,Sg1,Nom
16	puk-i	puk	PRON	Pron	Case=Nom|Clitic=AddI|Number=Sing	17	obj	_	GTtags=Pron,Sg,Nom,Clt
17	vääldam	väʹldded	VERB	V	Mood=Ind|Number=Sing|Person=1|Tense=Pres	10	conj	_	GTtags=Ind,Prs,Sg1,@+FMAINV|SpaceAfter=No
18	”	”	PUNCT	PUNCT	_	17	punct	_	GTtags=RIGHT|SpaceAfter=No
19	.	.	PUNCT	CLB	_	10	punct	_	_

~~~


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 10 6 mark	color:blue
1	Jiõm	ij	AUX	Aux	Mood=Ind|Number=Sing|Person=1|Polarity=Neg	2	aux:neg	_	GTtags=Neg,Ind,Sg1
2	pâsttam	pâʹstted	VERB	Aux	Connegative=Yes|Mood=Ind|Tense=Past	0	root	_	GTtags=Ind,Prt,ConNeg
3	seuʹrrjed	seuʹrrjed	VERB	V	VerbForm=Inf	2	xcomp	_	GTtags=Inf
4	suu	son	PRON	Pron	Case=Gen|Number=Sing|Person=3|PronType=Prs	5	det	_	GTtags=Pers,Sg3,Gen
5	urččmõõžž	urččmõš	NOUN	N	Case=Acc|Number=Sing	3	obj	_	GTtags=Sg,Acc
6	ǥu	ǥu	SCONJ	CS	_	10	mark	_	_
7	son	son	PRON	Pron	Case=Nom|Number=Sing|Person=3|PronType=Prs	10	nsubj	_	GTtags=Pers,Sg3,Nom
8	leäi	leeʹd	AUX	Aux	Mood=Ind|Number=Sing|Person=3|Tense=Past	10	cop	_	GTtags=IV,Ind,Prt,Sg3
9	samai	samai	ADV	Adv	_	10	advmod:deg	_	_
10	jåʹttel	jåʹttel	ADJ	A	Case=Nom|Number=Sing	2	advcl	_	GTtags=Sg,Nom|SpaceAfter=No
11	.	.	PUNCT	CLB	_	2	punct	_	_

~~~


