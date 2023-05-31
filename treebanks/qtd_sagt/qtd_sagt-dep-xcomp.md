---
layout: base
title:  'Statistics of xcomp in UD_Turkish_German-SAGT'
udver: '2'
---

## Treebank Statistics: UD_Turkish_German-SAGT: Relations: `xcomp`

This relation is universal.

322 nodes (1%) are attached to their parents as `xcomp`.

234 instances of `xcomp` (73%) are right-to-left (child precedes parent).
Average distance between parent and child is 2.16770186335404.

The following 12 pairs of parts of speech are connected with `xcomp`: <tt><a href="qtd_sagt-pos-VERB.html">VERB</a></tt>-<tt><a href="qtd_sagt-pos-VERB.html">VERB</a></tt> (191; 59% instances), <tt><a href="qtd_sagt-pos-VERB.html">VERB</a></tt>-<tt><a href="qtd_sagt-pos-NOUN.html">NOUN</a></tt> (61; 19% instances), <tt><a href="qtd_sagt-pos-VERB.html">VERB</a></tt>-<tt><a href="qtd_sagt-pos-ADJ.html">ADJ</a></tt> (36; 11% instances), <tt><a href="qtd_sagt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="qtd_sagt-pos-VERB.html">VERB</a></tt> (8; 2% instances), <tt><a href="qtd_sagt-pos-VERB.html">VERB</a></tt>-<tt><a href="qtd_sagt-pos-ADV.html">ADV</a></tt> (8; 2% instances), <tt><a href="qtd_sagt-pos-VERB.html">VERB</a></tt>-<tt><a href="qtd_sagt-pos-PROPN.html">PROPN</a></tt> (6; 2% instances), <tt><a href="qtd_sagt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="qtd_sagt-pos-VERB.html">VERB</a></tt> (4; 1% instances), <tt><a href="qtd_sagt-pos-VERB.html">VERB</a></tt>-<tt><a href="qtd_sagt-pos-PRON.html">PRON</a></tt> (4; 1% instances), <tt><a href="qtd_sagt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="qtd_sagt-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="qtd_sagt-pos-ADP.html">ADP</a></tt>-<tt><a href="qtd_sagt-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="qtd_sagt-pos-AUX.html">AUX</a></tt>-<tt><a href="qtd_sagt-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="qtd_sagt-pos-PART.html">PART</a></tt>-<tt><a href="qtd_sagt-pos-VERB.html">VERB</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 6 xcomp	color:blue
1	Eh	eh	INTJ	_	_	7	discourse	_	CSID=TR|Lang=tr
2	kitaplardan	kitap	NOUN	_	Case=Abl|Number=Plur	4	nmod	_	CSID=TR|Lang=tr
3	mesela	mesela	ADV	_	_	7	advmod	_	CSID=TR|Lang=tr
4	Abilektüre	Abilektüre	NOUN	_	Case=Nom|Gender=Fem|Number=Sing	5	nmod	_	CSID=DE|Lang=de
5	ne	ne	PRON	_	Case=Nom|Number=Sing	7	obj	_	CSID=TR|Lang=tr
6	okumanız	oku	VERB	_	Case=Nom|Number=Sing|Number[psor]=Plur|Person[psor]=2|VerbForm=Vnoun	7	xcomp	_	CSID=TR|Lang=tr
7	gerekti	gerek	VERB	_	Aspect=Perf|Evident=Fh|Mood=Ind|Number=Sing|Person=3|Tense=Past	0	root	_	CSID=TR|Lang=tr|SpaceAfter=No
8	?	?	PUNCT	_	_	7	punct	_	CSID=OTHER

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 4 xcomp	color:blue
1	Man	man	PRON	_	Case=Nom|Number=Sing|PronType=Ind	2	nsubj	_	CSID=DE|Lang=de
2	muss	müssen	VERB	_	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	6	reparandum	_	CSID=DE|Lang=de
3	allgemein	allgemein	ADJ	_	_	6	advmod	_	CSID=DE|Lang=de
4	şey	şey	NOUN	_	Case=Nom|Number=Sing	5	xcomp	_	CSID=TR|Lang=tr
5	olmak	ol	VERB	_	Number=Sing|VerbForm=Vnoun	6	csubj	_	CSID=TR|Lang=tr
6	lazım	lazım	ADJ	_	_	0	root	_	CSID=TR|Lang=tr
7	sprachenbegabt	Sprachebegabt	ADJ	_	_	6	dislocated	_	CSID=DE|Lang=de|DislocateHead=4
8	meinst	meinen	VERB	_	Mood=Ind|Number=Sing|Person=2|Tense=Pres	6	parataxis:discourse	_	CSID=DE|Lang=de
9	du	du	PRON	_	Case=Nom|Number=Sing|Person=2|PronType=Prs	8	nsubj	_	CSID=DE|Lang=de|SpaceAfter=No
10	?	?	PUNCT	_	_	6	punct	_	CSID=OTHER

~~~


~~~ conllu
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 11	bgColor:blue
# visual-style 11	fgColor:white
# visual-style 11 10 xcomp	color:blue
1	Habe	haben	AUX	_	Mood=Ind|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin	7	aux	_	CSID=DE|Lang=de
2	ich	ich	PRON	_	Case=Nom|Number=Sing|Person=1|PronType=Prs	7	nsubj	_	CSID=DE|Lang=de
3	mir	ich	PRON	_	Case=Dat|Number=Sing|Person=1|PronType=Prs|Reflex=Yes	7	expl:pv	_	CSID=DE|Lang=de
4	jetzt	jetzt	ADV	_	_	7	advmod	_	CSID=DE|Lang=de
5	überhaupt	überhaupt	ADV	_	_	6	advmod	_	CSID=DE|Lang=de
6	nicht	nicht	PART	_	Polarity=Neg	7	advmod	_	CSID=DE|Lang=de
7	überlegt	überlegen	VERB	_	VerbForm=Part	0	root	_	CSID=DE|Lang=de
8	ama	ama	CCONJ	_	_	10	cc	_	CSID=TR|Lang=tr
9	aslında	aslında	ADV	_	_	10	advmod	_	CSID=TR|Lang=tr
10	iyi	iyi	ADJ	_	_	11	xcomp	_	CSID=TR|Lang=tr
11	olur	ol	VERB	_	Aspect=Hab|Evident=Fh|Mood=Gen|Number=Sing|Person=3|Tense=Pres	7	conj	_	CSID=TR|Lang=tr|SpaceAfter=No
12	.	.	PUNCT	_	_	7	punct	_	CSID=OTHER

~~~


