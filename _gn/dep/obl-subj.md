---
layout: relation
title:  'obl:subj'
shortdef : 'NP-related subject'
udver: '2'
---

The relation `obl:subj` is used for the NP related to the subject core-argument in a head-marking language.
In Tupinambá, a strictly head-marking language, the core arguments are indexed on the predicate, but the NPs related to the core-arguments
are in free-order in relation to the head.

```
Aβá kuɲã o-s-epjak
man woman 3S-3O-see
The man sees the woman / the woman saw the man
```

~~~ sdparse
Aβá kuɲã osepjak . \n the man sees the woman .
obl:subj(osepjak, aβá)
obl:subj(3-3-see, man)
~~~


<!-- Interlanguage links updated Po 6. listopadu 2023, 21:43:21 CET -->
