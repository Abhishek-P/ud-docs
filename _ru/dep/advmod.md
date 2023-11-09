---
layout: relation
title: 'advmod'
shortdef: 'adverbial modifier'
udver: '2'
---

An adverbial modifier of a word is a (non-clausal) [adverb](ru-pos/ADV)
or adverbial phrase that serves to modify the meaning of the word.

We differentiate adverbials realized as adverbs (`advmod`) and
adverbials realized by noun phrases or adpositional phrases ([obl]()).
However, we do not differentiate between modifiers of predicates (adverbials in a narrow sense) and modifiers of other modifier words like adjectives or adverbs (sometime called qualifiers). These functions are all subsumed under `advmod`.

~~~ sdparse
генетически модифицированная еда \n genetically modified food
advmod(модифицированная, генетически)
advmod(modified, genetically)
~~~

~~~ sdparse
менее часто \n less often
advmod(часто, менее)
advmod(often, less)
~~~

~~~ sdparse
Он прожил очень долго . \n He lived for-a-very long-time .
advmod(прожил, долго)
advmod(lived, long-time)
advmod(долго, очень)
advmod(long-time, for-a-very)
~~~

~~~ sdparse
Более 200 человек пришло на встречу . \n More-than 200 people came to the-meeting .
advmod(200-2, Более)
advmod(200-10, More-than)
~~~

<!-- Interlanguage links updated Po 6. listopadu 2023, 21:42:20 CET -->
