---
layout: base
title:  'Statistics of obl:arg in UD_Latin-UDante'
udver: '2'
---

## Treebank Statistics: UD_Latin-UDante: Relations: `obl:arg`

This relation is a language-specific subtype of <tt><a href="la_udante-dep-obl.html">obl</a></tt>.
There are also 4 other language-specific subtypes of `obl`: <tt><a href="la_udante-dep-obl-agent.html">obl:agent</a></tt>, <tt><a href="la_udante-dep-obl-cmp.html">obl:cmp</a></tt>, <tt><a href="la_udante-dep-obl-lmod.html">obl:lmod</a></tt>, <tt><a href="la_udante-dep-obl-tmod.html">obl:tmod</a></tt>.

1009 nodes (2%) are attached to their parents as `obl:arg`.

630 instances of `obl:arg` (62%) are right-to-left (child precedes parent).
Average distance between parent and child is 2.60555004955401.

The following 21 pairs of parts of speech are connected with `obl:arg`: <tt><a href="la_udante-pos-VERB.html">VERB</a></tt>-<tt><a href="la_udante-pos-NOUN.html">NOUN</a></tt> (520; 52% instances), <tt><a href="la_udante-pos-VERB.html">VERB</a></tt>-<tt><a href="la_udante-pos-PRON.html">PRON</a></tt> (169; 17% instances), <tt><a href="la_udante-pos-VERB.html">VERB</a></tt>-<tt><a href="la_udante-pos-DET.html">DET</a></tt> (90; 9% instances), <tt><a href="la_udante-pos-ADJ.html">ADJ</a></tt>-<tt><a href="la_udante-pos-NOUN.html">NOUN</a></tt> (66; 7% instances), <tt><a href="la_udante-pos-VERB.html">VERB</a></tt>-<tt><a href="la_udante-pos-ADJ.html">ADJ</a></tt> (44; 4% instances), <tt><a href="la_udante-pos-VERB.html">VERB</a></tt>-<tt><a href="la_udante-pos-PROPN.html">PROPN</a></tt> (31; 3% instances), <tt><a href="la_udante-pos-VERB.html">VERB</a></tt>-<tt><a href="la_udante-pos-VERB.html">VERB</a></tt> (24; 2% instances), <tt><a href="la_udante-pos-ADJ.html">ADJ</a></tt>-<tt><a href="la_udante-pos-DET.html">DET</a></tt> (13; 1% instances), <tt><a href="la_udante-pos-NOUN.html">NOUN</a></tt>-<tt><a href="la_udante-pos-NOUN.html">NOUN</a></tt> (13; 1% instances), <tt><a href="la_udante-pos-ADJ.html">ADJ</a></tt>-<tt><a href="la_udante-pos-ADJ.html">ADJ</a></tt> (7; 1% instances), <tt><a href="la_udante-pos-NOUN.html">NOUN</a></tt>-<tt><a href="la_udante-pos-PRON.html">PRON</a></tt> (7; 1% instances), <tt><a href="la_udante-pos-ADJ.html">ADJ</a></tt>-<tt><a href="la_udante-pos-PRON.html">PRON</a></tt> (6; 1% instances), <tt><a href="la_udante-pos-ADV.html">ADV</a></tt>-<tt><a href="la_udante-pos-NOUN.html">NOUN</a></tt> (4; 0% instances), <tt><a href="la_udante-pos-ADJ.html">ADJ</a></tt>-<tt><a href="la_udante-pos-VERB.html">VERB</a></tt> (3; 0% instances), <tt><a href="la_udante-pos-ADJ.html">ADJ</a></tt>-<tt><a href="la_udante-pos-PROPN.html">PROPN</a></tt> (2; 0% instances), <tt><a href="la_udante-pos-DET.html">DET</a></tt>-<tt><a href="la_udante-pos-PRON.html">PRON</a></tt> (2; 0% instances), <tt><a href="la_udante-pos-NOUN.html">NOUN</a></tt>-<tt><a href="la_udante-pos-DET.html">DET</a></tt> (2; 0% instances), <tt><a href="la_udante-pos-PRON.html">PRON</a></tt>-<tt><a href="la_udante-pos-NOUN.html">NOUN</a></tt> (2; 0% instances), <tt><a href="la_udante-pos-VERB.html">VERB</a></tt>-<tt><a href="la_udante-pos-NUM.html">NUM</a></tt> (2; 0% instances), <tt><a href="la_udante-pos-DET.html">DET</a></tt>-<tt><a href="la_udante-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="la_udante-pos-VERB.html">VERB</a></tt>-<tt><a href="la_udante-pos-ADV.html">ADV</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 5 obl:arg	color:blue
1	Sed	sed	CCONJ	co	_	6	cc	_	_
2	stupor	stupor	NOUN	sms3n	Case=Nom|Gender=Masc|InflClass=IndEurX|Number=Sing	6	nsubj	_	_
3	subsequentis	subsequor	VERB	vd3ppsng	Aspect=Imp|Case=Gen|Gender=Neut|InflClass=LatX|InflClass[nominal]=IndEurI|Number=Sing|VerbForm=Part|Voice=Act	4	acl	_	TraditionalMood=Participium|TraditionalTense=Praesens
4	tonitrui	tonitruum	NOUN	sns2g	Case=Gen|Gender=Neut|InflClass=IndEurO|Number=Sing	5	nmod	_	_
5	terrore	terror	NOUN	sms3b	Case=Abl|Gender=Masc|InflClass=IndEurX|Number=Sing	6	obl:arg	_	_
6	cessavit	cesso	VERB	va1irs3	Aspect=Perf|InflClass=LatA|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	SpaceAfter=No|TraditionalMood=Indicativus|TraditionalTense=Perfectum
7	.	.	PUNCT	Pu	_	6	punct	_	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 5 obl:arg	color:blue
1	De	de	ADP	e	_	2	case	_	_
2	quo	qui	PRON	presnb	Case=Abl|Gender=Neut|InflClass=LatPron|Number=Sing|PronType=Rel	8	obl	_	_
3	Latinorum	latinus	ADJ	Smp2g	Case=Gen|Gender=Masc|InflClass=IndEurO|NameType=Nat|Number=Plur	4	nmod	_	_
4	neminem	nemo	PRON	dinsma	Case=Acc|Gender=Masc|InflClass=IndEurX|Number=Sing|Polarity=Neg|PronType=Ind	7	nsubj	_	_
5	nobis	ego	PRON	ppp1pmb	Case=Abl|InflClass=LatAnom|Number=Plur|Person=1|PronType=Prs	7	obl:arg	_	_
6	cum	cum	ADP	e9	_	5	case	_	_
7	dissentire	dissentio	VERB	va4fp	Aspect=Imp|InflClass=LatI|VerbForm=Inf|Voice=Act	8	ccomp	_	TraditionalMood=Infinitivus|TraditionalTense=Praesens
8	putamus	puto	VERB	va1ipp1	Aspect=Imp|InflClass=LatA|Mood=Ind|Number=Plur|Person=1|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	SpaceAfter=No|TraditionalMood=Indicativus|TraditionalTense=Praesens
9	.	.	PUNCT	Pu	_	8	punct	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 4 obl:arg	color:blue
1	«	«	PUNCT	Pu	_	3	punct	_	SpaceAfter=No
2	Non	non	PART	r	Polarity=Neg	3	advmod:neg	_	_
3	loquor	loquor	VERB	vd3ips1	Aspect=Imp|InflClass=LatX|Mood=Ind|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin|Voice=Pass	11	ccomp:reported	_	TraditionalMood=Indicativus|TraditionalTense=Praesens
4	his	hic	DET	ddipmd	Case=Dat|Gender=Masc|InflClass=LatPron|Number=Plur|PronType=Dem	3	obl:arg	_	SpaceAfter=No
5	,	,	PUNCT	Pu	_	8	punct	_	_
6	ymmo	immo	ADV	r	Degree=Abs	8	advmod:emph	_	_
7	studio	studium	NOUN	sns2b	Case=Abl|Gender=Neut|InflClass=IndEurO|Number=Sing	8	obl	_	_
8	callentibus	calleo	VERB	amp2d	Aspect=Imp|Case=Dat|Gender=Masc|InflClass=LatE|InflClass[nominal]=IndEurI|Number=Plur|VerbForm=Part|Voice=Act	4	conj	_	SpaceAfter=No|TraditionalMood=Participium|TraditionalTense=Praesens
9	»	»	PUNCT	Pu	_	3	punct	_	SpaceAfter=No
10	,	,	PUNCT	Pu	_	3	punct	_	_
11	inquis	inquam	VERB	va5-ips2	Aspect=Imp|InflClass=LatI2|Mood=Ind|Number=Sing|Person=2|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	SpaceAfter=No|TraditionalMood=Indicativus|TraditionalTense=Praesens
12	.	.	PUNCT	Pu	_	11	punct	_	_

~~~


