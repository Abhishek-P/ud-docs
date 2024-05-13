---
layout: base
title:  'Statistics of ccomp in UD_Romanian'
udver: '2'
---

## Treebank Statistics: UD_Romanian: Relations: `ccomp`

This relation is universal.
There are 1 language-specific subtypes of `ccomp`: <tt><a href="ro-dep-ccomp-pmod.html">ccomp:pmod</a></tt>.

2319 nodes (1%) are attached to their parents as `ccomp`.

2311 instances of `ccomp` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 3.39327296248383.

The following 20 pairs of parts of speech are connected with `ccomp`: <tt><a href="ro-pos-VERB.html">VERB</a></tt>-<tt><a href="ro-pos-VERB.html">VERB</a></tt> (2108; 91% instances), <tt><a href="ro-pos-VERB.html">VERB</a></tt>-<tt><a href="ro-pos-ADJ.html">ADJ</a></tt> (70; 3% instances), <tt><a href="ro-pos-VERB.html">VERB</a></tt>-<tt><a href="ro-pos-NOUN.html">NOUN</a></tt> (58; 3% instances), <tt><a href="ro-pos-VERB.html">VERB</a></tt>-<tt><a href="ro-pos-ADV.html">ADV</a></tt> (18; 1% instances), <tt><a href="ro-pos-ADV.html">ADV</a></tt>-<tt><a href="ro-pos-VERB.html">VERB</a></tt> (15; 1% instances), <tt><a href="ro-pos-ADJ.html">ADJ</a></tt>-<tt><a href="ro-pos-VERB.html">VERB</a></tt> (11; 0% instances), <tt><a href="ro-pos-VERB.html">VERB</a></tt>-<tt><a href="ro-pos-PRON.html">PRON</a></tt> (9; 0% instances), <tt><a href="ro-pos-INTJ.html">INTJ</a></tt>-<tt><a href="ro-pos-VERB.html">VERB</a></tt> (8; 0% instances), <tt><a href="ro-pos-NOUN.html">NOUN</a></tt>-<tt><a href="ro-pos-VERB.html">VERB</a></tt> (5; 0% instances), <tt><a href="ro-pos-PART.html">PART</a></tt>-<tt><a href="ro-pos-VERB.html">VERB</a></tt> (3; 0% instances), <tt><a href="ro-pos-VERB.html">VERB</a></tt>-<tt><a href="ro-pos-ADP.html">ADP</a></tt> (3; 0% instances), <tt><a href="ro-pos-AUX.html">AUX</a></tt>-<tt><a href="ro-pos-VERB.html">VERB</a></tt> (2; 0% instances), <tt><a href="ro-pos-VERB.html">VERB</a></tt>-<tt><a href="ro-pos-NUM.html">NUM</a></tt> (2; 0% instances), <tt><a href="ro-pos-ADJ.html">ADJ</a></tt>-<tt><a href="ro-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="ro-pos-ADP.html">ADP</a></tt>-<tt><a href="ro-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="ro-pos-NOUN.html">NOUN</a></tt>-<tt><a href="ro-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="ro-pos-NOUN.html">NOUN</a></tt>-<tt><a href="ro-pos-PRON.html">PRON</a></tt> (1; 0% instances), <tt><a href="ro-pos-SCONJ.html">SCONJ</a></tt>-<tt><a href="ro-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="ro-pos-VERB.html">VERB</a></tt>-<tt><a href="ro-pos-AUX.html">AUX</a></tt> (1; 0% instances), <tt><a href="ro-pos-VERB.html">VERB</a></tt>-<tt><a href="ro-pos-PROPN.html">PROPN</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 4 ccomp	color:blue
1	Cum	cum	ADV	Rw	PronType=Int,Rel	2	advmod	_	_
2	puteai	putea	VERB	Vmii2s	Mood=Ind|Number=Sing|Person=2|Tense=Imp|VerbForm=Fin	0	root	_	_
3	să	să	PART	Qs	Mood=Sub	4	mark	_	_
4	comunici	comunica	VERB	Vmip2s	Mood=Ind|Number=Sing|Person=2|Tense=Pres|VerbForm=Fin	2	ccomp	_	_
5	cu	cu	ADP	Spsa	AdpType=Prep|Case=Acc	6	case	_	_
6	viitorul	viitor	NOUN	Ncmsry	Case=Acc,Nom|Definite=Def|Gender=Masc|Number=Sing	4	obl	_	SpaceAfter=No
7	?	?	PUNCT	QUEST	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 12	bgColor:blue
# visual-style 12	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 12 ccomp	color:blue
1	Intră	intra	VERB	Vmis3s	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin	0	root	_	_
2	pe	pe	ADP	Spsa	AdpType=Prep|Case=Acc	3	case	_	_
3	dindos	dindos	NOUN	Ncmsrn	Case=Acc,Nom|Definite=Ind|Gender=Masc|Number=Sing	1	obl	_	_
4	în	în	ADP	Spsa	AdpType=Prep|Case=Acc	5	case	_	_
5	sufragerie	sufragerie	NOUN	Ncfsrn	Case=Acc,Nom|Definite=Ind|Gender=Fem|Number=Sing	1	nmod:pmod	_	SpaceAfter=No
6	,	,	PUNCT	COMMA	_	8	punct	_	_
7	unde	unde	ADV	Rw	PronType=Int,Rel	12	advmod	_	_
8	constată	constata	VERB	Vmis3s	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin	5	acl	_	_
9	că	că	SCONJ	Csssp	Polarity=Pos	12	mark	_	_
10	masa	masă	NOUN	Ncfsry	Case=Acc,Nom|Definite=Def|Gender=Fem|Number=Sing	12	nsubj	_	_
11	era	fi	AUX	Vmii3s	Mood=Ind|Number=Sing|Person=3|Tense=Imp|VerbForm=Fin	12	cop	_	_
12	nepusă	nepus	ADJ	Afpfsrn	Case=Acc,Nom|Definite=Ind|Degree=Pos|Gender=Fem|Number=Sing	8	ccomp	_	SpaceAfter=No
13	.	.	PUNCT	PERIOD	_	1	punct	_	_

~~~


~~~ conllu
# visual-style 11	bgColor:blue
# visual-style 11	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 11 ccomp	color:blue
1	n-	nu	PART	Qz-y	Polarity=Neg|Variant=Short	3	advmod	_	SpaceAfter=No
2	ai	avea	AUX	Va--2s	Number=Sing|Person=2	3	aux	_	_
3	avea	avea	VERB	Vmnp	Tense=Pres|VerbForm=Inf	0	root	_	_
4	baza	bază	NOUN	Ncfsry	Case=Acc,Nom|Definite=Def|Gender=Fem|Number=Sing	3	obj	_	_
5	pentru	pentru	ADP	Spsa	AdpType=Prep|Case=Acc	7	case	_	_
6	a	a	PART	Qn	PartType=Inf	7	mark	_	_
7	afirma	afirma	VERB	Vmnp	Tense=Pres|VerbForm=Inf	4	acl	_	_
8	că	că	SCONJ	Csssp	Polarity=Pos	11	mark	_	_
9	e	fi	AUX	Vmip3s	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	11	cop	_	_
10	un	un	DET	Timsr	Case=Acc,Nom|Gender=Masc|Number=Sing|PronType=Ind	11	det	_	_
11	cadavru	cadavru	NOUN	Ncms-n	Definite=Ind|Gender=Masc|Number=Sing	7	ccomp	_	SpaceAfter=No
12	.	.	PUNCT	PERIOD	_	3	punct	_	_

~~~


