---
layout: relation
title: 'nmod:poss'
shortdef: 'possessive nominal modifier'
udver: '2'
---

The `nmod:poss` subtype of [nmod]() is used for pronominal suffixes on nouns.

~~~ sdparse
אבי ו \n father his
nmod:poss(אבי, ו)
~~~

אביו
"his father"

~~~ conllu
# sent_id = Masoretic-Genesis-2:1-hbo
# text = וַיְכֻלּ֛וּ הַשָּׁמַ֥יִם וְהָאָ֖רֶץ וְכָל־צְבָאָֽם׃
# visual-style 11 12 nmod:poss color:blue
1-2	וַיְכֻלּ֛וּ	_	_	_	_	_	_	_	_
1	וַ	ו	CCONJ	conj	_	2	cc	_	Gloss=and|Ref=GEN_2.1
2	יְכֻלּ֛וּ	כלה	VERB	verb	Gender=Masc|HebBinyan=PUAL|Mood=Ind|Number=Plur|Person=3|Tense=Past|VerbForm=Fin	0	root	_	Gloss=be complete|Ref=GEN_2.1
3-4	הַשָּׁמַ֥יִם	_	_	_	_	_	_	_	_
3	הַ	ה	DET	art	PronType=Art	4	det	_	Gloss=the|Ref=GEN_2.1
4	שָּׁמַ֥יִם	שׁמים	NOUN	subs	Gender=Masc|Number=Plur	2	nsubj	_	Gloss=heavens|Ref=GEN_2.1
5-7	וְהָאָ֖רֶץ	_	_	_	_	_	_	_	_
5	וְ	ו	CCONJ	conj	_	7	cc	_	Gloss=and|Ref=GEN_2.1
6	הָ	ה	DET	art	PronType=Art	7	det	_	Gloss=the|Ref=GEN_2.1
7	אָ֖רֶץ	ארץ	NOUN	subs	Gender=Fem|Number=Sing	4	conj	_	Gloss=earth|Ref=GEN_2.1
8-9	וְכָל	_	_	_	_	_	_	_	SpaceAfter=No
8	וְ	ו	CCONJ	conj	_	9	cc	_	Gloss=and|Ref=GEN_2.1
9	כָל	כל	NOUN	subs	Gender=Masc|Number=Sing	4	conj	_	Gloss=whole|Ref=GEN_2.1
10	־	־	PUNCT	punct	_	11	punct	_	Ref=GEN_2.1|SpaceAfter=No
11-12	צְבָאָֽם	_	_	_	_	_	_	_	SpaceAfter=No
11	צְבָאָֽ	צבא	NOUN	subs	Gender=Masc|Number=Sing	9	compound:smixut	_	Gloss=service|Ref=GEN_2.1
12	ם	הם	PRON	prn	Gender=Masc|Number=Plur|Person=3|PronType=Prs	11	nmod:poss	_	Ref=GEN_2.1
13	׃	׃	PUNCT	punct	_	2	punct	_	Ref=GEN_2.1

~~~

ויכלו השמים והארץ וכל **צבאם**׃

And the sky and the land and all **their host** were completed.

<!-- Interlanguage links updated Po 11. listopadu 2024, 20:11:05 CET -->
