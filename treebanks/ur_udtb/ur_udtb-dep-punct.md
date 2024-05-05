---
layout: base
title:  'Statistics of punct in UD_Urdu-UDTB'
udver: '2'
---

## Treebank Statistics: UD_Urdu-UDTB: Relations: `punct`

This relation is universal.

6911 nodes (5%) are attached to their parents as `punct`.

6097 instances of `punct` (88%) are left-to-right (parent precedes child).
Average distance between parent and child is 2.88540008681812.

The following 14 pairs of parts of speech are connected with `punct`: <tt><a href="ur_udtb-pos-VERB.html">VERB</a></tt>-<tt><a href="ur_udtb-pos-PUNCT.html">PUNCT</a></tt> (5208; 75% instances), <tt><a href="ur_udtb-pos-PROPN.html">PROPN</a></tt>-<tt><a href="ur_udtb-pos-PUNCT.html">PUNCT</a></tt> (741; 11% instances), <tt><a href="ur_udtb-pos-NOUN.html">NOUN</a></tt>-<tt><a href="ur_udtb-pos-PUNCT.html">PUNCT</a></tt> (632; 9% instances), <tt><a href="ur_udtb-pos-ADJ.html">ADJ</a></tt>-<tt><a href="ur_udtb-pos-PUNCT.html">PUNCT</a></tt> (186; 3% instances), <tt><a href="ur_udtb-pos-NUM.html">NUM</a></tt>-<tt><a href="ur_udtb-pos-PUNCT.html">PUNCT</a></tt> (65; 1% instances), <tt><a href="ur_udtb-pos-PRON.html">PRON</a></tt>-<tt><a href="ur_udtb-pos-PUNCT.html">PUNCT</a></tt> (33; 0% instances), <tt><a href="ur_udtb-pos-AUX.html">AUX</a></tt>-<tt><a href="ur_udtb-pos-PUNCT.html">PUNCT</a></tt> (13; 0% instances), <tt><a href="ur_udtb-pos-PART.html">PART</a></tt>-<tt><a href="ur_udtb-pos-PUNCT.html">PUNCT</a></tt> (13; 0% instances), <tt><a href="ur_udtb-pos-PUNCT.html">PUNCT</a></tt>-<tt><a href="ur_udtb-pos-PUNCT.html">PUNCT</a></tt> (6; 0% instances), <tt><a href="ur_udtb-pos-ADV.html">ADV</a></tt>-<tt><a href="ur_udtb-pos-PUNCT.html">PUNCT</a></tt> (4; 0% instances), <tt><a href="ur_udtb-pos-DET.html">DET</a></tt>-<tt><a href="ur_udtb-pos-PUNCT.html">PUNCT</a></tt> (4; 0% instances), <tt><a href="ur_udtb-pos-X.html">X</a></tt>-<tt><a href="ur_udtb-pos-PUNCT.html">PUNCT</a></tt> (3; 0% instances), <tt><a href="ur_udtb-pos-ADP.html">ADP</a></tt>-<tt><a href="ur_udtb-pos-PUNCT.html">PUNCT</a></tt> (2; 0% instances), <tt><a href="ur_udtb-pos-INTJ.html">INTJ</a></tt>-<tt><a href="ur_udtb-pos-PUNCT.html">PUNCT</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 14	bgColor:blue
# visual-style 14	fgColor:white
# visual-style 12	bgColor:blue
# visual-style 12	fgColor:white
# visual-style 12 14 punct	color:blue
1	اس	یہ	DET	DEM	Case=Acc|Number=Sing|Person=3|PronType=Dem	2	det	_	ChunkId=NP|ChunkType=child|Translit=ās|LTranslit=īh
2	اقدام	اقدام	NOUN	NN	Case=Acc|Gender=Masc|Number=Sing|Person=3	12	obl	_	Vib=0|Tam=0|ChunkId=NP|ChunkType=head|Translit=āqdām|LTranslit=āqdām
3	سے	سے	ADP	PSP	AdpType=Post	2	case	_	ChunkId=NP|ChunkType=child|Translit=se|LTranslit=se
4	سرکاری	سرکاری	ADJ	JJ	Case=Acc	5	amod	_	ChunkId=NP2|ChunkType=child|Translit=srkārī|LTranslit=srkārī
5	خزانہ	خزانہ	NOUN	NN	Case=Acc|Gender=Masc|Number=Sing|Person=3	12	obl	_	Vib=0|Tam=0|ChunkId=NP2|ChunkType=head|Translit=xzānh|LTranslit=xzānh
6	پر	پر	ADP	PSP	AdpType=Post	5	case	_	ChunkId=NP2|ChunkType=child|Translit=pr|LTranslit=pr
7	95	95	NUM	QCC	NumType=Card	8	compound	_	ChunkId=NP3|ChunkType=child|Translit=95|LTranslit=95
8	کروڑ	کروڑ	NUM	QC	NumType=Card	9	nummod	_	ChunkId=NP3|ChunkType=child|Translit=krūr|LTranslit=krūr
9	روپیوں	روپیہ	NOUN	NN	Case=Acc|Gender=Masc|Number=Plur|Person=3	11	nmod	_	Vib=0|Tam=0|ChunkId=NP3|ChunkType=head|Translit=rūpīūñ|LTranslit=rūpīh
10	کا	کا	ADP	PSP	AdpType=Post|Case=Nom|Gender=Masc|Number=Sing	9	case	_	ChunkId=NP3|ChunkType=child|Translit=kā|LTranslit=kā
11	خسارہ	خسارہ	NOUN	NN	Case=Nom|Gender=Masc|Number=Sing|Person=3	12	compound	_	Vib=0|Tam=0|ChunkId=NP4|ChunkType=head|Translit=xsārh|LTranslit=xsārh
12	ہوا	ہونا	VERB	VM	Aspect=Perf|Gender=Masc|Number=Sing|VerbForm=Part|Voice=Act	0	root	_	ChunkId=VGF|ChunkType=head|LTranslit=hūnā|Stype=declarative|Tam=yA|Translit=hūā|Vib=یا
13	ہے	ہے	AUX	VAUX	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	12	aux	_	SpaceAfter=No|Vib=ہے|Tam=hE|ChunkId=VGF|ChunkType=child|Translit=he|LTranslit=he
14	۔	۔	PUNCT	SYM	_	12	punct	_	ChunkId=VGF|ChunkType=child|Translit=.|LTranslit=.

~~~


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 6 punct	color:blue
1	بدترین	بدترین	ADV	INTF	AdvType=Deg	2	advmod	_	ChunkId=NP|ChunkType=child|Translit=bdtrīn|LTranslit=bdtrīn
2	متاثرہ	متاثرہ	ADJ	JJ	Case=Nom	3	amod	_	ChunkId=NP|ChunkType=child|Translit=mtāþrh|LTranslit=mtāþrh
3	ریاست	ریاست	NOUN	NN	Case=Nom|Gender=Masc|Number=Sing|Person=3	4	nsubj	_	Vib=0|Tam=0|ChunkId=NP|ChunkType=head|Translit=rīāst|LTranslit=rīāst
4	الاباما	الاباما	PROPN	NNP	Case=Nom|Gender=Masc|Number=Sing|Person=3	0	root	_	Vib=0|Tam=0|ChunkId=NP2|ChunkType=head|Translit=ālābāmā|LTranslit=ālābāmā
5	ہے	ہے	AUX	VM	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	4	cop	_	SpaceAfter=No|AltTag=AUX-VERB|Vib=ہے|Tam=hE|ChunkId=VGF|ChunkType=head|Stype=declarative|Translit=he|LTranslit=he
6	۔	۔	PUNCT	SYM	_	4	punct	_	ChunkId=VGF|ChunkType=child|Translit=.|LTranslit=.

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 7 punct	color:blue
1	ریاستی	ریاستی	ADJ	JJ	Case=Acc	2	amod	_	ChunkId=NP|ChunkType=child|Translit=rīāstī|LTranslit=rīāstī
2	وزیر	وزیر	NOUN	NN	Case=Acc|Gender=Masc|Number=Sing|Person=3	5	nmod	_	Vib=0|Tam=0|ChunkId=NP|ChunkType=head|Translit=ūzīr|LTranslit=ūzīr
3	کے	کا	ADP	PSP	AdpType=Post|Case=Acc|Gender=Masc|Number=Sing	2	case	_	ChunkId=NP|ChunkType=child|Translit=ke|LTranslit=kā
4	بااعتماد	بااعتماد	ADJ	JJ	Case=Nom	5	amod	_	ChunkId=NP2|ChunkType=child|Translit=bāāʿtmād|LTranslit=bāāʿtmād
5	قائد	قائد	NOUN	NN	Case=Nom|Gender=Masc|Number=Sing|Person=3	0	root	_	Vib=0|Tam=0|ChunkId=NP2|ChunkType=head|Translit=qājd|LTranslit=qājd
6	ہےں	ہے	AUX	VM	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	5	cop	_	SpaceAfter=No|AltTag=AUX-VERB|Vib=ہے|Tam=hE|ChunkId=VGF|ChunkType=head|Stype=declarative|Translit=heñ|LTranslit=he
7	۔	۔	PUNCT	SYM	_	5	punct	_	ChunkId=VGF|ChunkType=child|Translit=.|LTranslit=.

~~~


