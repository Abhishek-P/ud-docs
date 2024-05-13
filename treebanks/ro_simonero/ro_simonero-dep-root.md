---
layout: base
title:  'Statistics of root in UD_Romanian-SiMoNERo'
udver: '2'
---

## Treebank Statistics: UD_Romanian-SiMoNERo: Relations: `root`

This relation is universal.

4681 nodes (3%) are attached to their parents as `root`.

4681 instances of `root` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 8.8523819696646.

The following 11 pairs of parts of speech are connected with `root`: -<tt><a href="ro_simonero-pos-VERB.html">VERB</a></tt> (3625; 77% instances), -<tt><a href="ro_simonero-pos-NOUN.html">NOUN</a></tt> (473; 10% instances), -<tt><a href="ro_simonero-pos-ADJ.html">ADJ</a></tt> (438; 9% instances), -<tt><a href="ro_simonero-pos-ADV.html">ADV</a></tt> (43; 1% instances), -<tt><a href="ro_simonero-pos-NUM.html">NUM</a></tt> (36; 1% instances), -<tt><a href="ro_simonero-pos-PRON.html">PRON</a></tt> (33; 1% instances), -<tt><a href="ro_simonero-pos-AUX.html">AUX</a></tt> (22; 0% instances), -<tt><a href="ro_simonero-pos-X.html">X</a></tt> (6; 0% instances), -<tt><a href="ro_simonero-pos-INTJ.html">INTJ</a></tt> (2; 0% instances), -<tt><a href="ro_simonero-pos-PROPN.html">PROPN</a></tt> (2; 0% instances), -<tt><a href="ro_simonero-pos-ADP.html">ADP</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 0	bgColor:blue
# visual-style 0	fgColor:white
# visual-style 0 6 root	color:blue
1	Din	din	ADP	Spsa	AdpType=Prep|Case=Acc	2	case	_	_
2	contra	contra	ADV	Rgp	Degree=Pos	6	obl	_	SpaceAfter=No
3	,	,	PUNCT	COMMA	_	2	punct	_	_
4	venele	venă	NOUN	Ncfpry	Case=Nom|Definite=Def|Gender=Fem|Number=Plur	6	nsubj	_	BioNERLabel=B-ANAT
5	centrale	central	ADJ	Afpfp-n	Definite=Ind|Degree=Pos|Gender=Fem|Number=Plur	4	amod	_	BioNERLabel=I-ANAT
6	devin	deveni	VERB	Vmip3p	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
7	subțiri	subțire	ADJ	Afp-p-n	Definite=Ind|Degree=Pos|Number=Plur	6	xcomp	_	_
8	și	și	CCONJ	Crssp	Polarity=Pos	10	cc	_	_
9	ușor	ușor	ADV	Rgp	Degree=Pos	10	advmod	_	_
10	distensibile	distensibil	ADJ	Afpfp-n	Definite=Ind|Degree=Pos|Gender=Fem|Number=Plur	7	conj	_	SpaceAfter=No
11	.	.	PUNCT	PERIOD	_	6	punct	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 0	bgColor:blue
# visual-style 0	fgColor:white
# visual-style 0 3 root	color:blue
1	Consecința	consecință	NOUN	Ncfsry	Case=Nom|Definite=Def|Gender=Fem|Number=Sing	3	nsubj	_	_
2	este	fi	AUX	Vaip3s	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	3	cop	_	_
3	scăderea	scădere	NOUN	Ncfsry	Case=Nom|Definite=Def|Gender=Fem|Number=Sing	0	root	_	_
4	biodisponibilității	biodisponibilitate	NOUN	Ncfsoy	Case=Gen|Definite=Def|Gender=Fem|Number=Sing	3	nmod	_	_
5	oxidului	oxid	NOUN	Ncmsoy	Case=Gen|Definite=Def|Gender=Masc|Number=Sing	4	nmod	_	BioNERLabel=B-CHEM
6	nitric	nitric	ADJ	Afpms-n	Definite=Ind|Degree=Pos|Gender=Masc|Number=Sing	5	amod	_	BioNERLabel=I-CHEM
7	(	(	PUNCT	LPAR	_	8	punct	_	SpaceAfter=No
8	NO	NO	NOUN	Yn	Abbr=Yes	3	appos	_	BioNERLabel=B-CHEM|SpaceAfter=No
9	)	)	PUNCT	RPAR	_	8	punct	_	SpaceAfter=No
10	.	.	PUNCT	PERIOD	_	3	punct	_	_

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 0	bgColor:blue
# visual-style 0	fgColor:white
# visual-style 0 7 root	color:blue
1	De	de	ADP	Spsa	AdpType=Prep|Case=Acc	7	advmod	_	_
2	aceea	acela	PRON	Pd3fsr	Case=Nom|Gender=Fem|Number=Sing|Person=3|PronType=Dem	1	fixed	_	SpaceAfter=No
3	,	,	PUNCT	COMMA	_	1	punct	_	_
4	testele	test	NOUN	Ncfpry	Case=Nom|Definite=Def|Gender=Fem|Number=Plur	7	nsubj	_	BioNERLabel=B-PROC
5	non-invazive	non-invaziv	ADJ	Afpfp-n	Definite=Ind|Degree=Pos|Gender=Fem|Number=Plur	4	amod	_	BioNERLabel=I-PROC
6	sunt	fi	AUX	Vaip3p	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	7	cop	_	_
7	importante	important	ADJ	Afpfp-n	Definite=Ind|Degree=Pos|Gender=Fem|Number=Plur	0	root	_	_
8	pentru	pentru	ADP	Spsa	AdpType=Prep|Case=Acc	9	case	_	_
9	diagnostic	diagnostic	NOUN	Ncms-n	Definite=Ind|Gender=Masc|Number=Sing	7	obl	_	SpaceAfter=No
10	.	.	PUNCT	PERIOD	_	7	punct	_	_

~~~


