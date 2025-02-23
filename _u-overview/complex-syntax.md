---
layout: base
title:  'Complex Clauses'
permalink: u/overview/complex-syntax.html
udver: '2'
---

# Complex Clauses

This section of the [syntax overview](syntax.html) is devoted to complex clauses, namely:

* [Coordinated clauses](#coordination)
* [Subordinate clauses](#subordination)
* [Predicate clauses](#predicate-clauses)
* [Secondary predicates](#secondary-predicates)

## Coordination

Complex clauses involving coordination arise when two main clauses or two subordinate clauses at the same level are
linked in a coordinate structure, which may or may not involve an overt coordinating conjunction. Coordinate structures are in principle symmetrical, but the first clause is by convention treated as the parent (or “technical head”) of all subsequent coordinated clauses via the [u-dep/conj]() relation. Coordinating conjunctions and punctuation delimiting the conjuncts are attached to the associated conjunct using the [u-dep/cc]() and [u-dep/punct]() relations respectively.

~~~ sdparse
He came home , took a shower and immediately went to bed .
conj(came, took)
conj(came, went)
punct(took, ,-4)
cc(went, and)
~~~

Asyndetic coordination occurs when there is no overt coordinating conjunction.

~~~ sdparse
Veni , vidi , vici .
conj(Veni, vidi)
conj(Veni, vici)
punct(vidi, ,-2)
punct(vici, ,-4)
~~~

As a special case, the first conjunct may be implicit or part of an earlier sentence.

~~~ sdparse
And then we left .
cc(left, And)
~~~

### Ellipsis in Clause Coordination

Coordination is often combined with _ellipsis_, where one or more of the normally obligatory constituents
of a clause or omitted because they can be inferred from material in another conjunct.

If the main predicate is elided, an associated `aux` or `cop` can be promoted to head of the clause.

~~~ sdparse
Sue likes pasta and Peter does , too .

nsubj(likes-2, Sue-1)
obj(likes-2, pasta-3)
conj(likes-2, does-6)
nsubj(does-6, Peter-5)
advmod(does-6, too-8)
~~~

~~~ sdparse
Sue is hungry and Peter is , too .

nsubj(hungry-3, Sue-1)
cop(hungry-3, is-2)
conj(hungry-3, is-6)
nsubj(is-6, Peter-5)
advmod(is-6, too-8)
~~~

In more complicated cases where a predicate is elided but no `aux` or `cop` is present, promotion can lead to unnatural and confusing relations. For example, in the following sentence, _you_ would be the subject of _coffee_, suggesting that the second clause contains a nonverbal predication rather than an elided predicate.

~~~ sdparse
I like tea and you coffee .

nsubj(like-2, I-1)
obj(like-2, tea-3)
nsubj(coffee-6, you-5)
conj(like-2, coffee-6)
~~~

In such cases, we therefore use the special `orphan` relation to attach siblings to the promoted element.

~~~ sdparse
I like tea and you coffee .

nsubj(like-2, I-1)
obj(like-2, tea-3)
conj(like-2, you-5)
cc(you-5, and-4)
orphan(you-5, coffee-6)
~~~

~~~ sdparse
Mary wants to buy a book and Jenny a CD .

nsubj(wants-2, Mary-1)
xcomp(wants-2, buy-4)
obj(buy-4, book-6)
conj(wants-2, Jenny-8)
orphan(Jenny-8, CD-10)
~~~

~~~ sdparse
They had left the company , many for good .

nsubj(left, They)
obj(left, company)
conj(left, many)
orphan(many, good)
~~~

~~~ sdparse
Mary wants to buy a book . ROOT And Jenny a CD .

nsubj(wants-2, Mary-1)
xcomp(wants-2, buy-4)
obj(buy-4, book-6)
root(ROOT, Jenny)
orphan(Jenny, CD)
~~~

Note that the `orphan` relation is only used when an ordinary relation would be misleading (for example, when attaching an object to a subject). In particular, the ordinary `cc` relation should be used for the coordinating conjunction, which attaches to the pseudo-constituent formed through the `orphan` dependency.

## Subordination

Complex clauses involving subordination arise because a core or non-core dependent is realized as a clausal structure.
We distinguish four basic types:

1. Clausal subjects ([u-dep/csubj]()).
2. Clausal complements (objects), divided into those with obligatory control ([u-dep/xcomp]()) and those without ([u-dep/ccomp]()).
3. Adverbial clause modifiers ([u-dep/advcl]()).
4. Adnominal clause modifiers ([u-dep/acl]()) (with relative clauses as an important subtype in many languages).

In addition, we discuss _secondary predicates_, which are analyzed as clausal complements or adnominal clause modifiers.

### Clausal Subjects

A clausal subject is a clausal syntactic subject of a clause. Its governor may be a verb or a nonverbal predicate.
If the governor is in the passive, the subtype [csubj:pass]() is strongly recommended.

~~~ sdparse
Eating meals at regular times can improve digestion
csubj(improve, Eating)
~~~

~~~ sdparse
That nobody said anything drives me crazy
csubj(drives, said)
~~~

~~~ sdparse
Whether pigs fly has been disputed
csubj:pass(disputed, fly)
~~~

### Clausal Complements (Objects)

A clausal complement of a verb or adjective is a dependent clause
which is a core argument. That is, it functions like an object of the verb, or
adjective.

~~~ sdparse
He says that you like to swim
ccomp(says, like)
mark(like, that)
~~~

~~~ sdparse
He says you like to swim
ccomp(says, like)
~~~

Such clausal complements may be finite or nonfinite. However, if the
subject of the clausal complement is controlled (that is, _must_ be the same
as the higher subject or object, with no other possible interpretation),
the appropriate relation is [xcomp]().

~~~ sdparse
The boss said to start digging
ccomp(said, start)
mark(start, to)
xcomp(start, digging)
~~~

~~~ sdparse
We started digging
xcomp(started, digging)
~~~

The key difference here is that, in the first sentence, who will be starting to do the digging is a question of anaphora (it may be some contextually relevant individual or group, which may or may not include the boss), while in both sentences, the person or persons who are starting to do something are necessarily the same people who are digging (i.e., in the second sentence, the subject of __digging__ can only be __we__).
This is what distinguishes `ccomp` and `xcomp`.

The controlled subject of the [xcomp]() can also be an object ([obj]() or [iobj]()) – indeed, it is usually the object when one is present (Visser's generalization). UD adopts an object with infinitive (or "raising to object") analysis of such constructions (rather than the "small clause" or "exceptional case marking" analyses that are prominent in many recent strands of generative grammar). So UD uses analyses like the following for cases where there is obligatory control between an object and the subject of a subordinate clause:

~~~ sdparse
Sue wanted Fred to accept the job.
obj(wanted, Fred)
mark(accept, to)
xcomp(wanted, accept)
~~~

~~~ sdparse
Sue asked Fred to accept the job.
iobj(asked, Fred)
mark(accept, to)
xcomp(asked, accept)
~~~

~~~ sdparse
Please let us know
discourse(let, Please)
obj(let, us)
xcomp(let, know)
~~~

(`ccomp` is no longer used for a copular predicate which is itself a clause: see [Predicate Clauses](#predicate-clauses).)

### Adverbial Clause Modifiers

An adverbial clause modifier is a clause which modifies a verb or other predicate (adjective, etc.),
as a modifier not as a core complement. This includes things such as a temporal clause, consequence, conditional clause, purpose
clause, etc. The dependent must be clausal (or else it is an [advmod]()) and the dependent is the main predicate of the clause.

~~~ sdparse
The accident happened as night was falling
advcl(happened, falling)
~~~

~~~ sdparse
If you know who did it, you should tell the teacher
advcl(tell, know)
~~~

~~~ sdparse
He talked to him in order to secure the account
advcl(talked, secure)
~~~

~~~ sdparse
He was upset when I talked to him
advcl(upset, talked)
~~~

This relation is also used for optional depictives:

~~~ sdparse
She entered the room sad
advcl(entered, sad)
~~~

~~~ sdparse
He painted the model naked
advcl(painted, naked)
~~~

### Adnominal Clause Modifiers

An adnominal clause modifier is a clause which modifies a nominal.

~~~ sdparse
the issues as he sees them
acl(issues, sees)
~~~

~~~ sdparse
Cette affaire à suivre \n This case to follow
acl(affaire, suivre)
~~~

A relative clause is a special type of adnominal clause, characterized by finiteness and usually omission of
the modified noun in the embedded clause. Some languages use the subtype [acl:relcl]() for relative clauses.

~~~ sdparse
I saw the man you love
acl:relcl(man, love)
~~~

Some languages allow finite clausal complements for nouns with
a subset of nouns like *fact* or *report*. These look roughly like relative clauses, but do not have any
omitted role in the dependent clause. This is the class of "content
clauses" in Huddleston and Pullum (2002). These are also analyzed as `acl`.

~~~ sdparse
the fact that nobody cares
acl(fact, cares)
~~~

## Predicate Clauses

In copula constructions, the predicate may be an entire clause. Because UD does not represent constituent structure, the word that is the predicate of the inner clause does double duty as the head of the outer copula construction. This means that there may be multiple subject relations with the same head—an exception to the usual rule that a word should have at most one [nsubj]() or [csubj]() dependent. The subtype `:outer` can be used to distinguish the subject that belongs to the outer clause (the innermost nested clause is the "normal" clause; if it has a subject, it does not receive any special designation):

~~~ sdparse
-ROOT- The problem is that this has never been tried .
nsubj:outer(tried, problem)
cop(tried, is)
mark(tried, that)
nsubj:pass(tried, this)
aux(tried, has)
advmod(tried, never)
aux:pass(tried, been)
root(-ROOT-, tried)
~~~

~~~ sdparse
The title is Some Like It Hot .
nsubj:outer(Like, title)
cop(Like, is)
nsubj(Like, Some)
obj(Like, It)
xcomp(Like, Hot)
~~~

There may be an outer subject with no inner subject:

~~~ sdparse
The important thing is to keep calm .
nsubj:outer(keep, thing)
cop(keep, is)
mark(keep, to)
xcomp(keep, calm)
~~~

~~~ sdparse
To hike in the mountains is to experience the best of nature .
csubj:outer(experience, hike)
obl(hike, mountains)
mark(hike, To)
cop(experience, is)
mark(experience, to)
obj(experience, best)
~~~

Some languages have zero copula constructions—that is, there is no overt copula, but the nesting is the same, and the outer subject can be distinguished with [nsubj:outer]() or [csubj:outer](). 
Here is a Hebrew sentence demonstrating a copular clause nested within another copular clause, i.e. _The problem (is) that Kim (is) tired_:

~~~ sdparse
ha/DET be'aya/NOUN she/SCONJ Kim/PROPN 'ayefa/ADJ .
det(be'aya, ha)
nsubj:outer('ayefa, be'aya)
mark('ayefa, she)
nsubj('ayefa, Kim)
~~~

In principle there could be multiple levels of nesting with multiple `:outer` subjects (though this is extremely rare in practice):

~~~ sdparse
My memory is that the problem is that Kim will be traveling in March .
nsubj:outer(traveling, memory)
cop(traveling, is-3)
mark(traveling, that-4)
nsubj:outer(traveling, problem)
cop(traveling, is-7)
mark(traveling, that-8)
nsubj(traveling, Kim)
~~~

(This was [changed](/changes.html#multiple-subjects) from earlier versions of the guidelines, where the outer copula was the head of a `ccomp` relation.)

## Secondary Predicates

A clause can contain a _secondary predication_ or _predicative_. The most common case is with adjectives, although the same effect can sometimes be achieved with a predicative noun or preposition-marked phrase.

* _She declared the cake **beautiful**._
* _She declared the cake **a success**._
* _She entered the room **sad**._
* _She hammered the metal **flat**._

There are two predicates in such sentences, the main predicate and an additional one, such as *the cake* being *beatiful* or *She* being *sad*.

Huddleston and Pullum (2002) “The Cambridge Grammar of the English Language”, chapter 4 section 5.3, divide predicatives into obligatory and optional predicatives, which can be either depictives or resultatives, and which can appear in an intransitive or transitive clause, giving eight possibilities:

* _He looked **fantastic**._ [obligatory, depictive, intransitive host]
* _She kept Kim **warm**._ [obligatory, depictive, transitive host]
* _The boss became **angry**._ [obligatory, resultative, intransitive host]
* _This made me **furious**._ [obligatory, resultative, transitive host]
* _He died **young**._ [optional, depictive, intransitive host]
* _He ate the steak **almost raw**._ [optional, depictive, transitive host]
* _The pond froze **solid**._ [optional, resultative, intransitive host]
* _He painted the house **blue**._ [optional, resultative, transitive host]

In UD, obligatory predicatives are always treated as an `xcomp`: The secondary predicate is attached as an `xcomp` of the main predicate. In most cases, as well as an adjective depictive, you can use a verbal or nominal predicate in the same position (e.g., _He looked [an idiot]_; _This made me [seethe with anger]_).

~~~ sdparse
She declared the cake beautiful .
nsubj(declared, She)
obj(declared, cake)
xcomp(declared, beautiful)
~~~

In the enhanced representation, there is an additional subject link showing the secondary predication, which is obligatorily a particular role in the higher clause:

~~~ sdparse
She declared the cake beautiful .
nsubj(declared, She)
obj(declared, cake)
xcomp(declared, beautiful)
nsubj(beautiful, cake)
~~~

A Czech example:

~~~ sdparse
jmenovat někoho generálem \n to-appoint someone as-a-general
obj(jmenovat, někoho)
xcomp(jmenovat, generálem)
~~~

The relation `xcomp` is used for core arguments of clausal predicates,
so it will not be used for some other instances of secondary predication.
Optional depictives are analyzed as [advcl]() adjuncts.

For instance, in _She entered the room sad_ we also have a double predication
(she entered the room; she was sad).
But _sad_ is not a core argument of _enter:_ leaving it out will neither affect grammaticality
nor significantly alter the meaning of the verb.
On the other hand, leaving out _beautiful_ in _She declared the cake beautiful_
will either render the sentence ungrammatical or lead to a different interpretation of _declared._

The result is that in _She entered the room sad_, _sad_ is considered a modifier (not complement) of the verb,
with the relation [advcl]() instead of `xcomp`. 
(This was [changed](/changes.html#optional-depictives) from the previous approach which analyzed the secondary predication directly with [acl](), 
because the nominal predicand is not always overt, and even when it is, the adjective does not really belong to the same nominal phrase.)

~~~ sdparse
She entered the room sad .
nsubj(entered, She)
det(room, the)
obj(entered, room)
advcl(entered, sad)
punct(entered, .)
~~~

~~~ sdparse
Entering the room sad is not recommended .
csubj(recommended, Entering)
det(room, the)
obj(Entering, room)
advcl(Entering, sad)
cop(recommended, is)
advmod(recommended, not)
punct(recommended, .)
~~~

Notice that *while* can be inserted before *sad*, clearly marking it as a clause. 

A Czech example:

~~~ sdparse
Vstoupila do místnosti smutná . \n She-entered to room sad .
advcl(Vstoupila, smutná)
advcl(She-entered, sad)
~~~

There is no need to decide whether an example like the following is a depictive or a manner adverbial:

~~~ sdparse
Linda found the money walking our dog .
nsubj(found, Linda)
det(money, the)
obj(found, money)
advcl(found, walking)
det(dog, our)
obj(walking, dog)
punct(found, .)
~~~

The optional secondary predication or controlled adjunct subject relation can be represented with an enhanced dependency edge 
in addition to the [advcl]() relation.

The remaining, most subtle case is optional resultatives. For these,
we uniformly use `xcomp`:

~~~ sdparse
He painted the house blue .
obj(painted, house)
xcomp(painted, blue)
~~~

Even though the resultative is optional here, one may argue that it is still a complement (an argument) of the higher verb
(he is painting something blue), in a way that is not true of depictives. Such an analysis of optional resultatives as core arguments is adopted for English by Huddleston and Pullum (p. 262). In LFG terms, we would say that the verb has acquired a new
subcategorization frame by application of a lexical rule, and that this frame
includes an additional `xcomp` argument. Such an analysis is buttressed by the fact that normally intransitive verbs like _to bark_ can also form similar resultatives by gaining a new subcategorization which adds both a `obj` and an `xcomp`, as in the example below.

~~~ sdparse
The dog barked the neighbors awake .
obj(barked, neighbors)
xcomp(barked, awake)
~~~

