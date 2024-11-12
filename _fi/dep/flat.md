---
layout: relation
title: 'flat'
redirect_from: "fi/dep/name.html"
shortdef : 'flat phrase without a clear head'
udver: '2'
---

Proper names constituted of more than one word are annotated using the dependency type `flat`. The first (leftmost) word is the head, and the other words are direct dependents of the head.

The `flat` dependency relation is used in cases where the multi-word name does not have an obvious internal syntactic structure, as is the case with for instance names of people (*Matti Virtanen*) or cities (*New York*).

If a name has an obvious internal structure, as is often the case in names of books and movies for instance, this structure is marked instead, and the `flat` relation is marked as a secondary relation (DEPS field) spanning over the whole name phrase (from first token to the last).

<!-- fname:name.pdf -->
~~~ sdparse
Jumalat juhlivat öisin on Donna Tarttin esikoisteos . \n Gods celebrate by_night is Donna Tartt's first_work .
nsubj(juhlivat-2, Jumalat-1)
nmod(juhlivat-2, öisin-3)
flat(Jumalat-1, öisin-3)
nsubj:cop(esikoisteos-7, juhlivat-2)
cop(esikoisteos-7, on-4)
punct(esikoisteos-7, .-8)
flat(Donna-5, Tarttin-6)
nmod:poss(esikoisteos-7, Donna-5)
~~~

<!-- Interlanguage links updated Po 11. listopadu 2024, 20:10:55 CET -->
