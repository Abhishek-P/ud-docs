---
layout: relation
title:  'nsubj'
shortdef : 'nominal subject'
udver: '2'
---

The dependency type `nsubj` marks nominal subjects of a clause.

~~~ sdparse
Азамат ағашқа қарай жүгірді . \n Azamat tree-to towards ran .
nsubj(жүгірді-4, Азамат-1)
case(ағашқа-2, қарай-3)
punct(жүгірді-4, .-5)
obl(жүгірді-4, ағашқа-2)
~~~

Another example:

~~~ sdparse
Мұнда үлкен шара өтеді . \n Here big event takes-place .
nsubj(өтеді-4, шара-3)
amod(шара-3, үлкен-2)
advmod(өтеді-4, Мұнда-1)
punct(өтеді-4, .-5)
~~~

Note that the governor may not always be a verb, in copula
predication, non-verbal predicates are possible:

~~~ sdparse
Сары жылы түс . \n Yellow warm colour .
nsubj(түс-3, Сары-1)
amod(түс-3, жылы-2)
punct(түс-3, .-4)
~~~

<!-- Interlanguage links updated Út 9. května 2023, 20:04:22 CEST -->
