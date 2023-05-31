---
layout: base
title:  'Statistics of nmod in UD_Kazakh'
udver: '2'
---

## Treebank Statistics: UD_Kazakh: Relations: `nmod`

This relation is universal.
There are 1 language-specific subtypes of `nmod`: <tt><a href="kk-dep-nmod-poss.html">nmod:poss</a></tt>.

234 nodes (2%) are attached to their parents as `nmod`.

231 instances of `nmod` (99%) are right-to-left (child precedes parent).
Average distance between parent and child is 2.52564102564103.

The following 22 pairs of parts of speech are connected with `nmod`: <tt><a href="kk-pos-VERB.html">VERB</a></tt>-<tt><a href="kk-pos-NOUN.html">NOUN</a></tt> (103; 44% instances), <tt><a href="kk-pos-NOUN.html">NOUN</a></tt>-<tt><a href="kk-pos-NOUN.html">NOUN</a></tt> (53; 23% instances), <tt><a href="kk-pos-VERB.html">VERB</a></tt>-<tt><a href="kk-pos-PRON.html">PRON</a></tt> (22; 9% instances), <tt><a href="kk-pos-ADJ.html">ADJ</a></tt>-<tt><a href="kk-pos-NOUN.html">NOUN</a></tt> (13; 6% instances), <tt><a href="kk-pos-NOUN.html">NOUN</a></tt>-<tt><a href="kk-pos-NUM.html">NUM</a></tt> (7; 3% instances), <tt><a href="kk-pos-NOUN.html">NOUN</a></tt>-<tt><a href="kk-pos-PROPN.html">PROPN</a></tt> (7; 3% instances), <tt><a href="kk-pos-ADJ.html">ADJ</a></tt>-<tt><a href="kk-pos-PRON.html">PRON</a></tt> (4; 2% instances), <tt><a href="kk-pos-VERB.html">VERB</a></tt>-<tt><a href="kk-pos-PROPN.html">PROPN</a></tt> (4; 2% instances), <tt><a href="kk-pos-NOUN.html">NOUN</a></tt>-<tt><a href="kk-pos-PRON.html">PRON</a></tt> (3; 1% instances), <tt><a href="kk-pos-PROPN.html">PROPN</a></tt>-<tt><a href="kk-pos-NOUN.html">NOUN</a></tt> (3; 1% instances), <tt><a href="kk-pos-VERB.html">VERB</a></tt>-<tt><a href="kk-pos-ADJ.html">ADJ</a></tt> (3; 1% instances), <tt><a href="kk-pos-NUM.html">NUM</a></tt>-<tt><a href="kk-pos-NUM.html">NUM</a></tt> (2; 1% instances), <tt><a href="kk-pos-ADJ.html">ADJ</a></tt>-<tt><a href="kk-pos-NUM.html">NUM</a></tt> (1; 0% instances), <tt><a href="kk-pos-ADJ.html">ADJ</a></tt>-<tt><a href="kk-pos-PROPN.html">PROPN</a></tt> (1; 0% instances), <tt><a href="kk-pos-ADV.html">ADV</a></tt>-<tt><a href="kk-pos-PRON.html">PRON</a></tt> (1; 0% instances), <tt><a href="kk-pos-AUX.html">AUX</a></tt>-<tt><a href="kk-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="kk-pos-NOUN.html">NOUN</a></tt>-<tt><a href="kk-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="kk-pos-NOUN.html">NOUN</a></tt>-<tt><a href="kk-pos-SYM.html">SYM</a></tt> (1; 0% instances), <tt><a href="kk-pos-NUM.html">NUM</a></tt>-<tt><a href="kk-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="kk-pos-VERB.html">VERB</a></tt>-<tt><a href="kk-pos-ADV.html">ADV</a></tt> (1; 0% instances), <tt><a href="kk-pos-VERB.html">VERB</a></tt>-<tt><a href="kk-pos-NUM.html">NUM</a></tt> (1; 0% instances), <tt><a href="kk-pos-VERB.html">VERB</a></tt>-<tt><a href="kk-pos-VERB.html">VERB</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 2 nmod	color:blue
1	Адам	адам	NOUN	n	Case=Nom	6	nsubj	_	_
2	лаж	лаж	NOUN	n	Case=Nom	6	nmod	_	_
3	сыз	сыз	ADP	post	_	2	case	_	_
4	елінің	ел	NOUN	n	Case=Gen|Number[psor]=Plur,Sing|Person[psor]=3	5	nmod:poss	_	_
5	тілегіне	тілек	NOUN	n	Case=Dat|Number[psor]=Plur,Sing|Person[psor]=3	6	nmod	_	_
6	бағынады	бағын	VERB	v	Mood=Ind|Number=Sing|Person=3|Tense=Aor|VerbForm=Fin	0	root	_	SpaceAfter=No
7	.	.	PUNCT	sent	_	6	punct	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 3 nmod	color:blue
1	-	-	PUNCT	guio	_	9	punct	_	_
2	Алматының	Алматы	PROPN	np	Case=Gen	6	nsubj	_	_
3	күннен	күн	NOUN	n	Case=Abl	5	nmod	_	SpaceAfter=No
4	-	-	PUNCT	guio	_	5	punct	_	SpaceAfter=No
5	күнге	күн	NOUN	n	Case=Dat	6	obl	_	_
6	көркеюін	көркей	VERB	v	Case=Acc|Number[psor]=Plur,Sing|Person[psor]=3|VerbForm=Ger	7	ccomp	_	_
7	көру	көр	VERB	v	Case=Nom|VerbForm=Ger	9	csubj	_	_
8	өте	өте	ADV	adv	_	9	advmod	_	_
9	қуанышты	қуанышты	ADJ	adj	_	0	root	_	SpaceAfter=No
10	.	.	PUNCT	sent	_	9	punct	_	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 2 nmod	color:blue
1	Бірақ	бірақ	CCONJ	cnjcoo	_	4	cc	_	_
2	оған	ол	PRON	prn	Case=Dat|PronType=Dem	4	nmod	_	_
3	артық	артық	ADV	adv	_	4	advmod	_	_
4	араласпаймын	аралас	VERB	v	Mood=Ind|Number=Sing|Person=1|Polarity=Neg|Tense=Aor|VerbForm=Fin	0	root	_	SpaceAfter=No
5	.	.	PUNCT	sent	_	4	punct	_	_

~~~


