---
layout: relation
title: 'conj'
shortdef: 'conjunction'
udver: '2'
---

The `conj` relation is typically used to coordinate noun phrases or clauses which are joined by ו.

~~~ conllu
# sent_id = Masoretic-Genesis-1:1-hbo
# text = בְּרֵאשִׁ֖ית בָּרָ֣א אֱלֹהִ֑ים אֵ֥ת הַשָּׁמַ֖יִם וְאֵ֥ת הָאָֽרֶץ׃
# visual-style 7 11 conj color:blue
1-2	בְּרֵאשִׁ֖ית	_	_	_	_	_	_	_	_
1	בְּ	ב	ADP	prep	_	2	case	_	Gloss=in|Ref=GEN_1.1
2	רֵאשִׁ֖ית	ראשׁית	NOUN	subs	Gender=Fem|Number=Sing	3	obl	_	Gloss=beginning|Ref=GEN_1.1
3	בָּרָ֣א	ברא	VERB	verb	Aspect=Perf|Gender=Masc|HebBinyan=PAAL|Mood=Ind|Number=Sing|Person=3|VerbForm=Fin	0	root	_	Gloss=create|Ref=GEN_1.1
4	אֱלֹהִ֑ים	אלהים	NOUN	subs	Gender=Masc|Number=Plur	3	nsubj	_	Gloss=god(s)|Ref=GEN_1.1
5	אֵ֥ת	את	ADP	prep	_	7	case	_	Gloss=<object.marker>|Ref=GEN_1.1
6-7	הַשָּׁמַ֖יִם	_	_	_	_	_	_	_	_
6	הַ	ה	DET	art	PronType=Art	7	det	_	Gloss=the|Ref=GEN_1.1
7	שָּׁמַ֖יִם	שׁמים	NOUN	subs	Gender=Masc|Number=Plur	3	obj	_	Gloss=heavens|Ref=GEN_1.1
8-9	וְאֵ֥ת	_	_	_	_	_	_	_	_
8	וְ	ו	CCONJ	conj	_	11	cc	_	Gloss=and|Ref=GEN_1.1
9	אֵ֥ת	את	ADP	prep	_	11	case	_	Gloss=<object.marker>|Ref=GEN_1.1
10-11	הָאָֽרֶץ	_	_	_	_	_	_	_	_
10	הָ	ה	DET	art	PronType=Art	11	det	_	Gloss=the|Ref=GEN_1.1
11	אָֽרֶץ	ארץ	NOUN	subs	Gender=Fem|Number=Sing	7	conj	_	Gloss=earth|Ref=GEN_1.1
12	׃	׃	PUNCT	punct	_	3	punct	_	Ref=GEN_1.1

~~~

_בראשית ברא אלהים את השמים ואת הארץ׃_

_In the beginning, God created the sky and the land._

When several items occur in sequence and one in the middle lacks a conjunction, it is still attached with `conj`.

~~~ conllu
# sent_id = Masoretic-Genesis-2:14-hbo
# text = וְשֵׁ֨ם הַנָּהָ֤ר הַשְּׁלִישִׁי֙ חִדֶּ֔קֶל ה֥וּא הַֽהֹלֵ֖ךְ קִדְמַ֣ת אַשּׁ֑וּר וְהַנָּהָ֥ר הָֽרְבִיעִ֖י ה֥וּא פְרָֽת׃
# visual-style 7 10 conj color:blue
1-2	וְשֵׁ֨ם	_	_	_	_	_	_	_	_
1	וְ	ו	CCONJ	conj	_	7	cc	_	Gloss=and|Ref=GEN_2.14
2	שֵׁ֨ם	שׁם	NOUN	subs	Gender=Masc|Number=Sing	7	nsubj	_	Gloss=name|Ref=GEN_2.14
3-4	הַנָּהָ֤ר	_	_	_	_	_	_	_	_
3	הַ	ה	DET	art	PronType=Art	4	det	_	Gloss=the|Ref=GEN_2.14
4	נָּהָ֤ר	נהר	NOUN	subs	Gender=Masc|Number=Sing	2	compound:smixut	_	Gloss=stream|Ref=GEN_2.14
5-6	הַשְּׁלִישִׁי֙	_	_	_	_	_	_	_	_
5	הַ	ה	DET	art	PronType=Art	6	det	_	Gloss=the|Ref=GEN_2.14
6	שְּׁלִישִׁי֙	שׁלישׁי	NUM	adjv	Gender=Masc|Number=Sing|NumType=Ord	4	nummod	_	Gloss=third|Ref=GEN_2.14
7	חִדֶּ֔קֶל	חדקל	PROPN	nmpr	Number=Sing	0	root	_	Gloss=Tigris|Ref=GEN_2.14
8	ה֥וּא	הוא	PRON	prps	Gender=Masc|Number=Sing|Person=3|PronType=Prs	10	nsubj:outer	_	Gloss=he|Ref=GEN_2.14
9-10	הַֽהֹלֵ֖ךְ	_	_	_	_	_	_	_	_
9	הַֽ	ה	SCONJ	art	_	10	mark	_	Gloss=the|Ref=GEN_2.14
10	הֹלֵ֖ךְ	הלך	VERB	verb	Gender=Masc|HebBinyan=PAAL|Number=Sing|VerbForm=Part	7	conj	_	Gloss=walk|Ref=GEN_2.14
11	קִדְמַ֣ת	קדמה	NOUN	subs	Gender=Fem|Number=Sing	10	obl	_	Gloss=front|Ref=GEN_2.14
12	אַשּׁ֑וּר	אשׁור	PROPN	nmpr	Number=Sing	11	compound:smixut	_	Gloss=Asshur|Ref=GEN_2.14
13-15	וְהַנָּהָ֥ר	_	_	_	_	_	_	_	_
13	וְ	ו	CCONJ	conj	_	19	cc	_	Gloss=and|Ref=GEN_2.14
14	הַ	ה	DET	art	PronType=Art	15	det	_	Gloss=the|Ref=GEN_2.14
15	נָּהָ֥ר	נהר	NOUN	subs	Gender=Masc|Number=Sing	19	dislocated	_	Gloss=stream|Ref=GEN_2.14
16-17	הָֽרְבִיעִ֖י	_	_	_	_	_	_	_	_
16	הָֽ	ה	DET	art	PronType=Art	17	det	_	Gloss=the|Ref=GEN_2.14
17	רְבִיעִ֖י	רביעי	NUM	adjv	Gender=Masc|Number=Sing|NumType=Ord	15	nummod	_	Gloss=fourth|Ref=GEN_2.14
18	ה֥וּא	הוא	PRON	prps	Gender=Masc|Number=Sing|Person=3|PronType=Prs	19	nsubj	_	Gloss=he|Ref=GEN_2.14
19	פְרָֽת	פרת	PROPN	nmpr	Number=Sing	7	conj	_	Gloss=Euphrates|Ref=GEN_2.14|SpaceAfter=No
20	׃	׃	PUNCT	punct	_	7	punct	_	Ref=GEN_2.14

~~~

_ושם הנהר השלישי חדקל הוא ההלך קדמת אשור והנהר הרביעי הוז פרת׃_

_And the name of the third river was Chidkal, it was the one that flowed from Asshur, and the fourth river, it was Parat._

However, if there is not a following conjunction, [parataxis]() is used.

The `conj` relation is also used to attach prepositional phrases which express a range.

~~~ conllu
# sent_id = Masoretic-Genesis-31:29-hbo
# text = יֶשׁ־לְאֵ֣ל יָדִ֔י לַעֲשֹׂ֥ות עִמָּכֶ֖ם רָ֑ע וֵֽאלֹהֵ֨י אֲבִיכֶ֜ם אֶ֣מֶשׁ׀ אָמַ֧ר אֵלַ֣י לֵאמֹ֗ר הִשָּׁ֧מֶר לְךָ֛ מִדַּבֵּ֥ר עִֽם־יַעֲקֹ֖ב מִטֹּ֥וב עַד־רָֽע׃
# visual-style 31 34 conj color:blue
1	יֶשׁ	ישׁ	VERB	subs	Mood=Ind|VerbForm=Fin	0	root	_	Gloss=existence|Ref=GEN_31.29|SpaceAfter=No
2	־	־	PUNCT	punct	_	4	punct	_	Ref=GEN_31.29|SpaceAfter=No
3-4	לְאֵ֣ל	_	_	_	_	_	_	_	_
3	לְ	ל	ADP	prep	_	4	case	_	Gloss=to|Ref=GEN_31.29
4	אֵ֣ל	אל	NOUN	subs	Gender=Masc|Number=Sing	1	obl	_	Gloss=power|Ref=GEN_31.29
5-6	יָדִ֔י	_	_	_	_	_	_	_	_
5	יָדִ֔	יד	NOUN	subs	Gender=Fem|Number=Sing	4	compound:smixut	_	Gloss=hand|Ref=GEN_31.29
6	י	אני	PRON	prn	Number=Sing|Person=1|PronType=Prs	5	nmod:poss	_	Ref=GEN_31.29
7-8	לַעֲשֹׂ֥ות	_	_	_	_	_	_	_	_
7	לַ	ל	ADP	prep	_	8	case	_	Gloss=to|Ref=GEN_31.29
8	עֲשֹׂ֥ות	עשׂה	VERB	verb	HebBinyan=PAAL|VerbForm=Inf	1	advcl	_	Gloss=make|Ref=GEN_31.29
9-10	עִמָּכֶ֖ם	_	_	_	_	_	_	_	_
9	עִמָּ	עם	ADP	prep	_	10	case	_	Gloss=with|Ref=GEN_31.29
10	כֶ֖ם	אתם	PRON	prn	Gender=Masc|Number=Plur|Person=2|PronType=Prs	8	obl	_	Ref=GEN_31.29
11	רָ֑ע	רע	ADJ	adjv	Gender=Masc|Number=Sing	8	obj	_	Gloss=evil|Ref=GEN_31.29
12-13	וֵֽאלֹהֵ֨י	_	_	_	_	_	_	_	_
12	וֵֽ	ו	CCONJ	conj	_	18	cc	_	Gloss=and|Ref=GEN_31.29
13	אלֹהֵ֨י	אלהים	NOUN	subs	Gender=Masc|Number=Plur	18	nsubj	_	Gloss=god(s)|Ref=GEN_31.29
14-15	אֲבִיכֶ֜ם	_	_	_	_	_	_	_	_
14	אֲבִי	אב	NOUN	subs	Gender=Masc|Number=Sing	13	compound:smixut	_	Gloss=father|Ref=GEN_31.29
15	כֶ֜ם	אתם	PRON	prn	Gender=Masc|Number=Plur|Person=2|PronType=Prs	14	nmod:poss	_	Ref=GEN_31.29
16	אֶ֣מֶשׁ	אמשׁ	ADV	subs	_	18	advmod	_	Gloss=yesterday.evening|Ref=GEN_31.29|SpaceAfter=No
17	׀	׀	PUNCT	punct	_	16	punct	_	Ref=GEN_31.29
18	אָמַ֧ר	אמר	VERB	verb	Aspect=Perf|Gender=Masc|HebBinyan=PAAL|Mood=Ind|Number=Sing|Person=3|VerbForm=Fin	1	conj	_	Gloss=say|Ref=GEN_31.29
19-20	אֵלַ֣י	_	_	_	_	_	_	_	_
19	אֵלַ֣	אל	ADP	prep	_	20	case	_	Gloss=to|Ref=GEN_31.29
20	י	אני	PRON	prn	Number=Sing|Person=1|PronType=Prs	18	obl	_	Ref=GEN_31.29
21	לֵאמֹ֗ר	לאמר	SCONJ	verb	_	22	mark	_	Gloss=say|Ref=GEN_31.29
22	הִשָּׁ֧מֶר	שׁמר	VERB	verb	Gender=Masc|HebBinyan=NIFAL|Mood=Imp|Number=Sing|Person=2|VerbForm=Fin	18	ccomp	_	Gloss=keep|Ref=GEN_31.29
23-24	לְךָ֛	_	_	_	_	_	_	_	_
23	לְ	ל	ADP	prep	_	24	case	_	Gloss=to|Ref=GEN_31.29
24	ךָ֛	אתה	PRON	prn	Gender=Masc|Number=Sing|Person=2|PronType=Prs	22	obl	_	Ref=GEN_31.29
25-26	מִדַּבֵּ֥ר	_	_	_	_	_	_	_	_
25	מִ	מן	ADP	prep	_	26	case	_	Gloss=from|Ref=GEN_31.29
26	דַּבֵּ֥ר	דבר	VERB	verb	HebBinyan=PIEL|VerbForm=Inf	22	advcl	_	Gloss=speak|Ref=GEN_31.29
27	עִֽם	עם	ADP	prep	_	29	case	_	Gloss=with|Ref=GEN_31.29|SpaceAfter=No
28	־	־	PUNCT	punct	_	27	punct	_	Ref=GEN_31.29|SpaceAfter=No
29	יַעֲקֹ֖ב	יעקב	PROPN	nmpr	Gender=Masc|Number=Sing	26	obl	_	Gloss=Jacob|Ref=GEN_31.29
30-31	מִטֹּ֥וב	_	_	_	_	_	_	_	_
30	מִ	מן	ADP	prep	_	31	case	_	Gloss=from|Ref=GEN_31.29
31	טֹּ֥וב	טוב	ADJ	adjv	Gender=Masc|Number=Sing	26	obl	_	Gloss=good|Ref=GEN_31.29
32	עַד	עד	ADP	prep	_	34	case	_	Gloss=unto|Ref=GEN_31.29|SpaceAfter=No
33	־	־	PUNCT	punct	_	32	punct	_	Ref=GEN_31.29|SpaceAfter=No
34	רָֽע	רע	ADJ	adjv	Gender=Masc|Number=Sing	31	conj	_	Gloss=evil|Ref=GEN_31.29|SpaceAfter=No
35	׃	׃	PUNCT	punct	_	1	punct	_	Ref=GEN_31.29

~~~

_יש לאל ידי לעשות עמכם רע ואלהי אביכם אמש אמר אלי לאמר השמר לך מדבר עם יעקב מטוב עד רע׃_

_It was to the power of my hand to do evil to you and the god your fathers yesterday evening said to me "Guard your from speaking with Jacob from good to bad."._
