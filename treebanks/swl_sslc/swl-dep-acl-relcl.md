---
layout: base
title:  'Statistics of acl:relcl in UD_Swedish_Sign_Language'
udver: '2'
---

## Treebank Statistics: UD_Swedish_Sign_Language: Relations: `acl:relcl`

This relation is a language-specific subtype of <tt><a href="swl-dep-acl.html">acl</a></tt>.

8 nodes (0%) are attached to their parents as `acl:relcl`.

7 instances of `acl:relcl` (88%) are left-to-right (parent precedes child).
Average distance between parent and child is 3.75.

The following 5 pairs of parts of speech are connected with `acl:relcl`: <tt><a href="swl-pos-NOUN.html">NOUN</a></tt>-<tt><a href="swl-pos-VERB.html">VERB</a></tt> (3; 38% instances), <tt><a href="swl-pos-VERB.html">VERB</a></tt>-<tt><a href="swl-pos-VERB.html">VERB</a></tt> (2; 25% instances), <tt><a href="swl-pos-NOUN.html">NOUN</a></tt>-<tt><a href="swl-pos-ADJ.html">ADJ</a></tt> (1; 13% instances), <tt><a href="swl-pos-NOUN.html">NOUN</a></tt>-<tt><a href="swl-pos-NOUN.html">NOUN</a></tt> (1; 13% instances), <tt><a href="swl-pos-VERB.html">VERB</a></tt>-<tt><a href="swl-pos-NOUN.html">NOUN</a></tt> (1; 13% instances).


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 8 acl:relcl	color:blue
1	JA@ub@z	_	INTJ	INTERJ	_	9	discourse	_	_
2	POJKE	_	NOUN	NN	_	9	nsubj	_	_
3	LITEN-PERSON@kl	_	NOUN	NNKL	_	2	clf	_	_
4	SE-UT	_	VERB	VB	_	2	cop	_	_
5	SJU_ÅTTA	_	NUM	RG	_	6	nummod	_	_
6	ÅR@b	_	NOUN	NN	_	2	acl:relcl	_	_
7	HUND	_	NOUN	NN	_	2	conj	_	_
8	SITTA(VVb)	_	VERB	VBAV	_	7	acl:relcl	_	_
9	TITTA-PÅ@z	_	VERB	VB	_	0	root	_	_
10	TITTA-PÅ	_	VERB	VB	_	9	conj	_	_

~~~


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 6 acl:relcl	color:blue
1	HA	_	VERB	VB	_	0	root	_	_
2	form(Yb)@p@&	_	VERB	VBAV	_	4	reparandum	_	_
3	GLAS	_	NOUN	NN	_	4	compound	_	_
4	FORM(YYb)+BESKRIVNING@p	_	VERB	VBAV	_	1	obj	_	_
5	FORM(Yb)@p@hd	_	VERB	VBAV	_	6	obl	_	_
6	INUTI	_	VERB	VBPP	_	1	acl:relcl	_	_
7	GRODA	_	NOUN	NN	_	6	nsubj	_	_
8	DJUR(JJv)@ca	_	VERB	VBCA	_	6	conj	_	_
9	AVGRÄNS	_	X	BOJ	_	10	obl	_	_
10	INUTI	_	VERB	VBPP	_	6	conj	_	_
11	TITTA-PÅ	_	VERB	VB	_	1	conj	_	_
12	SAMTALA	_	VERB	VB	_	1	conj	_	_
13	GLOSA:(PD)@z	_	X	?	_	1	conj	_	_

~~~


~~~ conllu
# visual-style 13	bgColor:blue
# visual-style 13	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 13 acl:relcl	color:blue
1	GRODA	_	NOUN	NN	_	2	nmod:poss	_	_
2	MAMMA*PAPPA	_	NOUN	NN	_	3	nsubj	_	_
3	SITTA(VVb)	_	VERB	VBAV?/VB?	_	0	root	_	_
4	SITTA(Vb)@hd	_	VERB	VBAV	_	3	conj	_	_
5	UNGE	_	NOUN	NN	_	6	nsubj	_	_
6	SITTA(Vb).FL	_	VERB	VBAV	_	3	conj	_	_
7	HEJ-DÅ@g@z	_	X	G	_	3	conj	_	_
8	EN-TILL	_	NUM	RG	_	9	nummod	_	_
9	UNGE	_	NOUN	NN	_	11	nsubj	_	_
10	BAKOM	_	ADP	PP	_	11	advmod	_	_
11	SITTA(Vb)	_	VERB	VBAV	_	3	conj	_	_
12	SYNS	_	VERB	VB	_	13	cop	_	_
13	TJOCK	_	ADJ	JJ	_	9	acl:relcl	_	_
14	OMÖJLIG	_	ADV	AB	_	16	aux	_	_
15	SITTA(Vb)@hd	_	VERB	VBAV	_	3	conj	_	_
16	VARELSE(Vb)+HOPPA-UPP@p	_	VERB	VBAV	_	3	conj	_	_
17	PASSIVERAD@z	_	ADJ	JJ	_	3	conj	_	_

~~~


