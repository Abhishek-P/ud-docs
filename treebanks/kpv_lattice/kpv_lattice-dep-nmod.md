---
layout: base
title:  'Statistics of nmod in UD_Komi_Zyrian-Lattice'
udver: '2'
---

## Treebank Statistics: UD_Komi_Zyrian-Lattice: Relations: `nmod`

This relation is universal.
There are 4 language-specific subtypes of `nmod`: <tt><a href="kpv_lattice-dep-nmod-lmod.html">nmod:lmod</a></tt>, <tt><a href="kpv_lattice-dep-nmod-obj.html">nmod:obj</a></tt>, <tt><a href="kpv_lattice-dep-nmod-poss.html">nmod:poss</a></tt>, <tt><a href="kpv_lattice-dep-nmod-subj.html">nmod:subj</a></tt>.

321 nodes (4%) are attached to their parents as `nmod`.

307 instances of `nmod` (96%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.33644859813084.

The following 17 pairs of parts of speech are connected with `nmod`: <tt><a href="kpv_lattice-pos-NOUN.html">NOUN</a></tt>-<tt><a href="kpv_lattice-pos-NOUN.html">NOUN</a></tt> (228; 71% instances), <tt><a href="kpv_lattice-pos-ADJ.html">ADJ</a></tt>-<tt><a href="kpv_lattice-pos-NOUN.html">NOUN</a></tt> (27; 8% instances), <tt><a href="kpv_lattice-pos-NOUN.html">NOUN</a></tt>-<tt><a href="kpv_lattice-pos-PRON.html">PRON</a></tt> (16; 5% instances), <tt><a href="kpv_lattice-pos-VERB.html">VERB</a></tt>-<tt><a href="kpv_lattice-pos-NOUN.html">NOUN</a></tt> (16; 5% instances), <tt><a href="kpv_lattice-pos-VERB.html">VERB</a></tt>-<tt><a href="kpv_lattice-pos-PRON.html">PRON</a></tt> (5; 2% instances), <tt><a href="kpv_lattice-pos-NOUN.html">NOUN</a></tt>-<tt><a href="kpv_lattice-pos-PROPN.html">PROPN</a></tt> (4; 1% instances), <tt><a href="kpv_lattice-pos-NOUN.html">NOUN</a></tt>-<tt><a href="kpv_lattice-pos-VERB.html">VERB</a></tt> (4; 1% instances), <tt><a href="kpv_lattice-pos-PRON.html">PRON</a></tt>-<tt><a href="kpv_lattice-pos-NOUN.html">NOUN</a></tt> (4; 1% instances), <tt><a href="kpv_lattice-pos-ADV.html">ADV</a></tt>-<tt><a href="kpv_lattice-pos-NOUN.html">NOUN</a></tt> (3; 1% instances), <tt><a href="kpv_lattice-pos-NOUN.html">NOUN</a></tt>-<tt><a href="kpv_lattice-pos-ADJ.html">ADJ</a></tt> (3; 1% instances), <tt><a href="kpv_lattice-pos-PRON.html">PRON</a></tt>-<tt><a href="kpv_lattice-pos-PRON.html">PRON</a></tt> (3; 1% instances), <tt><a href="kpv_lattice-pos-ADP.html">ADP</a></tt>-<tt><a href="kpv_lattice-pos-NOUN.html">NOUN</a></tt> (2; 1% instances), <tt><a href="kpv_lattice-pos-PROPN.html">PROPN</a></tt>-<tt><a href="kpv_lattice-pos-VERB.html">VERB</a></tt> (2; 1% instances), <tt><a href="kpv_lattice-pos-ADJ.html">ADJ</a></tt>-<tt><a href="kpv_lattice-pos-PRON.html">PRON</a></tt> (1; 0% instances), <tt><a href="kpv_lattice-pos-ADJ.html">ADJ</a></tt>-<tt><a href="kpv_lattice-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="kpv_lattice-pos-NOUN.html">NOUN</a></tt>-<tt><a href="kpv_lattice-pos-DET.html">DET</a></tt> (1; 0% instances), <tt><a href="kpv_lattice-pos-PROPN.html">PROPN</a></tt>-<tt><a href="kpv_lattice-pos-NOUN.html">NOUN</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 1 nmod	color:blue
1	Лун	лун	NOUN	N	Case=Nom|Number=Sing	2	nmod	_	_
2	шӧр	шӧр	NOUN	N	Case=Nom|Number=Sing	3	nmod	_	_
3	кадланьыс	кад	NOUN	N	Case=Apr|Number=Sing|Number[psor]=Sing|Person[psor]=3	7	obl:tmod	_	_
4	нин	нин	ADV	Adv	_	3	advmod:emph	_	_
5	кыськӧ	кысь	ADV	Adv	Case=Ela	7	obl:lmod	_	_
6	шур-шар	шур-шар	ADV	Adv	_	7	advmod	_	_
7	воис	воны	VERB	V	Mood=Ind|Number=Sing|Person=3|Tense=Past	0	root	_	_
8	неыджыд	неыджыд	ADJ	A	Case=Nom|Number=Sing|Polarity=Neg	9	amod	_	_
9	тӧвру	тӧвру	NOUN	N	Case=Nom|Number=Sing	7	nsubj	_	SpaceAfter=No
10	.	.	PUNCT	CLB	_	7	punct	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 3 nmod	color:blue
1	Первойсӧ	первой	ADV	Adv	Clitic=So	4	advmod:tmod	_	OrigLang=ru
2	ичӧтик	ичӧтик	ADJ	A	Case=Nom|Derivation=Ik|Number=Sing	3	amod	_	_
3	баляяс	баля	NOUN	N	Case=Nom|Number=Plur	4	nmod	_	_
4	кодьӧсь	кодь	ADJ	A	Case=Nom|Number[subj]=Plur	0	root	_	SpaceAfter=No
5	.	.	PUNCT	CLB	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 5 nmod	color:blue
1	Бур	бур	ADJ	A	Case=Nom|Number=Sing	2	amod	_	_
2	урожай	урожай	NOUN	N	Case=Nom|Number=Sing	3	nsubj	_	OrigLang=ru
3	воис	воны	VERB	V	Mood=Ind|Number=Sing|Person=3|Tense=Past	0	root	_	_
4	таво	таво	ADV	Adv	_	3	advmod:tmod	_	_
5	миян	ми	PRON	Pron	Case=Gen|Number=Plur|Person=1|PronType=Prs	7	nmod	_	_
6	районувса	районувса	ADJ	A	Case=Nom|Number=Sing	7	amod	_	OrigLang=ru
7	колхозъясын	колхоз	NOUN	N	Case=Ine|Number=Plur	3	obl:lmod	_	OrigLang=ru|SpaceAfter=No
8	.	.	PUNCT	CLB	_	3	punct	_	_

~~~


