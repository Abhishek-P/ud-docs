---
layout: base
title:  'Statistics of obj in UD_Latin-UDante'
udver: '2'
---

## Treebank Statistics: UD_Latin-UDante: Relations: `obj`

This relation is universal.

2103 nodes (4%) are attached to their parents as `obj`.

1459 instances of `obj` (69%) are right-to-left (child precedes parent).
Average distance between parent and child is 2.44174988112221.

The following 16 pairs of parts of speech are connected with `obj`: <tt><a href="la_udante-pos-VERB.html">VERB</a></tt>-<tt><a href="la_udante-pos-NOUN.html">NOUN</a></tt> (1152; 55% instances), <tt><a href="la_udante-pos-VERB.html">VERB</a></tt>-<tt><a href="la_udante-pos-PRON.html">PRON</a></tt> (487; 23% instances), <tt><a href="la_udante-pos-VERB.html">VERB</a></tt>-<tt><a href="la_udante-pos-DET.html">DET</a></tt> (204; 10% instances), <tt><a href="la_udante-pos-VERB.html">VERB</a></tt>-<tt><a href="la_udante-pos-ADJ.html">ADJ</a></tt> (117; 6% instances), <tt><a href="la_udante-pos-VERB.html">VERB</a></tt>-<tt><a href="la_udante-pos-PROPN.html">PROPN</a></tt> (63; 3% instances), <tt><a href="la_udante-pos-VERB.html">VERB</a></tt>-<tt><a href="la_udante-pos-VERB.html">VERB</a></tt> (33; 2% instances), <tt><a href="la_udante-pos-VERB.html">VERB</a></tt>-<tt><a href="la_udante-pos-X.html">X</a></tt> (21; 1% instances), <tt><a href="la_udante-pos-VERB.html">VERB</a></tt>-<tt><a href="la_udante-pos-AUX.html">AUX</a></tt> (9; 0% instances), <tt><a href="la_udante-pos-VERB.html">VERB</a></tt>-<tt><a href="la_udante-pos-NUM.html">NUM</a></tt> (7; 0% instances), <tt><a href="la_udante-pos-VERB.html">VERB</a></tt>-<tt><a href="la_udante-pos-ADV.html">ADV</a></tt> (3; 0% instances), <tt><a href="la_udante-pos-NOUN.html">NOUN</a></tt>-<tt><a href="la_udante-pos-PRON.html">PRON</a></tt> (2; 0% instances), <tt><a href="la_udante-pos-ADJ.html">ADJ</a></tt>-<tt><a href="la_udante-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="la_udante-pos-DET.html">DET</a></tt>-<tt><a href="la_udante-pos-PRON.html">PRON</a></tt> (1; 0% instances), <tt><a href="la_udante-pos-NOUN.html">NOUN</a></tt>-<tt><a href="la_udante-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="la_udante-pos-PART.html">PART</a></tt>-<tt><a href="la_udante-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="la_udante-pos-VERB.html">VERB</a></tt>-<tt><a href="la_udante-pos-SCONJ.html">SCONJ</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 2 obj	color:blue
1	An	an	PART	co	PartType=Int	5	discourse	_	_
2	parum	parum	NOUN	r	Case=Acc|Gender=Neut|InflClass=IndEurO|Number=Sing	5	obj	_	_
3	timoris	timor	NOUN	sms3g	Case=Gen|Gender=Masc|InflClass=IndEurX|Number=Sing	2	nmod	_	_
4	prelibata	praelibo	VERB	vp1prpnn	Aspect=Perf|Case=Nom|Gender=Neut|InflClass=LatA|InflClass[nominal]=IndEurO|Number=Plur|VerbForm=Part|Voice=Pass	5	nsubj	_	TraditionalMood=Participium|TraditionalTense=Perfectum
5	incutiunt	incutio	VERB	va3ipp3	Aspect=Imp|InflClass=LatX|Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	SpaceAfter=No|TraditionalMood=Indicativus|TraditionalTense=Praesens
6	?	?	PUNCT	Pu	_	5	punct	_	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 8 obj	color:blue
1	Sed	sed	CCONJ	co	_	2	cc	_	_
2	attendat	attendo	VERB	va3cps3	Aspect=Imp|InflClass=LatX|Mood=Sub|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	TraditionalMood=Subiunctivus|TraditionalTense=Praesens
3	ad	ad	ADP	e	_	4	case	_	_
4	laqueum	laqueus	NOUN	sms2a	Case=Acc|Gender=Masc|InflClass=IndEurO|Number=Sing	2	obl:arg	_	_
5	mulier	mulier	NOUN	sfs3n	Case=Nom|Gender=Fem|InflClass=IndEurX|Number=Sing	2	nsubj	_	_
6	furiata	furio	VERB	vp1prsfn	Aspect=Perf|Case=Nom|Gender=Fem|InflClass=LatA|InflClass[nominal]=IndEurA|Number=Sing|VerbForm=Part|Voice=Pass	5	acl	_	TraditionalMood=Participium|TraditionalTense=Perfectum
7	quo	qui	PRON	presmb	Case=Abl|Gender=Masc|InflClass=LatPron|Number=Sing|PronType=Rel	9	obl	_	_
8	se	sui	PRON	ppp3snb	Case=Abl|InflClass=LatAnom|Person=3|PronType=Prs|Reflex=Yes	9	obj	_	_
9	innectit	innecto	VERB	va3ips3	Aspect=Imp|InflClass=LatX|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	4	acl:relcl	_	SpaceAfter=No|TraditionalMood=Indicativus|TraditionalTense=Praesens
10	.	.	PUNCT	Pu	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 1 obj	color:blue
1	Hoc	hic	DET	ddisna	Case=Acc|Gender=Neut|InflClass=LatPron|Number=Sing|PronType=Dem	3	obj	_	_
2	ne	ne	PART	9i	PartType=Int|Polarity=Neg	1	fixed	_	_
3	meruit	mereo	VERB	va2irs3	Aspect=Perf|InflClass=LatE|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	TraditionalMood=Indicativus|TraditionalTense=Perfectum
4	innocentia	innocentia	NOUN	sfs1n	Case=Nom|Gender=Fem|InflClass=IndEurA|Number=Sing	3	nsubj	_	_
5	manifesta	manifestus	ADJ	afs1n	Case=Nom|Compound=Yes|Gender=Fem|InflClass=IndEurA|Number=Sing	4	amod	_	_
6	quibuslibet	quilibet	DET	dinpmd	Case=Dat|Compound=Yes|Gender=Masc|InflClass=LatPron|Number=Plur|PronType=Ind	4	obl	_	SpaceAfter=No
7	?	?	PUNCT	Pu	_	3	punct	_	_

~~~


