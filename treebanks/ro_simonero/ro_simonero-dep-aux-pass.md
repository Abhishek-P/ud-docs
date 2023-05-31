---
layout: base
title:  'Statistics of aux:pass in UD_Romanian-SiMoNERo'
udver: '2'
---

## Treebank Statistics: UD_Romanian-SiMoNERo: Relations: `aux:pass`

This relation is a language-specific subtype of <tt><a href="ro_simonero-dep-aux.html">aux</a></tt>.

1076 nodes (1%) are attached to their parents as `aux:pass`.

1071 instances of `aux:pass` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.10780669144981.

The following 3 pairs of parts of speech are connected with `aux:pass`: <tt><a href="ro_simonero-pos-VERB.html">VERB</a></tt>-<tt><a href="ro_simonero-pos-AUX.html">AUX</a></tt> (1012; 94% instances), <tt><a href="ro_simonero-pos-ADJ.html">ADJ</a></tt>-<tt><a href="ro_simonero-pos-AUX.html">AUX</a></tt> (58; 5% instances), <tt><a href="ro_simonero-pos-NOUN.html">NOUN</a></tt>-<tt><a href="ro_simonero-pos-AUX.html">AUX</a></tt> (6; 1% instances).


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 2 aux:pass	color:blue
1	Stentarea	stentare	NOUN	Ncfsry	Case=Nom|Definite=Def|Gender=Fem|Number=Sing	3	nsubj:pass	_	BioNERLabel=B-PROC
2	este	fi	AUX	Vaip3s	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	3	aux:pass	_	_
3	rezervată	rezerva	VERB	Vmp--sf	Gender=Fem|Number=Sing|VerbForm=Part	0	root	_	_
4	cazurilor	caz	NOUN	Ncfpoy	Case=Gen|Definite=Def|Gender=Fem|Number=Plur	3	iobj	_	_
5	cu	cu	ADP	Spsa	AdpType=Prep|Case=Acc	6	case	_	_
6	APTL	APTL	NOUN	Yn	Abbr=Yes	4	nmod	_	BioNERLabel=B-PROC
7	suboptimală	suboptimal	ADJ	Afpfsrn	Case=Nom|Definite=Ind|Degree=Pos|Gender=Fem|Number=Sing	6	amod	_	_
8	(	(	PUNCT	LPAR	_	9	punct	_	SpaceAfter=No
9	39	39	NUM	Mc-s-d	Number=Sing|NumForm=Digit|NumType=Card	3	parataxis	_	SpaceAfter=No
10	)	)	PUNCT	RPAR	_	9	punct	_	SpaceAfter=No
11	.	.	PUNCT	PERIOD	_	3	punct	_	_

~~~


~~~ conllu
# visual-style 12	bgColor:blue
# visual-style 12	fgColor:white
# visual-style 13	bgColor:blue
# visual-style 13	fgColor:white
# visual-style 13 12 aux:pass	color:blue
1	Din	din	ADP	Spsa	AdpType=Prep|Case=Acc	3	case	_	_
2	cauza	cauză	NOUN	Ncfsry	Case=Nom|Definite=Def|Gender=Fem|Number=Sing	13	obl	_	_
3	costului	cost	NOUN	Ncmsoy	Case=Gen|Definite=Def|Gender=Masc|Number=Sing	13	obl	_	_
4	ridicat	ridicat	ADJ	Afpms-n	Definite=Ind|Degree=Pos|Gender=Masc|Number=Sing	3	amod	_	_
5	al	al	DET	Tsms	Gender=Masc|Number=Sing|Poss=Yes|PronType=Prs	6	det	_	_
6	materialelor	material	NOUN	Ncfpoy	Case=Gen|Definite=Def|Gender=Fem|Number=Plur	3	nmod	_	SpaceAfter=No
7	,	,	PUNCT	COMMA	_	3	punct	_	_
8	numărul	număr	NOUN	Ncmsry	Case=Nom|Definite=Def|Gender=Masc|Number=Sing	13	nsubj:pass	_	_
9	de	de	ADP	Spsa	AdpType=Prep|Case=Acc	10	case	_	_
10	intervenții	intervenție	NOUN	Ncfp-n	Definite=Ind|Gender=Fem|Number=Plur	8	nmod	_	_
11	a	avea	AUX	Va--3s	Number=Sing|Person=3	13	aux	_	_
12	fost	fi	AUX	Vap--sm	Gender=Masc|Number=Sing|VerbForm=Part	13	aux:pass	_	_
13	limitat	limitat	ADJ	Afpms-n	Definite=Ind|Degree=Pos|Gender=Masc|Number=Sing	0	root	_	SpaceAfter=No
14	.	.	PUNCT	PERIOD	_	13	punct	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 4 aux:pass	color:blue
1	Acești	acest	DET	Dd3mpr---e	Case=Nom|Gender=Masc|Number=Plur|Person=3|Position=Prenom|PronType=Dem	2	det	_	_
2	precursori	precursor	NOUN	Ncmp-n	Definite=Ind|Gender=Masc|Number=Plur	3	nsubj	_	_
3	pot	putea	VERB	Vmip3p	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
4	fi	fi	AUX	Vanp	Tense=Pres|VerbForm=Inf	5	aux:pass	_	_
5	aminoacizi	aminoacid	NOUN	Ncmp-n	Definite=Ind|Gender=Masc|Number=Plur	3	ccomp	_	BioNERLabel=B-CHEM|SpaceAfter=No
6	,	,	PUNCT	COMMA	_	7	punct	_	_
7	lactat	lactat	NOUN	Ncms-n	Definite=Ind|Gender=Masc|Number=Sing	5	conj	_	BioNERLabel=B-CHEM|SpaceAfter=No
8	,	,	PUNCT	COMMA	_	9	punct	_	_
9	piruvat	piruvat	NOUN	Ncms-n	Definite=Ind|Gender=Masc|Number=Sing	5	conj	_	BioNERLabel=B-CHEM
10	și	și	CCONJ	Crssp	Polarity=Pos	11	cc	_	_
11	glicerol	glicerol	NOUN	Ncms-n	Definite=Ind|Gender=Masc|Number=Sing	5	conj	_	BioNERLabel=B-CHEM
12	(	(	PUNCT	LPAR	_	13	punct	_	SpaceAfter=No
13	18	18	NUM	Mc-s-d	Number=Sing|NumForm=Digit|NumType=Card	3	parataxis	_	SpaceAfter=No
14	)	)	PUNCT	RPAR	_	13	punct	_	SpaceAfter=No
15	.	.	PUNCT	PERIOD	_	3	punct	_	_

~~~


