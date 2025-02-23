---
layout: base
title:  'Statistics of acl in UD_Scottish_Gaelic-ARCOSG'
udver: '2'
---

## Treebank Statistics: UD_Scottish_Gaelic-ARCOSG: Relations: `acl`

This relation is universal.
There are 1 language-specific subtypes of `acl`: <tt><a href="gd_arcosg-dep-acl-relcl.html">acl:relcl</a></tt>.

100 nodes (0%) are attached to their parents as `acl`.

100 instances of `acl` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 3.86.

The following 8 pairs of parts of speech are connected with `acl`: <tt><a href="gd_arcosg-pos-NOUN.html">NOUN</a></tt>-<tt><a href="gd_arcosg-pos-VERB.html">VERB</a></tt> (53; 53% instances), <tt><a href="gd_arcosg-pos-NOUN.html">NOUN</a></tt>-<tt><a href="gd_arcosg-pos-NOUN.html">NOUN</a></tt> (16; 16% instances), <tt><a href="gd_arcosg-pos-NOUN.html">NOUN</a></tt>-<tt><a href="gd_arcosg-pos-PRON.html">PRON</a></tt> (14; 14% instances), <tt><a href="gd_arcosg-pos-VERB.html">VERB</a></tt>-<tt><a href="gd_arcosg-pos-VERB.html">VERB</a></tt> (7; 7% instances), <tt><a href="gd_arcosg-pos-VERB.html">VERB</a></tt>-<tt><a href="gd_arcosg-pos-NOUN.html">NOUN</a></tt> (3; 3% instances), <tt><a href="gd_arcosg-pos-VERB.html">VERB</a></tt>-<tt><a href="gd_arcosg-pos-PRON.html">PRON</a></tt> (3; 3% instances), <tt><a href="gd_arcosg-pos-ADJ.html">ADJ</a></tt>-<tt><a href="gd_arcosg-pos-PRON.html">PRON</a></tt> (2; 2% instances), <tt><a href="gd_arcosg-pos-NOUN.html">NOUN</a></tt>-<tt><a href="gd_arcosg-pos-ADJ.html">ADJ</a></tt> (2; 2% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 5 acl	color:blue
1	oh	oh	INTJ	I	_	3	discourse	_	_
2	thì	thì	INTJ	I	_	3	discourse	_	_
3	fhios	fios	NOUN	Ncsmn	Case=Nom|Gender=Masc|Number=Sing	0	root	_	_
4	gun	gu	PART	Qa	PartType=Cmpl	5	mark:prt	_	_
5	robh	bi	VERB	V-s--d	Mood=Ind|Tense=Past|VerbForm=Fin	3	acl	_	_
6	e	e	PRON	Pp3sm	Gender=Masc|Number=Sing|Person=3|PronType=Prs	5	nsubj	_	_
7	ag	ag	PART	Sa	_	8	case	_	_
8	obair	obraich	NOUN	Nv	VerbForm=Vnoun	5	xcomp:pred	_	_
9	air	air	ADP	Sp	_	10	case	_	_
10	iad	iad	PRON	Pp3p	Number=Plur|Person=3|PronType=Prs	8	obl	_	_
11	an-raoir	an-raoir	ADV	Rt	_	8	advmod	_	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 8 acl	color:blue
1	chan	cha	PART	Qn	PartType=Vb|Polarity=Neg	2	mark:prt	_	_
2	eil	bi	VERB	V-p--d	Mood=Ind|Tense=Pres|VerbForm=Fin	0	root	_	_
3	fhios	fios	NOUN	Ncsmn	Case=Nom|Gender=Masc|Number=Sing	2	nsubj	_	_
4	aig	aig	ADP	Sp	_	5	case	_	_
5	mi	mi	PRON	Pp1s	Number=Sing|Person=1|PronType=Prs	2	xcomp:pred	_	_
6	dè	dè	PRON	Uq	PronType=Int	8	nmod	_	_
7	an	an	DET	Tds	Definite=Def|Number=Sing|PronType=Art	8	det	_	_
8	title	title	NOUN	Xfe	Foreign=Yes	3	acl	_	_
9	a	a	PART	Q-r	PartType=Vb|PronType=Rel	10	nsubj	_	_
10	bh’	bi	VERB	V-s	Mood=Ind|Tense=Past|VerbForm=Fin	8	acl:relcl	_	_
11	air	air	ADP	Sp	_	12	case	_	_
12	e	e	PRON	Pp3sm	Gender=Masc|Number=Sing|Person=3|PronType=Prs	10	xcomp:pred	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 4 acl	color:blue
1	Johnson	Johnson	PROPN	Nn	_	0	root	_	_
2	a'	ag	PART	Sa	_	3	case	_	_
3	faicinn	faic	NOUN	Nv	VerbForm=Vnoun	1	xcomp:pred	_	_
4	cò	cò	PRON	Uq	PronType=Int	3	acl	_	_
5	th'	bi	VERB	V-p	Mood=Ind|Tense=Pres|VerbForm=Fin	4	acl:relcl	_	_
6	aig	aig	ADP	Sp	_	7	case	_	_
7	e	e	PRON	Pp3sm	Gender=Masc|Number=Sing|Person=3|PronType=Prs	5	xcomp:pred	_	_

~~~


