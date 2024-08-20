---
layout: base
title:  'Turkish UD'
udver: '2'
---

# UD for Turkish <span class="flagspan"><img class="flag" src="../../flags/svg/TR.svg" /></span>

This is a **work-in-progress** overview of the UD annotation for Turkish.

Unfortunately, different treebanks follow (slightly) different annotation guidelines, and, as of v2.4, multiple uncoordinated attempts of correction efforts were known. Currently, as of v2.14, there's a group working on the unification of the Turkish treebanks, named [the UD Turkic Group](https://github.com/ud-turkic/).

## Tokenization and Word Segmentation

* In general, words are delimited by whitespaces or punctuation.
    Whitespaces or punctuation may appear in some abbreviations
    or numeric expressions.
* Clitics are treated as separate words. This includes
    the clitics that follow word-internal processes (e.g., vowel
    harmony) such as question clitic  _mI_ and  adverbial _DA_.
* Due to the interaction of syntax and rich morphology,
    the following list  affixes introduce new "syntactic words".
        - Copular suffix attached to nouns or adverbs (if not null),
            including the conditional _-(y)sA_ and converbial _-(y)ken_
        - _-ki_
        - _-lI_
        - _-sIz_
        - _-lIk_

For more details, see [tokenization](tokenization.html).

## Morphology

Turkish has a rich inflectional and derivational morphology.
Some of the morphological phenomena are not satisfactorily annotated as of UD v2.
This includes some missing feature-value pairs,
e.g., 'reflexive voice' which is marked using language specific value ``Voice=Rfl``.
Another open issue is multiple values for certain UD morphological features.
For example, a _gelemeselerdi_ "if they were not able to come_ expresses
two different modalities, requiring assigning both ``Pot`` and ``Cnd``
to the [Mood]() feature.
Currently these multiple features are expressed
by concatenating the values together in alphabetic order,
resulting in feature-value pairs like ``Mood=CndPot``.
Besides ``Mood``, ``Voice`` may also have multiple values.

### Tags

This is an overview only. For more detailed discussion and examples,
see the list of [Turkish POS tags](pos/index.html)
and [Turkish features](feat/index.html).

* The use of UD POS tags vary among different treebanks. ``PART`` is
    not used in any of the current treebanks.
* Negation particle _değil_ is marked either as ``AUX`` in some treebanks, and ``VERB`` in others.
* The question particle _mI_ is tagged as ``AUX``.
* The copular suffix -_(y)_-, which is treated as a syntactic word, and its clitic counterpart _i-_ is marked as AUX.
* Treatment of auxiliary/copula _ol_ differs among different treebanks.
* There are four main (de)verbal forms, distinguished by the value of the [VerbForm]() feature:
  * Finite verb `Fin`.
  * Participle `Part`.
  * Converb `Conv`.
  * Verbal noun `Vnoun` (it includes the citation forms with _-mak_, sometimes called the infinitive).

## Syntax

This is an overview only. For more detailed discussion and examples,
see the list of [relations](dep/index.html),


### Relations Overview

* The following relation subtypes are used in Turkish:
   * [advmod:emph]()
   * [aux:q]()
   * [compound:lvc]()
   * [compound:redup]()
   * [nmod:poss]()
   * [nmod:tmod]()
   * [obl:tmod]()
   * [nsubj:cop]()
   * [csubj:cop]()
   * [nmod:part]()
   * [nmod:comp]()
   * [obl:agent]()

## Treebanks

As of UD 2.13, there are [nine](../treebanks/tr-comparison.html) Turkish UD treebanks, with more treebanks in progress.

  * [Turkish-ATIS](../treebanks/tr_atis/index.html)
  * [Turkish-BOUN](../treebanks/tr_boun/index.html)
  * [Turkish-FrameNet](../treebanks/tr_framenet/index.html)
  * [Turkish-GB](../treebanks/tr_gb/index.html)
  * [Turkish-IMST](../treebanks/tr_imst/index.html)
  * [Turkish-Kenet](../treebanks/tr_kenet/index.html)
  * [Turkish-PUD](../treebanks/tr_pud/index.html)
  * [Turkish-Penn](../treebanks/tr_penn/index.html)
  * [Turkish-Tourism](../treebanks/tr_tourism/index.html)
