---
layout: relation
title: 'vocative:mention'
shortdef: 'Twitter mentions'
udver: '2'
---

The specialization of `vocative`, `vocative:mention` used for sicial media @-mentions and it links the addressee (i.e. the used called out by means of the @-mention) to its host sentence. This follows earlier examples for Italian and Irish social media treebanks.

~~~ sdparse
@user Își bate dracu' nevasta 😂
vocative:mention(dracu', @user)
~~~

However, just like hashtags, whenever they are syntactically integrated into the sentence, they are annotated according to their actual syntactic role.

~~~ sdparse
vorba lui @user
nmod(vorba, @user)
~~~
<!-- Interlanguage links updated Po 6. listopadu 2023, 21:43:29 CET -->
