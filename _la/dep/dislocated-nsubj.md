---
layout: relation
title: 'dislocated:nsubj'
shortdef: 'dislocated nominal subject'
udver: '2'
---

Through different subtypes of [`dislocated`](u-dep/dislocated) we more precisely identify which argument has been dislocated in the sentence and how it is realized in this position (nominally or clausally). This information is not directly retrievable otherwise from "basic" dependencies, since the `dislocated` relation always depends on the local head. It is also kept distinct from the use of `dislocated` for topicalisations and similar phenomena, which are not directly related to an argument expressed in the matrix clause.

In the translation of the example, the bold passage corresponds to the dislocated element, and the underlined passage to the dislocating one.

~~~ sdparse
Paraclitus spiritus sanctus , quem mittet pater in nomine meo , ille vos docebit omnia . \n Paraclete spirit holy , whom he-will-send father in name my , that to-ye he-will-teach all .
dislocated:nsubj(docebit,Paracletus)
flat(Paraclitus,spiritus)
nsubj(docebit,ille)
dislocated:nsubj(he-will-teach,Paraclete)
flat(Paraclete,spirit)
nsubj(he-will-teach,that)
~~~

'**The Paraclete, the Holy Ghost**, whom the Father will send in My name, <u>He</u> will teach you all things.' (*Summa contra Gentiles* citing John 14:26, ITTB)

<u>Note:</u> in general, the dislocated element does not need to be of the same form as the corresponding argument appearing in the matrix clause, and there can be alternation between clausal and nominal realisations. The subtype of `dislocated` depends on the type of the dislocated element, not on that of the argument in the matrix clause.  


<!-- Interlanguage links updated Ne 5. května 2024, 18:21:11 CEST -->
