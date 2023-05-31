---
layout: relation
title:  'nsubj:cop'
shortdef : 'nominal copular subject'
udver: '2'
---

The dependency type `nsubj:cop` is used for the nominal subject
of a copular clause. The predicative is the head of the copular
clause, and also the governor of the `nsubj:cop` dependency.

<!-- TODO: Replace the Finnish Example with a Turkish one. -->

~~~ sdparse
Matto on jo kuiva . \n The_mat is already dry .
nsubj:cop(kuiva-4, Matto-1)
cop(kuiva-4, on-2)
advmod(kuiva-4, jo-3)
punct(kuiva-4, .-5)
~~~

<!-- Interlanguage links updated Út 9. května 2023, 20:04:23 CEST -->
