---
layout: base
title:  'Statistics of csubj:pass in UD_Latvian-LVTB'
udver: '2'
---

## Treebank Statistics: UD_Latvian-LVTB: Relations: `csubj:pass`

This relation is a language-specific subtype of <tt><a href="lv_lvtb-dep-csubj.html">csubj</a></tt>.

138 nodes (0%) are attached to their parents as `csubj:pass`.

131 instances of `csubj:pass` (95%) are left-to-right (parent precedes child).
Average distance between parent and child is 5.7463768115942.

The following 7 pairs of parts of speech are connected with `csubj:pass`: <tt><a href="lv_lvtb-pos-VERB.html">VERB</a></tt>-<tt><a href="lv_lvtb-pos-VERB.html">VERB</a></tt> (122; 88% instances), <tt><a href="lv_lvtb-pos-VERB.html">VERB</a></tt>-<tt><a href="lv_lvtb-pos-NOUN.html">NOUN</a></tt> (9; 7% instances), <tt><a href="lv_lvtb-pos-VERB.html">VERB</a></tt>-<tt><a href="lv_lvtb-pos-ADJ.html">ADJ</a></tt> (3; 2% instances), <tt><a href="lv_lvtb-pos-ADJ.html">ADJ</a></tt>-<tt><a href="lv_lvtb-pos-VERB.html">VERB</a></tt> (1; 1% instances), <tt><a href="lv_lvtb-pos-VERB.html">VERB</a></tt>-<tt><a href="lv_lvtb-pos-ADV.html">ADV</a></tt> (1; 1% instances), <tt><a href="lv_lvtb-pos-VERB.html">VERB</a></tt>-<tt><a href="lv_lvtb-pos-AUX.html">AUX</a></tt> (1; 1% instances), <tt><a href="lv_lvtb-pos-VERB.html">VERB</a></tt>-<tt><a href="lv_lvtb-pos-PRON.html">PRON</a></tt> (1; 1% instances).


~~~ conllu
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 10 csubj:pass	color:blue
1	Ja	ja	SCONJ	cs	_	3	mark	3:mark	LvtbNodeId=a-p10016-p5s5w1
2	viņš	viņš	PRON	pp3msnn	Case=Nom|Gender=Masc|Number=Sing|Person=3|PronType=Prs	3	nsubj	3:nsubj	LvtbNodeId=a-p10016-p5s5w2
3	strādā	strādāt	VERB	vmnipi230an	Evident=Fh|Mood=Ind|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	6	advcl	6:advcl	LvtbNodeId=a-p10016-p5s5w3|SpaceAfter=No
4	,	,	PUNCT	zc	_	3	punct	3:punct	LvtbNodeId=a-p10016-p5s5w4
5	tiek	tikt	AUX	vanipi130an	Evident=Fh|Mood=Ind|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	6	aux:pass	6:aux:pass	LvtbNodeId=a-p10016-p5s5w5
6	domāts	domāt	VERB	vmnpdmsnpsnpn	Aspect=Perf|Case=Nom|Definite=Ind|Degree=Pos|Gender=Masc|Number=Sing|Polarity=Pos|Tense=Past|VerbForm=Part|Voice=Pass	0	root	0:root	LvtbNodeId=a-p10016-p5s5w6|SpaceAfter=No
7	,	,	PUNCT	zc	_	10	punct	10:punct	LvtbNodeId=a-p10016-p5s5w7
8	kā	kā	SCONJ	cs	_	10	mark	10:mark	LvtbNodeId=a-p10016-p5s5w8
9	sodu	sods	NOUN	ncmsa1	Case=Acc|Gender=Masc|Number=Sing	10	obj	10:obj	LvtbNodeId=a-p10016-p5s5w9
10	apvienot	apvienot	VERB	vmnn0t2000n	Polarity=Pos|VerbForm=Inf	6	csubj:pass	6:csubj:pass	LvtbNodeId=a-p10016-p5s5w10
11	ar	ar	ADP	spsa	_	12	case	12:case	LvtbNodeId=a-p10016-p5s5w11
12	darbu	darbs	NOUN	ncmsa1	Case=Acc|Gender=Masc|Number=Sing	10	iobj	10:iobj	LvtbNodeId=a-p10016-p5s5w12|SpaceAfter=No
13	.	.	PUNCT	zs	_	6	punct	6:punct	LvtbNodeId=a-p10016-p5s5w13

~~~


~~~ conllu
# visual-style 21	bgColor:blue
# visual-style 21	fgColor:white
# visual-style 11	bgColor:blue
# visual-style 11	fgColor:white
# visual-style 11 21 csubj:pass	color:blue
1	Tajā	tas	DET	pd3msln	Case=Loc|Gender=Masc|Number=Sing|Person=3|PronType=Dem	3	det	3:det	LvtbNodeId=a-s93-p5s3w1
2	pašā	pats	DET	pg0msln	Case=Loc|Gender=Masc|Number=Sing|PronType=Tot	1	fixed	1:fixed	LvtbNodeId=a-s93-p5s3w2
3	laikā	laiks	NOUN	ncmsl1	Case=Loc|Gender=Masc|Number=Sing	5	obl	5:obl:loc	LvtbNodeId=a-s93-p5s3w3
4	mēs	mēs	PRON	pp10pnn	Case=Nom|Number=Plur|Person=1|PronType=Prs	5	nsubj	5:nsubj	LvtbNodeId=a-s93-p5s3w4
5	zinām	zināt	VERB	vmnipt31pan	Evident=Fh|Mood=Ind|Number=Plur|Person=1|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	0:root	LvtbNodeId=a-s93-p5s3w5|SpaceAfter=No
6	,	,	PUNCT	zc	_	11	punct	11:punct	LvtbNodeId=a-s93-p5s3w6
7	ka	ka	SCONJ	cs	_	11	mark	11:mark	LvtbNodeId=a-s93-p5s3w7
8	Satversmē	Satversme	PROPN	npfsl5	Case=Loc|Gender=Fem|Number=Sing	11	obl	11:obl:loc	LvtbNodeId=a-s93-p5s3w8
9	mums	mēs	PRON	pp10pdn	Case=Dat|Number=Plur|Person=1|PronType=Prs	11	iobj	11:iobj	LvtbNodeId=a-s93-p5s3w9
10	ir	būt	AUX	vcnipii30an	Evident=Fh|Mood=Ind|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	11	aux:pass	11:aux:pass	LvtbNodeId=a-s93-p5s3w10
11	pateikts	pateikt	VERB	vmnpdmsnpsnpn	Aspect=Perf|Case=Nom|Definite=Ind|Degree=Pos|Gender=Masc|Number=Sing|Polarity=Pos|Tense=Past|VerbForm=Part|Voice=Pass	5	ccomp	5:ccomp	LvtbNodeId=a-s93-p5s3w11|SpaceAfter=No
12	,	,	PUNCT	zc	_	21	punct	21:punct	LvtbNodeId=a-s93-p5s3w12
13	ka	ka	SCONJ	cs	_	21	mark	21:mark	LvtbNodeId=a-s93-p5s3w13
14	latviešu	latvietis	NOUN	ncmpg2	Case=Gen|Gender=Masc|Number=Plur	15	nmod	15:nmod:gen	LvtbNodeId=a-s93-p5s3w14
15	valoda	valoda	NOUN	ncfsn4	Case=Nom|Gender=Fem|Number=Sing	21	nsubj	21:nsubj	LvtbNodeId=a-s93-p5s3w15
16	ir	būt	AUX	vcnipii30an	Evident=Fh|Mood=Ind|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	21	cop	21:cop	LvtbNodeId=a-s93-p5s3w16
17	galvenā	galvenais	ADJ	arfsnyp	Case=Nom|Definite=Def|Degree=Pos|Gender=Fem|Number=Sing	21	amod	21:amod	LvtbNodeId=a-s93-p5s3w17
18	un	un	CCONJ	cc	_	19	cc	19:cc	LvtbNodeId=a-s93-p5s3w18
19	vienīgā	vienīgs	ADJ	arfsnyp	Case=Nom|Definite=Def|Degree=Pos|Gender=Fem|Number=Sing	17	conj	17:conj|21:amod	LvtbNodeId=a-s93-p5s3w19
20	valsts	valsts	NOUN	ncfsg6	Case=Gen|Gender=Fem|Number=Sing	21	nmod	21:nmod:gen	LvtbNodeId=a-s93-p5s3w20
21	valoda	valoda	NOUN	ncfsn4	Case=Nom|Gender=Fem|Number=Sing	11	csubj:pass	11:csubj:pass	LvtbNodeId=a-s93-p5s3w21|SpaceAfter=No
22	.	.	PUNCT	zs	_	5	punct	5:punct	LvtbNodeId=a-s93-p5s3w22

~~~


~~~ conllu
# visual-style 19	bgColor:blue
# visual-style 19	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 19 csubj:pass	color:blue
1	Secināts	secināt	VERB	vmnpdmsnpsnpn	Aspect=Perf|Case=Nom|Definite=Ind|Degree=Pos|Gender=Masc|Number=Sing|Polarity=Pos|Tense=Past|VerbForm=Part|Voice=Pass	0	root	0:root	LvtbNodeId=a-z25-p37s1w1|SpaceAfter=No
2	,	,	PUNCT	zc	_	19	punct	19:punct	LvtbNodeId=a-z25-p37s1w2
3	ka	ka	SCONJ	cs	_	19	mark	19:mark	CorrectionType=InsertedPunctAfter|LvtbNodeId=a-z25-p37s1w3
4	kaut	kaut	SCONJ	cs	_	9	mark	9:mark	LvtbNodeId=a-z25-p37s1w5
5	gan	gan	PART	q	_	4	fixed	4:fixed	LvtbNodeId=a-z25-p37s1w6
6	gaļas	gaļa	NOUN	ncfsg4	Case=Gen|Gender=Fem|Number=Sing	7	nmod	7:nmod:gen	LvtbNodeId=a-z25-p37s1w7
7	liellopu	liellops	NOUN	ncmpg1	Case=Gen|Gender=Masc|Number=Plur	8	nmod	8:nmod:gen	LvtbNodeId=a-z25-p37s1w8
8	skaits	skaits	NOUN	ncmsn1	Case=Nom|Gender=Masc|Number=Sing	9	nsubj	9:nsubj|10:nsubj	LvtbNodeId=a-z25-p37s1w9
9	turpina	turpināt	VERB	vpnipi330an	Evident=Fh|Mood=Ind|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	19	advcl	19:advcl	LvtbNodeId=a-z25-p37s1w10
10	pieaugt	pieaugt	VERB	vmnn0i1000n	Polarity=Pos|VerbForm=Inf	9	xcomp	9:xcomp	LvtbNodeId=a-z25-p37s1w11|SpaceAfter=No
11	,	,	PUNCT	zc	_	9	punct	9:punct	LvtbNodeId=a-z25-p37s1w12
12	mūsu	mēs	PRON	pp10pgn	Case=Gen|Number=Plur|Person=1|PronType=Prs	13	nmod	13:nmod	LvtbNodeId=a-z25-p37s1w13
13	valsts	valsts	NOUN	ncfsg6	Case=Gen|Gender=Fem|Number=Sing	16	nmod	16:nmod:gen	LvtbNodeId=a-z25-p37s1w14
14	liellopu	liellops	NOUN	ncmpg1	Case=Gen|Gender=Masc|Number=Plur	15	nmod	15:nmod:gen	LvtbNodeId=a-z25-p37s1w15
15	gaļas	gaļa	NOUN	ncfsg4	Case=Gen|Gender=Fem|Number=Sing	16	nmod	16:nmod:gen	LvtbNodeId=a-z25-p37s1w16
16	bilancē	bilance	NOUN	ncfsl5	Case=Loc|Gender=Fem|Number=Sing	19	obl	19:obl:loc	LvtbNodeId=a-z25-p37s1w17
17	tas	tas	DET	pd3msnn	Case=Nom|Gender=Masc|Number=Sing|Person=3|PronType=Dem	19	nsubj	19:nsubj	LvtbNodeId=a-z25-p37s1w18
18	ir	būt	AUX	vcnipii30an	Evident=Fh|Mood=Ind|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	19	cop	19:cop	LvtbNodeId=a-z25-p37s1w19
19	neliels	neliels	ADJ	armsnnp	Case=Nom|Definite=Ind|Degree=Pos|Gender=Masc|Number=Sing	1	csubj:pass	1:csubj:pass	LvtbNodeId=a-z25-p37s1w20|SpaceAfter=No
20	.	.	PUNCT	zs	_	1	punct	1:punct	LvtbNodeId=a-z25-p37s1w21

~~~


