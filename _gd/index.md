---
layout: base
title:  'Scottish Gaelic UD'
udver: '2'
---

# UD for Scottish Gaelic <span class="flagspan"><img class="flag" src="../../flags/svg/GB-SCT.svg" /></span>

At present UD for Scottish Gaelic contains a single corpus, the Annotated Reference Corpus of Scottish Gaelic.

## Tokenisation and Word Segmentation

Words are delimited by whitespace or punctuation.
There are no multiword tokens.
There are however multitoken words.

### Reconstructing spacing
Context: ARCOSG does not contain the original texts, so we have to reconstruct them in a consistent way.
We use GOC (Gaelic Orthographic Conventions, https://www.sqa.org.uk/files_ccc/SQA-Gaelic_Orthographic_Conventions-En-e.pdf) for consistency in reconstructing spacing, but don't apply any other corrections.

According to the latest GOC:
* There are spaces after _a'_, _b'_, _d'_ or _m'_.
* There are no spaces after _dh'_.
* Do not close up before _'m_ or _'n_.

Also (not covered explicitly by GOC but shown in examples):
* Close up _h-_, _t-_, and _n-_.
* Don't close up after _th'_ and _bh'_.

If an elided _a'_ or _ag_ before a verbal noun is indicated by _'_, close this up.

Close up around the hyphen in _a-measg_, _a-rèir_, _a-thaobh_ and similar but don't close up around hyphens if they're being used as dashes.
Also don't attempt to bring into line with GOC by adding or taking away hyphens.

Also close up _dhà-na-tri_ (see fp05\_012).

### Multiword tokens

The original version of ARCOSG contains tokens that contain spaces.
For UD, however, we need to split these up.
For the moment we duplicate the UPOS and the XPOS for each of the words.
PROPNs have a `flat:name` relation; others use `fixed`.

The multiword expressions using the `fixed` relation are documented at [https://universaldependencies.org/gd/deps/fixed.html](deps/fixed).

### Multitoken words

Conversely, there are single tokens in ARCOSG that correspond to more than one word in the UD sense.
Here are the most common families:
* Inflected prepositions (tagged `Pr*` in ARCOSG) such as _orm_, _agam_ and _ann_ are divided into the preposition which is `ADP` and the personal pronoun which is `PRON`.
* Similarly prepositions (tagged `Spa-s` in ARCOSG) which have been fused with a following article such as _dhan_, _mun_, _tron_ are divided into a preposition and an article. _'san_ and the like, which are short for _anns an_, are divided into two `ADP`s with a `fixed` relation between the two.
* Prepositions and aspect markers (see below) which have been fused with a possessive pronoun (tagged `Sap*` or `Spp*`) in ARCOSG.
* Where _'se_ and _'sann_ are a single orthographical word they too are separated out. See the section on _is_ below for details.

## Morphology

### Parts of speech

Standard UPOS tags are used throughout. Generally we follow the choices made in the Irish UD treebanks.
* `AUX` is used for _is_ (the copula) and _rach_ (the passive copula).
_bi_ is tagged as `VERB`.
* The following words are tagged `PART`: the adverbialiser _gu_ (_gu math_ 'well'), the comparative particle _nas_, the superlative particle _as_, the agreement particle _a_ (_a dol_ 'to go'), the vocative particle _a_ (_a Sheumais_ 'James'), the patronymic particles _Mac_ and _Nic_, the numerical particle _a_ (_a h-aon) 'one'), the past tense marker _do_, the negative particles _cha_ and _nach_, the interrogative particles _a_ and _an_ and the relative particle _a_.
* Verbal nouns are tagged as `NOUN` with `VerbType=Vnoun`.
* Deverbal adjectives are tagged as `ADJ`.
* The aspectual particles _ag_/_a'_, _air_, _gu_ and _ri_ (all prototypically adpositions) are tagged as `ADP`.
* Demonstrative pronouns, _seo_, _sin_ and _siud_ are tagged as `PRON` as in Irish.
* If they are acting as determiners (and tagged as `Dd` in ARCOSG) then they are tagged `DET`, as in Irish again.

### Features

Gaelic has two genders (masculine and feminine), four cases (nominative/accusative, genitive, dative and vocative), three numbers (singular, dual and plural), the usual three persons and an impersonal form.

The words _fèin_ and _cheile_ take `Reflex=Yes`.

The indicative mood is default and we mark the conditional (`Cnd`), imperative (`Imp`) and interrogative (`Int`) moods. The tenses we mark are 

We also follow Irish in marking three pronoun types (`Emp` = emphatic, `Int` = interrogative and `Rel` = relative), polarity (`Neg` on negative particles) and the following particle types: `Ad` (adverbialiser), `Comp` (comparative), `Cmpl` (complement), `Inf` (agreement particle), `Int` (interrogative), `Num` (numerical), `Pat` (patronymic), `Vb` (verbal) and `Voc` (vocative).

We also have `Foreign=Yes` for words that are in Irish or English according to the original ARCOSG tagging.

## Syntax

### VSO clause structure

Main clauses and subordinate clauses are VSO.
The subject almost invariably follows the verb but 
* _Chuala mi sin gun teagamh._ 'I heard that without a doubt' (V S O ADV)
* _Can gun do chaith thu e_ 'Say that you did it' (V SCONJ past-tense-marker V S O)

However, if there is an externally-controlled complement then the object follows the verbal noun if it is in the progressive aspect with a nominal object, but precedes it if it is in the progressive aspect with a pronominal object.
* _Bha iad a' toirt an teachd-an-tìr_ 'They were making a living' (V S asp V O)
* _Bheil thu ga mo leantainn?_ 'Are you following me?' (V S asp O V)
* _Bha esan air a bhean a chaill_ 'He had lost his wife' (V S asp O V)

### Core arguments, oblique arguments and adjuncts

The core arguments are marked by `nsubj` and `obj` if they are noun phrases. Oblique arguments and adjuncts are marked by `obl` when they are prepositional phrases. Occasionally they are noun phrases in which case we use `obl:tmod` if they indicate a stretch of time or `obl:smod` if they indicate a distance.

In terms of clausal subjects `csubj:cop` is used for expressions like:
* _B' àbhaist do dhaoine saoilsinn..._ 'People usually think...'
where _àbhaist do dhaoine_ is the root, _bu_ (here in the reduced form _b'_) is the copula and _saoilsinn_ is the clausal subject. In Gaelic clefting constructions are much more common than in Irish:
* _'se caoraich a th' aice_ 'it is sheep that they have'
* _chan e gearrain aon duine a th' ann_ (lit. it is not the complaint of one person that is in it) 'it is not the complaint of one person'
The expletive particle _e_ or _ann_ is linked to the copula with `fixed`.

### Language-specific labels
With three exceptions, these follow Irish:
* `acl:relcl` for relative clauses
* `aux:pass` for _rach_-passives
* `case:voc` for vocative particles
* `csubj:cleft` for cleft subjects
* `csubj:cop` for copular clausal subjects
* `mark:prt` for particles not otherwise marked
* `nmod:poss` for possessive pronouns (but we use `obj` where the use of the possessive pronoun indicates an object)
* `nsubj:outer` for where there are two subjects for a _rach_-passive.
* `nsubj:pass` for the subjects of _rach_-passives
* `obl:smod` (not in Irish) for spatial modifiers
* `obl:tmod` for temporal modifiers
* `xcomp:pred` for predicates of the substantive verb _bi_ 'to be'. _bi_ does not take an object. To identify the predicate: the most likely is a verbal noun, followed by an existential prepositional phrase _ann_ or a prepositional phrase expressing location, a noun phrase expressing temporal extent, spatial extent or cost, and lastly an adverb.


## Some specific cases

### The verbal noun
Annotate as a `NOUN`.

#### With aspect markers (continuous tenses and depictives)

Here it has `VerbType=VNoun`.
_ag_, _air_, _ri_ and so forth preceding it have a `case` relationship as in Irish.
Here it is an `xcomp:pred` of the verb _bi_.

#### Inversion structures and _rach_-passives

Here it has `VerbType=Inf`.
Usually it is preceded by an infinitive particle _a_ but this is elided where it begins with a vowel or _fh_.
In inversion structures, the object is `obj` of the verbal noun, with the exception of _rach_-passives where it is `nsubj:pass` or exceptionally `nsubj:outer`.

### _agus_, _is_ and _'s'_

* Usually these are `CCONJ` and are related to what they are conjoining with `cc`.
* However if they are being used cosubordinatively, to introduce an adverbial phrase that looks like a `bi` clause where the verb has been elided, they are `SCONJ` and the relation is `mark`.
* **Caution**: one eighth of ARCOSG is football commentary where the verb is routinely elided. In this case look at whether the events being related are sequential or simultaneous. If they are sequential, then _agus_ is a coordinating conjunction. If they are simultaneous then _agus_ is a subordinating conjunction.
* In expressions like _fad 's_ and _o chionn 's_, then _'s_ has a `fixed` relation to the subordinating conjunction.
* However in expressions like _corr is_ and _fiù 's_, where the word preceding it is a content word, then it is a coordinating conjunction and behaves as normal.

### _air ais_

In ARCOSG, _ais_ is tagged as `Nf` (fossilized noun).
However there are phrases like _air ais no air adhart_ in which there seems to be no good reason to treat the first half differently from the second half, even if _ais_ is no longer productive.

c04\_024: 'she did not write back yet'
~~~ conllu
1	cha	cha	PART	Qn	PartType=Vb|Polarity=Neg	3	mark:prt	_	_
2	do	do	PART	Q--s	Tense=Past	3	mark:prt	_	_
3	sgrìobh	sgrìobh	VERB	V-s	Tense=Past	0	root	_	_
4	i	i	PRON	Pp3sf	Gender=Fem|Number=Sing|Person=3	3	nsubj	_	_
5	air	air	ADP	Sp	_	6	case	_	_
6	ais	ais	NOUN	Nf	_	3	obl	_	_
7	fhathast	fhathast	ADV	Rt	_	3	advmod	_	_
~~~

### _bi_
Auxiliary use: we follow the Irish UD treebank and treat _bi_ as a `VERB`, and the verbal noun as a `NOUN` linked back to _bi_ with an `xcomp:pred` deprel.

Predicative use: again, we follow Irish and use `xcomp:pred` for predicative adjectives, PPs and adverbs. There is a construction exemplified in c02\_009a, c02\_009b and c02\_010 _bi... agam... ri dhol..._ and in this case we assume that the PP with _aig_ is the quirky experiencer and _ri_ is the predicate.

However (see f01\_028), there are also uses of _bi_ for extent in time (n03\_041) and space.

### _còrr is_ and friends

Example taken from pw01\_015a: in _còrr is deich bliadhna_, _bliadhna_ is conjoined with _còrr_ and _deich_ is a `nummod` of _bliadhna_.

From ns04\_053: in _thachair an tubaist còrr is bliadhna gu leth_ _còrr_ is `obl:tmod` of _thachair_ because the phrase as a whole is a time phrase.

### _dè cho..._

'how' as in 'how big'. _dè_ remains `PRON` and _cho_ is `advmod` of the succeeding adjective.

### _feuch_

When this is tagged as `Vm-2s` the sense in which it is usually used is 'to try to', in which case it is linked to the higher clause with an `xcomp` deprel.
For example n04\_002: _... gu robh e 'dol a dh’fhalbh feuch a faigheadh..._, _feuch_ is an `xcomp` of _dh’fhalbh_.

### _fhios agad_ and variants

'you know'. Treat as `parataxis` as it is explicitly excluded from `discourse`. See also `parataxis` below.

### _an ìre mhath_

This means 'almost'. See s08_061b for an example. Use `nmod`.

### _is_
_'S_, _b'_, _bu_, _'se_, _'sann_ and so on are `cop` and the root is whatever has been fronted by it.
We treat _'S e_ as a fixed expression where _e_ has a `fixed` relation with the `AUX`.
Likewise _'S ann_, except of course _ann_ is divided up into _an_ and _e_ and both have a `fixed` relation with the `AUX`.

Following Cox in _Geàrr Ghràmar na Gàidhlig_, p. 284, in phrases like _is ann a cheannaich mi bainne_, _cheannaich_ is still the root even though it's preceded by a relative particle.

Again we follow Irish and whatever comes after the root is a subject, be it a nominal subject, `nsubj`, or a clausal subject, `csubj:cleft` or `csubj:cop`.

### _mas_

_Mas_ ('if') is divided into the two words _ma_ (`SCONJ`) and _is_ (`AUX`).

### _nach maireann_

(as in _Dr Calum MacGilleathain nach maireann_, 'The late Dr Calum Maclean') This is `acl:relcl` of the deceased because _nach_ is the negative relativiser.

### `parataxis`

Where you have a big long sentence with lots of "ars' esan" and "ars' ise"s in it, treat them like punctuation and make them `parataxis` of the most contentful content word in the nearest quoted text so as to avoid non-projectivity. Sentence n01\_038 is an example of this.

### _an t-seachdain seo chaidh_ and others

'last week', literally 'this week that went'. Treat _chaidh_ as being `acl:relcl` of _t-seachdain_ (pw05\_005, also _ceud_ in the sense of 'century': see fp01_034).

### _urrainn_

In most dialects the person (or thing) that can follows the preposition _do_ so is of course `nmod`.
In some, however, you can say, for example, _'s urrainn mi_, so in this case _mi_ is `nmod` of _urrainn_.

---

## Treebanks

There is one Scottish Gaelic UD treebank:

  * [ARCOSG](../treebanks/UD_Scottish_Gaelic-ARCOSG/index.html)

## References

* Colin Batchelor, 2019. Universal dependencies for Scottish Gaelic: syntax, in Proceedings of CLTW2019 at Machine Translation Summit XVII, Dublin, August
* Lamb, William, Sharon Arbuthnot, Susanna Naismith, and Samuel Danso. 2016. Annotated Reference Corpus of Scottish Gaelic (ARCOSG), 1997–2016 [dataset]. Technical report, University of Edinburgh; School of Literatures, Languages and Cultures; Celtic and Scottish Studies. https://doi.org/10.7488/ds/1411.
* Lynn, Teresa and Jennifer Foster, [Universal Dependencies for Irish] (http://www.nclt.dcu.ie/~tlynn/Lynn_CLTW2016.pdf), CLTW 2016, Paris, France, July 2016

