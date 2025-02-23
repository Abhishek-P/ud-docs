---
layout: relation
title: 'compound:svc'
shortdef: 'compound:svc'
udver: '2'
---


### Definition

In Kyrgyz the verbs "жат-" and as a suffix at the end of a sentence "элек" , "эле"  may function as auxiliary verbs.
Instead of AUX (because it is complex) we used 'compound:svc'. 
UD is treating one of the verbs as an xcomp of the other, or in some languages as a serial verb construction (compound:svc).
So We  use the `compound:svc`.
The dependency label indicates their use (auxiliary, copula or content verb).

### Examples
~~~ sdparse
мектептердин курулушу кандай жүрүп жатат? \n How is the construction of schools going?.
compound:svc(жүрүп, жатат )
~~~

~~~ sdparse
Караколдо жашы жете элек 12 бала эмгекке тартылган \n 12 underage children were forced to work in the police station
compound:svc(жете, элек)
~~~


<!-- Interlanguage links updated Po 11. listopadu 2024, 20:10:39 CET -->
