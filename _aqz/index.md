---
layout: base
title:  'Akuntsu UD'
udver: '2'
---

# UD for Akuntsu <span class="flagspan"><img class="flag" src="../../flags/svg/BR.svg" /></span>

## Tokenization and Word Segmentation



* Akuntsú uses all 17 [UPOS](https://universaldependencies.org/u/pos/index.html), although the class of adjectives is a complicated matter that requires more examination.
* Tokenization and semgmentatoin in Akunstú is straightforward. There are no multiwords that require spaces or dashes.
* In general, words are delimited by whitespace characters. Description of exceptions follows.
* According to typographical rules, many punctuation marks are attached to a neighboring word. We always tokenize them as separate tokens (words).

Mapping UPOS to XPOS Akuntsú

 UPOS | XPOS |
:----: | :------: |
 ADJ   | adj      |
 ADV   | adv      |
 INTJ  | intj     |
 NOUN  | n        |
 PROPN | ppn      |
 VERB  | v, vi, vt|
 ADP   | pp       |
 AUX   | aux      |
 CCONJ | cc       |
 DET   | det      |
 NUM   | num      |
 PART  | pcl      |
 PRON  | pro      |
 SCONJ | sc       |
 PUNCT | punct    |
 SYM   | sym      |
 X     | x        |

## Morphology 

### Tags

* Akuntsú is mostly a suffixing language, though its number of affixes and suffixes are relatively small if compared to some other South American languages. Words in this language can be composed as few as single morpheme, or can bear to different affixes. Inflection, derivation and compounding are processes found in the language, and derivation and compounding are productive in word formation.

### Features

NOMINAL FEATURE
* Nominal words, NOUN, PROPN and PRON, are not marked for Gender, plural or animacy.
* There are no classifiers.
* The two main values of the Number feature are Sing and Plural.
* The notion of plural is expressed through numerals, particles or through reduplication:

```
tɨrɨ-tɨrɨ apaɾa
two-two   banana
'four (or many) bananas'
```

```
ko-am           pega   ekwa 
fishhook-rope   bring  ITER
'(He) brings many fishing lines'
```

```
pi-pi
foot-foot
'feet'
```
* Akuntsú has postpositions and oblique clitics, including Ablative `Abl`, allative `All`, dative `Dat`,  essive `Ess`, locative `Loc`, translative `Tra` and inessive `Ine`. The bound (non-clitic) oblique markers are treated as `case`, while the term “postposition” is reserved only for cases of independent words, not bound forms which come after the word that they are grammatically related to.

Postpostion | Function   |           Example        |
:---------: | :---------:|:---------------------:   |
 etʃe       | Perlative  | _konitʃe okɨp **etʃe**_ 'The thorn gets **into** my leg' |    
 ete        | Comitative/Relative | _tekwata Buko **ete**_ 'He leaves **with** Buquá'| 
 pi         | Inessive  | _ojẽ **pi** õkwa_ 'I am washing the **interior** of my mouth'|      

Clitics     |            Function           |           Example        |
:---------: | :----------------------------:|:------------------------:|
(b)õ   | Allative/Dative/Instrumental  | _otʃipap tabɨt**õ** ka_ 'My grandmother went **to** the garden'             |    
(e)ɾi | Comitative                    | _ameko**ɾi** imaã_ 'because of the jaguar, she stores them'	|
na    | Essive/Translative            | _powpow iko**na**_ 'It will be owl's food (the bird that they killed) '             | 
pe    | Locative                      | _tɨeɾo kwiɾo**pe**_ 'Chicha is at the container'                | 

* The relational markers `Rel` indicate contiguity `Rel=Cont` or non-contiguity `Rel=NCont` between a head and its dependent. That is, the relational indicates whether the possessed noun is or is not contiguous to its possessor, as exemplified below:

Rel    | Form   |             Example                  |
:-----:|:---------:| :----------------------------------: |
Cont   | ∅     | _Konibu **ø**-ajtʃi Aɾamĩɾa_ 'Konibú's wife is Aramira'            |    
NCont  | t | _apaɾa **t**-ep tʃopa jẽ_ 'This one sees banana's leaf'    | 

* The reflexive/correferential morpheme _te_ is associated with the feature-value `Reflex=Yes`. 
* The demonstratives can occur as noun specifiers or as predicate complements, which receive the tag DEM with two values: `Deixis=Prox` and `Deixis=Dist`.

```
jẽ        kem-kɨ         jẽ        kem-kɨ=ɾom
DEM.PROX  breast-liquid  DEM.PROX  breast-liquid=NEG
'This one has breast-milk, this one doesn't have breast-milk'
```

```
otʃe t-ek         no        jẽɾom     tʃok
1PL.EXCL R-house  other     DEM.DIST  build 
'Our other house, they built that one'
```

* Nominal Reduplication: it marks pluralilty in nouns, as in *pi-pi* ‘feetʼ. It can be monosyllabic (involving the first or the second syllable of the stem) or dissyllabic. Reduplication is associated with the feature-value `Redup`.

* Augmentative and diminutive: the diminutive morpheme is -*tin* `Dim` and the augmentative -*atʃo* `Augm`. These morphemes refer to the size of something or the expansion of an event (if it is big or not). 

VERBAL FEATURE
* Verbs tend to combine with categories that denote aspect, modality, and voice.
* The aspectual morphemes include the iterative `Iter`, and habitual `Hab`. There is also a projective aspect.
* Akuntsú has the following voice features [VOICE](https://universaldependencies.org/u/feat/Voice.html): Middle `Mid` and causative `Cau` 
* Akuntsú has a set of [auxiliaries](https://universaldependencies.org/u/pos/AUX_.html) `Aux` that expresses the notion of ‘sitting,’ ‘lying,’ ‘standing,’ ‘walking,’  ‘moving,’  ‘coming’ and ‘going´. The auxiliaries are given in the table below:


| Standing | Sitting | Lying | In movement |Going|
:----: | :------: |:------: |:------: |:------: |
|ãm|jã|toa|tʃe|ka ~ ko

* Some verbs occur with the morpheme -*ka*, which is a transitivizer. This [feature](https://universaldependencies.org/u/feat/index.html) (`Trans`) takes the value YES if the when the morpheme is present.  Verbs that may or not combine with this morpheme take no overt object or require two obligatory arguments. 

* Verbal Reduplication: it assigns aspectual function in verbs, as in *ãbi-bi* ‘to pull successively.ʼ As in the nouns, it can be monosyllabic (involving the first or the second syllable of the stem) or dissyllabic. Reduplication is associated with the feature-value `Redup`.

* Nominalization: there are two productive nominalizer affixes in this language: -ap `Nomzr=Circ`and i- `Nomlzr=Obj`. 


    taptot     te=i-ko
manioc   3COR=OBJ.NMLZ-ingest ‘Manioc, his own food’
## Syntax

* Akuntsú is predominantly head-final. 
* Objects tend to precede verbs. The most frequent word order is (S)OV. 
* The basic clausal constituents may be described basically as [(PRONOMINAL CLITICS) + NOUNS + (NOMINAL MORPHOLOGY) + (OBJECT) + (VERBAL MORPHOLOGY) + VERB + (VERBAL MORPHOLOGY) + (AUXILIARY)]. 
* Clause combining mainly involves coordination, subordination, and complementation. Coordination is done by the simple juxtaposition of clauses; complementation is usually in the form of nominalizations. 

* In Akuntsú, the antipassive voice is not morphologically marked directly on the verb, but through the demotion of the object to an oblique position in a given transitive clause. The oblique clitic =*pe*, described with the feature `Obl`, marks the object when it is occurring outside of the usual syntactic position of the object.

```
tɨrɨ         puru-ru-ru         me-me-me          ek        pagop=pe
two          IDEO-RED-RED       IDEO-RED-RED      house     new=OBL
'In two (days) that one goes back and forth and builds [on] a new house'
```

## Treebanks

There is 1 Akuntsu UD treebank:

  * [Akuntsu](https://github.com/UniversalDependencies/UD_Akuntsu-TuDeT)

