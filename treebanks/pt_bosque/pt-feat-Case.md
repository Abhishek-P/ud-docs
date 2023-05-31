---
layout: base
title:  'Statistics of Case in UD_Portuguese'
udver: '2'
---

## Treebank Statistics: UD_Portuguese: Features: `Case`

This feature is universal.
It occurs with 3 different values: `Acc`, `Dat`, `Nom`.

2540 tokens (1%) have a non-empty value of `Case`.
41 types (0%) occur at least once with a non-empty value of `Case`.
12 lemmas (0%) occur at least once with a non-empty value of `Case`.
The feature is used with 1 part-of-speech tags: <tt><a href="pt-pos-PRON.html">PRON</a></tt> (2540; 1% instances).

### `PRON`

2540 <tt><a href="pt-pos-PRON.html">PRON</a></tt> tokens (35% of all `PRON` tokens) have a non-empty value of `Case`.

The most frequent other feature values with which `PRON` and `Case` co-occurred: <tt><a href="pt-feat-PronType.html">PronType</a></tt><tt>=Prs</tt> (2539; 100%), <tt><a href="pt-feat-Person.html">Person</a></tt><tt>=3</tt> (1936; 76%), <tt><a href="pt-feat-Number.html">Number</a></tt><tt>=Sing</tt> (1620; 64%), <tt><a href="pt-feat-Gender.html">Gender</a></tt><tt>=Masc</tt> (1364; 54%).

`PRON` tokens may have the following values of `Case`:

* `Acc` (1779; 70% of non-empty `Case`): <em>se, o, me, a, nos, lo, os, la, as, los</em>
* `Dat` (228; 9% of non-empty `Case`): <em>lhe, me, nos, lhes, se, Ihe, vos</em>
* `Nom` (533; 21% of non-empty `Case`): <em>ele, eu, eles, ela, você, nós, elas, vocês, voce, vós</em>
* `EMPTY` (4693): <em>que, o, isso, quem, tudo, isto, nada, os, qual, todos</em>

<table>
  <tr><th>Paradigm <i>ele</i></th><th><tt>Nom</tt></th><th><tt>Acc</tt></th><th><tt>Dat</tt></th></tr>
  <tr><td><tt><tt><a href="pt-feat-Gender.html">Gender</a></tt><tt>=Masc</tt>|<tt><a href="pt-feat-Number.html">Number</a></tt><tt>=Sing</tt>|<tt><a href="pt-feat-PronType.html">PronType</a></tt><tt>=Dem</tt></tt></td><td></td><td><em>o</em></td><td></td></tr>
  <tr><td><tt><tt><a href="pt-feat-Gender.html">Gender</a></tt><tt>=Masc</tt>|<tt><a href="pt-feat-Number.html">Number</a></tt><tt>=Sing</tt>|<tt><a href="pt-feat-PronType.html">PronType</a></tt><tt>=Prs</tt></tt></td><td><em>ele</em></td><td><em>o, lo, no</em></td><td><em>lhe, Ihe</em></td></tr>
  <tr><td><tt><tt><a href="pt-feat-Gender.html">Gender</a></tt><tt>=Masc</tt>|<tt><a href="pt-feat-Number.html">Number</a></tt><tt>=Plur</tt>|<tt><a href="pt-feat-PronType.html">PronType</a></tt><tt>=Prs</tt></tt></td><td><em>eles</em></td><td></td><td></td></tr>
  <tr><td><tt><tt><a href="pt-feat-Gender.html">Gender</a></tt><tt>=Fem</tt>|<tt><a href="pt-feat-Number.html">Number</a></tt><tt>=Sing</tt>|<tt><a href="pt-feat-PronType.html">PronType</a></tt><tt>=Prs</tt></tt></td><td><em>ela</em></td><td></td><td><em>lhe</em></td></tr>
  <tr><td><tt><tt><a href="pt-feat-Gender.html">Gender</a></tt><tt>=Fem</tt>|<tt><a href="pt-feat-Number.html">Number</a></tt><tt>=Plur</tt>|<tt><a href="pt-feat-PronType.html">PronType</a></tt><tt>=Prs</tt></tt></td><td><em>elas</em></td><td></td><td></td></tr>
  <tr><td><tt><tt><a href="pt-feat-Gender.html">Gender</a></tt><tt>=Unsp</tt>|<tt><a href="pt-feat-Number.html">Number</a></tt><tt>=Sing</tt>|<tt><a href="pt-feat-PronType.html">PronType</a></tt><tt>=Prs</tt></tt></td><td></td><td></td><td><em>lhe</em></td></tr>
</table>

## Relations with Agreement in `Case`

The 10 most frequent relations where parent and child node agree in `Case`:
<tt>PRON --[<tt><a href="pt-dep-conj.html">conj</a></tt>]--> PRON</tt> (4; 100%),
<tt>PRON --[<tt><a href="pt-dep-parataxis.html">parataxis</a></tt>]--> PRON</tt> (1; 100%).

