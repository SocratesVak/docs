---
layout: feature
title: 'Degree'
shortdef: 'degree of comparison'
udver: '2'
---

<table class="typeindex" border="1">
<tr>
  <td style="background-color:cornflowerblue;color:white"><strong>Values:</strong> </td>
   <td><a href="#Abs">Abs</a></td>
  <td><a href="#Cmp">Cmp</a></td>
  <td><a href="#Sup">Sup</a></td>	
  <td><a href="#Pos">Pos</a></td>
  <td><a href="#Dim">Dim</a></td>
  <td><a href="#Aug">Aug</a></td>
</tr>
</table>

Degree of comparison is typically an inflectional feature of some
[adjectives](el-pos/ADJ) and [adverbs](el-pos/ADV). Modern Greek marks morphologically the positive, comparative and absolute superlative degree  while the superlative degree of adjectives is composite (definite article + comparative degree). 

### <a name="Pos">`Pos`</a>: positive, first degree

This is the base form that merely states a quality of something,
without comparing it to qualities of others. The adverbs express a manner.

#### Examples

<b>Adjectives</b>
- _νέος άντρας_ "_young_ man"
- _άσχημο παιδί_ "_ugly_ child"

<b>Adverbs</b>
- _έξυπνα, καλά_ "cleverly, good"

### <a name="Cmp">`Cmp`</a>: comparative, second degree

The quality of one object is compared to the same quality of another
object. The adverbs express a comparison of manners.

#### Examples

<b>Adjectives</b>
- _ο άντρας είναι νεώτερός μου_ "the man is _younger_ than me"
- _το παιδί είναι ασχημότερο απο τον πατέρα_ "the child is _more ugly_ than the father"

<b>Adverbs</b>
- _εξυπνότερα, καλύτερα_ "more cleverly, better"
- _πιο_ "more" (the adverb is used to form composite comparative degree of adjectives and adverbs: _ο άντρας είναι πιο νέος από εμένα_ "the man is _younger_ than me"),   _η Μαρία μιλάει πιο δυνατά από τον Γιώργο_ "Maria speaks _more loudly_ than George"

### <a name="Abs">`Abs`</a>: absolute superlative

The adjective expresses morphologically that the studied quality of
the given object is so strong that there is hardly any other object
exceeding it. The quality is not actually compared to any particular
set of objects. The adverbs express the highest degree of a manner.

#### Examples

<b>Adjectives</b>
- _Η Μαρία ήταν ωραιότατη._ "Maria was _most beautiful_." 

Modern Greek expresses degree modification of nouns, adjectives, past participles and adverbs with a set of prefixes and suffixes (and a set of syntactic means);  suffixation may 
 change the gender of the noun, e.g., _χέρι_ "hand" (neutral) vs. _χερούκλα_ "large hand" (feminine), _άντρας_ "man" (masculine) vs. _αντράκι_ "little/insignificant/bully man" (neuter).

All affixation cases are assigned the lemma of the original word and the feature <code>el-DegreeMod</code>  takes one of the two available values. 

### <a name="Dim">`Dim`</a>: diminutive

#### Examples

* <b>Nouns</b> (suffixation)  
	* _χταποδάκι_ / *chtapodaki* "little octopus"
	* _πορτούλα_ / *portoula* "little door" 
	* _φωνίτσα_ / *fonitsa* "little voice"
	* _εικονίδιο_ / _ikonidio_  "little picture"
	
* <b>Adjectives</b> (suffixation)
	 * _μικρούτσικος_ / *mikroutsikos* "smallish" 
	 * _κιτρινούλης_ / *kitrinoulis* "yellowish" 
	 * _ασπρουλιάρης_ / _asprouliaris_ "whitish"

* <b>Passive participles</b> (prefixation)
	* _μισοδαγκωμένος_ / _misodagkomenos_ "slightly bitten"
	* _ψιλοθυμωμένος_ / _psilothimomenos_ "slightly angry"
	
* <b>Adverbs</b> (suffixation)
	* _καλούτσικα_ / _kaloutsika_ "slightly good"
	

### <a name="Aug">`Aug`</a>: augmentative

#### Examples

* <b>Nouns</b> (suffixation)
	*  *τρυπάρα* / *tripara* "large hole"
	*   *ψευταράς* / *pseftaras* "great lier"
	*  _χερούκλα_/ *cheroukla* "large hand"
	  
* <b>Adjectives</b> (prefixation)
	 * _κατά-μαυρος_ / *katamavros "stark black"
	 * _ολό-φωτος_ / *olofotos* "very bright"
	
* <b>Passive participles</b> (prefixation)
	* _κατα-κουρασμένος_ / _katakourasmenos_ "very tired"
	* _χιλιο-ταλαιπωρημένος_ / _chiliotalaiporimenos_ "exhausted, worn out" 
	
* <b>Adverbs</b>
	* _ωραιότατα, κάλλιστα_ "most nicely, best"

<!-- Interlanguage links updated So kvě 14 19:02:11 CEST 2022 -->
