---
layout: base
title:  'Statistics of VerbForm in UD_Dutch-Alpino'
udver: '2'
---

## Treebank Statistics: UD_Dutch-Alpino: Features: `VerbForm`

This feature is universal.
It occurs with 3 different values: `Fin`, `Inf`, `Part`.

31788 tokens (15%) have a non-empty value of `VerbForm`.
5218 types (19%) occur at least once with a non-empty value of `VerbForm`.
2710 lemmas (12%) occur at least once with a non-empty value of `VerbForm`.
The feature is used with 2 part-of-speech tags: <tt><a href="nl_alpino-pos-VERB.html">VERB</a></tt> (21972; 11% instances), <tt><a href="nl_alpino-pos-AUX.html">AUX</a></tt> (9816; 5% instances).

### `VERB`

21972 <tt><a href="nl_alpino-pos-VERB.html">VERB</a></tt> tokens (100% of all `VERB` tokens) have a non-empty value of `VerbForm`.

The most frequent other feature values with which `VERB` and `VerbForm` co-occurred: <tt><a href="nl_alpino-feat-Number.html">Number</a></tt><tt>=EMPTY</tt> (11304; 51%), <tt><a href="nl_alpino-feat-Tense.html">Tense</a></tt><tt>=EMPTY</tt> (11304; 51%).

`VERB` tokens may have the following values of `VerbForm`:

* `Fin` (10668; 49% of non-empty `VerbForm`): <em>heeft, komt, heet, wil, is, gaat, zei, kwam, noemt, hebben</em>
* `Inf` (4728; 22% of non-empty `VerbForm`): <em>komen, gaan, maken, zien, doen, nemen, laten, zeggen, worden, geven</em>
* `Part` (6576; 30% of non-empty `VerbForm`): <em>gemaakt, gehouden, genoemd, genomen, gedaan, gezien, afgelopen, gegeven, gekomen, geworden</em>

<table>
  <tr><th>Paradigm <i>hebben</i></th><th><tt>Fin</tt></th><th><tt>Inf</tt></th><th><tt>Part</tt></th></tr>
  <tr><td><tt>_</tt></td><td></td><td><em>hebben</em></td><td><em>gehad</em></td></tr>
  <tr><td><tt><tt><a href="nl_alpino-feat-Number.html">Number</a></tt><tt>=Sing</tt>|<tt><a href="nl_alpino-feat-Tense.html">Tense</a></tt><tt>=Past</tt></tt></td><td><em>had</em></td><td></td><td></td></tr>
  <tr><td><tt><tt><a href="nl_alpino-feat-Number.html">Number</a></tt><tt>=Sing</tt>|<tt><a href="nl_alpino-feat-Tense.html">Tense</a></tt><tt>=Pres</tt></tt></td><td><em>heeft, heb, hebt, hebbe</em></td><td></td><td></td></tr>
  <tr><td><tt><tt><a href="nl_alpino-feat-Number.html">Number</a></tt><tt>=Plur</tt>|<tt><a href="nl_alpino-feat-Tense.html">Tense</a></tt><tt>=Past</tt></tt></td><td><em>hadden</em></td><td></td><td></td></tr>
  <tr><td><tt><tt><a href="nl_alpino-feat-Number.html">Number</a></tt><tt>=Plur</tt>|<tt><a href="nl_alpino-feat-Tense.html">Tense</a></tt><tt>=Pres</tt></tt></td><td><em>hebben</em></td><td></td><td></td></tr>
</table>

### `AUX`

9816 <tt><a href="nl_alpino-pos-AUX.html">AUX</a></tt> tokens (100% of all `AUX` tokens) have a non-empty value of `VerbForm`.

The most frequent other feature values with which `AUX` and `VerbForm` co-occurred: <tt><a href="nl_alpino-feat-Number.html">Number</a></tt><tt>=Sing</tt> (6827; 70%), <tt><a href="nl_alpino-feat-Tense.html">Tense</a></tt><tt>=Pres</tt> (6250; 64%).

`AUX` tokens may have the following values of `VerbForm`:

* `Fin` (8669; 88% of non-empty `VerbForm`): <em>is, was, heeft, zijn, werd, wordt, zal, zou, kan, hebben</em>
* `Inf` (1078; 11% of non-empty `VerbForm`): <em>worden, zijn, kunnen, moeten, hebben, zullen, mogen, krijgen, wezen</em>
* `Part` (69; 1% of non-empty `VerbForm`): <em>geweest, gekregen, zijnde, gehad, geworden</em>

<table>
  <tr><th>Paradigm <i>zijn</i></th><th><tt>Fin</tt></th><th><tt>Inf</tt></th><th><tt>Part</tt></th></tr>
  <tr><td><tt>_</tt></td><td></td><td><em>zijn, wezen</em></td><td><em>geweest, zijnde</em></td></tr>
  <tr><td><tt><tt><a href="nl_alpino-feat-Number.html">Number</a></tt><tt>=Sing</tt>|<tt><a href="nl_alpino-feat-Tense.html">Tense</a></tt><tt>=Past</tt></tt></td><td><em>was</em></td><td></td><td></td></tr>
  <tr><td><tt><tt><a href="nl_alpino-feat-Number.html">Number</a></tt><tt>=Sing</tt>|<tt><a href="nl_alpino-feat-Tense.html">Tense</a></tt><tt>=Pres</tt></tt></td><td><em>is, ben, bent, ware, zij, Wees, Weest, zijn</em></td><td></td><td></td></tr>
  <tr><td><tt><tt><a href="nl_alpino-feat-Number.html">Number</a></tt><tt>=Plur</tt>|<tt><a href="nl_alpino-feat-Tense.html">Tense</a></tt><tt>=Past</tt></tt></td><td><em>waren</em></td><td></td><td></td></tr>
  <tr><td><tt><tt><a href="nl_alpino-feat-Number.html">Number</a></tt><tt>=Plur</tt>|<tt><a href="nl_alpino-feat-Tense.html">Tense</a></tt><tt>=Pres</tt></tt></td><td><em>zijn</em></td><td></td><td></td></tr>
</table>

## Relations with Agreement in `VerbForm`

The 10 most frequent relations where parent and child node agree in `VerbForm`:
<tt>VERB --[<tt><a href="nl_alpino-dep-conj.html">conj</a></tt>]--> VERB</tt> (860; 73%),
<tt>VERB --[<tt><a href="nl_alpino-dep-parataxis.html">parataxis</a></tt>]--> VERB</tt> (270; 58%),
<tt>AUX --[<tt><a href="nl_alpino-dep-conj.html">conj</a></tt>]--> AUX</tt> (8; 100%),
<tt>VERB --[<tt><a href="nl_alpino-dep-acl.html">acl</a></tt>]--> VERB</tt> (8; 62%),
<tt>VERB --[<tt><a href="nl_alpino-dep-csubj-outer.html">csubj:outer</a></tt>]--> VERB</tt> (7; 58%),
<tt>VERB --[<tt><a href="nl_alpino-dep-orphan.html">orphan</a></tt>]--> VERB</tt> (4; 100%),
<tt>AUX --[<tt><a href="nl_alpino-dep-conj.html">conj</a></tt>]--> VERB</tt> (2; 100%),
<tt>VERB --[<tt><a href="nl_alpino-dep-cc.html">cc</a></tt>]--> VERB</tt> (1; 100%).

