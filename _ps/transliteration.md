---
layout: base
title:  'Transliteration and phonology'
udver: '2'
---

# Transliteration

* All pashto texts in UD are transliterated to capture their pronounciation.
* The transliteration used here is strictly phonemic: it aims on including all pronounced sounds, although they are not expressed in writing and on the contrary, it omits all unpronounced orthographic letters.
* The transliteration of each sentence is written on a line beginning with `# translit =`.
* The transliteration of word is given in the MISC column under the [Translit]() attribute.
* The transliteration of each lemma is shown in the MISC column under the [LTranslit]() attribute, but only if it differs from `Translit`.

<table>
<tr>
  <td align="middle"><b>Character</b></td>
  <td align="middle"><b>Corresponding phonemes</b></td>
</tr>
<tr>
  <td align="middle">ا ـا</td>
  <td align="left">- / i / a / u (word-initially)</br>â (word-initially, improper orthgraphy)</br>â (elsewhere)</td>
</tr>
<tr>
  <td align="middle">آ</td>
  <td align="left">(occurs only word-initailly)</br>â</td>
</tr>
<tr>
  <td align="middle">ن نـ ـنـ ـن</td>
  <td align="left">n</td>
</tr>
<tr>
  <td align="middle">ڼ ڼـ ـڼـ ـڼ</td>
  <td align="left">ṇ</td>
</tr>
<tr>
  <td align="middle">ب بـ ـبـ ـب</td>
  <td align="left">b</td>
</tr>
<tr>
  <td align="middle">ت تـ ـتـ ـت</td>
  <td align="left">t</td>
</tr>
<tr>
  <td align="middle">ټ ټـ ـټـ ـټ</td>
  <td align="left">ṭ</td>
</tr>
<tr>
  <td align="middle">یـ ـیـ</td>
  <td align="left">(does not occur word-finally)</br>y</br>i</td>
</tr>
<tr>
  <td align="middle">ي ـي</td>
  <td align="left">(occurs only word-finally)</br>i</td>
</tr>
<tr>
  <td align="middle">ی ـی</td>
  <td align="left">(occurs only word-finally)</br>ay (after a consonant)</br>y (after a vowel)</td>
</tr>
<tr>
  <td align="middle">ۍ ـۍ</td>
  <td align="left">(occurs only word-finally, feminine nominal ending)</br>ëy</td>
</tr>
<tr>
  <td align="middle">ئ ـئ</td>
  <td align="left">(occurs only word-finally, verb ending for the second person plural)</br>ëy (after a consonant)</br>y (after a vowel)</td>
</tr>
<tr>
  <td align="middle">ې ېـ ـېـ ـې</td>
  <td align="left">e</td>
</tr>
<tr>
  <td align="middle">ث ـث ـثـ ـث</td>
  <td align="left">s (only in words of Arabic origin)</td>
</tr>
<tr>
  <td align="middle">پ ـپ ـپـ ـپ</td>
  <td align="left">p</td>
</tr>
<tr>
  <td align="middle">ح حـ ـحـ ـح</td>
  <td align="left">h (only in words of Arabic origin)</td>
</tr>
<tr>
  <td align="middle">خ خـ ـخـ ـخ</td>
  <td align="left">x</td>
</tr>
<tr>
  <td align="middle">ج جـ ـجـ ـج</td>
  <td align="left">ǰ</td>
</tr>
<tr>
  <td align="middle">څ څـ ـڅـ ـڅ</td>
  <td align="left">c</td>
</tr>
<tr>
  <td align="middle">چ چـ ـچـ ـچ</td>
  <td align="left">č</td>
</tr>
<tr>
  <td align="middle">ځ ځـ ـځـ ـځ</td>
  <td align="left">ż</td>
</tr>
<tr>
  <td align="middle">ر ـر</td>
  <td align="left">r</td>
</tr>
<tr>
  <td align="middle">ړ ـړ</td>
  <td align="left">ṛ</td>
</tr>
<tr>
  <td align="middle">ز ـز</td>
  <td align="left">z</td>
</tr>
<tr>
  <td align="middle">ږ ـږ</td>
  <td align="left">ǧ</td>
</tr>
<tr>
  <td align="middle">ژ ـژ</td>
  <td align="left">ž</td>
</tr>
<tr>
  <td align="middle">د ـد</td>
  <td align="left">d</td>
</tr>
<tr>
  <td align="middle">ډ ـډ</td>
  <td align="left">ḍ</td>
</tr>
<tr>
  <td align="middle">ذ ـذ</td>
  <td align="left">z (only in words of Arabic origin)</td>
</tr>
<tr>
  <td align="middle">س سـ ـسـ ـس</td>
  <td align="left">s</td>
</tr>
<tr>
  <td align="middle">ښ ـښ ـښـ ـښ</td>
  <td align="left">x̌</td>
</tr>
<tr>
  <td align="middle">ش ـش ـشـ ـش</td>
  <td align="left">š</td>
</tr>
<tr>
  <td align="middle">ص صـ ـصـ ـص</td>
  <td align="left">s (only in words of Arabic origin)</td>
</tr>
<tr>
  <td align="middle">ض ضـ ـضـ ـض</td>
  <td align="left">z (only in words of Arabic origin)</td>
</tr>
<tr>
  <td align="middle">ط طـ ـطـ ـط</td>
  <td align="left">t (only in words of Arabic origin)</td>
</tr>
<tr>
  <td align="middle">ظ ظـ ـظـ ـظ</td>
  <td align="left">z (only in words of Arabic origin)</td>
</tr>
<tr>
  <td align="middle">ع عـ ـعـ ـع</td>
  <td align="left">(only in words of Arabic origin)</br>' / 'i / 'a / 'u (word-initially and word-centrally)</br>' (word-finally)</td>
</tr>
<tr>
  <td align="middle">غ غـ ـغـ ـغ</td>
  <td align="left">ġ</td>
</tr>
<tr>
  <td align="middle">ف فـ ـفـ ـف</td>
  <td align="left">f</td>
</tr>
<tr>
  <td align="middle">ق قـ ـقـ ـق</td>
  <td align="left">q</td>
</tr>
<tr>
  <td align="middle">ک کـ ـکـ ـک</td>
  <td align="left">k</td>
</tr>
<tr>
  <td align="middle">ګ ګـ ـګـ ـګ</td>
  <td align="left">g</td>
</tr>
<tr>
  <td align="middle">ل لـ ـلـ ـل</td>
  <td align="left">n</td>
</tr>
<tr>
  <td align="middle">م مـ ـمـ ـم</td>
  <td align="left">m</td>
</tr>
<tr>
  <td align="middle">ه هـ ـهـ ـه</td>
  <td align="left">h</br>a (only word-finally)</br>ë (only word finally, improper orthography)</td>
</tr>
<tr>
  <td align="middle">ۀ ـۀ</td>
  <td align="left">(occurs only word-finally)</br>ë</td>
</tr>
<tr>
  <td align="middle">و ـو</td>
  <td align="left">w</br>u</br>o</td>
</tr>
</table>
 
# Phonology
* For each phoneme the tables provide:
  * The phonetic realization
  * The usual orthographic realization depending on the position within the word: word-initial, word-central and word-final; the orthography of foreign words is not taken into account

## Vowels
<table>
<tr>
  <td align="middle" rowspan="2"><b>Phoneme</b></td>
  <td align="middle" rowspan="2"><b>Phonetic realization</b></td>
  <td align="middle" colspan="3"><b>Orthographic representation</b></td>
</tr>
<tr>
  <td align="middle"><b>Final</b></td>
  <td align="middle"><b>Central</b></td>
  <td align="middle"><b>Initial</b></td>
</tr>
<tr>
  <td align="middle"><i>i</i></td>
  <td align="left">closed front vowel [i]</td>
  <td align="middle">ـي ي</td>
  <td align="middle">ـیـ یـ / ـ</td>
  <td align="middle">ایـ / ا</td>
</tr>
<tr>
  <td align="middle"><i>e</i></td>
  <td align="left">mid front vowel [ɛ]</td>
  <td align="middle">ـې ې</td>
  <td align="middle">ـېـ ېـ</td>
  <td align="middle">اېـ</td>
</tr>
<tr>
  <td align="middle"><i>a</i></td>
  <td align="left">open front vowel [a]</td>
  <td align="middle">ـه ه</td>
  <td align="middle">-</td>
  <td align="middle">ا</td>
</tr>
<tr>
  <td align="middle"><i>ë</i></td>
  <td align="left">mid central vowel (shwa) [ə]</td>
  <td align="middle">ـۀ ۀ (ـه ه)</td>
  <td align="middle">-</td>
  <td align="middle"></td>
</tr>
<tr>
  <td align="middle"><i>u</i></td>
  <td align="left">closed back rounded vowel [u]</td>
  <td align="middle">ـو و</td>
  <td align="middle">ـو و / ـ</td>
  <td align="middle">او / ا</td>
</tr>
<tr>
  <td align="middle"><i>o</i></td>
  <td align="left">mid back rounded vowel [o]</td>
  <td align="middle">ـو و</td>
  <td align="middle">ـو و</td>
  <td align="middle">او</td>
</tr>
<tr>
  <td align="middle"><i>â</i></td>
  <td align="middle">open back rounded vowel [ɒ]</td>
  <td align="middle">ـا ا</td>
  <td align="middle">ـا ا</td>
  <td align="middle">آ (ا)</td>
</tr>
</table>

NOTES:
* The characters in brackets are often used istead of the proper ones.
* The sign "ـ" denotes that the phoneme does/may not have the ortographic realization in that position.

## Consonants

### Nasals
<table>
<tr>
  <td align="middle"><b>Phoneme</b></td>
  <td align="middle"><b>Phonetic realization</b></td>
  <td align="middle"><b>Orthographic representation</b></td>
</tr>
<tr>
  <td align="middle"><i>m</i></td>
  <td align="left">bilabial nasal [m]</td>
  <td align="middle">م مـ ـمـ ـم</td>
</tr>
<tr>
  <td align="middle"><i>n</i></td>
  <td align="left">alveolar nasal [n]</td>
  <td align="middle">ن نـ ـنـ ـن</td>
</tr>
<tr>
  <td align="middle"><i>ṇ</i></td>
  <td align="left">retroflex nasal [ɳ]</td>
  <td align="middle">ڼ ڼـ ـڼـ ـڼ</td>
</tr>
</table>

### Plosives
<table>
<tr>
  <td align="middle"><b>Phoneme</b></td>
  <td align="middle"><b>Phonetic realization</b></td>
  <td align="middle"><b>Orthographic representation</b></td>
</tr>
<tr>
  <td align="middle"><i>b</i></td>
  <td align="left">voiced bilabial plosive [b]</td>
  <td align="middle">ب بـ ـبـ ـب</td>
</tr>
<tr>
  <td align="middle"><i>p</i></td>
  <td align="left">unvoiced bilabial plosive [p]</td>
  <td align="middle">پ پـ ـپـ ـپ</td>
</tr>
<tr>
  <td align="middle"><i>d</i></td>
  <td align="left">voiced alveolar plosive [d]</td>
  <td align="middle">د ـد</td>
</tr>
<tr>
  <td align="middle"><i>t</i></td>
  <td align="left">unvoiced alveolar plosive [t]</td>
  <td align="middle">ت تـ ـتـ ـت</td>
</tr>
<tr>
  <td align="middle"><i>ḍ</i></td>
  <td align="left">voiced retroflex plosive [ɖ]</td>
  <td align="middle">ډ ـډ</td>
</tr>
<tr>
  <td align="middle"><i>ṭ</i></td>
  <td align="left">unvoiced retroflex plosive [ʈ]</td>
  <td align="middle">ټ ټـ ـټـ ـټ</td>
</tr>
<tr>
  <td align="middle"><i>g</i></td>
  <td align="left">voiced velar plosive [g]</td>
  <td align="middle">ګ ګـ ـګـ ـګ</td>
</tr>
<tr>
  <td align="middle"><i>k</i></td>
  <td align="left">unvoiced velar plosive [k]</td>
  <td align="middle">ک کـ ـکـ ـک</td>
</tr>
<tr>
  <td align="middle"><i>q</i></td>
  <td align="left">unvoiced uvular plosive [q]</td>
  <td align="middle">ق قـ ـقـ ـق</td>
</tr>
<tr>
  <td align="middle"><i>'</i></td>
  <td align="left">glottal stop [ʔ]</td>
  <td align="middle">عـ ـعـ</td>
</tr>
</table>

### Fricatives
<table>
<tr>
  <td align="middle"><b>Phoneme</b></td>
  <td align="middle"><b>Phonetic realization</b></td>
  <td align="middle"><b>Orthographic representation</b></td>
</tr>
<tr>
  <td align="middle"><i>f</i></td>
  <td align="left">unvoiced labiodental fricative [f]</td>
  <td align="middle">ف فـ ـفـ ـف</td>
</tr>
<tr>
  <td align="middle"><i>z</i></td>
  <td align="left">voiced alveolar fricative [z]</td>
  <td align="middle">ز ـز</td>
</tr>
<tr>
  <td align="middle"><i>s</i></td>
  <td align="left">unvoiced alveolar fricative [s]</td>
  <td align="middle">س سـ ـسـ ـس</td>
</tr>
<tr>
  <td align="middle"><i>ž</i></td>
  <td align="left">voiced post-alveolar fricative [ʒ]</td>
  <td align="middle">ژ ـژ</td>
</tr>
<tr>
  <td align="middle"><i>š</i></td>
  <td align="left">unvoiced post-alveolar fricative [ʃ]</td>
  <td align="middle">ش شـ ـشـ ـش</td>
</tr>
<tr>
  <td align="middle"><i>ǧ</i></td>
  <td align="left">the local realization of this voiced fricative<br/> spans from post-alveolar [ʒ] through retroflex [ʐ]<br/> and palatal [ʑ] to velar [ɣ] depending on dialect</td>
  <td align="middle">ږ ـږ</td>
</tr>
<tr>
  <td align="middle"><i>x̌</i></td>
  <td align="left">the local realization of this unvoiced fricative<br/> spans from post-alveolar [ʃ] through retroflex [ʂ]<br/> and palatal [ɕ] to velar [x] depending on dialect</td>
  <td align="middle">ښ ښـ ـښـ ـښ</td>
</tr>
<tr>
  <td align="middle"><i>ġ</i></td>
  <td align="left">voiced velar or uvular fricative [ɣ ~ ʁ]</td>
  <td align="middle">غ غـ ـغـ ـغ</td>
</tr>
<tr>
  <td align="middle"><i>x</i></td>
  <td align="left">unvoiced velar or uvular fricative [x ~ χ]</td>
  <td align="middle">خ خـ ـخـ ـخ</td>
</tr>
<tr>
  <td align="middle"><i>h</i></td>
  <td align="left">glottal fricative [h]</td>
  <td align="middle">ه هـ ـهـ ـه</td>
</tr>
</table>


### Affricates
<table>
<tr>
  <td align="middle"><b>Phoneme</b></td>
  <td align="middle"><b>Phonetic realization</b></td>
  <td align="middle"><b>Orthographic representation</b></td>
</tr>
<tr>
  <td align="middle"><i>ż</i></td>
  <td align="left">voiced alveolar affricate [d͡z]</td>
  <td align="middle">ځ ځـ ـځـ ـځ</td>
</tr>
<tr>
  <td align="middle"><i>c</i></td>
  <td align="left">unvoiced alveolar affricate [t͡s]</td>
  <td align="middle">څ څـ ـڅـ ـڅ</td>
</tr>
<tr>
  <td align="middle"><i>ǰ</i></td>
  <td align="left">voiced post-alveolar affricate [d͡ʒ]</td>
  <td align="middle">ج جـ ـجـ ـج</td>
</tr>
<tr>
  <td align="middle"><i>č</i></td>
  <td align="left">voiced alveolar affricate [t͡ʃ]</td>
  <td align="middle">چ چـ ـچـ ـچ</td>
</tr>
</table>


### Taps and Approximants
<table>
<tr>
  <td align="middle"><b>Phoneme</b></td>
  <td align="middle"><b>Phonetic realization</b></td>
  <td align="middle"><b>Orthographic representation</b></td>
</tr>
<tr>
  <td align="middle"><i>r</i></td>
  <td align="left">alveolar tap [ɾ]</td>
  <td align="middle">ر ـر</td>
</tr>
<tr>
  <td align="middle"><i>ṛ</i></td>
  <td align="left">retroflex tap [ɽ]</td>
  <td align="middle">ړ ـړ</td>
</tr>
<tr>
  <td align="middle"><i>l</i></td>
  <td align="left">alveolar lateral approximant [l]</td>
  <td align="middle">ل لـ ـلـ ـل</td>
</tr>
<tr>
  <td align="middle"><i>w</i></td>
  <td align="left">bilabial approximant [w]</td>
  <td align="middle">و ـو</td>
</tr>
<tr>
  <td align="middle"><i>y</i></td>
  <td align="left">palatal approximant [j]</td>
  <td align="middle">یـ ـیـ ـی ی ـئ ئ</td>
</tr>
</table>

## Stress
* Pashto has a phonemic stress that can fall on any syllable (but mostly falls on the last one).
* The stress should be marked with an accent mark (´) above the vowel of the stressed syllable in every word that includes two or more syllables.
* If such a word does not bear a stress, it indicates that it forms a stress group with another word, which is stressed (نه کوم _në́ kawëm_ “I do not do”)
