---
layout: relation
title: 'nsubj'
shortdef: 'nominal subject'
udver: '2'
---

A nominal subject is a noun phrase which is the syntactic subject of a clause. 

~~~ sdparse
Ali okuyor \n Ali is reading
nsubj(okuyor, Ali)
~~~

``nsubj`` is also used for subjects of  adjectival or nominal predicates.
~~~ sdparse
Ali doktor \n Ali is a doctor
nsubj(doktor, Ali)
~~~

~~~ sdparse
Kitap kalın \n The book is thick
nsubj(kalın, Kitap)
~~~


For existential sentences, "the thing that exists" is the subject.
This includes possessive existentials.
~~~ sdparse
Üç kitap var \n There are three books
nsubj(var, kitap)
~~~

~~~ sdparse
Benim üç kitabım var \n I have three books
nsubj(var, kitabım)
~~~


``nsubj`` (without a subtype) is also used
for the grammatical subject of a passivized verb.
The subtype ``nsubj:pass`` is not used.
~~~ sdparse
Kitap okundu \n The book was read
nsubj(okundu, Kitap)
~~~

Note that [csubj]() relation used for clausal subjects,
even those with a the verbal noun head.

<!-- Interlanguage links updated Po 11. listopadu 2024, 20:11:07 CET -->
