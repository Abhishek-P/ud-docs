---
layout: base
title:  'Statistics of PronType in UD_French-PUD'
udver: '2'
---

## Treebank Statistics: UD_French-PUD: Features: `PronType`

This feature is universal.
It occurs with 7 different values: `Art`, `Dem`, `Ind`, `Int`, `Neg`, `Prs`, `Rel`.

4834 tokens (20%) have a non-empty value of `PronType`.
121 types (2%) occur at least once with a non-empty value of `PronType`.
29 lemmas (1%) occur at least once with a non-empty value of `PronType`.
The feature is used with 2 part-of-speech tags: <tt><a href="fr_pud-pos-DET.html">DET</a></tt> (3737; 15% instances), <tt><a href="fr_pud-pos-PRON.html">PRON</a></tt> (1097; 4% instances).

### `DET`

3737 <tt><a href="fr_pud-pos-DET.html">DET</a></tt> tokens (96% of all `DET` tokens) have a non-empty value of `PronType`.

The most frequent other feature values with which `DET` and `PronType` co-occurred: <tt><a href="fr_pud-feat-Definite.html">Definite</a></tt><tt>=Def</tt> (2785; 75%), <tt><a href="fr_pud-feat-Number.html">Number</a></tt><tt>=Sing</tt> (2757; 74%), <tt><a href="fr_pud-feat-Gender.html">Gender</a></tt><tt>=Masc</tt> (1952; 52%).

`DET` tokens may have the following values of `PronType`:

* `Art` (3452; 92% of non-empty `PronType`): <em>le, la, les, l', un, une, des, l’, de, d'</em>
* `Int` (2; 0% of non-empty `PronType`): <em>quelle</em>
* `Neg` (8; 0% of non-empty `PronType`): <em>aucun, aucune</em>
* `Prs` (275; 7% of non-empty `PronType`): <em>son, sa, ses, leur, leurs, notre, nos, mon, votre, ma</em>
* `EMPTY` (141): <em>cette, ce, ces, toute, d’, tout, cet, La, L’, ladite</em>

### `PRON`

1097 <tt><a href="fr_pud-pos-PRON.html">PRON</a></tt> tokens (100% of all `PRON` tokens) have a non-empty value of `PronType`.

The most frequent other feature values with which `PRON` and `PronType` co-occurred: <tt><a href="fr_pud-feat-Person.html">Person</a></tt><tt>=3</tt> (626; 57%), <tt><a href="fr_pud-feat-Gender.html">Gender</a></tt><tt>=EMPTY</tt> (619; 56%).

`PRON` tokens may have the following values of `PronType`:

* `Dem` (118; 11% of non-empty `PronType`): <em>ce, c', cela, c’, ça, ceci, ceux, -ce, ca, celle</em>
* `Ind` (54; 5% of non-empty `PronType`): <em>on, un, quelqu'un, -t-on, certaines</em>
* `Int` (8; 1% of non-empty `PronType`): <em>qui, quoi, où, que</em>
* `Neg` (8; 1% of non-empty `PronType`): <em>rien, aucun, personne</em>
* `Prs` (691; 63% of non-empty `PronType`): <em>il, se, elle, ils, y, s', je, nous, lui, s’</em>
* `Rel` (218; 20% of non-empty `PronType`): <em>qui, où, que, qu', laquelle, lequel, lesquelles, qu’</em>

<table>
  <tr><th>Paradigm <i>qui</i></th><th><tt>Int</tt></th><th><tt>Rel</tt></th></tr>
  <tr><td><tt></tt></td><td><em>qui</em></td><td><em>qui</em></td></tr>
</table>

## Relations with Agreement in `PronType`

The 10 most frequent relations where parent and child node agree in `PronType`:
<tt>DET --[<tt><a href="fr_pud-dep-fixed.html">fixed</a></tt>]--> DET</tt> (2; 100%),
<tt>PRON --[<tt><a href="fr_pud-dep-fixed.html">fixed</a></tt>]--> PRON</tt> (2; 100%),
<tt>PRON --[<tt><a href="fr_pud-dep-conj.html">conj</a></tt>]--> PRON</tt> (1; 100%).

