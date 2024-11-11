---
layout: base
title:  'UD_Japanese-GSDLUW'
udver: '2'
---

<!-- This page is automatically generated from the README file and from
     the data files in the latest release.

     Please do not edit this page directly. -->

# UD Japanese GSDLUW

Language: [Japanese](/ja/index.html) (code: `ja`)<br/>
Family: Japanese

This treebank has been part of Universal Dependencies since the UD v2.9 release.

The following people have contributed to making this treebank part of UD: Mai Omura, Yusuke Miyao, Hiroshi Kanayama, Hiroshi Matsuda, Aya Wakasa, Kayo Yamashita, Masayuki Asahara, Takaaki Tanaka, Yugo Murawaki, Yuji Matsumoto, Shinsuke Mori, Sumire Uematsu, Ryan McDonald, Joakim Nivre, Daniel Zeman.

Repository: [UD_Japanese-GSDLUW](https://github.com/UniversalDependencies/UD_Japanese-GSDLUW)<br />
Search this treebank on-line: [PML-TQ](https://lindat.mff.cuni.cz/services/pmltq/#!/treebank/udja_gsdluw215)<br />
Download all treebanks: [UD 2.15](/#download)

License: CC BY-SA 4.0

Genre: news, blog

Questions, comments?
General annotation questions (either Japanese-specific or cross-linguistic) can be raised in the [main UD issue tracker](https://github.com/UniversalDependencies/docs/issues).
You can report bugs in this treebank in the [treebank-specific issue tracker on Github](https://github.com/UniversalDependencies/UD_Japanese-GSDLUW/issues).
If you want to collaborate, please contact [masayu-a&nbsp;(æt)&nbsp;ninjal&nbsp;•&nbsp;ac&nbsp;•&nbsp;jp].
Development of the treebank happens directly in the UD repository, so you may submit bug fixes as pull requests against the dev branch.

| Annotation | Source |
|------------|--------|
| Lemmas | annotated manually in non-UD style, automatically converted to UD |
| UPOS | annotated manually in non-UD style, automatically converted to UD |
| XPOS | annotated manually |
| Features | not available |
| Relations | annotated manually in non-UD style, automatically converted to UD |

## Description

This Universal Dependencies (UD) Japanese treebank is based on the definition of UD Japanese convention described in the UD documentation. The original sentences are from Google UDT 2.0.



The Japanese UD treebank contains the sentences from Google Universal Dependency Treebanks v2.0 (legacy): https://github.com/ryanmcd/uni-dep-tb. First, Google UDT v2.0 was converted to UD-style with bunsetsu-based word units (say "master" corpus).

The word units in "master" is significantly different from the definition of the documents based on Short Word Unit (SWU) [1], then the sentences are automatically re-processed by Hiroshi Kanayama in Feb 2017. It is the Japanese_UD v2.0 and used in the CoNLL 2017 shared task.
In November 2017, UD_Japanese v2.0 is merged with the "master" data so that the manual annotations for dependencies can be reflected to the corpus. It reduced the errors in the dependency structures and relation labels.

Still there are slight differences in the word unit between UD_Japanese v2.1 and UD_Japanese-KTC 1.3.

In May 2020, we introduce UD_Japanese BCCWJ[3] like coversion method for UD_Japanese GSD v2.6.

In May 2021, we introduce the other word segmentation version of UD_Japanese-GSD.

## Acknowledgments

The original treebank was provided by:

- Adam LaMontagne
- Milan Souček
- Timo Järvinen
- Alessandra Radici

via

- Dan Zeman.

The corpus was converted by:

- Mai Omura
- Aya Wakasa
- Masayuki Asahara

through annotation, discussion and validation with

- Kayo Yamashita


# Statistics of UD Japanese GSDLUW

## POS Tags

[ADJ](ja_gsdluw-pos-ADJ.html) – [ADP](ja_gsdluw-pos-ADP.html) – [ADV](ja_gsdluw-pos-ADV.html) – [AUX](ja_gsdluw-pos-AUX.html) – [CCONJ](ja_gsdluw-pos-CCONJ.html) – [DET](ja_gsdluw-pos-DET.html) – [INTJ](ja_gsdluw-pos-INTJ.html) – [NOUN](ja_gsdluw-pos-NOUN.html) – [NUM](ja_gsdluw-pos-NUM.html) – [PART](ja_gsdluw-pos-PART.html) – [PRON](ja_gsdluw-pos-PRON.html) – [PROPN](ja_gsdluw-pos-PROPN.html) – [PUNCT](ja_gsdluw-pos-PUNCT.html) – [SCONJ](ja_gsdluw-pos-SCONJ.html) – [SYM](ja_gsdluw-pos-SYM.html) – [VERB](ja_gsdluw-pos-VERB.html) – [X](ja_gsdluw-pos-X.html)

## Features

[Polarity](ja_gsdluw-feat-Polarity.html)

## Relations

[acl](ja_gsdluw-dep-acl.html) – [advcl](ja_gsdluw-dep-advcl.html) – [advmod](ja_gsdluw-dep-advmod.html) – [amod](ja_gsdluw-dep-amod.html) – [aux](ja_gsdluw-dep-aux.html) – [case](ja_gsdluw-dep-case.html) – [cc](ja_gsdluw-dep-cc.html) – [ccomp](ja_gsdluw-dep-ccomp.html) – [compound](ja_gsdluw-dep-compound.html) – [cop](ja_gsdluw-dep-cop.html) – [csubj](ja_gsdluw-dep-csubj.html) – [csubj:outer](ja_gsdluw-dep-csubj-outer.html) – [dep](ja_gsdluw-dep-dep.html) – [det](ja_gsdluw-dep-det.html) – [discourse](ja_gsdluw-dep-discourse.html) – [fixed](ja_gsdluw-dep-fixed.html) – [mark](ja_gsdluw-dep-mark.html) – [nmod](ja_gsdluw-dep-nmod.html) – [nsubj](ja_gsdluw-dep-nsubj.html) – [nsubj:outer](ja_gsdluw-dep-nsubj-outer.html) – [nummod](ja_gsdluw-dep-nummod.html) – [obj](ja_gsdluw-dep-obj.html) – [obl](ja_gsdluw-dep-obl.html) – [punct](ja_gsdluw-dep-punct.html) – [root](ja_gsdluw-dep-root.html)

<h2>Tokenization and Word Segmentation</h2>


<ul>
<li>This corpus contains 8100 sentences and 150243 tokens.</li>
</ul>

<ul>
<li>This corpus contains 142134 tokens (95%) that are not followed by a space.</li>
</ul>

<ul>
<li>This corpus contains 153 types of words with spaces. Examples: You Tube, DEATH NOTE, EEP ROM, Mozilla Firefox, 12.1型WXGA TFT液晶, AOL Key words, ASIA GIRLS EXPLOSION, Acoustic UK, Ad Planner, André Franquin, Arc Sight株, Ars Technica, BAD TIMES, Bill of Lading, Biohazard archives, BlackBerry Bold9700, Blue tooth, Blues Attack, Brian Brazil, British Rail termini, COCK AND BULL TUNES, CRYSTAL BALLカードミラー, CS 5, City of Sarnia, Club Class, DARK SIDE REPORT, DFJ Esprit, DRAGON GATE RECORDS代表兼プロデューサー, Deep Junior, Deep Sjeng, Detailed Baseline Report, Direct X, Double Click Ad Planner, EMI CLASSICS, Enterprise Java Beans, F-ZERO AX, FM TOWNS, FRIDAY NIGHT, Feeling Heart, GNU Cライブラリ, GTC Speed, Galaxy Tab, HOUND DOG, HTTP Proxy/SSH/Socks, Happy Tablet, HellChose Me, Herbert J.Zeiger, Hugo Pratt, IBM PC/AT以来, IT’S FRIDAY</li>
</ul>

<ul>
<li>This corpus contains 999 types of words that contain both letters and punctuation. Examples: レアル・マドリード, J-WAVE, SETI@home, T-72, Wi-Fi, 『真型』以前, エドガー・ダイクストラ, スター・ウォーズ, テーブル“T”, ルイ・ヴィトン, 一、二塁, 阪神・淡路大震災, 0.2%減, 0.5%減, 0.6%安, 1%未満, 100%有機, 11ウォール・ストリート, 15%急落, 157km/h, 1ch・2ch・12ch, 2.6%減, 2両・3両単位, 3%増, 30%アップ, 323A-1, 35%程度, 3人目・4度目, 3回転ルッツ-3回転ループ, 4.4%減, 5%以下, 50%以上, 50%以下, 6344P-L, 6・7%増, 6・7・DS, 6番・出口, 7.0%増, 70%以上, 80’sカルチャー, 90%以上, A&Mレコード, A&S, A.T.フィールド, AC/DC, ACミネロス・デ・グアヤナ所属, AMX-10RC, AQTI-2型クリッパー発売, AT-X, AW.55アポロ</li>
</ul>

<ul>
</ul>

<h2>Morphology</h2>

<h3>Tags</h3>

<ul>
<li>This corpus uses 17 UPOS tags out of 17 possible: <a>ADJ</a>, <a>ADP</a>, <a>ADV</a>, <a>AUX</a>, <a>CCONJ</a>, <a>DET</a>, <a>INTJ</a>, <a>NOUN</a>, <a>NUM</a>, <a>PART</a>, <a>PRON</a>, <a>PROPN</a>, <a>PUNCT</a>, <a>SCONJ</a>, <a>SYM</a>, <a>VERB</a>, <a>X</a></li>
</ul>

<ul>
<li>This corpus contains 36 word types tagged as particles (PART): か, かしらん, くらい, ぐらい, さ, さえ, しか, すら, ぞ, ぞお, たり, だけ, だけでなく, だり, って, どころ, な, なぁ, なあ, など, なんて, なー, ね, ねえ, の, のみ, ばかり, ほど, まで, や, よ, よぉ, よー, わ, 程, 風</li>
</ul>

<ul>
<li>This corpus contains 44 lemmas tagged as pronouns (PRON): あちこち, おめえ等, こっち, こんな, そらあ, そんな, どんな, わしゃ, 何, 何れ, 何処, 何方, 何時, 何等, 余, 俺, 僕, 僕等, 其れ, 其れ等, 其処, 其方, 君, 己, 彼, 彼れ, 彼女, 彼女達, 彼方, 彼等, 御前, 御宅, 我, 我々, 本の, 此れ, 此れ等, 此処, 此方, 私, 私達, 誰, 貴方, 貴様</li>
</ul>

<ul>
<li>This corpus contains 8 lemmas tagged as determiners (DET): あらゆる, とある, 何の, 其の, 彼の, 我が, 或る, 此の</li>
</ul>

<ul>
</ul>

<ul>
<li>This corpus contains 79 lemmas tagged as auxiliaries (AUX): かもしれない, かもしれません, ことがある, ことができない, ことができる, こととなる, ことにする, ことになる, ことはない, こともある, こともない, ごとし, させる, ざるを得ない, しかない, じゃ, ず, せる, そう, た, たい, たがる, たらいい, たり, だ, ちゃう, つう, つつある, てある, ていく, ていただく, ている, ておく, ておる, てく, てくださる, てくる, てくれる, てしまう, てはいけない, てはならない, てほしい, てみる, てもいい, てもらう, てやる, てる, である, です, でない, ではありません, ではない, でもある, とく, ない, ないではいられない, なくてはならない, なければならない, なり, に過ぎない, に違いない, のだ, のである, のです, のではない, ばいい, べし, まい, まじ, ます, までもない, みたい, む, や, らしい, られる, れる, わけにはいかない, 様</li>
</ul>

<ul>
<li>Out of the above, 1 lemmas occurred sometimes as AUX and sometimes as VERB: ている</li>
</ul>

<ul>
<li>This corpus does not use the VerbForm feature.</li>
</ul>

<h3>Nominal Features</h3>








<h3>Degree and Polarity</h3>



<ul>
  <li><a>Polarity</a></li>
</ul>

<ul>
  <li>Neg
    <ul>
      <li>AUX: ない, ず, ん, なかっ, なく, なけれ, なければならない, ぬ, ざるをえない, ざるを得ない</li>
      <li>NOUN: なし</li>
    </ul>
  </li>
</ul>


<h3>Verbal Features</h3>







<h3>Pronouns, Determiners, Quantifiers</h3>










<h3>Other Features</h3>


<h2>Syntax</h2>

<h3>Auxiliary Verbs and Copula</h3>

<ul>
<li>This corpus uses 2 lemmas as copulas (<a>cop</a>). Examples: だ, です.</li>
</ul>

<ul>
<li>This corpus uses 79 lemmas as auxiliaries (<a>aux</a>). Examples: た, ている, だ, れる, ます, である, ない, です, られる, のだ, ず, 様, ておる, せる, てくる, たい, ではない, てしまう, のです, てくれる, てる, ていく, ことができる, てもらう, ことになる, そう, てみる, ていただく, べし, てくださる, ことがある, こともある, らしい, でもある, のである, みたい, こととなる, のではない, でない, かもしれない, ちゃう, ではありません, ておく, てある, てく, かもしれません, ことはない, なければならない, てほしい, てもいい.</li>
</ul>

<h3>Core Arguments, Oblique Arguments and Adjuncts</h3>

Here we consider only relations between verbs (parent) and nouns or pronouns (child).
<ul>
  <li><a>nsubj</a>
    <ul>
      <li>VERB--NOUN-ADP(が) (2474)</li>
      <li>VERB--NOUN-ADP(は) (1532)</li>
      <li>VERB--NOUN-ADP(も) (527)</li>
      <li>VERB--PRON-ADP(が) (51)</li>
      <li>VERB--PRON-ADP(は) (105)</li>
      <li>VERB--PRON-ADP(も) (50)</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>obj</a>
    <ul>
      <li>VERB--NOUN-ADP(か)-ADP(を) (2)</li>
      <li>VERB--NOUN-ADP(だけ)-ADP(を) (2)</li>
      <li>VERB--NOUN-ADP(と)-ADP(か)-ADP(を) (1)</li>
      <li>VERB--NOUN-ADP(と)-ADP(を) (3)</li>
      <li>VERB--NOUN-ADP(など)-ADP(を) (52)</li>
      <li>VERB--NOUN-ADP(など)-ADP(を通じて) (2)</li>
      <li>VERB--NOUN-ADP(により)-ADP(を) (2)</li>
      <li>VERB--NOUN-ADP(の)-ADP(の)-ADP(を) (1)</li>
      <li>VERB--NOUN-ADP(のみ)-ADP(を) (3)</li>
      <li>VERB--NOUN-ADP(まで)-ADP(を) (2)</li>
      <li>VERB--NOUN-ADP(を) (4458)</li>
      <li>VERB--NOUN-ADP(を)-ADP(で)-ADP(も) (1)</li>
      <li>VERB--NOUN-ADP(を)-ADP(に) (1)</li>
      <li>VERB--NOUN-ADP(を)-ADP(も) (2)</li>
      <li>VERB--NOUN-ADP(をはじめ) (1)</li>
      <li>VERB--NOUN-ADP(をもって) (7)</li>
      <li>VERB--NOUN-ADP(を通じて) (5)</li>
      <li>VERB--PRON-ADP(か)-ADP(を) (5)</li>
      <li>VERB--PRON-ADP(まで)-ADP(を) (1)</li>
      <li>VERB--PRON-ADP(を) (83)</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>iobj</a>
    <ul>
    </ul>
  </li>
</ul>




<h3>Relations Overview</h3>

<ul>
<li>This corpus uses 2 relation subtypes: <a>csubj:outer</a>, <a>nsubj:outer</a></li>
<li>The following 14 relation types are not used in this corpus at all: <a>iobj</a>, <a>xcomp</a>, <a>vocative</a>, <a>expl</a>, <a>dislocated</a>, <a>appos</a>, <a>clf</a>, <a>conj</a>, <a>flat</a>, <a>list</a>, <a>parataxis</a>, <a>orphan</a>, <a>goeswith</a>, <a>reparandum</a></li>
</ul>
