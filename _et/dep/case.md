---
layout: relation
title: 'case'
shortdef: 'case marking'
udver: '2'
---
The dependency type `case` is used for the adposition in pre- and postpositional phrases.
Case-marking elements (i.e. adpositions) are treated as dependents of the noun they attach to.

~~~ sdparse
Rüütel läks lossi juurde .
nsubj(läks-2, Rüütel-1)
nmod(läks-2, lossi-3)
case(lossi-3, juurde-4)
punct(läks-2, .-5)
~~~

"Knight went near the castle."

~~~ sdparse
Pärast teda ei tulnud kedagi .
case(teda, Pärast)
~~~

"No one came after him"

<!-- Interlanguage links updated Po 6. listopadu 2023, 21:42:31 CET -->
