---
layout: relation
title: 'obl:unmarked'
shortdef: 'unmarked oblique nominal'
udver: '2'
---

The `obl:unmarked` relation is used for a nominal (noun, pronoun, noun phrase) functioning as a non-core (oblique) argument or adjunct which is not marked with a preposition.
Usually this is for expressions of time but can also be for expressions of location or dimension.

Where the nominal is marked with a preposition we use [obl]().

### Examples
#### Days of the week

_[...] a lorg faisg air baile Thetford ann an Sasuinn <b>Dihaoine</b> 'sa chaidh_ '[...] found near Thetford in England last <b>Friday</b>' (ns05\_008)

~~~sdparse
a lorg faisg air baile Thetford ann an Sasuinn <b>Dihaoine</b> 'sa chaidh
nmod:unmarked(Dihaoine, lorg)
acl:relcl(chaidh, Dihaoine)
det('sa, Dihaoine)
mark:prt(a, lorg)
~~~

#### Spells of time

_bidh ainm air Clàr nan Drabastair <b>fad</b> deich bliadhna_ 'his name will be on the Sex Offenders Register for a <b>spell</b> of ten years_ (ns07\_009)

~~~sdparse
bidh ainm air Clàr nan Drabastair fad deich bliadhna
nsubj(ainm, bidh)
xcomp:pred(Clàr, bidh)
obl:unmarked(fad, bidh)
nmod(bliadhna, fad)
nummod(deich, bliadhna)
~~~
