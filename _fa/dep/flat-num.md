---
layout: relation
title:  'flat:num'
shortdef : 'compound number'
udver: '2'
---

The `flat:num` subtype of the [flat]() relation is used to connect parts of a multi-word numeral.

~~~ sdparse
381 هزار نفر به 110 کرج زنگ زدند . \n 381 thousand people called 110 Karaj .
nummod(نفر, 381-1)
nummod(people, 381-11)
flat:num(381-1, هزار)
flat:num(381-1, thousand)
~~~

<!-- Interlanguage links updated Út 9. května 2023, 20:04:16 CEST -->
