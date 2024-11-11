---
layout: relation
title: 'nsubj:pass'
shortdef: 'passive nominal subject'
udver: '2'
---

A passive nominal subject is a noun phrase which is the syntactic subject of a passive clause. Examples in Indonesian:

~~~ sdparse
ROOT Ia dilarang memasuki rumah . \n  He was prohibited from entering the house .
nsubj:pass(Ia, dilarang)
advcl(dilarang, memasuki)
root(ROOT, dilarang)
obj(memasuki, rumah)
~~~

~~~ sdparse
ROOT Beberapa peradaban kuno terletak di sekitar pesisir Mediterania . \n Several ancient civilisations were located around the Mediterranean shores .
nsubj:pass(terletak, peradaban)
root(ROOT, terletak)
obl(terletak, pesisir)
nmod:lmod(pesisir, sekitar)
~~~


<!-- Interlanguage links updated Po 11. listopadu 2024, 20:11:10 CET -->
