---
layout: base
title:  'Statistics of case in UD_Turkish-GB'
udver: '2'
---

## Treebank Statistics: UD_Turkish-GB: Relations: `case`

This relation is universal.

347 nodes (2%) are attached to their parents as `case`.

347 instances of `case` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.06628242074928.

The following 9 pairs of parts of speech are connected with `case`: <tt><a href="tr_gb-pos-NOUN.html">NOUN</a></tt>-<tt><a href="tr_gb-pos-ADP.html">ADP</a></tt> (212; 61% instances), <tt><a href="tr_gb-pos-PRON.html">PRON</a></tt>-<tt><a href="tr_gb-pos-ADP.html">ADP</a></tt> (74; 21% instances), <tt><a href="tr_gb-pos-NUM.html">NUM</a></tt>-<tt><a href="tr_gb-pos-ADP.html">ADP</a></tt> (20; 6% instances), <tt><a href="tr_gb-pos-NOUN.html">NOUN</a></tt>-<tt><a href="tr_gb-pos-ADV.html">ADV</a></tt> (15; 4% instances), <tt><a href="tr_gb-pos-PROPN.html">PROPN</a></tt>-<tt><a href="tr_gb-pos-ADP.html">ADP</a></tt> (15; 4% instances), <tt><a href="tr_gb-pos-PRON.html">PRON</a></tt>-<tt><a href="tr_gb-pos-ADV.html">ADV</a></tt> (4; 1% instances), <tt><a href="tr_gb-pos-NOUN.html">NOUN</a></tt>-<tt><a href="tr_gb-pos-NOUN.html">NOUN</a></tt> (3; 1% instances), <tt><a href="tr_gb-pos-PROPN.html">PROPN</a></tt>-<tt><a href="tr_gb-pos-NOUN.html">NOUN</a></tt> (3; 1% instances), <tt><a href="tr_gb-pos-PRON.html">PRON</a></tt>-<tt><a href="tr_gb-pos-NOUN.html">NOUN</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 2 case	color:blue
1	Öğleden	öğle	NOUN	_	Case=Abl|Number=Sing	4	obl:tmod	_	_
2	sonra	sonra	ADP	_	_	1	case	_	_
3	bize	biz	PRON	_	Case=Dat|Number=Sing|Person=1|PronType=Prs	4	obl	_	_
4	gelsin	gel	VERB	_	Mood=Opt|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	SpaceAfter=No
5	.	.	PUNCT	_	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 4 case	color:blue
1	Londra	Londra	PROPN	_	Number=Sing	5	nsubj	_	_
2	sonbaharda	sonbahar	NOUN	_	Case=Loc|Number=Sing	5	obl:tmod	_	_
3	o	o	PRON	_	Case=Nom|Number=Sing|PronType=Dem	5	nmod	_	_
4	kadar	kadar	ADP	_	_	3	case	_	_
5	güzel	güzel	ADJ	_	_	0	root	_	_
6	olur	ol	AUX	_	Aspect=Hab|Mood=Gen|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	5	cop	_	_
7	ki	ki	ADV	_	_	5	advmod:emph	_	SpaceAfter=No
8	!	!	PUNCT	_	_	5	punct	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 3 case	color:blue
1	Saat	saat	NOUN	_	Case=Nom|Number=Sing	2	nmod	_	_
2	ikiden	iki	NUM	_	Case=Abl|Number=Sing|NumType=Card	6	obl:tmod	_	_
3	sonra	sonra	ADP	_	_	2	case	_	_
4	beni	ben	PRON	_	Case=Acc|Number=Sing|Person=1|PronType=Prs	6	obj	_	_
5	telefonla	telefon	NOUN	_	Case=Ins|Number=Sing	6	obl	_	_
6	ara	ara	VERB	_	Mood=Imp|Number=Sing|Person=2|Tense=Pres|VerbForm=Fin	0	root	_	SpaceAfter=No
7	.	.	PUNCT	_	_	6	punct	_	_

~~~


