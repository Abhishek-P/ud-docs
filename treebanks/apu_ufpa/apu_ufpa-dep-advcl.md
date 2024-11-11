---
layout: base
title:  'Statistics of advcl in UD_Apurina-UFPA'
udver: '2'
---

## Treebank Statistics: UD_Apurina-UFPA: Relations: `advcl`

This relation is universal.
There are 1 language-specific subtypes of `advcl`: <tt><a href="apu_ufpa-dep-advcl-tcl.html">advcl:tcl</a></tt>.

7 nodes (1%) are attached to their parents as `advcl`.

4 instances of `advcl` (57%) are left-to-right (parent precedes child).
Average distance between parent and child is 2.28571428571429.

The following 4 pairs of parts of speech are connected with `advcl`: <tt><a href="apu_ufpa-pos-VERB.html">VERB</a></tt>-<tt><a href="apu_ufpa-pos-VERB.html">VERB</a></tt> (4; 57% instances), <tt><a href="apu_ufpa-pos-ADJ.html">ADJ</a></tt>-<tt><a href="apu_ufpa-pos-NOUN.html">NOUN</a></tt> (1; 14% instances), <tt><a href="apu_ufpa-pos-ADJ.html">ADJ</a></tt>-<tt><a href="apu_ufpa-pos-VERB.html">VERB</a></tt> (1; 14% instances), <tt><a href="apu_ufpa-pos-NOUN.html">NOUN</a></tt>-<tt><a href="apu_ufpa-pos-VERB.html">VERB</a></tt> (1; 14% instances).


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 4 advcl	color:blue
1	Inhinhiã	inhinhiã	ADV	Adv	_	2	advmod:tmod	_	gloss[pt]=então
2	atamatary	atama	VERB	XPOS=ver-VBLZ	Number[obj]=Sing|Person[obj]=3	0	root	_	gloss[pt]=ver-VBLZ-3SG.M.O
3	ãkiti	hãkiti	NOUN	N	Case=Nom|Gender=Masc|Number=Sing	2	obj:agent	_	gloss[pt]=onça
4	nhikanãtary	nhi	VERB	XPOS=comer-PRED-PROGR-VBLZ-3SG.M.O	Aspect=Prog|Gender[obj]=Masc|Number[obj]=Sing|Person[obj]=3	2	advcl	_	gloss[pt]=comer-PRED-PROGR-VBLZ-3SG.M.O
5	ixuwa	ixuwa	NOUN	XPOS=tamanduá	_	6	nmod:poss	_	gloss[pt]=tamanduá
6	xinhi	xinhi	NOUN	XPOS=carne.de	_	4	obj	_	gloss[pt]=carne.de|SpaceAfter=No
7	.	.	PUNCT	_	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 4 advcl	color:blue
1	Txamary	txamary	CCONJ	XPOS=AUX-FRUSTR	Gender[obj]=Masc|Number[obj]=Sing|Person[obj]=3	4	cc	_	gloss[pt]=AUX-FRUSTR-3SG.M.O
2	nynuwa	nynuwa	PRON	Pron	Case=Nom|Number=Plur|Person=3|PronType=Prs	3	det	_	gloss[pt]=3PL
3	aapuku	awapukutxi	NOUN	XPOS=casa.de	Case=Nom|Gender=Masc|Gender[psor]=Masc|Number=Sing|Number[psor]=Sing|Possessed=Yes	4	nsubj	_	gloss[pt]=casa.de
4	kiumãtxipeinhinhixika	kiumã	NOUN	XPOS=velho.de-N.POSSD-PFTV-SER-AFET-palha	_	6	advcl	_	gloss[pt]=velho.de-N.POSSD-PFTV-SER-AFET-palha|SpaceAfter=No
5	,	,	PUNCT	_	_	4	punct	_	_
6	patsukarepyryna	tsuka	ADJ	XPOS=ATRIB.INTENS-??-POSSD-???	_	0	root	_	gloss[pt]=ATRIB.INTENS-??-POSSD-???
7	awinhinã	awinhitxi	NOUN	XPOS=casa.de	Case=Loc|Number=Sing|Possessed=Yes	6	nsubj	_	gloss[pt]=casa.de-?LOC|SpaceAfter=No
8	.	.	PUNCT	_	_	6	punct	_	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 5 advcl	color:blue
1	Ataũpytykara	ataũ	ADJ	A	_	0	root	_	_
2	pitxa	txa	AUX	_	Number[subj]=Sing|Person[subj]=2	1	cop	_	GTtags=Aux,ScSg2
3	kutxi	kutxi	SCONJ	CS	_	5	mark	_	_
4	nyry	yry	NOUN	N	Case=Nom|Gender=Masc|Number=Sing|Number[psor]=Sing|Person[psor]=1|Possessed=Yes	5	nsubj	_	GTtags=Msc,Sg,PxSg1,Possd,Nom
5	xinhikapikary	xinhika	VERB	V	Gender[obj]=Masc|Number[obj]=Plur,Sing|Person[obj]=3	1	advcl	_	GTtags=TV,Hab,Pred,Oc3M
6	pyry	yry	NOUN	N	Case=Nom|Gender=Masc|Number=Sing|Number[psor]=Sing|Person[psor]=2|Possessed=Yes	5	obj	_	GTtags=Msc,Sg,PxSg2,Possd,Nom|SpaceAfter=No
7	.	.	PUNCT	PUNCT	_	1	punct	_	_

~~~


