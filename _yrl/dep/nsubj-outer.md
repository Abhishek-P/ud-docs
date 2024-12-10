---
layout: relation
title: 'nsubj:outer'
shortdef: 'outer clause nominal subject'
udver: '2'
---

This relation specifies a nominal subject of a copular clause whose predicate is itself a clause, 
to signal that it is not the subject of the nested clause.
See discussion of [Predicate Clauses](../overview/complex-syntax.html#predicate-clauses).

~~~ sdparse
-ROOT- Ape kwá Deus akangaiwasawa puranga piri apigawa-itá ukwawasawa suí .
advmod(puranga, Ape)
det(akangaiwasawa, kwá)
nmod:poss(akangaiwasawa, Deus)
nsubj:outer(puranga, akangaiwasawa)
root(-ROOT-, puranga)
advmod(puranga, piri)
nsubj(ukwawasawa, apigawa-itá)
obl(puranga, ukwawasawa)
case(ukwawasawa, suí)
punct(puranga, .)

~~~



The `:outer` subtype is *not* intended for most nominal subjects of copular clauses—only those where the predicate is itself a clause. 
Plain [nsubj]() (or another subtype) will be appropriate if the copular clause predicate is a nominal, adjective, etc.:

~~~ sdparse
Nhaã papera puranga .
nsubj(puranga, papera)
~~~

~~~ sdparse
The title is Green Eggs and Ham .
nsubj(Eggs, title)
~~~
<!-- Interlanguage links updated Ne 5. května 2024, 18:21:28 CEST -->
