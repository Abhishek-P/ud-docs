---
layout: relation
title:  'acl:relcl'
shortdef : 'relative clause modifier'
udver: '2'
---

`acl:relcl` connects a clause to a noun phrase.
Usually the verb is marked by the relative particle _a_ but this may be omitted in speech.

### Examples

~~~ conllu
1	Thàinig	thig	VERB	V-s	Mood=Ind|Tense=Past|VerbForm=Fin	0	root	_	_
2	nighean	nighean	NOUN	Ncsfn	Case=Nom|Gender=Fem|Number=Sing	1	nsubj	_	_
3	a	a	PART	Q-r	PartType=Vb|PronType=Rel	4	nsubj	_	_
4	bha	bi	VERB	V-s	Mood=Ind|Tense=Past|VerbForm=Fin	2	acl:relcl	_	_
5	a'	ag	PART	Sa	_	6	case	_	_
6	frìthealadh	frìtheal	NOUN	Nv	VerbForm=Vnoun	4	xcomp:pred	_	_
7	is	is	CCONJ	Cc	_	8	cc	_	_
8	dh'iarr	iarr	VERB	V-s	Mood=Ind|Tense=Past|VerbForm=Fin	1	conj	_	_
9	Màiri	Màiri	PROPN	Nn-fn	Case=Nom|Gender=Fem	8	nsubj	_	_
10	cupa	cupa	NOUN	Ncsmn	Case=Nom|Gender=Masc|Number=Sing	8	obj	_	_
11	ti	ti	NOUN	Ncsfg	Case=Gen|Gender=Fem|Number=Sing	10	nmod	_	SpaceAfter=No
~~~

'The girl who was serving came and Màiri ordered a cup of tea.' (f01\_089)

~~~ conllu
19	facal	facal	NOUN	Ncsmn	Case=Nom|Gender=Masc|Number=Sing	17	obj	_	_
20-21	den	_	_	_	_	_	_	_	_
20	de	de	ADP	Sp	_	22	case	_	_
21	an	an	DET	Tds	Definite=Def|Number=Sing|PronType=Art	22	det	_	_
22	chànain	cànan	NOUN	Ncsfd	Case=Dat|Gender=Fem|Number=Sing	19	nmod	_	_
23	anns	an	ADP	Sp	_	25	case	_	_
24	an	an	PART	Qq	PartType=Vb|PronType=Int	25	mark:prt	_	_
25	robh	bi	VERB	V-s--d	Mood=Ind|Tense=Past|VerbForm=Fin	22	acl:relcl	_	_
26	ise	i	PRON	Pp3sf-e	Form=Emp|Gender=Fem|Number=Sing|Person=3|PronType=Prs	25	nsubj	_	_
27	cho	cho	ADV	Rg	AdvType=Man	28	advmod	_	_
28	fileanta	fileanta	ADJ	Ap	_	25	xcomp:pred	_	SpaceAfter=No
~~~

'a word of the language in which she was so fluent' (f01\_097)

### Related deprels

* `advcl:relcl` for the analogous case where the head is an adverb or possibly an adjective or adverb.
* `csubj:cleft` for where a relative clause is part of a cleft sentence.
* `csubj:cop` for where a relative clause is part of a different sort of sentence including a copula.
