---
layout: relation
title: 'det:nummod'
shortdef: 'pronominal quantifier agreeing in case with the noun'
udver: '2'
---

Pronominal quantifiers in Slavic languages are labeled `det:nummod` or [det:numgov]() instead of [det]()
because they normally do not agree with the quantified noun in case
(unlike non-quantifying determiners).
They do agree only if the whole phrase (quantifier + noun) fills a role where
genitive, dative, locative or instrumental noun phrases are expected.
In these situations they are labeled `det:nummod`.

Czech:

~~~ sdparse
Nepamatuji si , s kolika muži jsem hrál karty . \n I-do-not-remember myself , with how-many men I-have played cards .
ccomp(Nepamatuji, hrál)
expl:pv(Nepamatuji, si)
punct(hrál, ,-3)
aux(hrál, jsem)
obj(hrál, karty)
iobj(hrál, muži)
case(muži, s)
det:nummod(muži, kolika)
punct(Nepamatuji, .-10)
ccomp(I-do-not-remember, played)
expl:pv(I-do-not-remember, myself)
punct(played, ,-14)
aux(played, I-have)
obj(played, cards)
iobj(played, men)
case(men, with)
det:nummod(men, how-many)
punct(I-do-not-remember, .-21)
~~~

See also [nummod:gov]() and [det:numgov]().

<!-- Interlanguage links updated Po 11. listopadu 2024, 20:10:49 CET -->
