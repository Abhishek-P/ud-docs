---
layout: relation
title: 'list'
shortdef: 'list'
udver: '2'
---

`list` is used for list items.

The relation is mostly used in the PoSTWITA-UD treebank for examples like the following:

~~~ sdparse
TT ITALIA 05:28 1. #cinemaInChiesa 2. #serviziopubblico 3. #Grillo 4. Trota 5. Levon Helm 6. Damon and Elena 7. Prince Of Persia 8. Lega
list(TT, #cinemaInChiesa)
list(TT, #serviziopubblico)
list(TT, #Grillo)
list(TT, Trota)
list(TT, Levon)
list(TT, Damon)
list(TT, Prince)
list(TT, Lega)
~~~

<code>list</code> covers bullet points, numbered lists and similar cases, as illustrated above. However it does **not** cover list items constructed with coordinating conjunctions and punctuation: those cases are covered by the dependency relations [cc]() and [conj]().
<!-- Interlanguage links updated Út 9. května 2023, 20:04:18 CEST -->
