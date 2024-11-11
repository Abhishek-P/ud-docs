---
layout: relation
title: 'advmod:obl'
shortdef: 'contracted advmod and oblique nominal'
udver: '2'
---

In the current version of the Old French treebank, fused words have not been split the way they
should be in Universal Dependencies. One of the contraction types that occur in Old French is
an adverbial modifier with an oblique pronoun, e.g. _sin_ = _si + en_.
These contractions are are currently attached to the verb as `advmod:obl`.

~~~ sdparse
En ipse verbe sin dimes
advmod:obl(dimes, sin)
~~~
<!-- Interlanguage links updated Po 11. listopadu 2024, 20:10:23 CET -->
