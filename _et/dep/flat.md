---
layout: relation
title: 'flat'
shortdef: 'flat multiword expression'
udver: '2'
---

The dependency relation 'flat' is used for exocentric (headless) semi-fixed MWEs like names (Arvo Pärt), dates and foreign phrases. 

~~~ sdparse
Arvo Pärt
flat(Pärt-2, Arvo-1)
~~~

~~~ sdparse
entry level kaamerate hinnad \n prices for entry level cameras
flat(entry-1, level-2)
flat(entry-8, level-9)
nmod(kaamerate,entry-1)
nmod(cameras,entry-8)
~~~


<!-- Interlanguage links updated Út 9. května 2023, 20:04:15 CEST -->
