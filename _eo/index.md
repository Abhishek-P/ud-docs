---
layout: base
title:  'Esperanto UD'
udver: '2'
---

# UD for Esperanto <span class="flagspan"><img class="flag" src="../../flags/svg/ESPERANTO.svg" /></span>
As of January 2025, Esperanto UD contains one document (Manufest de Prago) annotated with Universal Dependencies.

## Tokenization and Word Segmentation

Esperanto words are delimited by whitespace or punctuation, and no tokens in any of the UD Esperanto corpus currently contain whitespace. Only a few multiword tokens should be used for Esperanto clitics, such as dank'al ("danke" + "al", "thanks to"), or l' (reduced form of the definite article "la"). 

(To be continued)

## Morphology
In Esperanto, the word-ending morpheme of a word indicates its part of speech: Nouns end with "-o" (when nominative singular), infinitive verbs with "-i," adjectives with "-a," and adverbs with "-e." For example,with the root "aŭd-", "aŭdo" means "hearing," "aŭdi" means "to hear," "aŭda" means "auditory," and "aŭde" means "by ear."

### Nouns:
Suffixes on nouns indicate their case and number: Nouns ending with "-o" are nominative singular, those with "-oj" are nominative plural, "-on" accusative singular, and "-ojn" accusative plural. For example,

"Esploristo faras eksperimenton." "A researcher is conducting an experiment."

The noun "esploristo" is a nominative singular, functioning as the subject of the verb "faras," while the noun "eksperimenton" is an accusative singular, functioning as the object of the same verb. For another example, 

"Esploristoj faras eksperimentojn." "Researchers are conducting experiments."

The noun "esploristoj" is a nominative plural, functioning as the subject of the verb "faras" (Esperanto does not have subject-verb agreement). The noun "eksperimentojn" is an accusative plural, functioning as the object of the same verb.

### Adjectives:
Adjectives agree with the nouns they modify in terms of their case and number: Adjectives ending with "-a" are nominative singular, those with "-aj" are nominative plural, "-an" accusative singular, and "-ajn" accusative plural. For example, 

"Laborema esploristo faras malfacilan eksperimenton." "A hard-working researcher is conducting a difficult experiment."

The nominative singular adjective "laborema" agrees with the nominative singular noun "esploristo", while the accusative singular adjective "malfacilan" agrees with the accusative singular noun "experimenton." For another example,

"Laboremaj esploristoj faras malfacilajn eksperimentojn." "Hard-working researchers are conducting difficult experiments."

The nominative plural adjective "laboremaj" agrees with the nominative plural noun "esploristoj", while the accusative plural adjective "malfacilajn" agrees with the accusative plural noun "experimentojn."

Adjectives also agree with the subject when they are the complement of the copula "esti." For example,

"Ĉi tiuj eksperimentoj estas malfacilaj." "These experiments are difficult."

The nominative plural adjective "malfacilaj" agrees with the nominative plural noun "eksperimentoj."

(To be continued)
### Tags

*

---
**Instruction**: Specify any unused tags. Explain what words are tagged as PART. Describe how the AUX-VERB and DET-PRON distinctions are drawn, and specify whether there are (de)verbal forms tagged as ADJ, ADV or NOUN. Include links to language-specific tag definitions if any.

---

### Features

*

---
**Instruction**: Describe inherent and inflectional features for major word classes (at least NOUN and VERB). Describe other noteworthy features. Include links to language-specific feature definitions if any.

---

## Syntax

*

---
**Instruction**: Give criteria for identifying core arguments (subjects and objects), and describe the range of copula constructions in nonverbal clauses. List all subtype relations used. Include links to language-specific relations definitions if any.

---

## Treebanks

There are [N](../treebanks/eo-comparison.html) Esperanto UD treebanks:

  * [Esperanto-A](../treebanks/eo_a/index.html)
  * [Esperanto-B](../treebanks/eo_b/index.html)

---
**Instruction**: Treebank-specific pages are generated automatically from the README file in the treebank repository and
from the data in the latest release. Link to the respective `*-index.html` page in the `treebanks` folder, using the language code
and the treebank code in the file name.

---
