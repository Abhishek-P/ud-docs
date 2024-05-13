---
layout: base
title:  'Statistics of Mood in UD_Danish-DDT'
udver: '2'
---

## Treebank Statistics: UD_Danish-DDT: Features: `Mood`

This feature is universal.
It occurs with 2 different values: `Imp`, `Ind`.

10178 tokens (10%) have a non-empty value of `Mood`.
1516 types (8%) occur at least once with a non-empty value of `Mood`.
918 lemmas (7%) occur at least once with a non-empty value of `Mood`.
The feature is used with 2 part-of-speech tags: <tt><a href="da_ddt-pos-VERB.html">VERB</a></tt> (5902; 6% instances), <tt><a href="da_ddt-pos-AUX.html">AUX</a></tt> (4276; 4% instances).

### `VERB`

5902 <tt><a href="da_ddt-pos-VERB.html">VERB</a></tt> tokens (54% of all `VERB` tokens) have a non-empty value of `Mood`.

The most frequent other feature values with which `VERB` and `Mood` co-occurred: <tt><a href="da_ddt-feat-Definite.html">Definite</a></tt><tt>=EMPTY</tt> (5902; 100%), <tt><a href="da_ddt-feat-Number.html">Number</a></tt><tt>=EMPTY</tt> (5902; 100%), <tt><a href="da_ddt-feat-VerbForm.html">VerbForm</a></tt><tt>=Fin</tt> (5734; 97%), <tt><a href="da_ddt-feat-Voice.html">Voice</a></tt><tt>=Act</tt> (5461; 93%), <tt><a href="da_ddt-feat-Tense.html">Tense</a></tt><tt>=Pres</tt> (3753; 64%).

`VERB` tokens may have the following values of `Mood`:

* `Imp` (168; 3% of non-empty `Mood`): <em>lad, rør, se, skær, brug, hold, hæld, steg, prøv, Bland</em>
* `Ind` (5734; 97% of non-empty `Mood`): <em>er, har, siger, var, får, fik, sagde, bliver, kommer, blev</em>
* `EMPTY` (4996): <em>få, gå, se, have, fået, komme, blive, være, gøre, tage</em>

<table>
  <tr><th>Paradigm <i>få</i></th><th><tt>Ind</tt></th><th><tt>Imp</tt></th></tr>
  <tr><td><tt>_</tt></td><td></td><td><em>Få</em></td></tr>
  <tr><td><tt><tt><a href="da_ddt-feat-Tense.html">Tense</a></tt><tt>=Past</tt>|<tt><a href="da_ddt-feat-VerbForm.html">VerbForm</a></tt><tt>=Fin</tt>|<tt><a href="da_ddt-feat-Voice.html">Voice</a></tt><tt>=Act</tt></tt></td><td><em>fik</em></td><td></td></tr>
  <tr><td><tt><tt><a href="da_ddt-feat-Tense.html">Tense</a></tt><tt>=Pres</tt>|<tt><a href="da_ddt-feat-VerbForm.html">VerbForm</a></tt><tt>=Fin</tt>|<tt><a href="da_ddt-feat-Voice.html">Voice</a></tt><tt>=Act</tt></tt></td><td><em>får</em></td><td></td></tr>
  <tr><td><tt><tt><a href="da_ddt-feat-Tense.html">Tense</a></tt><tt>=Pres</tt>|<tt><a href="da_ddt-feat-VerbForm.html">VerbForm</a></tt><tt>=Fin</tt>|<tt><a href="da_ddt-feat-Voice.html">Voice</a></tt><tt>=Pass</tt></tt></td><td><em>fås</em></td><td></td></tr>
</table>

`Mood` seems to be **lexical feature** of `VERB`. 93% lemmas (857) occur only with one value of `Mood`.

### `AUX`

4276 <tt><a href="da_ddt-pos-AUX.html">AUX</a></tt> tokens (90% of all `AUX` tokens) have a non-empty value of `Mood`.

The most frequent other feature values with which `AUX` and `Mood` co-occurred: <tt><a href="da_ddt-feat-VerbForm.html">VerbForm</a></tt><tt>=Fin</tt> (4276; 100%), <tt><a href="da_ddt-feat-Voice.html">Voice</a></tt><tt>=Act</tt> (4276; 100%), <tt><a href="da_ddt-feat-Tense.html">Tense</a></tt><tt>=Pres</tt> (3245; 76%).

`AUX` tokens may have the following values of `Mood`:

* `Ind` (4276; 100% of non-empty `Mood`): <em>er, har, kan, var, skal, vil, blev, kunne, havde, må</em>
* `EMPTY` (454): <em>være, været, have, blevet, blive, kunne, kunnet, måttet, skulle, turde</em>

## Relations with Agreement in `Mood`

The 10 most frequent relations where parent and child node agree in `Mood`:
<tt>VERB --[<tt><a href="da_ddt-dep-conj.html">conj</a></tt>]--> VERB</tt> (596; 69%),
<tt>VERB --[<tt><a href="da_ddt-dep-dep.html">dep</a></tt>]--> VERB</tt> (12; 52%),
<tt>VERB --[<tt><a href="da_ddt-dep-obl-lmod.html">obl:lmod</a></tt>]--> VERB</tt> (1; 100%).

