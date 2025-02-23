---
layout: relation
title: 'acl'
shortdef: 'clausal modifier of noun'
udver: '2'
---

`acl` stands for finite and non-finite clauses that modify a noun, in
contrast to the [advcl]() relation which is used for adverbial clauses
that modify a predicate. The head of the `acl` relation is the noun
that is modified, and the dependent is the head of the clause that
modifies the noun.

We use `acl` for:

Verbal adjectives that modify nouns:

~~~ sdparse
Тез   жүгіретін   спортшылар   көрдім . \n Fast running athletes saw-I .
acl(спортшылар-3, жүгіретін-2)
advmod(жүгіретін-2, Тез-1)
obj(көрдім-4, спортшылар-3)
punct(көрдім-4, .-5)
~~~

This relation may be tagged with `acl:relcl` in the future, as it is the way
in which Turkic languages do relative clauses.

Gerunds in genitive modifying a noun:

~~~ sdparse
Некенің тоқтатылуы жаңадан некеге тұру құқығын туғызады . \n Marriage-of terminating new-from marriage-to ? right is-born .
acl(құқығын-6, тұру-5)
~~~

Fronted relative clauses with empty copula:

~~~ sdparse
Шашы       ұзын     қызды     көрдім . \n Hair long girl saw-I .
acl(қызды-3, ұзын-2)
obj(көрдім-4, қызды-3)
nsubj(ұзын-2, Шашы-1)
punct(көрдім-4, .-5)
~~~

<!-- TODO: Do we put a copula here between ұзын and қызды -->

Conditional phrases with 'болса':

~~~ sdparse
Құлдық пен құл саудасына , қандай түрде болса да , тыйым салынады . \n Slavery and slave trade , whichever form-in may-be also , prohibition is-placed-on .
acl(түрде-7, болса-8)
advmod(болса-8, да-9)
~~~

<!-- Interlanguage links updated Po 11. listopadu 2024, 20:10:12 CET -->
