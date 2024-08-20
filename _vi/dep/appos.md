---
layout: relation
title: 'appos'
shortdef: 'appositional modifier'
udver: '2'
---

An appositional modier of an NP is an NP immediately to the right of the first NP that serves to
define or modify that NP.

~~~ sdparse
Ông Minh , chủ_tịch FPT , khai_mạc hội_nghị 。
flat(Ông, Minh)
punct(Ông, ,-3)
flat(chủ_tịch, FPT)
punct(chủ_tịch, ,)
nsubj(khai_mạc, Ông)
obj(khai_mạc, hội_nghị)
appos(Ông, chủ_tịch)
punct(khai_mạc, 。)
~~~

<!-- Interlanguage links updated Ne 5. května 2024, 18:20:44 CEST -->
