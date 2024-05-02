---
layout: base
title:  'UD_Dutch-Alpino'
udver: '2'
---

<!-- This page is automatically generated from the README file and from
     the data files in the latest release.

     Please do not edit this page directly. -->

# UD Dutch Alpino

Language: [Dutch](/nl/index.html) (code: `nl`)<br/>
Family: Indo-European, Germanic

This treebank has been part of Universal Dependencies since the UD v1.2 release.

The following people have contributed to making this treebank part of UD: Daniel Zeman, Zdeněk Žabokrtský, Gosse Bouma, Gertjan van Noord.

Repository: [UD_Dutch-Alpino](https://github.com/UniversalDependencies/UD_Dutch-Alpino)<br />
Search this treebank on-line: [PML-TQ](https://lindat.mff.cuni.cz/services/pmltq/#!/treebank/udnl_alpino213)<br />
Download all treebanks: [UD 2.13](/#download)

License: CC BY-SA 4.0

Genre: news

Questions, comments?
General annotation questions (either Dutch-specific or cross-linguistic) can be raised in the [main UD issue tracker](https://github.com/UniversalDependencies/docs/issues).
You can report bugs in this treebank in the [treebank-specific issue tracker on Github](https://github.com/UniversalDependencies/UD_Dutch-Alpino/issues).
If you want to collaborate, please contact [g&nbsp;•&nbsp;bouma&nbsp;(æt)&nbsp;rug&nbsp;•&nbsp;nl].
Development of the treebank happens outside the UD repository.
If there are bugs, either the original data source or the conversion procedure must be fixed.
Do not submit pull requests against the UD repository.

| Annotation | Source |
|------------|--------|
| Lemmas | annotated manually in non-UD style, automatically converted to UD |
| UPOS | annotated manually in non-UD style, automatically converted to UD |
| XPOS | annotated manually |
| Features | annotated manually in non-UD style, automatically converted to UD |
| Relations | annotated manually in non-UD style, automatically converted to UD |

## Description

This corpus consists of samples from various treebanks annotated at the University of Groningen using the Alpino annotation tools and guidelines.



The data consists of samples from various treebanks annotated at the University of Groningen using the Alpino annotation tools and guidelines:

* train consists of material from the original Alpino CD-ROM (file id 'cdb' 7000+ sentences from the Eindhoven corpus), questions using in a QA project (file ids with qa and wpspel), material from suites used for grammar maintenance (id: g_suite, h_suite, leuven_yellow_pages), example sentence from the Dutch reference grammar ANS (eans), and the WR-P-P-H section of the Lassy Small corpus
* dev consists of material from the WR-P-P-H section of the Lassy Small corpus
* test consists of material from the WR-P-P-H and WR-P-P-L sections of the Lassy Small corpus

The data was thoroughly revised by Gosse Bouma and Gertjan van Noord for UD 2.1 in November 2017.
The new version was created using the same conversion script as was used for Dutch LassySmall.
As sources, we used the (manually corrected) Alpino treebank annotation for this material as it is
available in Groningen. Links to original files have been added. Note that tokenization may differ
from the previous UD version.

The (Go and XQuery) conversion script is available for download at https://github.com/rug-compling/alud. It can be used to convert additional material annotated according to Lassy/CGN guidelines or annotated automatically using the Alpino parser.

## Acknowledgments


# Statistics of UD Dutch Alpino

## POS Tags

[ADJ](nl_alpino-pos-ADJ.html) – [ADP](nl_alpino-pos-ADP.html) – [ADV](nl_alpino-pos-ADV.html) – [AUX](nl_alpino-pos-AUX.html) – [CCONJ](nl_alpino-pos-CCONJ.html) – [DET](nl_alpino-pos-DET.html) – [INTJ](nl_alpino-pos-INTJ.html) – [NOUN](nl_alpino-pos-NOUN.html) – [NUM](nl_alpino-pos-NUM.html) – [PRON](nl_alpino-pos-PRON.html) – [PROPN](nl_alpino-pos-PROPN.html) – [PUNCT](nl_alpino-pos-PUNCT.html) – [SCONJ](nl_alpino-pos-SCONJ.html) – [SYM](nl_alpino-pos-SYM.html) – [VERB](nl_alpino-pos-VERB.html) – [X](nl_alpino-pos-X.html)

## Features

[Abbr](nl_alpino-feat-Abbr.html) – [Case](nl_alpino-feat-Case.html) – [Definite](nl_alpino-feat-Definite.html) – [Degree](nl_alpino-feat-Degree.html) – [Gender](nl_alpino-feat-Gender.html) – [Number](nl_alpino-feat-Number.html) – [Person](nl_alpino-feat-Person.html) – [Poss](nl_alpino-feat-Poss.html) – [PronType](nl_alpino-feat-PronType.html) – [Reflex](nl_alpino-feat-Reflex.html) – [Tense](nl_alpino-feat-Tense.html) – [VerbForm](nl_alpino-feat-VerbForm.html)

## Relations

[acl](nl_alpino-dep-acl.html) – [acl:relcl](nl_alpino-dep-acl-relcl.html) – [advcl](nl_alpino-dep-advcl.html) – [advmod](nl_alpino-dep-advmod.html) – [amod](nl_alpino-dep-amod.html) – [appos](nl_alpino-dep-appos.html) – [aux](nl_alpino-dep-aux.html) – [aux:pass](nl_alpino-dep-aux-pass.html) – [case](nl_alpino-dep-case.html) – [cc](nl_alpino-dep-cc.html) – [cc:preconj](nl_alpino-dep-cc-preconj.html) – [ccomp](nl_alpino-dep-ccomp.html) – [compound:prt](nl_alpino-dep-compound-prt.html) – [conj](nl_alpino-dep-conj.html) – [cop](nl_alpino-dep-cop.html) – [csubj](nl_alpino-dep-csubj.html) – [csubj:outer](nl_alpino-dep-csubj-outer.html) – [det](nl_alpino-dep-det.html) – [expl](nl_alpino-dep-expl.html) – [expl:pv](nl_alpino-dep-expl-pv.html) – [fixed](nl_alpino-dep-fixed.html) – [flat](nl_alpino-dep-flat.html) – [iobj](nl_alpino-dep-iobj.html) – [mark](nl_alpino-dep-mark.html) – [nmod](nl_alpino-dep-nmod.html) – [nmod:poss](nl_alpino-dep-nmod-poss.html) – [nsubj](nl_alpino-dep-nsubj.html) – [nsubj:outer](nl_alpino-dep-nsubj-outer.html) – [nsubj:pass](nl_alpino-dep-nsubj-pass.html) – [nummod](nl_alpino-dep-nummod.html) – [obj](nl_alpino-dep-obj.html) – [obl](nl_alpino-dep-obl.html) – [obl:agent](nl_alpino-dep-obl-agent.html) – [orphan](nl_alpino-dep-orphan.html) – [parataxis](nl_alpino-dep-parataxis.html) – [punct](nl_alpino-dep-punct.html) – [root](nl_alpino-dep-root.html) – [xcomp](nl_alpino-dep-xcomp.html)

<h2>Tokenization and Word Segmentation</h2>


<ul>
<li>This corpus contains 13603 sentences, 208613 tokens and 208614 syntactic words.</li>
</ul>

<ul>
<li>This corpus contains 21716 tokens (10%) that are not followed by a space.</li>
</ul>

<ul>
<li>This corpus does not contain words with spaces.</li>
</ul>

<ul>
<li>This corpus contains 1464 types of words that contain both letters and punctuation. Examples: J., mr., dr., zo'n, 't, H., a., 's, C., W., M., drs., B., prof., G., p., pct., d., R., 'n, F., L., o.a., K., Zuid-Afrika, T., z'n, v., S., auto's, jl., n.v., E., ir., Sovjet-Unie, St., West-Duitsland, o.m., Noord-Korea, mln., D'66, a.s., binnen-, m'n, mevr., Mina's, Oost-Berlijn, directeur-generaal, ds., etc.</li>
</ul>

<ul>
<li>This corpus contains 1 multi-word tokens. On average, one multi-word token consists of 2.00 syntactic words.</li>
<li>There are 1 types of multi-word tokens. Examples: nogeens.</li>
</ul>

<h2>Morphology</h2>

<h3>Tags</h3>

<ul>
<li>This corpus uses 16 UPOS tags out of 17 possible: <a>ADJ</a>, <a>ADP</a>, <a>ADV</a>, <a>AUX</a>, <a>CCONJ</a>, <a>DET</a>, <a>INTJ</a>, <a>NOUN</a>, <a>NUM</a>, <a>PRON</a>, <a>PROPN</a>, <a>PUNCT</a>, <a>SCONJ</a>, <a>SYM</a>, <a>VERB</a>, <a>X</a></li>
<li>This corpus does not use the following tags: PART</li>
</ul>

<ul>
</ul>

<ul>
<li>This corpus contains 69 lemmas tagged as pronouns (PRON): al, allebei, alles, beide, dat, datgeen, degeen, deze, die, diegene, dit, een, elk, elkaar, enig, enkel, er, ge, geen, gij, haar, haarzelf, hem, hemzelf, hen, het, hetgeen, hij, hijzelf, hun, ieder, iedereen, iemand, iets, ik, je, jezelf, jij, jou, jullie, me, meerdere, men, mezelf, mij, mijn, niemand, niets, niks, ons, onszelf, sommig, u, veel, wat, we, weinig, welk, wie, wij, ze, zich, zichzelf, zij, zijn, zijzelf, zo'n, zoiets, zulk</li>
</ul>

<ul>
<li>This corpus contains 81 lemmas tagged as determiners (DET): 1/2, 1/3, 1/4, 1/8, 1000, 2.392, 2/3, 20.000, 22,1, 2500, 33, 37,7, 47, 5.001, 5000, 9.000, al, allerlei, anderhalf, andermans, beide, bijna, dat, datzelfde, de, deze, dezelfde, die, diezelfde, dit, dll, een, eenzelfde, elk, elkaar, enig, enkel, ettelijk, flo, geen, genoeg, helemaal, het, hetzelfde, hoe, ieder, maar, meerdere, menig, min, net, niemand, niet, nog, nogal, onvoldoende, reeds, slechts, sommig, steeds, te, teveel, the, veel, voldoende, vrijwel, wat, weinig, wel, welhaast, welk, weten, wie, x, zeer, zes-, zestig-, zijn/haar, zo, zo'n, zulk</li>
</ul>

<ul>
<li>Out of the above, 24 lemmas occurred sometimes as PRON and sometimes as DET: al, beide, dat, deze, die, dit, een, elk, elkaar, enig, enkel, geen, het, ieder, meerdere, niemand, sommig, veel, wat, weinig, welk, wie, zo'n, zulk</li>
</ul>

<ul>
<li>This corpus contains 8 lemmas tagged as auxiliaries (AUX): hebben, krijgen, kunnen, moeten, mogen, worden, zijn, zullen</li>
</ul>

<ul>
<li>Out of the above, 8 lemmas occurred sometimes as AUX and sometimes as VERB: hebben, krijgen, kunnen, moeten, mogen, worden, zijn, zullen</li>
</ul>

<ul>
<li>There are 3 <a href="../feat/VerbForm.html">(de)verbal forms:</a></li>
</ul>

<ul>
  <li>Fin
  <ul>
    <li>AUX: is, was, heeft, zijn, werd, wordt, zal, zou, kan, hebben</li>
    <li>VERB: heeft, komt, heet, wil, is, gaat, zei, kwam, noemt, hebben</li>
  </ul>
  </li>
</ul>

<ul>
  <li>Inf
  <ul>
    <li>AUX: worden, zijn, kunnen, moeten, hebben, zullen, mogen, krijgen, wezen</li>
    <li>VERB: komen, gaan, maken, zien, doen, nemen, laten, zeggen, worden, geven</li>
  </ul>
  </li>
</ul>

<ul>
  <li>Part
  <ul>
    <li>AUX: geweest, gekregen, zijnde, gehad, geworden</li>
    <li>VERB: gemaakt, gehouden, genoemd, genomen, gedaan, gezien, afgelopen, gegeven, gekomen, geworden</li>
  </ul>
  </li>
</ul>

<h3>Nominal Features</h3>


<ul>
  <li><a>Gender</a></li>
</ul>

<ul>
  <li>Com
    <ul>
      <li>NOUN: heer, plaats, tijd, minister, man, stad, dag, week, politie, trein</li>
      <li>PROPN: zaterdag, januari, zondag, JGZ, Robbert, mei, juli, september, vrijdag, God</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Com,Neut
    <ul>
      <li>NOUN: soort, boord, opzet, subsidie, stempel, opium, affiche, aperitief, cacaopoeder, cementpoeder</li>
      <li>PROPN: Greenpeace, Beernink, DFC, Interpay, Laurus, Mendes-France, Noerejew, Poema, Springer, Ulysses</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Neut
    <ul>
      <li>NOUN: jaar, land, uur, aantal, deel, procent, huis, miljoen, werk, leven</li>
      <li>PROPN: Nederland, Amsterdam, Groningen, Rotterdam, Europa, Engeland, Aduard, Frankrijk, Utrecht, Ajax</li>
    </ul>
  </li>
</ul>


<ul>
  <li><a>Number</a></li>
</ul>

<ul>
  <li>Plur
    <ul>
      <li>AUX-Fin: zijn, hebben, worden, zullen, waren, werden, kunnen, zouden, moeten, hadden</li>
      <li>NOUN: mensen, kinderen, jaren, problemen, zaken, landen, boeken, dagen, vrouwen, weken</li>
      <li>PROPN: Nederlanders, Amsterdammers, Rotterdammers, Duitsers, Italianen, Russen, Amerikanen, Engelsen, Romeinen, VS</li>
      <li>VERB-Fin: hebben, zijn, gaan, willen, komen, kwamen, hadden, krijgen, waren, staan</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Sing
    <ul>
      <li>AUX-Fin: is, was, heeft, werd, wordt, zal, zou, kan, moet, had</li>
      <li>NOUN: jaar, land, heer, plaats, tijd, minister, uur, man, stad, aantal</li>
      <li>PROPN: Nederland, Amsterdam, zaterdag, Groningen, Rotterdam, Europa, Engeland, januari, zondag, Aduard</li>
      <li>VERB-Fin: heeft, komt, heet, wil, is, gaat, zei, kwam, noemt, ligt</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Case</a></li>
</ul>

<ul>
  <li>Acc
    <ul>
      <li>PRON: zich, hem, me, ons, mij, elkaar, haar, hen, je, zichzelf</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Dat
    <ul>
      <li>PRON: dien, dezen</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Gen
    <ul>
      <li>PRON: zijns, uwer, zijner</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Nom
    <ul>
      <li>PRON: hij, ik, we, men, je, zij, wij, u, jij, ie</li>
    </ul>
  </li>
</ul>


<ul>
  <li><a>Definite</a></li>
</ul>

<ul>
  <li>Def
    <ul>
      <li>DET: de, het, der, 's, 't, des, den, dé</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Ind
    <ul>
      <li>DET: een, 'n, en</li>
    </ul>
  </li>
</ul>

<h3>Degree and Polarity</h3>


<ul>
  <li><a>Degree</a></li>
</ul>

<ul>
  <li>Cmp
    <ul>
      <li>ADJ: verder, beter, later, eerder, jongeren, vroeger, langer, groter, grotere, hoger</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Pos
    <ul>
      <li>ADJ: nieuwe, grote, andere, goed, Nederlandse, heel, groot, Amerikaanse, eigen, goede</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Sup
    <ul>
      <li>ADJ: laatste, grootste, beste, belangrijkste, hoogste, best, jongste, voornaamste, allerminst, oudste</li>
    </ul>
  </li>
</ul>



<h3>Verbal Features</h3>




<ul>
  <li><a>Tense</a></li>
</ul>

<ul>
  <li>Past
    <ul>
      <li>AUX-Fin: was, werd, zou, had, waren, werden, kon, zouden, moest, hadden</li>
      <li>VERB-Fin: zei, kwam, had, werd, was, vond, kreeg, vroeg, maakte, won</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Pres
    <ul>
      <li>AUX-Fin: is, heeft, zijn, wordt, zal, kan, hebben, moet, heb, worden</li>
      <li>VERB-Fin: heeft, komt, heet, wil, is, gaat, noemt, hebben, ligt, zijn</li>
    </ul>
  </li>
</ul>



<h3>Pronouns, Determiners, Quantifiers</h3>


<ul>
  <li><a>PronType</a></li>
</ul>

<ul>
  <li>Dem
    <ul>
      <li>PRON: dat, dit, er, die, deze, zo'n, degenen, datgene, degene, d'r</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Ind
    <ul>
      <li>PRON: meer, iets, niets, veel, alles, wat, enige, minder, iedereen, weinig</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Int
    <ul>
      <li>PRON: wat, wie, welke, welk</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Prs
    <ul>
      <li>PRON: hij, ik, het, zijn, zich, ze, we, je, men, hun</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Rcp
    <ul>
      <li>PRON: elkaar</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Rel
    <ul>
      <li>PRON: die, dat, hetgeen, hetgene</li>
    </ul>
  </li>
</ul>


<ul>
  <li><a>Poss</a></li>
</ul>

<ul>
  <li>Yes
    <ul>
      <li>PRON: zijn, hun, haar, mijn, onze, ons, je, uw, z'n, m'n</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Reflex</a></li>
</ul>

<ul>
  <li>Yes
    <ul>
      <li>PRON: zich, zichzelf</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Person</a></li>
</ul>

<ul>
  <li>1
    <ul>
      <li>PRON: ik, we, ons, wij, me, mijn, mij, onze, mezelf, m'n</li>
    </ul>
  </li>
</ul>

<ul>
  <li>2
    <ul>
      <li>PRON: je, u, jullie, jij, jou, uw, gij, jouw, jezelf, ge</li>
    </ul>
  </li>
</ul>

<ul>
  <li>3
    <ul>
      <li>PRON: hij, het, dat, zijn, wat, zich, ze, wie, men, hun</li>
    </ul>
  </li>
</ul>




<h3>Other Features</h3>


<ul>
  <li><a>Abbr</a>
    <ul>
      <li>Yes
        <ul>
          <li>X: pct., o.a., jl., o.m., pct, mln., a.s., etc., rk, v.j.</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<h2>Syntax</h2>

<h3>Auxiliary Verbs and Copula</h3>

<ul>
<li>This corpus uses 1 lemmas as copulas (<a>cop</a>). Examples: zijn.</li>
</ul>

<ul>
<li>This corpus uses 6 lemmas as auxiliaries (<a>aux</a>). Examples: hebben, zullen, kunnen, zijn, moeten, mogen.</li>
<li>This corpus uses 3 lemmas as passive auxiliaries (<a>aux:pass</a>). Examples: worden, zijn, krijgen.</li>
</ul>

<h3>Core Arguments, Oblique Arguments and Adjuncts</h3>

Here we consider only relations between verbs (parent) and nouns or pronouns (child).
<ul>
  <li><a>nsubj</a>
    <ul>
      <li>VERB-Fin--NOUN (3749)</li>
      <li>VERB-Fin--NOUN-ADP(op) (1)</li>
      <li>VERB-Fin--PRON (1784)</li>
      <li>VERB-Fin--PRON-Nom (2616)</li>
      <li>VERB-Inf--NOUN (595)</li>
      <li>VERB-Inf--PRON (315)</li>
      <li>VERB-Inf--PRON-Nom (556)</li>
      <li>VERB-Part--NOUN (806)</li>
      <li>VERB-Part--PRON (284)</li>
      <li>VERB-Part--PRON-Nom (514)</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>obj</a>
    <ul>
      <li>VERB-Fin--NOUN (2778)</li>
      <li>VERB-Fin--PRON (528)</li>
      <li>VERB-Fin--PRON-Acc (211)</li>
      <li>VERB-Inf--NOUN (1428)</li>
      <li>VERB-Inf--NOUN-ADP(voor) (1)</li>
      <li>VERB-Inf--PRON (265)</li>
      <li>VERB-Inf--PRON-Acc (103)</li>
      <li>VERB-Part--NOUN (719)</li>
      <li>VERB-Part--PRON (183)</li>
      <li>VERB-Part--PRON-Acc (48)</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>iobj</a>
    <ul>
      <li>VERB-Fin--NOUN (68)</li>
      <li>VERB-Fin--PRON (3)</li>
      <li>VERB-Fin--PRON-ADP(aan) (1)</li>
      <li>VERB-Fin--PRON-Acc (175)</li>
      <li>VERB-Inf--NOUN (44)</li>
      <li>VERB-Inf--PRON (5)</li>
      <li>VERB-Inf--PRON-ADP(aan) (1)</li>
      <li>VERB-Inf--PRON-Acc (46)</li>
      <li>VERB-Part--NOUN (46)</li>
      <li>VERB-Part--PRON (3)</li>
      <li>VERB-Part--PRON-ADP(aan) (2)</li>
      <li>VERB-Part--PRON-Acc (61)</li>
    </ul>
  </li>
</ul>

<h3>Reflexive Verbs</h3>

<ul>
  <li>This corpus contains 170 lemmas that occur at least once with an <a>expl:pv</a> child. Examples: bevinden zich, voor_doen zich, bewust zich, voelen zich, af_vragen zich, laten zich, maken zich, tonen zich, melden zich, ontwikkelen zich, plaatsen zich, af_spelen zich, bewegen zich, mee_brengen zich, richten zich, uit_spreken zich, aan_melden zich, begeven zich, beraden zich, concentreren zich, houden zich, op_stellen zich, vergissen zich, af_scheiden zich, af_vragen me, gedragen zich, herstellen zich, stellen zich, voelen me, voelen ons, voltrekken zich, wagen zich, wreken zich, af_vragen ons, begeven ons, beperken zich, buigen zich, mengen zich, permitteren zich, schamen je, schamen zich, terug_vechten zich, toe_leggen zich, verzetten zich, aan_sluiten zich, aan_trekken zich, af_wenden zich, beklagen me, bemoeien zich, bloot_geven zich</li>
</ul>


<h3>Verbs with Reflexive Core Objects</h3>

<ul>
  <li>This corpus contains 85 lemmas that occur at least once with a reflexive core object (<a>obj</a> or <a>iobj</a>). Examples: bezig_houden zich, stellen zich, houden zich, aan_sluiten zich, handhaven zich, laten zich, maken zich, uit_breiden zich, voor_bereiden zich, aan_schaffen zich, achten zich, interesseren zich, noemen zich, om_vormen zich, prikken zichzelf, redden zich, uit_strekken zich, versterken zich, verwonden zichzelf, wassen zich, wringen zich, zien zich, aan_bieden zich, aan_kondigen zich, aan_stellen zichzelf, aaneen_sluiten zich, afficheren zich, bekeren zich, belasten zich, beschermen zich, binden zich, blesseren zich, chanteren zich, dekken zich, doen zichzelf, dringen zich, dupliceren zich, emanciperen zich, forceren zich, fêteren zich, geven zich, herhalen zichzelf, in_kapselen zich, installeren zich, intimideren zich, kennen zich, los_maken zich, misbruiken zich, nemen zich, noemen zichzelf</li>
    <ul>
      <li>Out of those, 4 lemmas occurred more than once, but never without a reflexive dependent. Examples: aan_schaffen, om_vormen, uit_strekken, wringen</li>
    </ul>
</ul>

<h3>Relations Overview</h3>

<ul>
<li>This corpus uses 10 relation subtypes: <a>acl:relcl</a>, <a>aux:pass</a>, <a>cc:preconj</a>, <a>compound:prt</a>, <a>csubj:outer</a>, <a>expl:pv</a>, <a>nmod:poss</a>, <a>nsubj:outer</a>, <a>nsubj:pass</a>, <a>obl:agent</a></li>
<li>The following 1 main types are not used alone, they are always subtyped: <a>compound</a></li>
<li>The following 8 relation types are not used in this corpus at all: <a>vocative</a>, <a>dislocated</a>, <a>discourse</a>, <a>clf</a>, <a>list</a>, <a>goeswith</a>, <a>reparandum</a>, <a>dep</a></li>
</ul>
