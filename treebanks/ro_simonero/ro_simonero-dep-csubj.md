---
layout: base
title:  'Statistics of csubj in UD_Romanian-SiMoNERo'
udver: '2'
---

## Treebank Statistics: UD_Romanian-SiMoNERo: Relations: `csubj`

This relation is universal.
There are 1 language-specific subtypes of `csubj`: <tt><a href="ro_simonero-dep-csubj-pass.html">csubj:pass</a></tt>.

297 nodes (0%) are attached to their parents as `csubj`.

290 instances of `csubj` (98%) are left-to-right (parent precedes child).
Average distance between parent and child is 3.15151515151515.

The following 13 pairs of parts of speech are connected with `csubj`: <tt><a href="ro_simonero-pos-VERB.html">VERB</a></tt>-<tt><a href="ro_simonero-pos-VERB.html">VERB</a></tt> (216; 73% instances), <tt><a href="ro_simonero-pos-ADV.html">ADV</a></tt>-<tt><a href="ro_simonero-pos-VERB.html">VERB</a></tt> (37; 12% instances), <tt><a href="ro_simonero-pos-VERB.html">VERB</a></tt>-<tt><a href="ro_simonero-pos-ADJ.html">ADJ</a></tt> (15; 5% instances), <tt><a href="ro_simonero-pos-ADJ.html">ADJ</a></tt>-<tt><a href="ro_simonero-pos-VERB.html">VERB</a></tt> (9; 3% instances), <tt><a href="ro_simonero-pos-ADV.html">ADV</a></tt>-<tt><a href="ro_simonero-pos-NOUN.html">NOUN</a></tt> (5; 2% instances), <tt><a href="ro_simonero-pos-ADV.html">ADV</a></tt>-<tt><a href="ro_simonero-pos-ADJ.html">ADJ</a></tt> (4; 1% instances), <tt><a href="ro_simonero-pos-VERB.html">VERB</a></tt>-<tt><a href="ro_simonero-pos-NOUN.html">NOUN</a></tt> (4; 1% instances), <tt><a href="ro_simonero-pos-NOUN.html">NOUN</a></tt>-<tt><a href="ro_simonero-pos-VERB.html">VERB</a></tt> (2; 1% instances), <tt><a href="ro_simonero-pos-AUX.html">AUX</a></tt>-<tt><a href="ro_simonero-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="ro_simonero-pos-NOUN.html">NOUN</a></tt>-<tt><a href="ro_simonero-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="ro_simonero-pos-NOUN.html">NOUN</a></tt>-<tt><a href="ro_simonero-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="ro_simonero-pos-VERB.html">VERB</a></tt>-<tt><a href="ro_simonero-pos-PRON.html">PRON</a></tt> (1; 0% instances), <tt><a href="ro_simonero-pos-VERB.html">VERB</a></tt>-<tt><a href="ro_simonero-pos-X.html">X</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 4 csubj	color:blue
1	Bolnavii	bolnav	NOUN	Ncmpry	Case=Nom|Definite=Def|Gender=Masc|Number=Plur	4	nsubj	_	_
2	trebuie	trebui	VERB	Vmip3	Mood=Ind|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
3	să	să	PART	Qs	Mood=Sub	4	mark	_	_
4	trateze	trata	VERB	Vmsp3	Mood=Sub|Person=3|Tense=Pres|VerbForm=Fin	2	csubj	_	_
5	ambele	ambele	NUM	Mlfpr	Case=Nom|Gender=Fem|Number=Plur|NumType=Card|PronType=Tot	6	nummod	_	_
6	boli	boală	NOUN	Ncfp-n	Definite=Ind|Gender=Fem|Number=Plur	4	obj	_	BioNERLabel=B-DISO|SpaceAfter=No
7	.	.	PUNCT	PERIOD	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 6 csubj	color:blue
1	Este	fi	AUX	Vaip3s	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	4	cop	_	_
2	de	de	ADP	Spsa	AdpType=Prep|Case=Acc	4	advmod	_	_
3	asemenea	asemenea	ADV	Rgp	Degree=Pos	2	fixed	_	_
4	necesar	necesar	ADV	Rgp	Degree=Pos	0	root	_	_
5	să	să	PART	Qs	Mood=Sub	6	mark	_	_
6	țineți	ține	VERB	Vmsp2p	Mood=Sub|Number=Plur|Person=2|Tense=Pres|VerbForm=Fin	4	csubj	_	_
7	acul	ac	NOUN	Ncmsry	Case=Nom|Definite=Def|Gender=Masc|Number=Sing	6	obj	_	_
8	în	în	ADP	Spsa	AdpType=Prep|Case=Acc	9	case	_	_
9	piele	piele	NOUN	Ncfsrn	Case=Nom|Definite=Ind|Gender=Fem|Number=Sing	6	obl	_	_
10	și	și	CCONJ	Crssp	Polarity=Pos	12	cc	_	_
11	să	să	PART	Qs	Mood=Sub	12	mark	_	_
12	numărați	număra	VERB	Vmsp2p	Mood=Sub|Number=Plur|Person=2|Tense=Pres|VerbForm=Fin	6	conj	_	SpaceAfter=No
13	.	.	PUNCT	PERIOD	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 13	bgColor:blue
# visual-style 13	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 13 csubj	color:blue
1	Durata	durată	NOUN	Ncfsry	Case=Nom|Definite=Def|Gender=Fem|Number=Sing	13	nsubj	_	_
2	de	de	ADP	Spsa	AdpType=Prep|Case=Acc	3	case	_	_
3	administrare	administrare	NOUN	Ncfsrn	Case=Nom|Definite=Ind|Gender=Fem|Number=Sing	1	nmod	_	_
4	a	al	DET	Tsfs	Gender=Fem|Number=Sing|Poss=Yes|PronType=Prs	5	det	_	_
5	nitroprusiatului	nitroprusiat	NOUN	Ncmsoy	Case=Gen|Definite=Def|Gender=Masc|Number=Sing	3	nmod	_	BioNERLabel=B-CHEM
6	de	de	ADP	Spsa	AdpType=Prep|Case=Acc	7	case	_	BioNERLabel=I-CHEM
7	sodiu	sodiu	NOUN	Ncms-n	Definite=Ind|Gender=Masc|Number=Sing	5	nmod	_	BioNERLabel=I-CHEM
8	nu	nu	PART	Qz	Polarity=Neg	9	advmod	_	_
9	trebuie	trebui	VERB	Vmip3	Mood=Ind|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
10	să	să	PART	Qs	Mood=Sub	13	mark	_	_
11	fie	fi	AUX	Vasp3	Mood=Sub|Person=3|Tense=Pres|VerbForm=Fin	13	cop	_	_
12	mai	mai	ADV	Rp	_	13	advmod	_	_
13	mare	mare	ADJ	Afpfsrn	Case=Nom|Definite=Ind|Degree=Pos|Gender=Fem|Number=Sing	9	csubj	_	_
14	de	de	ADP	Spsa	AdpType=Prep|Case=Acc	18	case	_	_
15	24	24	NUM	Mc-s-d	Number=Sing|NumForm=Digit|NumType=Card	18	nummod	_	SpaceAfter=No
16	-	-	PUNCT	DASH	_	17	punct	_	SpaceAfter=No
17	48	48	NUM	Mc-s-d	Number=Sing|NumForm=Digit|NumType=Card	15	conj	_	_
18	ore	oră	NOUN	Ncfp-n	Definite=Ind|Gender=Fem|Number=Plur	13	obl	_	SpaceAfter=No
19	.	.	PUNCT	PERIOD	_	9	punct	_	_

~~~


