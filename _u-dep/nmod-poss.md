---
layout: relation
title:  'nmod:poss'
shortdef : 'possessive nominal modifier'
udver: '2'
---

`nmod:poss` is used for a possessive nominal modifier. In English, for example, it is marked with the genitive `case` clitic _'s_ or one of its variant forms.

~~~ sdparse
Marie 's book
nmod:poss(book, Marie)
case(Marie, 's)
~~~

`nmod:poss` must not be confused with the [feature](https://universaldependencies.org/en/feat/Poss.html) `Poss=Yes` used for possessive pronouns. 
`nmod:poss` is only relevant for languages that have a particular construction, such as the possessive construction of English (also called Saxon genitive), that we want to distinguish from other `nmod` constructions.

<!-- Interlanguage links updated Ne 5. května 2024, 18:21:24 CEST -->
