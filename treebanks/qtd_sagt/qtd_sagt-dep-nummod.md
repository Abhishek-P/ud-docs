---
layout: base
title:  'Statistics of nummod in UD_Turkish_German-SAGT'
udver: '2'
---

## Treebank Statistics: UD_Turkish_German-SAGT: Relations: `nummod`

This relation is universal.

241 nodes (1%) are attached to their parents as `nummod`.

222 instances of `nummod` (92%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.2655601659751.

The following 10 pairs of parts of speech are connected with `nummod`: <tt><a href="qtd_sagt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="qtd_sagt-pos-NUM.html">NUM</a></tt> (212; 88% instances), <tt><a href="qtd_sagt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="qtd_sagt-pos-NUM.html">NUM</a></tt> (13; 5% instances), <tt><a href="qtd_sagt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="qtd_sagt-pos-NUM.html">NUM</a></tt> (5; 2% instances), <tt><a href="qtd_sagt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="qtd_sagt-pos-NOUN.html">NOUN</a></tt> (3; 1% instances), <tt><a href="qtd_sagt-pos-ADV.html">ADV</a></tt>-<tt><a href="qtd_sagt-pos-NUM.html">NUM</a></tt> (2; 1% instances), <tt><a href="qtd_sagt-pos-NUM.html">NUM</a></tt>-<tt><a href="qtd_sagt-pos-NUM.html">NUM</a></tt> (2; 1% instances), <tt><a href="qtd_sagt-pos-PRON.html">PRON</a></tt>-<tt><a href="qtd_sagt-pos-NUM.html">NUM</a></tt> (1; 0% instances), <tt><a href="qtd_sagt-pos-VERB.html">VERB</a></tt>-<tt><a href="qtd_sagt-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="qtd_sagt-pos-VERB.html">VERB</a></tt>-<tt><a href="qtd_sagt-pos-NUM.html">NUM</a></tt> (1; 0% instances), <tt><a href="qtd_sagt-pos-X.html">X</a></tt>-<tt><a href="qtd_sagt-pos-NOUN.html">NOUN</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 1 nummod	color:blue
1	İki	iki	NUM	_	NumType=Card	2	nummod	_	CSID=TR|Lang=tr
2	ta--	tane	NOUN	_	Case=Nom|Number=Sing|Typo=Yes	4	reparandum	_	CSID=TR|Lang=tr|CorrectForm=tane
3	iki	iki	NUM	_	NumType=Card	4	nummod	_	CSID=TR|Lang=tr
4	tane	tane	NOUN	_	Case=Nom|Number=Sing	5	nmod	_	CSID=TR|Lang=tr
5	Lektüre	Lektüre	NOUN	_	Case=Acc|Gender=Fem|Number=Sing	6	obj	_	CSID=DE|Lang=de
6	okumamız	oku	VERB	_	Case=Nom|Number=Sing|Number[psor]=Plur|Person[psor]=1|VerbForm=Vnoun	0	root	_	CSID=TR|Lang=tr
7	lazım	lazım	ADJ	_	_	6	csubj	_	CSID=TR|Lang=tr
8	dı	i	AUX	_	Aspect=Perf|Evident=Fh|Mood=Ind|Number=Sing|Person=3|Tense=Past	6	cop	_	CSID=TR|Lang=tr
9	Almanca'da	Almanca	PROPN	_	Case=Loc|Number=Sing	6	obl	_	CSID=TR|Lang=tr|SpaceAfter=No
10	.	.	PUNCT	_	_	6	punct	_	CSID=OTHER

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 5 nummod	color:blue
1	Ben	ben	PRON	_	Case=Nom|Number=Sing|Person=1|PronType=Prs	3	nsubj	_	CSID=TR|Lang=tr
2	şeye	şey	NOUN	_	Case=Dat|Number=Sing	3	obl	_	CSID=TR|Lang=tr
3	çalışıyorum	çalış	VERB	_	Aspect=Prog|Evident=Fh|Mood=Ind|Number=Sing|Person=1|Tense=Pres	0	root	_	CSID=TR|Lang=tr|SpaceAfter=No
4	,	,	PUNCT	_	_	7	punct	_	CSID=OTHER
5	450	450	NUM	_	NumType=Card	6	nummod	_	CSID=DE|Lang=de|DislocateHead=2
6	Euro	Euro	PROPN	_	Case=Nom|Gender=Masc|Number=Plur	7	compound	_	CSID=DE|Lang=de
7	Basis	Basis	NOUN	_	Case=Nom|Gender=Fem|Number=Sing	3	dislocated	_	CSID=DE|Lang=de|SpaceAfter=No
8	.	.	PUNCT	_	_	3	punct	_	CSID=OTHER

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 5 nummod	color:blue
1	Ben	ben	PRON	_	Case=Nom|Number=Sing|Person=1|PronType=Prs	3	nsubj	_	CSID=TR|Lang=tr
2	de	de	ADV	_	_	1	advmod:emph	_	CSID=TR|Lang=tr
3	hesapladım	hesapla	VERB	_	Aspect=Perf|Evident=Fh|Mood=Ind|Number=Sing|Person=1|Tense=Past	0	root	_	CSID=TR|Lang=tr
4	yirmi	yirmi	NUM	_	NumType=Card	6	nummod	_	CSID=TR|Lang=tr
5	bir	bir	NUM	_	NumType=Card	6	nummod	_	CSID=TR|Lang=tr
6	buçuk	buçuk	ADJ	_	_	9	advcl	_	CSID=TR|Lang=tr
7	oder	oder	CCONJ	_	_	8	cc	_	CSID=DE|Lang=de
8	einundzwanzigle	einundzwanzig	NOUN	_	Case=Ins|Number=Sing	6	conj	_	CSID=MIXED|CSPoint=einundzwanzig§le|DeCase=Dat|DeGender=Fem|Lang=qtd
9	biteceğim	bit	VERB	_	Aspect=Perf|Case=Nom|Evident=Fh|Mood=Ind|Number=Sing|Number[psor]=Sing|Person[psor]=1|Tense=Fut	3	ccomp	_	CSID=TR|Lang=tr
10	zaten	zaten	ADV	_	_	9	advmod	_	CSID=TR|Lang=tr
11	Allah	Allah	PROPN	_	Case=Nom|Number=Sing	13	nsubj	_	CSID=TR|Lang=tr
12	izin	izin	NOUN	_	Case=Nom|Number=Sing	13	obj	_	CSID=TR|Lang=tr
13	verirse	ver	VERB	_	Aspect=Imp|Evident=Fh|Mood=Cnd|Number=Sing|Person=3|Tense=Pres	3	parataxis	_	CSID=TR|Lang=tr
14	mesleğimle	meslek	NOUN	_	Case=Ins|Number=Sing|Number[psor]=Sing|Person[psor]=1	13	obl	_	CSID=TR|Lang=tr|SpaceAfter=No
15	.	.	PUNCT	_	_	3	punct	_	CSID=OTHER

~~~


