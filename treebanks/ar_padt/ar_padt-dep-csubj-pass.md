---
layout: base
title:  'Statistics of csubj:pass in UD_Arabic-PADT'
udver: '2'
---

## Treebank Statistics: UD_Arabic-PADT: Relations: `csubj:pass`

This relation is a language-specific subtype of <tt><a href="ar_padt-dep-csubj.html">csubj</a></tt>.

1 nodes (0%) are attached to their parents as `csubj:pass`.

1 instances of `csubj:pass` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 2.

The following 1 pairs of parts of speech are connected with `csubj:pass`: <tt><a href="ar_padt-pos-VERB.html">VERB</a></tt>-<tt><a href="ar_padt-pos-VERB.html">VERB</a></tt> (1; 100% instances).


~~~ conllu
# visual-style 27	bgColor:blue
# visual-style 27	fgColor:white
# visual-style 25	bgColor:blue
# visual-style 25	fgColor:white
# visual-style 25 27 csubj:pass	color:blue
1	المناقشون	مُنَاقِش	NOUN	N------P1D	Case=Nom|Definite=Def|Number=Plur	6	nsubj	6:nsubj	Vform=اَلمُنَاقِشُونَ|Gloss=debater,arguing|Root=n q ^s|Translit=al-munāqišūna|LTranslit=munāqiš
2	ب	بِ	ADP	P---------	AdpType=Prep	3	case	3:case	Gloss=by,with|LTranslit=bi|Root=bi|Translit=bi|Vform=بِ
3	الوقائع	وَقِيعَة	NOUN	N------P2D	Case=Gen|Definite=Def|Number=Plur	1	nmod	1:nmod:بِ:gen	Gloss=incident,event|LTranslit=waqīʿat|Root=w q `|Translit=al-waqāʾiʿi|Vform=اَلوَقَائِعِ
4	و	وَ	CCONJ	C---------	_	5	cc	5:cc	Gloss=and|LTranslit=wa|Root=wa|Translit=wa|Vform=وَ
5	الأرقام	رَقم	NOUN	N------P1D	Case=Nom|Definite=Def|Number=Plur	3	conj	1:nmod:بِ:gen|3:conj	Gloss=number,numeral,record|LTranslit=raqm|Root=r q m|Translit=al-ʾarqāmu|Vform=اَلأَرقَامُ
6	ينطلقون	اِنطَلَق	VERB	VIIA-3MP--	Aspect=Imp|Gender=Masc|Mood=Ind|Number=Plur|Person=3|VerbForm=Fin|Voice=Act	0	root	0:root	Vform=يَنطَلِقُونَ|Gloss=take_off,be_sent_out|Root=.t l q|Translit=yanṭaliqūna|LTranslit=inṭalaq
7	من	مِن	ADP	P---------	AdpType=Prep	8	case	8:case	Vform=مِن|Gloss=from|Root=min|Translit=min|LTranslit=min
8	مقدمات	مُقَدَّمَة	NOUN	N------P2I	Case=Gen|Definite=Ind|Number=Plur	6	obl:arg	6:obl:arg:مِن:gen	Vform=مُقَدَّمَاتٍ|Gloss=preface,introduction,front_part|Root=q d m|Translit=muqaddamātin|LTranslit=muqaddamat
9	بسيطة	بَسِيط	ADJ	A-----FS2I	Case=Gen|Definite=Ind|Gender=Fem|Number=Sing	8	amod	8:amod	Vform=بَسِيطَةٍ|Gloss=simple,plain|Root=b s .t|Translit=basīṭatin|LTranslit=basīṭ
10	و	وَ	CCONJ	C---------	_	14	cc	14:cc	SpaceAfter=No|Vform=وَ|Gloss=and|Root=wa|Translit=wa|LTranslit=wa
11	.	.	PUNCT	G---------	_	14	punct	14:punct	SpaceAfter=No|Vform=.|Translit=.
12	.	.	PUNCT	G---------	_	14	punct	14:punct	SpaceAfter=No|Vform=.|Translit=.
13	.	.	PUNCT	G---------	_	14	punct	14:punct	Vform=.|Translit=.
14	صحيحة	صَحِيح	ADJ	A-----FS2I	Case=Gen|Definite=Ind|Gender=Fem|Number=Sing	9	conj	8:amod|9:conj	SpaceAfter=No|Vform=صَحِيحَةٍ|Gloss=true,correct|Root=.s .h .h|Translit=ṣaḥīḥatin|LTranslit=ṣaḥīḥ
15	:	:	PUNCT	G---------	_	14	punct	14:punct	Vform=:|Translit=:
16	المطلوب	مَطلُوب	ADJ	A-----MS1D	Case=Nom|Definite=Def|Gender=Masc|Number=Sing	6	parataxis	6:parataxis	Vform=اَلمَطلُوبُ|Gloss=required,necessary,demanded|Root=.t l b|Translit=al-maṭlūbu|LTranslit=maṭlūb
17	بناء	بِنَاء	NOUN	N------S1R	Case=Nom|Definite=Cons|Number=Sing	16	nsubj	16:nsubj	Vform=بِنَاءُ|Gloss=building,constructing|Root=b n y|Translit=bināʾu|LTranslit=bināʾ
18	دولة	دَولَة	NOUN	N------S2I	Case=Gen|Definite=Ind|Number=Sing	17	nmod	17:nmod:gen	Vform=دَولَةٍ|Gloss=state,country|Root=d w l|Translit=dawlatin|LTranslit=dawlat
19	ذات	ذَات	NOUN	N------S2R	Case=Gen|Definite=Cons|Number=Sing	18	nmod	18:nmod:gen	Vform=ذَاتِ|Gloss=self,being,essence|Root=_d|Translit=ḏāti|LTranslit=ḏāt
20	سيادة	سِيَادَة	NOUN	N------S2I	Case=Gen|Definite=Ind|Number=Sing	19	nmod	19:nmod:gen	SpaceAfter=No|Vform=سِيَادَةٍ|Gloss=sovereignty,supremacy,Excellency|Root=s w d|Translit=siyādatin|LTranslit=siyādat
21	.	.	PUNCT	G---------	_	6	punct	6:punct	Vform=.|Translit=.
22	تحرير	تَحرِير	NOUN	N------S1R	Case=Nom|Definite=Cons|Number=Sing	6	dep	6:dep	Vform=تَحرِيرُ|Gloss=liberation,liberating,editorship,editing|Root=.h r r|Translit=taḥrīru|LTranslit=taḥrīr
23	الأرض	أَرض	NOUN	N------S2D	Case=Gen|Definite=Def|Number=Sing	22	nmod	22:nmod:gen|25:nsubj:pass	Vform=اَلأَرضِ|Gloss=earth,territory,land|Root=' r .d|Translit=al-ʾarḍi|LTranslit=ʾarḍ
24	التي	اَلَّذِي	DET	SR----FS2-	Case=Gen|Gender=Fem|Number=Sing|PronType=Rel	25	nsubj:pass	23:ref	Vform=اَلَّتِي|Gloss=that,which|Root=l|Translit=allatī|LTranslit=allaḏī
25	يُعرف	عَرَف	VERB	VIIP-3MS--	Aspect=Imp|Gender=Masc|Mood=Ind|Number=Sing|Person=3|VerbForm=Fin|Voice=Pass	23	acl:relcl	23:acl:relcl	Vform=يُعرَفُ|Gloss=know,recognize,be_aware,be_acquainted|Root=` r f|Translit=yuʿrafu|LTranslit=ʿaraf
26	متى	مَتَى	DET	S---------	_	27	obl	27:obl	Vform=مَتَى|Gloss=when|Root=m t y|Translit=matā|LTranslit=matā
27	يكتمل	اِكتَمَل	VERB	VIIA-3MS--	Aspect=Imp|Gender=Masc|Mood=Ind|Number=Sing|Person=3|VerbForm=Fin|Voice=Act	25	csubj:pass	25:csubj:pass	Vform=يَكتَمِلُ|Gloss=be_completed,be_perfect,be_integral|Root=k m l|Translit=yaktamilu|LTranslit=iktamal
28	تحرير	تَحرِير	NOUN	N------S1R	Case=Nom|Definite=Cons|Number=Sing	27	nsubj	27:nsubj	Gloss=liberation,liberating,editorship,editing|LTranslit=taḥrīr|Root=.h r r|Translit=taḥrīru|Vform=تَحرِيرُ
29	ها	هُوَ	PRON	SP---3FS2-	Case=Gen|Gender=Fem|Number=Sing|Person=3|PronType=Prs	28	nmod	28:nmod:gen	Gloss=he,she,it|LTranslit=huwa|Translit=hā|Vform=هَا
30	،	،	PUNCT	G---------	_	29	punct	29:punct	Vform=،|Translit=,
31	و	وَ	CCONJ	C---------	_	32	cc	32:cc	Gloss=and|LTranslit=wa|Root=wa|Translit=wa|Vform=وَ
32	المبادرة	مُبَادَرَة	NOUN	N------S1D	Case=Nom|Definite=Def|Number=Sing	22	conj	6:dep|22:conj	Gloss=initiative,proposal|LTranslit=mubādarat|Root=b d r|Translit=al-mubādaratu|Vform=اَلمُبَادَرَةُ
33	سريعاً	سَرِيع	ADJ	A-----MS4I	Case=Acc|Definite=Ind|Gender=Masc|Number=Sing	32	amod	32:amod	Vform=سَرِيعًا|Gloss=quick,prompt|Root=s r `|Translit=sarīʿan|LTranslit=sarīʿ
34	الى	إِلَى	ADP	P---------	AdpType=Prep	35	case	35:case	Vform=إِلَى|Gloss=to,towards|Root=' l y|Translit=ʾilā|LTranslit=ʾilā
35	نشر	نَشر	NOUN	N------S2R	Case=Gen|Definite=Cons|Number=Sing	32	nmod	32:nmod:إِلَى:gen	Vform=نَشرِ|Gloss=spreading,propagation|Root=n ^s r|Translit=našri|LTranslit=našr
36	السلطة	سُلطَة	NOUN	N------S2D	Case=Gen|Definite=Def|Number=Sing	35	nmod	35:nmod:gen	Vform=اَلسُّلطَةِ|Gloss=power,authority,rule|Root=s l .t|Translit=as-sulṭati|LTranslit=sulṭat
37	فوق	فَوقَ	ADP	PI------4-	AdpType=Prep|Case=Acc	38	case	38:case	Gloss=above,over|LTranslit=fawqa|Root=f w q|Translit=fawqa|Vform=فَوقَ
38	ها	هُوَ	PRON	SP---3FS2-	Case=Gen|Gender=Fem|Number=Sing|Person=3|PronType=Prs	35	nmod	35:nmod:فَوقَ:gen	Gloss=he,she,it|LTranslit=huwa|Translit=hā|Vform=هَا
39	و	وَ	CCONJ	C---------	_	40	cc	40:cc	Gloss=and|LTranslit=wa|Root=wa|Translit=wa|Vform=وَ
40	ربط	رَبط	NOUN	N------S1R	Case=Nom|Definite=Cons|Number=Sing	35	conj	32:nmod:إِلَى:gen|35:conj	Gloss=tying,connecting|LTranslit=rabṭ|Root=r b .t|Translit=rabṭu|Vform=رَبطُ
41	ها	هُوَ	PRON	SP---3FS2-	Case=Gen|Gender=Fem|Number=Sing|Person=3|PronType=Prs	40	nmod	40:nmod:gen	Gloss=he,she,it|LTranslit=huwa|Translit=hā|Vform=هَا
42	ب	بِ	ADP	P---------	AdpType=Prep	43	case	43:case	Gloss=by,with|LTranslit=bi|Root=bi|Translit=bi|Vform=بِ
43	المركز	مَركَز	NOUN	N------S2D	Case=Gen|Definite=Def|Number=Sing	40	nmod	40:nmod:بِ:gen	Gloss=center,station|LTranslit=markaz|Root=r k z|Translit=al-markazi|Vform=اَلمَركَزِ
44	.	.	PUNCT	G---------	_	6	punct	6:punct	Vform=.|Translit=.
45	التطبيع	تَطبِيع	NOUN	N------S1D	Case=Nom|Definite=Def|Number=Sing	6	dep	6:dep	Vform=اَلتَّطبِيعُ|Gloss=normalization|Root=.t b `|Translit=at-taṭbīʿu|LTranslit=taṭbīʿ
46	ب	بِ	ADP	P---------	AdpType=Prep	47	case	47:case	Gloss=by,with|LTranslit=bi|Root=bi|Translit=bi|Vform=بِ
47	أسرع	أَسرَع	ADJ	A-----MS2R	Case=Gen|Definite=Cons|Gender=Masc|Number=Sing	45	amod	45:amod	Gloss=faster_/_fastest|LTranslit=ʾasraʿ|Root=s r `|Translit=ʾasraʿi|Vform=أَسرَعِ
48	وقت	وَقت	NOUN	N------S2I	Case=Gen|Definite=Ind|Number=Sing	47	nmod	47:nmod:gen	Vform=وَقتٍ|Gloss=time,moment,period_of_time|Root=w q t|Translit=waqtin|LTranslit=waqt
49	ممكن	مُمكِن	ADJ	A-----MS2I	Case=Gen|Definite=Ind|Gender=Masc|Number=Sing	48	amod	48:amod	Vform=مُمكِنٍ|Gloss=possible|Root=m k n|Translit=mumkinin|LTranslit=mumkin
50	مع	مَعَ	ADP	PI------4-	AdpType=Prep|Case=Acc	51	case	51:case	Vform=مَعَ|Gloss=with|Root=ma`|Translit=maʿa|LTranslit=maʿa
51	الحياة	حَيَاة	NOUN	N------S2D	Case=Gen|Definite=Def|Number=Sing	45	nmod	45:nmod:مَعَ:gen	Vform=اَلحَيَاةِ|Gloss=life|Root=.h y y|Translit=al-ḥayāti|LTranslit=ḥayāt
52	العادية	عَادِيّ	ADJ	A-----FS2D	Case=Gen|Definite=Def|Gender=Fem|Number=Sing	51	amod	51:amod	Vform=اَلعَادِيَّةِ|Gloss=ordinary,regular,normal|Root=` w d|Translit=al-ʿādīyati|LTranslit=ʿādīy
53	و	وَ	CCONJ	C---------	_	54	cc	54:cc	Gloss=and|LTranslit=wa|Root=wa|Translit=wa|Vform=وَ
54	تفكيك	تَفكِيك	NOUN	N------S1R	Case=Nom|Definite=Cons|Number=Sing	45	conj	6:dep|45:conj	Gloss=dismantling,dismemberment,fragmentation|LTranslit=tafkīk|Root=f k k|Translit=tafkīku|Vform=تَفكِيكُ
55	ظاهرات	ظاهرات	X	U---------	_	54	nmod	54:nmod	Vform=ظاهرات|Root=OOV|Translit=ẓāhrāt
56	السلاح	سِلَاح	NOUN	N------S2D	Case=Gen|Definite=Def|Number=Sing	55	nmod	55:nmod:gen	Vform=اَلسِّلَاحِ|Gloss=weapon|Root=s l .h|Translit=as-silāḥi|LTranslit=silāḥ
57	و	وَ	CCONJ	C---------	_	58	cc	58:cc	Gloss=and|LTranslit=wa|Root=wa|Translit=wa|Vform=وَ
58	التعبئة	تَعبِئَة	NOUN	N------S1D	Case=Nom|Definite=Def|Number=Sing	56	conj	55:nmod:gen|56:conj	Gloss=mobilization,alert|LTranslit=taʿbiʾat|Root=` b '|Translit=at-taʿbiʾatu|Vform=اَلتَّعبِئَةُ
59	.	.	PUNCT	G---------	_	6	punct	6:punct	Vform=.|Translit=.
60	الانصراف	الانصراف	X	U---------	_	6	dep	6:dep	Vform=الانصراف|Root=OOV|Translit=ālānṣrāf
61	الى	إِلَى	ADP	P---------	AdpType=Prep	62	case	62:case	Vform=إِلَى|Gloss=to,towards|Root=' l y|Translit=ʾilā|LTranslit=ʾilā
62	تحسين	تَحسِين	NOUN	N------S2R	Case=Gen|Definite=Cons|Number=Sing	60	nmod	60:nmod:إِلَى:gen	Vform=تَحسِينِ|Gloss=improving,making_better|Root=.h s n|Translit=taḥsīni|LTranslit=taḥsīn
63	الاقتصاد	اِقتِصَاد	NOUN	N------S2D	Case=Gen|Definite=Def|Number=Sing	62	nmod	62:nmod:gen	Vform=اَلِاقتِصَادِ|Gloss=economy,saving|Root=q .s d|Translit=al-i-ʼqtiṣādi|LTranslit=iqtiṣād
64	و	وَ	CCONJ	C---------	_	65	cc	65:cc	Gloss=and|LTranslit=wa|Root=wa|Translit=wa|Vform=وَ
65	التعليم	تَعلِيم	NOUN	N------S2D	Case=Gen|Definite=Def|Number=Sing	63	conj	62:nmod:gen|63:conj	Gloss=education,teaching,instructions,precepts|LTranslit=taʿlīm|Root=` l m|Translit=at-taʿlīmi|Vform=اَلتَّعلِيمِ
66	و	وَ	CCONJ	C---------	_	67	cc	67:cc	Gloss=and|LTranslit=wa|Root=wa|Translit=wa|Vform=وَ
67	الطبابة	طِبَابَة	NOUN	N------S1D	Case=Nom|Definite=Def|Number=Sing	63	conj	62:nmod:gen|63:conj	Gloss=medical_profession,medical_treatment|LTranslit=ṭibābat|Root=.t b b|Translit=aṭ-ṭibābatu|Vform=اَلطِّبَابَةُ
68	و	وَ	CCONJ	C---------	_	69	cc	69:cc	Gloss=and|LTranslit=wa|Root=wa|Translit=wa|Vform=وَ
69	المؤسسات	مُؤَسَّسَة	NOUN	N------P2D	Case=Gen|Definite=Def|Number=Plur	63	conj	62:nmod:gen|63:conj	Gloss=institution,organization,foundation|LTranslit=muʾassasat|Root=' s s|Translit=al-muʾassasāti|Vform=اَلمُؤَسَّسَاتِ
70	على	عَلَى	ADP	P---------	AdpType=Prep	71	case	71:case	Vform=عَلَى|Gloss=on,above|Root=` l w|Translit=ʿalā|LTranslit=ʿalā
71	أنواع	نَوع	NOUN	N------P2R	Case=Gen|Definite=Cons|Number=Plur	69	nmod	69:nmod:عَلَى:gen	Gloss=type,kind,form|LTranslit=nawʿ|Root=n w `|Translit=ʾanwāʿi|Vform=أَنوَاعِ
72	ها	هُوَ	PRON	SP---3FS2-	Case=Gen|Gender=Fem|Number=Sing|Person=3|PronType=Prs	71	nmod	71:nmod:gen	Gloss=he,she,it|LTranslit=huwa|Translit=hā|Vform=هَا
73	.	.	PUNCT	G---------	_	6	punct	6:punct	Vform=.|Translit=.

~~~


