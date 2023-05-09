---
layout: relation
title:  'advcl:tcl'
shortdef : 'temporal adverbial clause'
udver: '2'
---

A temporal clause is a subtype of the [advcl]() relation: if the subordinate clause is specifying a time, it is labeled as `tcl`.
This is parallel to [obl:tmod](), which covers temporal modifiers that are realized as nominals,
and [advmod:tmod](), which covers temporal modifiers that are realized as adverbs.

~~~ sdparse
Карӧ ветлӧм бӧрын, колӧ шойччыны.\n After going to town, you have to rest.
obl(ветлӧм, Карӧ)
case(ветлӧм, бӧрын)
advcl:tcl(колӧ, ветлӧм)
xcomp(колӧ, шойччыны)
~~~


<!-- Interlanguage links updated Út 9. května 2023, 20:03:55 CEST -->
