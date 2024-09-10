---
layout: relation
title:  'iobj'
shortdef : 'indirect object'
udver: '2'
---

The indirect object of a (verbal) predicate is the nominal which is the dative
object of the verb. The relation `iobj` is used for objects that are not direct
objects. It occurs only when there is a `obj` or `ccomp` in the clause.

~~~ sdparse
She gave me a raise
iobj(gave, me)
~~~

Note that prepositional phrases are not considered core arguments in English,
hence in _she gave it to me_, the _to me_ part is attached as [nmod]() although
semantically it corresponds to the dative.
<!-- Interlanguage links updated Ne 5. května 2024, 18:21:17 CEST -->
