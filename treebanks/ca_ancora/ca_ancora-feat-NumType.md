---
layout: base
title:  'Statistics of NumType in UD_Catalan-AnCora'
udver: '2'
---

## Treebank Statistics: UD_Catalan-AnCora: Features: `NumType`

This feature is universal.
It occurs with 3 different values: `Card`, `Frac`, `Ord`.

11575 tokens (2%) have a non-empty value of `NumType`.
1937 types (6%) occur at least once with a non-empty value of `NumType`.
1888 lemmas (8%) occur at least once with a non-empty value of `NumType`.
The feature is used with 2 part-of-speech tags: <tt><a href="ca_ancora-pos-NUM.html">NUM</a></tt> (9960; 2% instances), <tt><a href="ca_ancora-pos-ADJ.html">ADJ</a></tt> (1615; 0% instances).

### `NUM`

9960 <tt><a href="ca_ancora-pos-NUM.html">NUM</a></tt> tokens (100% of all `NUM` tokens) have a non-empty value of `NumType`.

The most frequent other feature values with which `NUM` and `NumType` co-occurred: <tt><a href="ca_ancora-feat-Gender.html">Gender</a></tt><tt>=EMPTY</tt> (8602; 86%), <tt><a href="ca_ancora-feat-Number.html">Number</a></tt><tt>=EMPTY</tt> (7305; 73%), <tt><a href="ca_ancora-feat-NumForm.html">NumForm</a></tt><tt>=Digit</tt> (6665; 67%).

`NUM` tokens may have the following values of `NumType`:

* `Card` (9946; 100% of non-empty `NumType`): <em>dos, tres, dues, quatre, cent, un, 10, cinc, una, sis</em>
* `Frac` (14; 0% of non-empty `NumType`): <em>cada, 1,1, 10, 15, 161, 17,8/100.000, 26,5/100.000, 3,9, 37,45, 57,9/100.000</em>
* `EMPTY` (2): <em>8'5, cent</em>

<table>
  <tr><th>Paradigm <i>1.1</i></th><th><tt>Card</tt></th><th><tt>Frac</tt></th></tr>
  <tr><td><tt></tt></td><td><em>1,1</em></td><td><em>1,1</em></td></tr>
</table>

`NumType` seems to be **lexical feature** of `NUM`. 100% lemmas (1865) occur only with one value of `NumType`.

### `ADJ`

1615 <tt><a href="ca_ancora-pos-ADJ.html">ADJ</a></tt> tokens (5% of all `ADJ` tokens) have a non-empty value of `NumType`.

The most frequent other feature values with which `ADJ` and `NumType` co-occurred: <tt><a href="ca_ancora-feat-VerbForm.html">VerbForm</a></tt><tt>=EMPTY</tt> (1615; 100%), <tt><a href="ca_ancora-feat-Number.html">Number</a></tt><tt>=Sing</tt> (1257; 78%), <tt><a href="ca_ancora-feat-Gender.html">Gender</a></tt><tt>=Masc</tt> (887; 55%).

`ADJ` tokens may have the following values of `NumType`:

* `Ord` (1615; 100% of non-empty `NumType`): <em>primer, primera, últims, segona, últim, segon, primers, tercer, última, darrers</em>
* `EMPTY` (28467): <em>passat, gran, nou, general, nova, catalana, espanyol, grans, baix, noves</em>

`NumType` seems to be **lexical feature** of `ADJ`. 100% lemmas (44) occur only with one value of `NumType`.

## Relations with Agreement in `NumType`

The 10 most frequent relations where parent and child node agree in `NumType`:
<tt>NUM --[<tt><a href="ca_ancora-dep-compound.html">compound</a></tt>]--> NUM</tt> (424; 100%),
<tt>NUM --[<tt><a href="ca_ancora-dep-conj.html">conj</a></tt>]--> NUM</tt> (245; 98%),
<tt>NUM --[<tt><a href="ca_ancora-dep-appos.html">appos</a></tt>]--> NUM</tt> (24; 100%),
<tt>NUM --[<tt><a href="ca_ancora-dep-nummod.html">nummod</a></tt>]--> NUM</tt> (12; 86%),
<tt>ADJ --[<tt><a href="ca_ancora-dep-conj.html">conj</a></tt>]--> ADJ</tt> (6; 67%),
<tt>ADJ --[<tt><a href="ca_ancora-dep-obj.html">obj</a></tt>]--> ADJ</tt> (1; 100%),
<tt>NUM --[<tt><a href="ca_ancora-dep-dep.html">dep</a></tt>]--> NUM</tt> (1; 100%),
<tt>NUM --[<tt><a href="ca_ancora-dep-obj.html">obj</a></tt>]--> NUM</tt> (1; 100%).

