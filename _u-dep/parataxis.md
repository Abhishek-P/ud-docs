---
layout: relation
title: 'parataxis'
shortdef: 'parataxis'
udver: '2'
---

The parataxis relation (from Greek for "place side by side") is a
relation between a word (often the main predicate of a sentence) and other
elements, such as a sentential parenthetical or a clause after a “:” or
a “;”, placed side by side without any explicit
coordination, subordination, or argument relation with the head word. Parataxis is a discourse-like equivalent of coordination, and so usually obeys an iconic ordering. Hence it is normal for the first part of a sentence to be the head and the second part to be the parataxis dependent, regardless of the headedness properties of the language.  But things do get more complicated, such as cases of parentheticals, which appear medially.

~~~ sdparse
Let 's face it we 're annoyed
parataxis(Let, annoyed)
~~~

~~~ sdparse
The guy , John said , left early in the morning
parataxis(left, said)
punct(said, ,-3)
punct(said, ,-6)
~~~

## An inventory of constructions to which parataxis has been applied

*The following material is duplicated in the [syntax overview](/u/overview/specific-syntax.html#paratactic-constructions).*

### Side-by-side sentences ("run-on sentences")

The parataxis relation is used for a pair of what could have been standalone sentences, 
but which are being treated together as a single sentence. This may happen because sentence
segmentation of the sentence was done primarily following the presence of sentence-final punctuation,
and these clauses are joined by punctuation such as a colon or comma, or not delimited by punctuation
at all. In a spoken corpus, it may happen because what is labeled as a sentence is more
commonly an utterance turn. Even if the treebanker is doing the sentence division, it may
happen because there seems to be a clear discourse relation linking two clauses. 
Sometimes there are more than two sentences joined in this way. In this case we make all the later sentences
dependents of the first one, to maximize similarity to the analysis used for conjunction.

~~~ sdparse
Bearded dragons are sight hunters , they need to see the food to move .
parataxis(hunters, need)
punct(need, ,)
~~~

This relation may happen with units that are smaller than sentences:

~~~ sdparse
Divided world the CIA
amod(world, Divided)
parataxis(world, CIA)
det(CIA, the)
~~~

### Paired clauses with non-conjunction connective ("X so Y" etc.)

The relation is also used for clauses connected by a word like *so*, *then*, *therefore*, or *however* 
if neither clause is interpreted as modifying the other, and there is no coordinating conjunction:

~~~ sdparse
He claimed to be a wizard ; however/ADV , he turned out to be a humbug .
parataxis(claimed, turned)
advmod(turned, however)
~~~

~~~ sdparse
I 'm hungry , so/ADV I 'm getting a bagel .
parataxis(hungry, getting)
advmod(getting, so)
~~~

The following, by contrast, are [advcl]() modifiers:

~~~ sdparse
Eat now so/ADV you wo n't be hungry later .
advcl(Eat, hungry)
advmod(hungry, so)
~~~

~~~ sdparse
If/SCONJ you build it , then/ADV they will come .
advcl(come, build)
mark(build, If)
advmod(come, then)
~~~

Note that *if*-clauses should almost always be analyzed as subordinate, even when *then* is present.

### Reported speech

When a speech verb interrupts reported speech content, the interruption is treated as a parenthetical parataxis:

~~~ sdparse
The guy , John said , left early in the morning
parataxis(left, said)
punct(said, ,-3)
punct(said, ,-6)
~~~

See further discussion of reported speech at [ccomp](ccomp.html#reported-speech).

### News article bylines

We have used the parataxis relation to connect the parts of a news article byline. 
There does not seem to be a better relation to use.

~~~ sdparse
Washington ( CNN ) :
parataxis(Washington, CNN)
punct(CNN, ()
punct(CNN, ))
punct(CNN, :)
~~~

### Interjected clauses

Single word or phrase interjections are analyzed as [discourse](), but when a whole clause is interjected, we use the relation parataxis.

~~~ sdparse
Calafia has great fries ( they are to die for ! )
parataxis(has, are)
punct(are, ()
punct(are, ))
~~~

~~~ sdparse
Just to let you all know Matt has confirmed the booking for 3rd Dec is OK .
parataxis(confirmed, let)
~~~

In the second example, we treat the second half as the head of the dependency
because the first half feels like a whole clause interjection, not like the main clause of the utterance.

### Tag questions

We also use the parataxis relation for tag questions such as _isn't it?_ or _haven't you?_.

~~~ sdparse
It 's not me , is it ?
parataxis(me, is)
punct(is, ,)
~~~
<!-- Interlanguage links updated Ne 5. května 2024, 18:21:43 CEST -->
