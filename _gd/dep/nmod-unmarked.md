---
layout: relation
title: 'nmod:unmarked'
shortdef: 'unmarked nominal modifier'
udver: '2'
---

The `nmod:unmarked` relation is used for nominal modifiers of nouns where there is no preposition and `Case=Nom`.
If there is a preposition or `Case=Gen` we use `nmod` instead.

### Examples

#### Indeclinables

Used where a nominal modifier is a noun and would normally be in the genitive form but has not been declined as it is a borrowing or a foreign name.

* _fo chomain aig obair <b>Flinn</b>_ 'under an obligation to the work of <b>Flinn</b>' (fp09\_014)
* _Thèid rannsachadh <b>post-mortem</b> a dhèanamh an-diugh_ 'A <b>post-mortem</b> examination will be done today' (ns08\_000)


#### _caomh_, _chòir_, _fheudar_, _toil_

_b' fheudar <b>dhuinn</b> am fàgail_ '<b>we</b> would have to leave them' (c02_001a)

~~~sdparse
b' fheudar dhuinn am fàgail
nmod:unmarked(fheudar, dhuinn)
cop(b', fheudar)
csubj:cop(fàgail, fheudar)
~~~


#### _fhèin_ 
_Bett <b>fhèin</b> a' ruith suas_ 'Bett <b>himself</b> running up' (s09_017)

~~~sdparse
Bett fhèin a' ruith suas
nmod:unmarked(Bett, fhèin)
~~~

####  Interrogatives

_gu dé na tréithean litreachail a dh’éirich mar thoradh_ 'what literary traits arose as a result' (fp09\_002)

~~~sdparse
gu dé na tréithean litreachail a dh’éirich mar thoradh
nmod:unmarked(gu, tréithean)
fixed(dé, gu)
det(na, tréithean)
~~~

#### Years

This is also used in phrases like _sa bhliadhna 1774_ 'in the year 1774' to link the year to the word for year.

~~~conllu
1-2	sa	_	_	_	_	_	_	_	_
1	anns	an	ADP	Sp	_	3	case	_	_
2	an	an	ADP	Sp	_	1	fixed	_	_
3	bhliadhna	bliadhna	NOUN	Ncsfd	Case=Dat|Gender=Fem|Number=Sing	0	obl	_	_
4	1774	1774	NUM	Mn	_	3	nmod:unmarked	_	SpaceAfter=No
~~~

