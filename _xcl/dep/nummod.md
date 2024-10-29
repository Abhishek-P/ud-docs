---
layout: relation
title: 'nummod'
shortdef: 'numeric modifier'
udver: '2'
---

A numeric modifier of a noun is any number phrase that serves to modify the meaning of the noun with a quantity.

~~~ sdparse
Եին առ մեզ եղբարք եւթն : \n Now there were seven brothers among us .
nummod(եղբարք, եւթն)
nummod(brothers, seven)
~~~

Note that indefinite quantifiers such as բազում/_bazowm_ “many” and սակաւ/_sakaw_ “few” are tagged DET and not NUM, and their relation to the quantified noun is not `nummod` but `det` ([det](xcl-dep/det)).