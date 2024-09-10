---
layout: base
title:  'Statistics of nsubj:pass in UD_Latin-PROIEL'
udver: '2'
---

## Treebank Statistics: UD_Latin-PROIEL: Relations: `nsubj:pass`

This relation is a language-specific subtype of <tt><a href="la_proiel-dep-nsubj.html">nsubj</a></tt>.
There are also 1 other language-specific subtypes of `nsubj`: <tt><a href="la_proiel-dep-nsubj-outer.html">nsubj:outer</a></tt>.

3885 nodes (2%) are attached to their parents as `nsubj:pass`.

2809 instances of `nsubj:pass` (72%) are right-to-left (child precedes parent).
Average distance between parent and child is 2.61647361647362.

The following 8 pairs of parts of speech are connected with `nsubj:pass`: <tt><a href="la_proiel-pos-VERB.html">VERB</a></tt>-<tt><a href="la_proiel-pos-NOUN.html">NOUN</a></tt> (2264; 58% instances), <tt><a href="la_proiel-pos-VERB.html">VERB</a></tt>-<tt><a href="la_proiel-pos-PRON.html">PRON</a></tt> (1253; 32% instances), <tt><a href="la_proiel-pos-VERB.html">VERB</a></tt>-<tt><a href="la_proiel-pos-PROPN.html">PROPN</a></tt> (146; 4% instances), <tt><a href="la_proiel-pos-VERB.html">VERB</a></tt>-<tt><a href="la_proiel-pos-ADJ.html">ADJ</a></tt> (104; 3% instances), <tt><a href="la_proiel-pos-VERB.html">VERB</a></tt>-<tt><a href="la_proiel-pos-VERB.html">VERB</a></tt> (90; 2% instances), <tt><a href="la_proiel-pos-VERB.html">VERB</a></tt>-<tt><a href="la_proiel-pos-NUM.html">NUM</a></tt> (20; 1% instances), <tt><a href="la_proiel-pos-VERB.html">VERB</a></tt>-<tt><a href="la_proiel-pos-ADV.html">ADV</a></tt> (6; 0% instances), <tt><a href="la_proiel-pos-VERB.html">VERB</a></tt>-<tt><a href="la_proiel-pos-AUX.html">AUX</a></tt> (2; 0% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 5 nsubj:pass	color:blue
1	et	et	CCONJ	C-	_	3	cc	_	ref=MARK_5.29
2	confestim	confestim	ADV	Df	_	3	advmod	_	ref=MARK_5.29
3	siccatus	sicco	VERB	V-	Aspect=Perf|Case=Nom|Gender=Masc|Number=Sing|Tense=Past|VerbForm=Part|Voice=Pass	0	root	_	ref=MARK_5.29
4	est	sum	AUX	V-	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	3	aux:pass	_	ref=MARK_5.29
5	fons	fons	NOUN	Nb	Case=Nom|Gender=Masc|Number=Sing	3	nsubj:pass	_	ref=MARK_5.29
6	sanguinis	sanguis	NOUN	Nb	Case=Gen|Gender=Masc|Number=Sing	5	nmod	_	ref=MARK_5.29
7	eius	is	PRON	Pp	Case=Gen|Gender=Fem|Number=Sing|Person=3|PronType=Prs	6	det	_	ref=MARK_5.29

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 8 nsubj:pass	color:blue
1	beati	beatus	ADJ	A-	Case=Nom|Degree=Pos|Gender=Masc|Number=Plur	0	root	_	ref=MATT_5.6
2	qui	qui	PRON	Pr	Case=Nom|Gender=Masc|Number=Plur|PronType=Rel	3	nsubj	_	ref=MATT_5.6
3	esuriunt	esurio	VERB	V-	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	1	nsubj	_	ref=MATT_5.6
4	et	et	CCONJ	C-	_	5	cc	_	ref=MATT_5.6
5	sitiunt	sitio	VERB	V-	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	3	conj	_	ref=MATT_5.6
6	iustitiam	iustitia	NOUN	Nb	Case=Acc|Gender=Fem|Number=Sing	5	obj	_	ref=MATT_5.6
7	quoniam	quoniam	SCONJ	G-	_	9	mark	_	ref=MATT_5.6
8	ipsi	ipse	PRON	Pp	Case=Nom|Gender=Masc|Number=Plur|Person=3|PronType=Prs	9	nsubj:pass	_	ref=MATT_5.6
9	saturabuntur	saturo	VERB	V-	Mood=Ind|Number=Plur|Person=3|Tense=Fut|VerbForm=Fin|Voice=Pass	1	advcl	_	ref=MATT_5.6

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 3 nsubj:pass	color:blue
1	et	et	CCONJ	C-	_	4	cc	_	ref=ACTS_9.40
2	viso	video	VERB	V-	Aspect=Perf|Case=Abl|Gender=Masc|Number=Sing|Tense=Past|VerbForm=Part|Voice=Pass	4	advcl	_	ref=ACTS_9.40
3	Petro	Petrus	PROPN	Ne	Case=Abl|Gender=Masc|Number=Sing	2	nsubj:pass	_	ref=ACTS_9.40
4	resedit	resideo	VERB	V-	Aspect=Perf|Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin|Voice=Act	0	root	_	ref=ACTS_9.40

~~~


