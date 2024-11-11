---
layout: base
title:  'Statistics of Gender in UD_English-LinES'
udver: '2'
---

## Treebank Statistics: UD_English-LinES: Features: `Gender`

This feature is universal.
It occurs with 3 different values: `Fem`, `Masc`, `Neut`.

2985 tokens (3%) have a non-empty value of `Gender`.
16 types (0%) occur at least once with a non-empty value of `Gender`.
7 lemmas (0%) occur at least once with a non-empty value of `Gender`.
The feature is used with 1 part-of-speech tags: <tt><a href="en_lines-pos-PRON.html">PRON</a></tt> (2985; 3% instances).

### `PRON`

2985 <tt><a href="en_lines-pos-PRON.html">PRON</a></tt> tokens (31% of all `PRON` tokens) have a non-empty value of `Gender`.

The most frequent other feature values with which `PRON` and `Gender` co-occurred: <tt><a href="en_lines-feat-Number.html">Number</a></tt><tt>=Sing</tt> (2985; 100%), <tt><a href="en_lines-feat-Person.html">Person</a></tt><tt>=3</tt> (2985; 100%), <tt><a href="en_lines-feat-PronType.html">PronType</a></tt><tt>=Prs</tt> (2985; 100%), <tt><a href="en_lines-feat-Poss.html">Poss</a></tt><tt>=EMPTY</tt> (1929; 65%).

`PRON` tokens may have the following values of `Gender`:

* `Fem` (568; 19% of non-empty `Gender`): <em>her, she, herself, hers, itself</em>
* `Masc` (2313; 77% of non-empty `Gender`): <em>he, his, him, himself</em>
* `Neut` (104; 3% of non-empty `Gender`): <em>its, itself</em>
* `EMPTY` (6592): <em>I, it, you, that, my, they, we, what, there, me</em>

<table>
  <tr><th>Paradigm <i>it</i></th><th><tt>Fem</tt></th><th><tt>Neut</tt></th></tr>
  <tr><td><tt><tt><a href="en_lines-feat-Case.html">Case</a></tt><tt>=Acc</tt>|<tt><a href="en_lines-feat-Reflex.html">Reflex</a></tt><tt>=Yes</tt></tt></td><td><em>itself</em></td><td><em>itself</em></td></tr>
  <tr><td><tt><tt><a href="en_lines-feat-Poss.html">Poss</a></tt><tt>=Yes</tt></tt></td><td></td><td><em>Its</em></td></tr>
</table>

## Relations with Agreement in `Gender`

The 10 most frequent relations where parent and child node agree in `Gender`:
<tt>PRON --[<tt><a href="en_lines-dep-nmod-unmarked.html">nmod:unmarked</a></tt>]--> PRON</tt> (4; 80%),
<tt>PRON --[<tt><a href="en_lines-dep-parataxis.html">parataxis</a></tt>]--> PRON</tt> (1; 100%).

