---
layout: relation
title:  'nmod:obl'
shortdef: 'oblique nominal modifier'
udver: '2'
---

This relation is a subtype of the [nmod]() relation. `nmod:obl` noun phrases attached to nouns are in different [cases](Case), usually follow the modified noun and functionally correspond to a non-core (oblique) argument or adjunct.

~~~ sdparse
Նրա վերադարձը հայրենիք հետաձգվում էր ։ \n His return to-matherland.Nom was-beeing postponed .
aux(հետաձգվում, էր)
nsubj:pass(հետաձգվում, վերադարձը)
nmod:obl(վերադարձը, հայրենիք)
det:poss(վերադարձը, Նրա)
aux(postponed, was-beeing)
nsubj:poss(postponed, return)
nmod:obl(return, to-matherland.Nom)
det:pass(return, His)
~~~

~~~ sdparse
Սպառազինությունների վաճառքը հակամարտության կողմերին արգելվեց ։ \n Arms sales to-the-parties.Dat of-conflict was-forbidden . 
nsubj:pass(արգելվեց, վաճառքը)
nmod:obl(վաճառքը, կողմերին)
nmod:pass(կողմերին, հակամարտության)
nmod:pass(վաճառքը, Սպառազինությունների)
nsubj:pass(was-forbidden, sales)
nmod:obl(sales, to-the-parties.Dat)
nmod:pass(to-the-parties.Dat, of-conflict)
nmod:pass(sales, Arms)
~~~

In conjunction with the [case]() relation, `nmod:obl` provides a uniform analysis for the oblique alternation:

~~~ sdparse
թշնամու դեմ պատերազմը \n the-war.Dat against the-enemy
nmod:obl(պատերազմը, թշնամու)
case(թշնամու, դեմ)
nmod:obl(the-war.Dat, the-enemy)
case(the-enemy, against)
~~~

~~~ sdparse
սեղանի վրայի գիրքը \n the-book on.Dat the-table.Dat 
nmod:obl(գիրքը, սեղանի)
case:loc(սեղանի, վրայի)
nmod:obl(the-book, the-table.Dat)
case:loc(the-table.Dat, on.Dat)
~~~

~~~ sdparse
այգու մոտի առուն \n the-brook near.Dat the-garden.Dat
nmod:obl(առուն, այգու)
case:loc(այգու, մոտի)
nmod:obl(the-brook, the-garden.Dat)
case:loc(the-garden.Dat, near.Dat)
~~~

~~~ sdparse
Նա եկավ ընտրություններից երկու օր առաջ ։ \n He came two days before the-elections .
case(ընտրություններից, առաջ)
nummod(օր, երկու)
obl(եկավ, ընտրություններից)
nmod:obl(ընտրություններից, օր)
case(the-elections, before)
nummod(days, two)
obl(came, the-elections)
nmod:obl(the-elections, days)
~~~

~~~ sdparse
Նա եկավ ընտրություններից օր առաջ ։ \n He came days before the-elections .
case(օր, առաջ)
obl(եկավ, օր)
nmod:obl(օր, ընտրություններից)
case(days, before)
obl(came, days)
nmod:obl(days, the-elections)
~~~
