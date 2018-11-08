---
layout: relation
title: 'appos'
shortdef: 'appositional modifier'
udver: '2'
---

An appositional modifier of a noun is a nominal immediately following the first noun that serves to define or modify that noun.
It includes parenthesized examples, as well as defining abbreviations in one of these structures.

~~~ sdparse
Sam , mon frère , est arrivé \n Sam , my brother , arrived
appos(Sam, frère)
~~~

~~~ sdparse
Appelation d'origine contrôlée  ( AOC )
appos(Appelation, AOC)
~~~

**UD_French-Spoken** does not use the `appos` relation anymore.
Instead there are two subrelations [appos:nmod]() and [appos:conj]().

The `appos:nmod` relation is used for appositions which modify nominal elements.

~~~ sdparse
la place Voltaire
appos:nmod(place, Voltaire)
~~~

The `appos:conj` relation is used for appositions that respect the prosody of list (the elements of such an appositions are in the same paradigm and have the same referent):

~~~ sdparse
Sam , mon frère , est arrivé . \n Sam, my brother, arrived.
appos:conj(Sam, frère)
~~~
