---
layout: base
title:  'Statistics of Mood in UD_Polish-PUD'
udver: '2'
---

## Treebank Statistics: UD_Polish-PUD: Features: `Mood`

This feature is universal.
It occurs with 2 different values: `Imp`, `Ind`.

1719 tokens (9%) have a non-empty value of `Mood`.
979 types (13%) occur at least once with a non-empty value of `Mood`.
599 lemmas (12%) occur at least once with a non-empty value of `Mood`.
The feature is used with 2 part-of-speech tags: <tt><a href="pl_pud-pos-VERB.html">VERB</a></tt> (1325; 7% instances), <tt><a href="pl_pud-pos-AUX.html">AUX</a></tt> (394; 2% instances).

### `VERB`

1325 <tt><a href="pl_pud-pos-VERB.html">VERB</a></tt> tokens (81% of all `VERB` tokens) have a non-empty value of `Mood`.

The most frequent other feature values with which `VERB` and `Mood` co-occurred: <tt><a href="pl_pud-feat-VerbForm.html">VerbForm</a></tt><tt>=Fin</tt> (1325; 100%), <tt><a href="pl_pud-feat-Voice.html">Voice</a></tt><tt>=Act</tt> (1296; 98%), <tt><a href="pl_pud-feat-Number.html">Number</a></tt><tt>=Sing</tt> (935; 71%), <tt><a href="pl_pud-feat-Animacy.html">Animacy</a></tt><tt>=EMPTY</tt> (885; 67%), <tt><a href="pl_pud-feat-Tense.html">Tense</a></tt><tt>=Past</tt> (811; 61%), <tt><a href="pl_pud-feat-Person.html">Person</a></tt><tt>=EMPTY</tt> (789; 60%), <tt><a href="pl_pud-feat-Aspect.html">Aspect</a></tt><tt>=Imp</tt> (731; 55%).

`VERB` tokens may have the following values of `Mood`:

* `Imp` (2; 0% of non-empty `Mood`): <em>Powiedzmy, Upuść</em>
* `Ind` (1323; 100% of non-empty `Mood`): <em>może, ma, powiedział, mogą, można, było, miał, jest, miała, mówi</em>
* `EMPTY` (303): <em>być, zrobić, doprowadzić, mieć, począwszy, tworząc, utrzymać, biorąc, poradzić, tworzyć</em>

<table>
  <tr><th>Paradigm <i>powiedzieć</i></th><th><tt>Ind</tt></th><th><tt>Imp</tt></th></tr>
  <tr><td><tt><tt><a href="pl_pud-feat-Animacy.html">Animacy</a></tt><tt>=Hum</tt>|<tt><a href="pl_pud-feat-Gender.html">Gender</a></tt><tt>=Masc</tt>|<tt><a href="pl_pud-feat-Number.html">Number</a></tt><tt>=Sing</tt>|<tt><a href="pl_pud-feat-Tense.html">Tense</a></tt><tt>=Past</tt></tt></td><td><em>powiedział</em></td><td></td></tr>
  <tr><td><tt><tt><a href="pl_pud-feat-Gender.html">Gender</a></tt><tt>=Fem</tt>|<tt><a href="pl_pud-feat-Number.html">Number</a></tt><tt>=Sing</tt>|<tt><a href="pl_pud-feat-Tense.html">Tense</a></tt><tt>=Past</tt></tt></td><td><em>powiedziała</em></td><td></td></tr>
  <tr><td><tt><tt><a href="pl_pud-feat-Number.html">Number</a></tt><tt>=Plur</tt>|<tt><a href="pl_pud-feat-Person.html">Person</a></tt><tt>=1</tt></tt></td><td></td><td><em>Powiedzmy</em></td></tr>
  <tr><td><tt><tt><a href="pl_pud-feat-Person.html">Person</a></tt><tt>=0</tt>|<tt><a href="pl_pud-feat-Tense.html">Tense</a></tt><tt>=Past</tt></tt></td><td><em>powiedziano</em></td><td></td></tr>
</table>

`Mood` seems to be **lexical feature** of `VERB`. 100% lemmas (597) occur only with one value of `Mood`.

### `AUX`

394 <tt><a href="pl_pud-pos-AUX.html">AUX</a></tt> tokens (86% of all `AUX` tokens) have a non-empty value of `Mood`.

The most frequent other feature values with which `AUX` and `Mood` co-occurred: <tt><a href="pl_pud-feat-VerbForm.html">VerbForm</a></tt><tt>=Fin</tt> (394; 100%), <tt><a href="pl_pud-feat-Voice.html">Voice</a></tt><tt>=Act</tt> (320; 81%), <tt><a href="pl_pud-feat-Animacy.html">Animacy</a></tt><tt>=EMPTY</tt> (310; 79%), <tt><a href="pl_pud-feat-Aspect.html">Aspect</a></tt><tt>=Imp</tt> (277; 70%), <tt><a href="pl_pud-feat-Number.html">Number</a></tt><tt>=Sing</tt> (263; 67%), <tt><a href="pl_pud-feat-Gender.html">Gender</a></tt><tt>=EMPTY</tt> (233; 59%), <tt><a href="pl_pud-feat-Person.html">Person</a></tt><tt>=EMPTY</tt> (205; 52%), <tt><a href="pl_pud-feat-Tense.html">Tense</a></tt><tt>=Pres</tt> (200; 51%).

`AUX` tokens may have the following values of `Mood`:

* `Ind` (394; 100% of non-empty `Mood`): <em>jest, to, był, są, został, będzie, było, była, zostały, były</em>
* `EMPTY` (66): <em>by, em, być, m, śmy, zostać, ście</em>

## Relations with Agreement in `Mood`

The 10 most frequent relations where parent and child node agree in `Mood`:
<tt>VERB --[<tt><a href="pl_pud-dep-conj.html">conj</a></tt>]--> VERB</tt> (145; 99%),
<tt>VERB --[<tt><a href="pl_pud-dep-ccomp.html">ccomp</a></tt>]--> VERB</tt> (35; 88%),
<tt>VERB --[<tt><a href="pl_pud-dep-parataxis-obj.html">parataxis:obj</a></tt>]--> VERB</tt> (32; 97%),
<tt>VERB --[<tt><a href="pl_pud-dep-ccomp-obj.html">ccomp:obj</a></tt>]--> VERB</tt> (29; 97%),
<tt>VERB --[<tt><a href="pl_pud-dep-aux.html">aux</a></tt>]--> AUX</tt> (13; 62%),
<tt>VERB --[<tt><a href="pl_pud-dep-parataxis-insert.html">parataxis:insert</a></tt>]--> VERB</tt> (5; 100%),
<tt>VERB --[<tt><a href="pl_pud-dep-advcl-relcl.html">advcl:relcl</a></tt>]--> VERB</tt> (3; 100%),
<tt>VERB --[<tt><a href="pl_pud-dep-csubj.html">csubj</a></tt>]--> VERB</tt> (3; 100%).

