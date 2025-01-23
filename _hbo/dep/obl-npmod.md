---
layout: relation
title: 'obl:npmod'
shortdef : 'noun phrase as adverbial modifier'
udver: '2'
---

This relation is a subtype of the [obl]() relation, which captures cases where something syntactically a noun phrase is
used as an adverbial modifier in a sentence. This primarily covers the construction which in traditional grammars is called the infinitive absolute.

~~~ conllu
# sent_id = Masoretic-Genesis-3:4-hbo
# text = וַיֹּ֥אמֶר הַנָּחָ֖שׁ אֶל־הָֽאִשָּׁ֑ה לֹֽא־מֹ֖ות תְּמֻתֽוּן׃
# visual-style 12 11 obl:npmod color:blue
1-2	וַיֹּ֥אמֶר	_	_	_	_	_	_	_	_
1	וַ	ו	CCONJ	conj	_	2	cc	_	Gloss=and|Ref=GEN_3.4
2	יֹּ֥אמֶר	אמר	VERB	verb	Gender=Masc|HebBinyan=PAAL|Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin	0	root	_	Gloss=say|Ref=GEN_3.4
3-4	הַנָּחָ֖שׁ	_	_	_	_	_	_	_	_
3	הַ	ה	DET	art	PronType=Art	4	det	_	Gloss=the|Ref=GEN_3.4
4	נָּחָ֖שׁ	נחשׁ	NOUN	subs	Gender=Masc|Number=Sing	2	nsubj	_	Gloss=serpent|Ref=GEN_3.4
5	אֶל	אל	ADP	prep	_	8	case	_	Gloss=to|Ref=GEN_3.4|SpaceAfter=No
6	־	־	PUNCT	punct	_	5	punct	_	Ref=GEN_3.4|SpaceAfter=No
7-8	הָֽאִשָּׁ֑ה	_	_	_	_	_	_	_	_
7	הָֽ	ה	DET	art	PronType=Art	8	det	_	Gloss=the|Ref=GEN_3.4
8	אִשָּׁ֑ה	אשׁה	NOUN	subs	Gender=Fem|Number=Sing	2	obl	_	Gloss=woman|Ref=GEN_3.4
9	לֹֽא	לא	ADV	nega	Polarity=Neg	12	advmod	_	Gloss=not|Ref=GEN_3.4|SpaceAfter=No
10	־	־	PUNCT	punct	_	9	punct	_	Ref=GEN_3.4|SpaceAfter=No
11	מֹ֖ות	מות	VERB	verb	HebBinyan=PAAL|VerbForm=Inf	12	obl:npmod	_	Gloss=die|Ref=GEN_3.4
12	תְּמֻתֽוּן	מות	VERB	verb	Aspect=Imp|Gender=Masc|HebBinyan=PAAL|Mood=Ind|Number=Plur|Person=2|VerbForm=Fin	2	ccomp	_	Gloss=die|Ref=GEN_3.4|SpaceAfter=No
13	׃	׃	PUNCT	punct	_	2	punct	_	Ref=GEN_3.4

~~~
<!-- Interlanguage links updated Po 11. listopadu 2024, 20:11:20 CET -->
