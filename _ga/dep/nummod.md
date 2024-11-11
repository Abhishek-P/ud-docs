---
layout: relation
title: 'nummod'
shortdef: 'numeric modifier'
udver: '2'
---

*Numeric modifiers* of a noun or NP such as cardinal numbers, are marked with the `nummod` dependency type. Quantifiers are also included.

### Examples

_don aoisghrúpa faoi <b>ocht</b> mbliana_ `for the under <b>eights</b> age group'

~~~ sdparse
don aoisghrúpa faoi ocht mbliana \n for_the age_group under eight years
nummod(mbliana, ocht)
~~~

_I gceann <b>cúig</b> bliana_ `within <b>five</b> years'

~~~ sdparse
I gceann cúig bliana \n In time_of five years
nummod(bliana, cúig)
~~~

_ina bhfuil <b>27</b> Ballstát_ `in which there are <b>27</b> Member States'

~~~ sdparse
ina bhfuil 27 Ballstát \n in_which are 27 Member_States
nummod(Ballstát, 27)
~~~
<!-- Interlanguage links updated Po 11. listopadu 2024, 20:11:11 CET -->
