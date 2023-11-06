---
layout: base
title:  'Statistics of csubj in UD_Komi_Zyrian-Lattice'
udver: '2'
---

## Treebank Statistics: UD_Komi_Zyrian-Lattice: Relations: `csubj`

This relation is universal.
There are 1 language-specific subtypes of `csubj`: <tt><a href="kpv_lattice-dep-csubj-cop.html">csubj:cop</a></tt>.

22 nodes (0%) are attached to their parents as `csubj`.

12 instances of `csubj` (55%) are right-to-left (child precedes parent).
Average distance between parent and child is 3.54545454545455.

The following 7 pairs of parts of speech are connected with `csubj`: <tt><a href="kpv_lattice-pos-VERB.html">VERB</a></tt>-<tt><a href="kpv_lattice-pos-VERB.html">VERB</a></tt> (11; 50% instances), <tt><a href="kpv_lattice-pos-ADV.html">ADV</a></tt>-<tt><a href="kpv_lattice-pos-VERB.html">VERB</a></tt> (3; 14% instances), <tt><a href="kpv_lattice-pos-VERB.html">VERB</a></tt>-<tt><a href="kpv_lattice-pos-NOUN.html">NOUN</a></tt> (3; 14% instances), <tt><a href="kpv_lattice-pos-ADJ.html">ADJ</a></tt>-<tt><a href="kpv_lattice-pos-VERB.html">VERB</a></tt> (2; 9% instances), <tt><a href="kpv_lattice-pos-ADJ.html">ADJ</a></tt>-<tt><a href="kpv_lattice-pos-NOUN.html">NOUN</a></tt> (1; 5% instances), <tt><a href="kpv_lattice-pos-NOUN.html">NOUN</a></tt>-<tt><a href="kpv_lattice-pos-NOUN.html">NOUN</a></tt> (1; 5% instances), <tt><a href="kpv_lattice-pos-NOUN.html">NOUN</a></tt>-<tt><a href="kpv_lattice-pos-VERB.html">VERB</a></tt> (1; 5% instances).


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 8 csubj	color:blue
1	Колхозъясын	колхоз	NOUN	N	Case=Ine|Number=Plur	3	obl:lmod	_	OrigLang=ru
2	ӧні	ӧні	ADV	Adv	_	3	advmod:tmod	_	_
3	мунӧ	мунны	VERB	V	Mood=Ind|Number=Sing|Person=3|Tense=Pres	0	root	_	_
4	тайӧ	тайӧ	PRON	Pron	Case=Nom|Number=Sing|PronType=Dem	7	det	_	_
5	воӧм	воны	VERB	V	Case=Nom|Number=Sing|Tense=Past|VerbForm=Part	7	acl	_	_
6	озыр	озыр	ADJ	A	Case=Nom|Number=Sing	7	amod	_	_
7	урожайсӧ	урожай	NOUN	N	Case=Acc|Number=Sing|Number[psor]=Sing|Person[psor]=3	8	nmod:obj	_	OrigLang=ru
8	идралӧм	идравны	VERB	V	Case=Nom|Number=Sing|Tense=Past|VerbForm=Part	3	csubj	_	SpaceAfter=No
9	.	.	PUNCT	CLB	_	3	punct	_	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 1 csubj	color:blue
1	Пукавны	пукавны	VERB	V	VerbForm=Inf	5	csubj	_	_
2	вадорын	вадор	NOUN	N	Case=Ine|Number=Sing	1	obl:lmod	_	_
3	водзӧ	водз	ADV	Adv	Case=Ill	5	advmod:lmod	_	_
4	вӧлі	вӧвны	AUX	V	Mood=Ind|Number=Sing|Person=3|Tense=Past	5	cop	_	_
5	весьшӧрӧ	весьшӧрӧ	ADV	Adv	Case=Ill	0	root	_	SpaceAfter=No
6	.	.	PUNCT	CLB	_	5	punct	_	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 2 csubj	color:blue
1	Латвияса	Латвия	PROPN	N	Case=Loc|Number=Sing	2	nmod:lmod	_	GTtags=Prop,Sem/Plc,Sem/Plc,Sg,Der,Der/LocMod,A,Nom
2	му	му	NOUN	N	Case=Nom|Number=Sing	6	csubj	_	GTtags=Sg,Nom
3	нинӧмӧн	нинӧм	PRON	Pron	Case=Ins|Number=Sing|Polarity=Neg	6	obl	_	GTtags=Neg,Sg,Ins
4	ёнасӧ	ёна	ADV	Adv	Clitic=So	6	advmod	_	GTtags=Clt/сӧ
5	оз	оз	AUX	V	Mood=Ind|Number=Sing|Person=3|Polarity=Neg|Tense=Pres	6	aux:neg	_	GTtags=Neg,Ind,Prs,Sg3
6	торъяв	торъявны	VERB	V	Connegative=Yes	0	root	_	GTtags=IV,ConNeg
7	Литваысь	Литва	NOUN	N	Case=Ela|Number=Sing	6	obl	_	GTtags=Prop,Sem/Plc,Sem/Plc,Sg,Ela|SpaceAfter=No
8	,	,	PUNCT	CLB	_	11	punct	_	_
9	местаясыс	места	NOUN	N	Case=Nom|Number=Plur|Number[psor]=Sing|Person[psor]=3	11	nsubj:cop	_	GTtags=Pl,Nom,PxSg3
10	быттьӧ	быттьӧ	ADV	Adv	_	11	advmod:eval	_	GTtags=Parenthetic
11	сэтшӧмӧсь	сэтшӧм	ADJ	A	Number[subj]=Plur|PronType=Dem	6	parataxis	_	GTtags=Det,Dem,Cop,Pl
12	жӧ	жӧ	ADV	Adv	_	11	advmod:eval	_	GTtags=Parenthetic
13	таті	таті	ADV	Adv	Case=Tra	11	advmod:lmod	_	GTtags=Tra|SpaceAfter=No
14	.	.	PUNCT	CLB	_	6	punct	_	_

~~~


