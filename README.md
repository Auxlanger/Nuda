<meta http-equiv="content-type" content="text/html;charset=utf-8">

---

# Nuda

by Robert Winter

<br/>

`Copyright © 2017 Robert Winter`

<br/><br/><br/><br/><br/><br/>

**Project Description**

Nuda is a simple international auxiliary language (auxlang).

**About the Author**

[Robert Winter](https://github.com/Auxlanger/Nuda) is the inventor of the Nuda language and the author of this document.

**Website**

Contact details will be added at a later date.  
For now, see [Nuda](https://github.com/Auxlanger/Nuda) on GitHub.

<br/><br/><br/><br/>

**Document Licence**

*<span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">Nuda</span>* by [Robert Winter](https://github.com/Auxlanger/Nuda) is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

[![License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

---

## Table of Contents

- [**Introduction**](#introduction)
- [**Timeline**](#timeline)
- [**Rationale**](#rationale)
    - [**Why *a priori*?**](#why-a-priori)
- [**Phonology**](#phonology)
    - [**Stress**](#stress)
- [**The Nuda Clock**](#the-nuda-clock)
- [**Scopes**](#scopes)
    - [**s1. Cardinal numbers 0 ... 12**](#s1.-cardinal-numbers-0-...-12)
    - [**s2. Lists**](#s2.-lists)
    - [**s3. Singular demonstratives**](#s3.-singular-demonstratives)
    - [**s4. Ordinal numbers 0 ... 12**](#s4.-ordinal-numbers-0-...-12)
    - [**s5. "is a"**](#s5.-is-a)
    - [**s6. "is"**](#s6.-is)
    - [**s7. "is, equals"**](#s7.-is-equals)
    - [**s8. Previous sentence: defu**](#s8.-previous-sentence-defu)
    - [**s9. Next sentence: gofu**](#s9.-next-sentence-gofu)
    - [**s10. Present sentence: fifu**](#s10.-present-sentence-fifu)
    - [**s11. Generalization: masi**](#s11.-generalization-masi)
    - [**s12. Specification**](#s12.-specification)
    - [**s13. Adjectives**](#s13.-adjectives)
- [**Word List**](#word-list)

---

## Introduction

This language is an *a priori* language in which **word roots are randomly generated using dice**.

For each syllable in a new root:

- a [D12](https://en.wikipedia.org/wiki/Dice#Standard_variations) is rolled to determine the initial consonant:  
1=b, 2=d, 3=f, 4=g, 5=k, 6=l, 7=m, 8=n, 9=p, 10=s, 11=t, 12=x  

- a [D6](https://en.wikipedia.org/wiki/Dice#Standard_variations) is rolled to determine the vowel:  
1=a, 2=a, 3=e, 4=i, 5=o, 6=u

The creation of new word roots is predominantly random by means of dice rolls as shown above. However, a randomly rolled word root can be rejected if for some reason inherent to the language it would be likely to cause problems. In that case the entire word root is rolled again.

**Not all word roots are randomly generated.** Exceptions include: proper nouns; words derived from international symbolic notations (such as the unit symbols of the International System of Units, and the symbols for chemical elements in the periodic table); words whose invented form is inherently likely to be easier phonetically, mnemonically, sequentially or logically.

The name of the language, *Nuda*, was the result of the first four dice rolls in the construction of the language.

The language shall have a **very small, strict grammar**.

The size of the **vocabulary is unlimited** but compounding of existing roots shall be preferred over creating new roots.

Spelling, pronunciation and grammar shall be **simple and easy**.

The language is intended to be **fun and practical**. It is not intended to rival natural languages in power. Rather, it is intended to be self-contained such that at each step of its development it is fun and practical to use within its current scope of development.

---

## Timeline

- 20170101 : Start of project
- 20170103 : Name of language randomly selected (from **bdfgklmnpsty** and **aiu**): Nuda
- 20170104 : Increased vowels from 3 to 5 (now **bdfgklmnpsty** and **aaeiou**) with **a** twice as likely as any other vowel
- 20170105 : Replaced **y** with **x** to eliminate accidental diphthongs (now **bdfgklmnpstx** and **aaeiou**)
- 20170105 : Invention of the Nuda clock
- 20170129 : s1. Cardinal numbers 0 ... 12
- 20170129 : s2. Lists
- 20170129 : s3. Singular demonstratives
- 20170203 : s4. Ordinal numbers 0 ... 12
- 20170203 : s5. "is a"
- 20170203 : s6. "is"
- 20170203 : s7. "is, equals"
- 20170204 : nu, ka, kanu
- 20170205 : defu, gofu
- 20170205 : mi, kami
- 20170206 : fifu
- 20170207 : Generalization, masi
- 20170207 : Specification
- 20170208 : Adjectives (singly applied)
- 20170209 : -to, -ki
- 20170210 : Adjectives (multiply applied as lists)
- 20170210 : ma changed to masi (more audible in sentences)
- 20170210 : Improved list grammar


---

## Rationale

### Why *a priori*?

Most modern auxlangs are *a posteriori* in the sense that their word roots are taken from existing natural languages. Nuda is an *a priori* language whose word roots are randomly generated by rolling dice. The principal reasons for this design decision were:

- Several well-developed and reasonably well-known *a posteriori* auxlangs are already available (Esperanto, Ido, Interlingua, Occidental, Lingua Franca Nova, Lingwa de Planeta). However, for passive literary use in reading sophisticated works of literature, Robert Winter, whose native language is English, found all of these languages to be far more difficult than French. This unexpected conclusion was reached after a few years of intermittent study of these auxlangs and of French. A major factor was that the resources available to assist the student of French were far superior to the resources available for any of the auxlangs. And although it was easier for Robert Winter to write simplistic sentences in the auxlangs than in French, the only auxlang he nearly always found to be easier than French for writing sophisticated sentences without assistance from another person was Interlingua, since it was possible to extrapolate from natural Romance languages to Interlingua when composing sophisticated sentences. However, Interlingua remained far more difficult than French for reading sophisticated works of literature. If a native speaker of English finds that French, although very difficult, is easier to learn to read in depth than any of these *a posteriori* auxlangs, despite their familiar vocabulary, it is even more likely that a native speaker of Chinese, to whom their vocabulary is unfamiliar, would reach the same conclusion. In short, the use of *a posteriori* vocabulary as the basis of an auxlang typically brings with it such difficulty (in idioms, grammar, word formation, pronunciation, phonotactics and spelling) that the auxlang is then unable to compete (even on the basis of ease alone) with the natural languages from which its vocabulary is sourced and for which better resources are available to support the student.

- As a thought experiment, an *a posteriori* auxlang was imagined whose vocabulary was predominantly Chinese and therefore unfamiliar to an English speaker. Almost certainly such an auxlang would have difficulties in idioms, grammar, word formation, pronunciation, phonotactics and spelling as a result of its vocabulary being predominantly Chinese. For the reasons given above, the reality is that if an English-speaking student needed to use Chinese vocabulary he or she would soon reject learning such an auxlang in favour of learning Chinese, because given the far greater resources available for learning Chinese (using pinyin) it would actually be the easier path. This is even without considering the economic advantages of learning Chinese.

- As a thought experiment, another auxlang was imagined, also intended to be accessible to speakers of English and to speakers of Chinese, but which used neither English vocabulary nor Chinese vocabulary. Its vocabulary would be entirely *a priori* and would be designed to be reasonably mnemonic to assist its memorization. Such an auxlang would not need to inherit any difficulties from either English or Chinese with respect to idioms, grammar, word formation, pronunciation, phonotactics and spelling but could instead be designed to be internally consistent. For example, it could have exceedingly easy pronunciation, phonotactics and spelling, unconstrained by any need to be capable of importing words from Chinese or English. In theory, if such a language were designed well enough to be fun and practical to use at least for some limited purposes, it could prosper because it could truly be easier than natural languages for those limited purposes. This thought experiment demonstrated the advantages of *a priori* vocabulary.

- It is possible that these conclusions are incorrect. If that is the case then happily some *a posteriori* auxlangs might become more successful in future. However, Robert Winter has chosen to focus his efforts on *a priori* auxlangs for the reasons given above.


---

## Phonology

Almost one letter, one phoneme. The exceptions are:

1. optionally, **a** can weaken from /a/ to /ə/ when unstressed
2. occasionally, **k** can be pronounced /kw/ to emphasize that it is not **g**
3. occasionally, **p** can be pronounced /pw/ to emphasize that it is not **b**
4. occasionally, **t** can be pronounced /tw/ to emphasize that it is not **d**

Thus:

- **a** ≈ /a/ `(optionally /ə/ when unstressed)`
- **b** = /b/
- **d** = /d/
- **e** ≈ /e/
- **f** = /f/
- **g** = /g/
- **i** ≈ /i/
- **k** = /k/ `(optionally /kw/)`
- **l** = /l/
- **m** = /m/
- **n** = /n/
- **o** ≈ /o/
- **p** = /p/ `(optionally /pw/)`
- **s** = /s/
- **t** = /t/ `(optionally /tw/)`
- **u** ≈ /u/
- **x** ≈ /ʃ/

That is:

- Consonants (C): **b d f g k l m n p s t x**
- Vowels (V): **a e i u o**

Syllable structure is:

- CV

Unused letters:

- c h j q r v w y z

### Stress

The penultimate syllable is normally the stressed syllable in all polysyllabic words. However, the speaker is welcome to shift stress to some other syllable for clarity or emphasis when doing so would facilitate communication.


---

## The Nuda Clock

The Nuda clock is a mnemonic device from which important core vocabulary of the Nuda language is derived. It is based on the order of the 12 consonants of the Nuda alphabet, combined with the order of the 5 vowels of the Nuda alphabet, geometrically applied to a clock face and also associated with colours and times of day.

Nuda is not a philosophical language; it is not based upon classifications. It is in part a mnemonic language and in part a randomly generated language. When being used mnemonically, the 13 syllables shown on the Nuda clock variously have associations such as colour, position, direction, time and number. They can also be combined, such as to signify geospatial relationships and mathematical operations. The Nuda clock is the key to memorizing important core vocabulary. It is a simple *aide-mémoire*.

![The Nuda clock (also dice tables and the pronunciation of the alphabet)](img/nuda-clock.jpg "The Nuda clock (also dice tables and the pronunciation of the alphabet)")

---

## Scopes

### s1. Cardinal numbers 0 ... 12

#### Scope

To be able to express the cardinal numbers from 0 to 12.

#### Means

Add suffix **na** to clock syllable: 0=xana, 1=bana, 2=dena, 3=fina, 4=gona, 5=kuna, 6=lana, 7=mena, 8=nina, 9=pona, 10=suna, 11=tana, 12=xena.


---

### s2. Lists

#### Scope

To be able to express a list.

#### Means

- Start the list with the delimiter **(** which is pronounced **do**
- If the list has more than 1 element, precede the last element with **na**
- If the list has more than 2 elements, separate other elements with the delimiter **,** which is also pronounced **na**
- End the list with the delimiter **)** which is pronounced **sa**

In colloquial speech you can choose not to pronounce these delimiters, instead only pronouncing each of the actual list elements themselves and the **na** preceding the last element. In formal speech all delimiters are pronounced.


#### Examples

A list with 3 elements:

> (1, 2 na 3) = (bana, dena na fina)

If a list has more than one element, the last element in the list must be preceded by the special delimiter **na** and this must be pronounced, even in colloquial speech. In formal speech each comma is also pronounced **na**.

Pronunciation:

> Formal speech: "do bana na dena na fina sa"  
> Colloquial speech: "bana, dena na fina"

You may pause slightly at the opening parenthesis of a list, at each comma in a list, and at the closing parenthesis of a list, to emphasize that you are enunciating the elements of a list.

A list with 1 element:

> \(1) = (bana)

Pronunciation:

> Formal speech: "do bana sa"  
> Colloquial speech: "bana"


---

### s3. Singular demonstratives

#### Scope

To be able to refer to something using a demonstrative pronoun.

#### Means

To declare a demonstrative, add suffix **ki** to clock syllable: 0th=xaki, 1st=baki, 2nd=deki, 3rd=fiki, 4th=goki, 5th=kuki, 6th=laki, 7th=meki, 8th=niki, 9th=poki, 10th=suki, 11th=taki, 12th=xeki. These are known as 'declaratives' (short for 'declarative pronouns').

To reference a previously declared demonstrative, add suffix **ko** to clock syllable: 0th=xako, 1st=bako, 2nd=deko, 3rd=fiko, 4th=goko, 5th=kuko, 6th=lako, 7th=meko, 8th=niko, 9th=poko, 10th=suko, 11th=tako, 12th=xeko.   These are known as 'referentials' (short for 'referential pronouns').

In everyday speech the most common of these pairs are **baki**/**bako** (*this*, or *this first one*) and **deki**/**deko** (*that*, or *that second one*). Less common are **fiki**/**fiko** (*that third one*) and **goki**/**goko** (*that fourth one*). It is rare to use any of the other demonstratives. It is usual for the speaker to declare demonstratives in some kind of logical order, such as from left to right when pointing, with the intention of facilitating understanding by the listener.

#### Examples

You and a friend are looking at 3 trees. You point at each tree in turn, from left to right, while saying:

> (baki, deki, fiki).  
> *This first one, that second one, that third one.*

You friend asks you which one you think is tallest. You say:

> deko.  
> *That second one.*

You friend disagrees by shaking his head and saying:

> bako.  
> *This first one.*


---

### s4. Ordinal numbers 0 ... 12

#### Scope

To be able to express the ordinal numbers from 0 to 12.

#### Means

Add suffix **fu** to the cardinal number: 0th=xanafu, 1st=banafu, 2nd=denafu, 3rd=finafu, 4th=gonafu, 5th=kunafu, 6th=lanafu, 7th=menafu, 8th=ninafu, 9th=ponafu, 10th=sunafu, 11th=tanafu, 12th=xenafu.


---

### s5. "is a"

#### Scope

To be able to express:

- "is a" in the sense of membership or classification

#### Means

Use the verb **tuni**.

#### Notes

The verb **tuni** was rolled (that is, randomly generated by rolling dice).

The words **lisusu** (*language*) and **lefu** (tree) were also rolled.

The more commonly a word root is expected to be used and compounded in everyday speech, the fewer syllables it is given. Here a design decision has been made that a word meaning *tree* would probably be used more commonly in everyday speech than a word meaning *language*, hence **lefu** has fewer syllables than **lisusu**. All single-syllable word roots are reserved for the core grammatical words of the Nuda language, such as **na**.

#### Examples

In general, word order in Nuda is SVO (subject, verb, object):

> Nuda tuni lisusu.  
> *Nuda is a language.*

You point at a tree and say:

> baki tuni lefu.  
> *This is a tree.*  
> = *This first one is a tree.*  
> = *That is a tree.*  
> = *That first one is a tree.*

Your friend agrees by nodding his head and saying:

> bako tuni lefu.  
> *It is a tree.*  
> = *This is a tree.*  
> = *This first one is a tree.*  
> = *That is a tree.*  
> = *That first one is a tree.*

Here the referential pronoun **bako** refers specifically to the very same thing which was most recently introduced into the conversation as the declarative pronoun **baki**. It is ungrammatical to use a referential pronoun (such as **bako**) whose corresponding declarative pronoun (such as **baki**) has not already been introduced into the conversation.


---

### s6. "is"

#### Scope

To be able to express:

- "is" in the sense of expressing an adjectival state or adjectival attribute
- "is" in the sense of identifying a language being used

#### Means

Use the verb **fa**.

#### Notes

The verb **fa** was rolled.

The word **nu** means *good* or *desirable* and was chosen since it corresponds to the first syllable of **Nuda** and is therefore easy to remember. The word **ka** means *opposite* and was chosen for its phonetic clarity and ease. Therefore **kanu** means *bad*.

#### Examples

You say:

> Nuda fa nu.  
> *Nuda is good.*

To explain that you are speaking Nuda you say:

> baki fa Nuda.  
> *This is Nuda.*

And then you say:

> bako fa nu.  
> *It is good.*

Your friend disagrees and says:

> bako fa kanu.  
> *It is bad.*


---

### s7. "is, equals"

#### Scope

To be able to express:

- "equals" in the mathematical sense
- "is" in the sense of equality
- "is" in the sense of identity (but not membership or classification)

#### Means

Use the verb **fifi**.

#### Notes

This verb was chosen logically. The hands of the Nuda clock show the time as being 3 o'clock. The syllable at that position is **fi**. This position on the clock is a reference point from which words, such as mathematical operators, are logically derived relative to the integer 3. The word **fifi** is the verb "to equal" (or "is" in the sense of equality) because it reduplicates the **fi** syllable to imply **(3, 3)** and the relationship between 3 and 3 is one of equality.

#### Examples

> Nuda fifi Nuda.  
> *Nuda is Nuda.*


> bana fifi bana.  
> *One equals one.*  
> 1 = 1


---

### s8. Previous sentence: defu

#### Scope

To be able to refer to the meaning of the previous sentence.

#### Means

Use the referential pronoun **defu**.  It can only refer to the meaning of the previous sentence.

#### Notes

This pronoun was chosen logically. On the Nuda clock, 3 o'clock is the reference point and is thought of as the present. The 2 o'clock syllable **de** is therefore prior to the reference point and here combined with **fu**, a syllable already associated with ordinality since it is the final syllable of all ordinal numbers, implies the general concept of being in the past or previous. However, **defu** is a special pronoun used only to refer to the meaning of the previous sentence. It is never used for any other purpose.

The referential pronoun **defu** is very commonly used.

The word **mi** was rolled. It means *true*. Thus **kami** means *false*.

#### Examples

> 1 = 1. defu fa mi.  
> *1 = 1. That is true.*  
> = *1 = 1. The previous sentence is true.*


> bana fifi bana. defu fa mi.  
> *One equals one. That is true.*  
> = *One equals one. The previous sentence is true.*


> 1 = 2. defu fa kami.  
> *1 = 2. That is false.*  
> = *1 = 2. The previous sentence is false.*


> bana fifi dena. defu fa kami.  
> *One equals two. That is false.*  
> = *One equals two. The previous sentence is false.*


> Nuda. defu fa nu.  
> *Nuda. It is good.*  
> = *Nuda. That is good.*  
> = *Nuda. Nuda is good.*  
> = *Nuda is good.*


> Nuda fa nu. defu fa mi.  
> *Nuda is good. That is true.*  
> = *Nuda is good. That Nuda is good is true.*  
> = *Nuda is good. The previous sentence is true.*  
> = *It is true that Nuda is good.*


---

### s9. Next sentence: gofu

#### Scope

To be able to refer to the meaning of the next sentence.

#### Means

Use the referential pronoun **gofu**. It can only refer to the meaning of the next sentence.

#### Notes

This pronoun was chosen logically. On the Nuda clock, 3 o'clock is the reference point and is thought of as the present. The 4 o'clock syllable **go** is therefore later than the reference point and here combined with **fu**, a syllable already associated with ordinality since it is the final syllable of all ordinal numbers, implies the general concept of being in the future or next. However, **gofu** is a special pronoun used only to refer to the meaning of the next sentence.  It is never used for any other purpose.

The referential pronoun **gofu** is used occasionally.

#### Examples

> gofu fa mi. 1 = 1.  
> *The next sentence is true. 1 = 1.*


> gofu fa mi. bana fifi bana.  
> *The next sentence is true. One equals one.*


> gofu fa kami. 1 = 2.  
> *The next sentence is false. 1 = 2.*


> gofu fa kami. bana fifi dena.  
> *The next sentence is false. One equals two.*


> gofu fa nu. Nuda.  
> *This is good: Nuda.*  
> = *Here is something good: Nuda.*  
> = *The next sentence is something good. Nuda.*  
> = *Nuda is good.*


> gofu fa mi. Nuda fa nu.  
> *This is true: Nuda is good.*  
> = *Here is something true: Nuda is good.*  
> = *The next sentence is true. Nuda is good.*  
> = *It is true that Nuda is good.*


---

### s10. Present sentence: fifu

#### Scope

To be able to refer to the present sentence as an entity.

#### Means

Use the referential pronoun **fifu**. It can only refer to the the present sentence itself; that is, the sentence in which **fifu** occurs. Unlike **defu** and **gofu**, which refer to the *meaning expressed by* the previous and next sentences respectively, **fifu** refers not to the meaning expressed by the present sentence but merely to the present sentence itself *as an entity*.

#### Notes

This pronoun was chosen logically. On the Nuda clock, 3 o'clock is the reference point and is thought of as the present. The 3 o'clock syllable **fi** is therefore here combined with **fu**, a syllable already associated with ordinality since it is the final syllable of all ordinal numbers, implying the general concept of the present or the present reference point. However, **fifu** is a special pronoun used only to refer to the present sentence as an entity.  It is never used for any other purpose.

The referential pronoun **fifu** is rarely used.

#### Examples

> fifu.  
> *This sentence.*  
> = *This present sentence.*

> fifu fa nu.  
> *This sentence is good.*  
> = *This present sentence is good.*  
> = *This sentence itself is good.*


---

### s11. Generalization: masi

#### Scope

To be able to express a generalization.

#### Means

Follow the subject with the generalizer **masi**.

#### Notes

Henceforth in this document, unless indicated otherwise, new word roots such as **masi** are assumed to have been rolled (that is, randomly generated by rolling dice). The word **fume** is a noun meaning *book*.

It is ungrammatical to qualify a generalized noun with a decalarative, because a generalization cannot be transformed into a specification. So this is ungrammatical nonsense: **fume masi baki** (*these 'books-in-general'* = nonsense). Remember that **masi**, if present, must end the noun phrase; it cannot be followed by any kind of qualifier or demonstrative.

#### Examples

By default, the subject of a sentence is specific.

To comment on a specific book:

> fume fa nu.  
> *The book is good.*

To comment on books in general:

> fume masi fa nu.  
> *Books are good.*  
> *Books in general are good.*

> fume masi fa nu. defu fa mi.  
> *Books are good. That is true.*  
> = *Books are good. The previous sentence is true.*  
> = *It is true that books in general are good.*


---

### s12. Specification

#### Scope

To be able to emphasize that you are being specific.

Subsequently, to be able to refer to that specific thing.

#### Means

Follow the subject with a declarative pronoun such as **baki**.

Subsequently, refer to it using the corresponding referential pronoun.

#### Notes

Nearly always **baki/bako** are used for this purpose unless in the context of the current conversation they are still being used to refer to something else, in which case the speaker would use the next pronoun pair in the ordinal sequence of referential/demonstrative pronoun pairs (**baki/bako**, **deki/deko**, **fiki/fiko** ...).

#### Examples

By default, the subject of a sentence is specific.

To comment on a specific book:

> fume fa nu.  
> *The book is good.*

Here **defu** refers to the meaning of the previous sentence:

> fume fa nu. defu fa mi.  
> *The book is good. That is true.*  
> = *The book is good. The previous sentence is true.*  
> = *It is true that the book is good.*

To emphasize that you are commenting on a specific book:

> fume baki fa nu.  
> *This book is good.*  
> = *This first book is good.*  
> = *That book is good.*  
> = *That first book is good.*

Here **defu** refers to the meaning of the previous sentence:

> fume baki fa nu. defu fa mi.  
> *This book is good. That is true.*  
> = *This book is good. The previous sentence is true.*  
> = *It is true that this book is good.*

Here **bako** refers to the specific book introduced in the previous sentence:

> fume baki fa nu. bako fa mi.  
> *This book is good. It is true.*  
> = *This book is good. It [the book] is true.*  
> = *This book is good and true.*  

The most recent use of a declarative pronoun, such as **baki**, supersedes its prior use:

> fume baki fa nu. lefu baki fa nu. bako fa nu.  
> *This book is good. This tree is good. It [the tree] is good.*  
> = *This book is good. This tree is good. The tree is good.*

> lefu baki fa nu. fume baki fa nu. bako fa nu.  
> *This tree is good. This book is good. It [the book] is good.*  
> = *This tree is good. This book is good. The book is good.*

To avoid such supersession, use the next pronoun pair (here **deki/deko**):

> fume baki fa nu. lefu deki fa nu. bako fa nu. deko fa nu.  
> *This book is good. This tree is good. It [the book] is good. It [the tree] is good.*  
> = *This book is good. This tree is good. The book is good. The tree is good.*

> fume baki. fume deki. bako fa nu. deko fa kanu.  
> *This book. That book. This one is good. That one is bad.*  
> *This book. That other book. This one is good. That other one is bad.*  
> *This first book. That second book. The first one is good. The second one is bad.*


---

### s13. Adjectives

#### Scope

To be able to qualify a noun by the use of one or more adjectives.

#### Means

For one adjective only: immediately follow the noun with the adjective.

For two or more adjectives: immediately follow the noun with a [list](#s2.-lists) of adjectives.

#### Notes

The adjective **xeno** means *new*. It can be converted into a noun by the addition of **-to** so as to mean *newness* (the degree of being new).

The nouns **defona** and **kadefona** mean *fiction* and *non-fiction* respectively. They can be converted into the adjectives *fictional* (being fiction) and *non-fictional* (being non-fiction) by the addition of **-ki**.

The final vowel of a word root does not indicate its part of speech. For example: **fume** (*book*), **lisusu** (*language*) and **defona** (*fiction*) are all nouns; **nu** (*good*), **mi** (*true*) and **xeno** (*new*) are all adjectives. You must memorize the meaning of a word root; there is no way to determine the part of speech of a word root from its structure. However, the structure of **xeno-to** (*newness*) clearly indicates by the presence of the hyphenated suffix **-to** that it is a noun (**xeno-to**) derived from an adjective (**xeno**). Similarly **defona-ki** (*fictional*) and **kadefona-ki** (*non-fictional*) are clearly adjectives derived from nouns.

#### Examples

Noun:

> fume.  
> *The book.*

Adjective:

> xeno.  
> *New.*

Noun:

> xeno-to.  
> *Newness.*

Qualified noun:

> fume xeno.  
> *The new book.*

Noun plus declarative:

> fume baki.  
> *This book.*

Qualified noun plus declarative:

> fume xeno baki.  
> *This new book.*

Generalized noun:

> fume masi.  
> *Books.*  
> = *Books in general.*

Qualified generalized noun:

> fume xeno masi.  
> *New books.*  
> = *New books in general.*

Above, **masi** correctly generalizes **fume xeno** (*the new book*) to become **fume xeno masi** (*new books*). It would be ungrammatical to say **fume masi xeno**; that is, **masi**, if present, must end the noun phrase.

Noun:

> defona.  
> *The fiction.*

Generalized noun:

> defona masi.  
> *Fiction.*  
> = *Fiction in general.*

Adjective:

> defona-ki.  
> *Fictional.*

Noun:

> fume.  
> *The book.*

Qualified noun:

> fume xeno.  
> *The new book.*

Multiply qualified noun:

> fume (xeno na defona-ki).  
> *The new fictional book.*

In a longer sentence:

> fume (xeno na defona-ki) fa nu.  
> *The new fictional book is good.*

In an even longer sentence:

> fume (xeno na defona-ki) fa (nu na mi).  
> *The new fictional book is good and true.*

Pronunciation (refer carefully to [**s2. Lists**](#s2.-lists)):

> Written sentence: **fume (xeno na defona-ki) fa (nu na mi).**  
> Colloquial pronunciation: "fume xeno na defona-ki fa nu mi."  
> Formal pronunciation: "fume do xeno na defona-ki sa fa do nu na mi sa."

A generalization:

> fume (xeno na defona-ki) masi fa nu.  
> *New fictional books are good.*

A statement about a bad book:

> fume (xeno, kami na kadefona-ki) fa kanu.  
> *The new, false, non-fiction book is bad.*

A statement about a good book:

> fume (xeno, mi na kadefona-ki) baki fa nu.  
> *This new, true, non-fiction book is good.*

---

## Word List

1. **baki** = this = this 1st one (declaration)
1. **bako** = this = this 1st one (reference)
1. **bana** = 1
1. **banafu** = 1st
1. **defona** = fiction
1. **defona-ki** = fictional
1. **defu** = the meaning of the previous sentence (special reference)
1. **deki** = that = that 2nd one (declaration)
1. **deko** = that = that 2nd one (reference)
1. **dena** = 2
1. **denafu** = 2nd
1. **do** = (
1. **fa** = is (expressing a state or attribute)
1. **fifi** = equals = is (expressing equality or identity)
1. **fifu** = the present sentence as an entity (special reference)
1. **fiki** = that = that 3rd one (declaration)
1. **fiko** = that = that 3rd one (reference)
1. **fina** = 3
1. **finafu** = 3rd
1. **fume** = book (noun)
1. **gofu** = the meaning of the next sentence (special reference)
1. **goki** = that = that 4th one (declaration)
1. **goko** = that = that 4th one (reference)
1. **gona** = 4
1. **gonafu** = 4th
1. **ka** = opposite
1. **kadefona** = non-fiction
1. **kadefona-ki** = non-fictional
1. **kami** = false, incorrect, inaccurate
1. **kanu** = bad, undesirable
1. **-ki** = converts a noun *X* into an adjective meaning *being X*
1. **kuki** = that = that 5th one (declaration)
1. **kuko** = that = that 5th one (reference)
1. **kuna** = 5
1. **kunafu** = 5th
1. **laki** = that = that 6th one (declaration)
1. **lako** = that = that 6th one (reference)
1. **lana** = 6
1. **lanafu** = 6th
1. **lefu** = tree
1. **lisusu** = language
1. **masi** = generalizes the preceding subject
1. **meki** = that = that 7th one (declaration)
1. **meko** = that = that 7th one (reference)
1. **mena** = 7
1. **menafu** = 7th
1. **mi** = true, correct, accurate
1. **na** = , (a delimiter situated between elements in a list)
1. **nu** = good, desirable
1. **niki** = that = that 8th one (declaration)
1. **niko** = that = that 8th one (reference)
1. **nina** = 8
1. **ninafu** = 8th
1. **Nuda** = Nuda
1. **poki** = that = that 9th one (declaration)
1. **poko** = that = that 9th one (reference)
1. **pona** = 9
1. **ponafu** = 9th
1. **sa** = )
1. **suki** = that = that 10th one (declaration)
1. **suko** = that = that 10th one (reference)
1. **suna** = 10
1. **sunafu** = 10th
1. **taki** = that = that 11th one (declaration)
1. **tako** = that = that 11th one (reference)
1. **tana** = 11
1. **tanafu** = 11th
1. **-to** = converts an adjective *X* into a noun meaning *the degree of being X*
1. **tuni** = is a (expressing membership or classification)
1. **xaki** = that = that 0th one (declaration)
1. **xako** = that = that 0th one (reference)
1. **xana** = 0
1. **xanafu** = 0th
1. **xeki** = that = that 12th one (declaration)
1. **xeko** = that = that 12th one (reference)
1. **xena** = 12
1. **xenafu** = 12th
1. **xeno** = new, newly created
1. **xeno-to** = newness (the degree of being new)


<!--
1. **** = 

-->

---

`20170103 / 20170210:1152`

---
