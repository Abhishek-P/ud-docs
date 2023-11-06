---
layout: feature
title: 'PronType'
shortdef: 'pronominal type'
udver: '2'
---

<table class="typeindex" border="1">
<tr>
  <td style="background-color:cornflowerblue;color:white"><strong>Values:</strong> </td>
  <td><a href="#Prs">Prs</a></td>
  <td><a href="#Art">Art</a></td>
  <td><a href="#Int">Int</a></td>
  <td><a href="#Rel">Rel</a></td>
  <td><a href="#Dem">Dem</a></td>
  <td><a href="#Tot">Tot</a></td>
  <td><a href="#Neg">Neg</a></td>
  <td><a href="#Ind">Ind</a></td>
  <td><a href="#Exc">Exc</a></td>
  <td><a href="#Predet">Predet</a></td>
  <td><a href="#Ord">Ord</a></td>
</tr>
</table>

This feature typically applies to [pronouns](u-pos/PRON),
[determiners](u-pos/DET), pronominal [numerals](u-pos/NUM)
(quantifiers) and pronominal [adverbs](u-pos/ADV).

### <a name="Prs">`Prs`</a>: personal or possessive personal pronoun or determiner

See also the [Poss]() feature that distinguishes normal personal
pronouns from possessives and the [Clitic]() feature that tells 
whether the pronoun is a clitic. Note that `Prs` also includes reflexive
personal/possessive pronouns (see the [Reflex]() feature).

#### Examples

* Personal pronouns: _Uno di <b>loro</b>_ "One among them", _Per <b>lui</b> è utile_ "For him it's useful"
* Possessive pronouns (`Poss=Yes`): _La <b>sua</b> è migliore_ "Hers is better", _I <b>suoi</b> sono felici_ "Her/his [parents] are happy"
* Possessive determiners/adjectives (`Poss=Yes`): _La <b>sua</b> scuola è migliore_ "Her/his school is better", _I <b>loro</b> amici_ "Their friends".
* Clitic pronouns (`Clitic=Yes`): _<b>Si</b> è trasformato_ "Has transformed itself" (reflexive), _<b>Ti</b> ho dato_ "I have given you" (indirect object), _Ora <b>si</b> cerca il colpevole_ "Now one/somebody searches for the culprit" (impersonal form), _<b>Lo</b> vediamo spesso_ "We often see him/it"

### <a name="Art">`Art`</a>: article

Article is a special case of determiner that bears the feature of
[definiteness](Definite).

#### Examples

* Definite articles (`Definite=Def`): _<b>La</b> luna_ "The moon", _<b>I</b> regali di Natale_ "Christmas presents"
* Indefinite articles (`Definite=Ind`): _<b>Un</b> amico_ "A friend", _<b>Una</b> sorpresa_ "A surprise"

### <a name="Int">`Int`</a>: interrogative pronoun, determiner, numeral or adverb

Note that possessive interrogative determiners (_whose_) can be
distinguished by the [Poss]() feature.

#### Examples:

* Interrogative pronouns: _<b>Chi</b> è il presidente?_ "Who is the president?"
* Interrogative determiners: _<b>Che</b> cosa faremo adesso?_ "What shall we do now?", _<b>Quale</b> libro hai letto?_ "Which book did you read?"

Note: for the time being we do not use the feature `ProntType=Int` interrogative pronouns such as _dove_ "where" and _quando_ "when" in sentences like _<b>Dov'</b> è Siena?_ "Where is Siena?".

### <a name="Rel">`Rel`</a>: relative pronoun, determiner, numeral or adverb

#### Examples:

* Relative pronouns: _La strada <b>che</b> porta al mare_ "The road which leads to the sea", _Il libro <b>che</b> ho letto_ "The book that I read".
* Relative determiners: _Un autore sul <b>cui</b> futuro puoi scommettere_ "An author on whose future you can bet".


### <a name="Dem">`Dem`</a>: demonstrative pronoun, determiner, numeral or adverb

These are often parallel to interrogatives.

#### Examples

* Demonstrative pronouns: _Per <b>questo</b> sono ambiziosi_ "For this [reason] they are ambitious".
* Demonstrative determiners: _Parte di <b>questo</b> denaro_ "Part of this money".

Note: Demonstrative adverbs such as _qui_ "here" and _là_ "there", _ora_ "now" e _allora_ "then" are not marked with `PronType=Dem`.

### <a name="Tot">`Tot`</a>: total (collective) pronoun, determiner or adverb

#### Examples

We are not using `PronType=Tot`.

### <a name="Neg">`Neg`</a>: negative pronoun, determiner or adverb

#### Examples:

We distinguish only negative adverbs such as: _non_, _nemmeno_, _neppure_.

### <a name="Ind">`Ind`</a>: indefinite pronoun, determiner, numeral or adverb

#### Examples

* Indefinite pronouns: _uno_ "one", _tutti_ "everybody", _ognuno_ "each one", _chiunque_ "anybody", _qualcosa_ "something", _qualcuno_ "somebody"
* indefinite determiners: _tutti_ "all", _qualche_ "some", _ogni_ "each", _alcuni_ "some", _diversi_ "several"

### <a name="Exc">`Exc`</a>: exclamative determiners.

#### Examples

* _che_ disastro "what a disaster", _che_ catastrofe "what a catastrophe"

### <a name="Predet">`Predet`</a>: predeterminer. This value is language specific.

It is always used along with _det:predet_ dependency relations.

#### Examples

* _tutta_ la giornata "all day"
* _tutti_ gli esseri umani "all human beings"
* _entrambi_ i prigionieri "both prisoners"

### <a name="Ord">`Ord`</a>: ordinal pronouns. This value is language specific.

It is used to mark ordinal pronouns. Part of speech is PRON/NO. When ordinals are used as noun modifiers they are marked as [ADJ].

#### Examples

* Il _primo_ sostiene che ...  "the first asserts that ...
* Un _quarto_ d'ora "a quarter of an hour"
* Valentina è _quinta_ "Valentina is fifth"
<!-- Interlanguage links updated Po 6. listopadu 2023, 21:42:04 CET -->
