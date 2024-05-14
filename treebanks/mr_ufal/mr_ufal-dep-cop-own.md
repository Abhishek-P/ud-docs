---
layout: base
title:  'Statistics of cop:own in UD_Marathi-UFAL'
udver: '2'
---

## Treebank Statistics: UD_Marathi-UFAL: Relations: `cop:own`

This relation is a language-specific subtype of <tt><a href="mr_ufal-dep-cop.html">cop</a></tt>.

4 nodes (0%) are attached to their parents as `cop:own`.

3 instances of `cop:own` (75%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.25.

The following 1 pairs of parts of speech are connected with `cop:own`: <tt><a href="mr_ufal-pos-NOUN.html">NOUN</a></tt>-<tt><a href="mr_ufal-pos-AUX.html">AUX</a></tt> (4; 100% instances).


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 3 cop:own	color:blue
1	भीमा	भीम	PROPN	_	Case=Abs|Gender=Masc|Number=Sing	4	nsubj	_	Translit=bhīmā|LTranslit=bhīma
2	कडे	कडे	ADP	_	_	1	case	_	Translit=kaḍe|LTranslit=kaḍe
3	असलेली	असणे	AUX	_	Aspect=Perf|Gender=Fem|Number=Sing|Person=3|Polarity=Pos|VerbForm=Part	4	cop:own	_	Translit=asalelī|LTranslit=asaṇe
4	जमीन	जमीन	NOUN	_	Case=Nom|Gender=Fem|Number=Sing	0	root	_	Translit=jamīna|LTranslit=jamīna
5	वास्तविक	वास्तविक	ADV	_	_	4	advmod	_	Translit=vāstavika|LTranslit=vāstavika
6	आपल	मी	PRON	_	Clusivity=In|Number=Plur|Person=1|PronType=Prs	4	nmod:poss	_	Translit=āpala|LTranslit=mī
7	ची	चा	ADP	_	Gender=Fem|Number=Sing	6	case	_	Translit=cī|LTranslit=cā
8	आहे	असणे	AUX	_	Number=Sing|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin	4	cop	_	SpaceAfter=No|Translit=āhe|LTranslit=asaṇe
9	.	.	PUNCT	_	_	4	punct	_	Translit=.|LTranslit=.

~~~


