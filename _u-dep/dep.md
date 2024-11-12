---
layout: relation
title: 'dep'
shortdef: 'unspecified dependency'
udver: '2'
---

A dependency can be labeled as `dep` when it is impossible to determine a more precise relation.
This may be because of a weird grammatical construction, or a limitation in conversion or parsing software.
The use of `dep` should be avoided as much as possible.

~~~ sdparse
my dad does nt really not that good
nmod(dad, my)
nsubj(does, dad)
advmod(does, nt)
advmod(does, really)
dep(does, good)
advmod(good, not)
advmod(good, that)
~~~

<!-- Interlanguage links updated Po 11. listopadu 2024, 20:10:46 CET -->
