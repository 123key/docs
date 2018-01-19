---
layout: base
title:  'Syntax'
udver: '2'
---

# Specific constructions

## Clausal structures

In Armenian, the standard case pattern of a predicate-argument construction is as follows:

* the first argument (subject) is in the Nominative case;

* the second argument (direct object) is in the Nominative or Dative case;

* all other arguments are coded in other cases or in prepositional phrase depending their semantics.

However, there are constructions which have non canonical case patterns.

### Ablative subject

The constructions are instantiated by a middle voice verb, the first argument of which is in the Ablative case with a partitive meaning and not in the canonical Nominative case. The ablative argument is also labeled [nsubj]().

~~~ sdparse
Հնչեցին երգերից/NOUN[Case=Abl] ։ \n Sounded from-songs .
nsubj(Հնչեցին, երգերից)
nsubj(Sounded, from-songs)
~~~

## Adjectival and adverbial constructions

### Comparative constructions

Armenian qualitative adjectives and adverbs have only periphrastic comparative forms, most of them can have also a periphrastic superlative (see the [Degree]() feature), e. g. _խելացի_ “smart”, _ավելի խելացի_ “smarter”, _ամենախելացի_ “smartest”, _ամենից խելացի_, _բոլորից խելացի_ “smartest”. The morphological superlative forms are assigned the `Sup` [Degree]() feature.

The most frequently used comparative constructions are the following:

* _Արամը_.Nom _եղբորից_.Abl <b>_խելացի_</b> / <b>_ավելի խելացի_</b> / _է_ ։ “Aram is <b>smarter</b> than his brother.” (with both types of comparatives)
* _Արամը_.Nom <b>_ավելի խելացի_</b> _է_, _քան (թե) եղբայրը_.Nom։ “Aram is <b>smarter</b> than his brother.”
* _Արամը_.Nom _բոլոր_ _ուսանողներից_.Abl <b>_ամենից խելացին_</b> / <b>_ամենախելացին_</b> _է_ ։ “Aram is <b>the smartest one</b> of all the students.” (with both types of superlatives)
* _Արամը_.Nom _եղբոր_.Dat _պես / նման / չափ_.POST <b>_խելացի_</b> _է_ ։ “Aram is <b>smart</b> as his brother.” (equality comparison)

The “lesser degree” comparison (expressed periphrastically) is marked the same way:

* _Արամը_.Nom <b>_նվազ խելացի_</b> / <b>_պակաս խելացի_</b> _է_, _քան (թե) եղբայրը_.Nom։ “Aram is <b>less smart</b> than his brother.” (with both types of comparatives)

~~~ sdparse
Արամը եղբորից խելացի է ։ \n Aram is smart than-his-brother .
obl(խելացի, եղբորից)
obl(smart, than-his-brother)
~~~

~~~ sdparse
Արամը բոլոր ուսանողներից ամենախելացին է ։ \n Aram is the-smartest-one of-all the-students .
obl(ամենախելացին, ուսանողներից)
obl(the-smartest-one, the-students)
det(ուսանողներից, բոլոր)
det(the-students, of-all)
~~~

If the standard of comparison is a nominal, it is marked morphologically by a ablative [Case]() or by a dative:

~~~ sdparse
Սիրունններից/Noun[Case=Abl] էլ ու ամենասիրունն էիր դուն ։ \n
obl(ամենասիրունն, Սիրունններից)
~~~

~~~ sdparse
Սիրուննների/Noun[Case=Dat] ամենասիրունն էիր դուն ։ \n
obl(ամենասիրունն, Սիրուննների)
~~~

To keep the analyses of the morphological and the periphrastic cases parallel
(and also to keep the analyses parallel cross-linguistically),
in the periphrastic examples the entity comapared to modifies still the adjective and not the adverb:

~~~ sdparse
Արամը եղբորից ավելի խելացի է ։ \n Aram is more smart than-his-brother .
obl(խելացի, եղբորից)
obl(smart, than-his-brother)
advmod(խելացի, ավելի)
advmod(smart, more)
~~~

~~~ sdparse
Արամը ավելի խելացի է , քան եղբայրը ։ \n Aram is more smart , than his-brother .
obl(խելացի, եղբայրը)
obl(smart, his-brother)
case(եղբայրը, քան)
case(his-brother, than)
~~~

~~~ sdparse
Արամը բոլոր ուսանողներից ամենից խելացին է ։ \n Aram is the-most smartest-one of-all the-students .
obl(խելացին, ուսանողներից)
obl(smartest-one, the-students)
det(ուսանողներից, բոլոր)
det(the-students, of-all)
advmod(խելացին, ամենից)
advmod(smartest-one, the-most)
~~~

~~~ sdparse
Արամը բոլորից խելացի է ։ \n Aram is smart of-all .
obl(խելացի, բոլորից)
obl(smart, of-all)
~~~

~~~ sdparse
Նա ինձնից շատ է կարդում ։ \n He reads more than-me .
advmod(կարդում, շատ)
obl(կարդում, ինձնից)
advmod(reads, more)
obl(reads, than-me)
~~~

### Relations in Equality Comparison

~~~ sdparse
Արամը եղբոր պես/ADP խելացի է ։ \n Aram is smart as his-brother .
obl(խելացի, եղբոր)
obl(smart, his-brother)
case(եղբոր, պես)
case(his-brother, as)
~~~

~~~ sdparse
Նպատակասլացությունը նույնքան/SCONJ կարևոր է , որքան/SCONJ խաղացողի տաղանդը ։ \n Commitment is as important as a-player's talent .
advmod(կարևոր, նույնքան)
advmod(important, as-13)
case(տաղանդը, որքան)
case(talent, as-15)
obl(կարևոր, տաղանդը)
obl(important, talent)
~~~

If a property is compared to a clause, the clause is attached as [advcl]() instead of [obl]()
and the conjunction _(քան)_ is attached to the subordinate clause as [mark]().

~~~ sdparse
Նա որքան/SCONJ աներկյուղ էր , նույնքան/SCONJ գեղեցիկ ։ \n She is as brave as beautiful .
advmod(աներկյուղ, որքան)
advmod(brave, as-12)
advcl(աներկյուղ, գեղեցիկ)
advcl(brave, beautiful)
mark(գեղեցիկ, նույնքան)
mark(beautiful, as-14)
~~~

~~~ sdparse
Ես ավելացրի այնքան/SCONJ ալյուր , որքան/SCONJ ասվում էր բաղադրատոմսում \n ։ I put in as-much flour as was called-for in-the-recipe .
det(ալյուր, այնքան)
det(flour, as-much)
advcl(այնքան, ասվում)
advcl(as, called-for)
~~~

~~~ sdparse
Նա այնքան/SCONJ հրապուրիչ էր , որ/SCONJ խմբագիրը հիացավ ։ \n She was so attractive , that the-editor admired .
advmod(հրապուրիչ, այնքան)
advmod(attractive, so)
advcl(այնքան, հիացավ)
advcl(so, admired)
mark(հիացավ, որ)
mark(admired, that)
~~~

### Inequality Scalar Comparison

~~~ sdparse
Արամը շատ ավելի խելացի է , քան թվում է ։ \n Aram is much more smart , than it seems .
advcl(խելացի, թվում)
advcl(smart, seems)
mark(թվում, քան)
mark(seems, than)
~~~


### Comparatives (quantity)

In certain contexts the comparative complement combines both the action or adjective that is being compared
and the quantity it is compared to:

* _ավելի քան 90 տոկոս_ “more than 90 percent”
* _ավելի քան վստահելի գործընկեր_ “more than trusted companion”
* _ավելի քան հավանական_ “more than likely”

In these cases we consider _ավելի քան_ to be a fixed multi-word expression because the two words are inseparable.
One cannot say _*ավելի գործընկեր քան վստահելի_ (the word _գործընկներ_ can be pulled to the front but then it will skip the whole MWE,
as in _գործընկերն ավելի էր, քան վստահելի_ lit. _the companion was more than trusted._)

~~~ sdparse
Դա ավելի քան հավանական է ։ \n That is more than likely .
nsubj(հավանական, Դա)
nsubj(likely, That)
cop(հավանական, է)
cop(likely, is)
advmod(հավանական, ավելի)
advmod(likely, more)
fixed(ավելի, քան)
fixed(more, than)
punct(հավանական, ։-6)
punct(likely, .-13)
~~~

### Constructions more and less quantity

_Ավելի_ / _քիչ_ / _պակաս_ governs the case of the cardinal numeral.

~~~ sdparse
Հարյուրից ավելի մարդ եկավ : \n Came more-than 100 people .
nsubj(եկավ, մարդ)
nsubj(Came, people)
nummod(մարդ, Հարյուրից)
nummod(people, 100)
case(Հարյուրից, ավելի)
case(100, more-than)
~~~

~~~ sdparse
Հարյուրից քիչ մարդ եկավ : \n Came less-than 100 people .
nsubj(եկավ, մարդ)
nsubj(Came, people)
nummod(մարդ, Հարյուրից)
nummod(people, 100)
case(Հարյուրից, քիչ)
case(100, less-than)
~~~

## Noun phrases with quantifiers

### Constructions with cardinal numerals

See [flat]() and [compound]() on the compound numerals.

Other types of QP:

* _երկու.Nom ամբողջ.Nom.Sg չորս.Nom տասն(եր)որդական.Nom.Sg միլիոն.Nom.Sg դրամ.Nom.Sg_ “2.4 million drams” (i.e. “four tenth parts of million” with the ellipsis of “parts”)

~~~ sdparse
երկու ամբողջ չորս տասնորդական միլիոն դրամ \n two whole-parts four tenth million drams
nummod(դրամ, միլիոն)
nummod(drams, million)
nummod(միլիոն, ամբողջ)
nummod(million, whole-parts)
nummod(տասնորդական, չորս)
nummod(tenth, four)
nummod(ամբողջ, երկու)
nummod(whole-parts, two)
conj(ամբողջ, տասնորդական)
conj(whole-parts, tenth)
~~~

### Constructions with numerals and adjectives

If the phrase with a numeral and adjective the numeral modifying the noun takes nominative and the noun is usuall in singular, cf.

* <b>_երկու_</b>.Nom <b>_սպիտակ_</b> <b>_նավակ_</b>.Sg

~~~ sdparse
երկու սպիտակ նավակ \n two white boats
nummod(նավակ, երկու)
nummod(boats, two)
amod(նավակ, սպիտակ)
amod(boats, white)
~~~
