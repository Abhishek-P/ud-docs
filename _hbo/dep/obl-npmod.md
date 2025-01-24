---
layout: relation
title: 'obl:npmod'
shortdef : 'noun phrase as adverbial modifier'
udver: '2'
---

This relation is a subtype of the [obl]() relation, which captures cases where something syntactically a noun phrase is
used as an adverbial modifier in a sentence. This primarily covers the construction which in traditional grammars is called the infinitive absolute.

<!-- genesis 59 -->
~~~ conllu
# sent_id = Masoretic-Genesis-3:4-hbo
# text = וַיֹּ֥אמֶר הַנָּחָ֖שׁ אֶל־הָֽאִשָּׁ֑ה לֹֽא־מֹ֖ות תְּמֻתֽוּן׃
# translit = ṿayoʼmer hanaḥash ʼel haʼishah loʼ mot temutun
# visual-style 12 11 obl:npmod color:blue
1-2	וַיֹּ֥אמֶר	_	_	_	_	_	_	_	_
1	וַ	ו	CCONJ	conj	_	2	cc	_	Gloss=and|Ref=GEN_3.4|Translit=ṿa
2	יֹּ֥אמֶר	אמר	VERB	verb	Gender=Masc|HebBinyan=PAAL|Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin	0	root	_	Gloss=say|Ref=GEN_3.4|Translit=yoʼmer
3-4	הַנָּחָ֖שׁ	_	_	_	_	_	_	_	_
3	הַ	ה	DET	art	PronType=Art	4	det	_	Gloss=the|Ref=GEN_3.4|Translit=ha
4	נָּחָ֖שׁ	נחשׁ	NOUN	subs	Gender=Masc|Number=Sing	2	nsubj	_	Gloss=serpent|Ref=GEN_3.4|Translit=naḥash
5	אֶל	אל	ADP	prep	_	8	case	_	Gloss=to|Ref=GEN_3.4|SpaceAfter=No|Translit=ʼel
6	־	־	PUNCT	punct	_	5	punct	_	Ref=GEN_3.4|SpaceAfter=No
7-8	הָֽאִשָּׁ֑ה	_	_	_	_	_	_	_	_
7	הָֽ	ה	DET	art	PronType=Art	8	det	_	Gloss=the|Ref=GEN_3.4|Translit=ha
8	אִשָּׁ֑ה	אשׁה	NOUN	subs	Gender=Fem|Number=Sing	2	obl	_	Gloss=woman|Ref=GEN_3.4|Translit=ʼishah
9	לֹֽא	לא	ADV	nega	Polarity=Neg	12	advmod	_	Gloss=not|Ref=GEN_3.4|SpaceAfter=No|Translit=loʼ
10	־	־	PUNCT	punct	_	9	punct	_	Ref=GEN_3.4|SpaceAfter=No
11	מֹ֖ות	מות	VERB	verb	HebBinyan=PAAL|VerbForm=Inf	12	obl:npmod	_	Gloss=die|Ref=GEN_3.4|Translit=mot
12	תְּמֻתֽוּן	מות	VERB	verb	Aspect=Imp|Gender=Masc|HebBinyan=PAAL|Mood=Ind|Number=Plur|Person=2|VerbForm=Fin	2	ccomp	_	Gloss=die|Ref=GEN_3.4|SpaceAfter=No|Translit=temutun
13	׃	׃	PUNCT	punct	_	2	punct	_	Ref=GEN_3.4

~~~

_ויאמר הנחש אל־האשה לא־מות תמתון׃_

_ṿayoʼmer hanaḥash ʼel haʼishah loʼ mot temutun_

_And the snake said to the woman "You will not definitely die."._

The majority of verbs in the infinitive absolute appear immediately before a finite verb with the same lemma, as in the example above.
In the rare cases where it appears afterwards, it usually either has a different lemma or is coordinated with another infinitive absolute form.
In both of these situations, it is attached with [advcl]() instead.

<!-- genesis 682 -->
~~~ conllu
# sent_id = Masoretic-Genesis-26:13-hbo
# text = וַיִּגְדַּ֖ל הָאִ֑ישׁ וַיֵּ֤לֶךְ הָלֹוךְ֙ וְגָדֵ֔ל עַ֥ד כִּֽי־גָדַ֖ל מְאֹֽד׃
# translit = ṿayigdal haʼish ṿayelekh halokh ṿegadel ʻad ki gadal meʼod
# visual-style 6 7 advcl color:blue
1-2	וַיִּגְדַּ֖ל	_	_	_	_	_	_	_	_
1	וַ	ו	CCONJ	conj	_	2	cc	_	Gloss=and|Ref=GEN_26.13|Translit=ṿa
2	יִּגְדַּ֖ל	גדל	VERB	verb	Gender=Masc|HebBinyan=PAAL|Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin	0	root	_	Gloss=be.strong|Ref=GEN_26.13|Translit=yigdal
3-4	הָאִ֑ישׁ	_	_	_	_	_	_	_	_
3	הָ	ה	DET	art	PronType=Art	4	det	_	Gloss=the|Ref=GEN_26.13|Translit=ha
4	אִ֑ישׁ	אישׁ	NOUN	subs	Gender=Masc|Number=Sing	2	nsubj	_	Gloss=man|Ref=GEN_26.13|Translit=ʼish
5-6	וַיֵּ֤לֶךְ	_	_	_	_	_	_	_	_
5	וַ	ו	CCONJ	conj	_	6	cc	_	Gloss=and|Ref=GEN_26.13|Translit=ṿa
6	יֵּ֤לֶךְ	הלך	VERB	verb	Gender=Masc|HebBinyan=PAAL|Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin	2	conj	_	Gloss=walk|Ref=GEN_26.13|Translit=yelekh
7	הָלֹוךְ֙	הלך	VERB	verb	HebBinyan=PAAL|VerbForm=Inf	6	advcl	_	Gloss=walk|Ref=GEN_26.13|Translit=halokh
8-9	וְגָדֵ֔ל	_	_	_	_	_	_	_	_
8	וְ	ו	CCONJ	conj	_	9	cc	_	Gloss=and|Ref=GEN_26.13|Translit=ṿe
9	גָדֵ֔ל	גדל	ADJ	adjv	Gender=Masc|Number=Sing	7	conj	_	Gloss=growing|Ref=GEN_26.13|Translit=gadel
10	עַ֥ד	עד	ADP	prep	ExtPos=SCONJ	13	mark	_	Gloss=unto|Ref=GEN_26.13|Translit=ʻad
11	כִּֽי	כי	SCONJ	conj	_	10	fixed	_	Gloss=that|Ref=GEN_26.13|SpaceAfter=No|Translit=ki
12	־	־	PUNCT	punct	_	10	punct	_	Ref=GEN_26.13|SpaceAfter=No
13	גָדַ֖ל	גדל	VERB	verb	Aspect=Perf|Gender=Masc|HebBinyan=PAAL|Mood=Ind|Number=Sing|Person=3|VerbForm=Fin	6	advcl	_	Gloss=be.strong|Ref=GEN_26.13|Translit=gadal
14	מְאֹֽד	מאד	ADV	subs	_	13	advmod	_	Gloss=might|Ref=GEN_26.13|SpaceAfter=No|Translit=meʼod
15	׃	׃	PUNCT	punct	_	2	punct	_	Ref=GEN_26.13

~~~

_ויגדל האיש וילך הלוך וגדל עד כי־גדל מאד׃_

_ṿayigdal haʼish ṿayelekh halokh ṿegadel ʻad ki gadal meʼod_

_And the man went, going and growing strong, until he was very strong._

<!-- Interlanguage links updated Po 11. listopadu 2024, 20:11:20 CET -->
