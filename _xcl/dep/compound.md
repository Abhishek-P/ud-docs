---
layout: relation
title: 'compound'
shortdef: 'compound'
udver: '2'
---

In Classical Armenian, the `compound` relation is used for compound numbers.
The rightmost numeral is the head, the other numerals are attached as its modifiers.

~~~ sdparse
Եին արք հինգ հազար . \n They were five thousand men .
nummod(արք, հազար)
nummod(men, thousand)
compound(հազար, հինգ)
compound(thousand, five)
~~~
