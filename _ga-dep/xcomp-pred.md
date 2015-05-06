---
layout: relation
title:  'xcomp:pred'
shortdef : 'predicate'
---

In Irish, the substantive verb _bí_ `to be' can have predicate arguments in the form of adverbs, adjectives and prepositional phrases.
Note that this differs from ([copula]()) constructions. 

#### Adjective Predicate
~~~ sdparse
Bhí sé dochreidte go raibh sé fós beo \n It was unbelieveable that he was still alive
xcomp:pred(Bhí, dochreidte)
xcomp:pred(was, unbelievable)
~~~

#### Prepositional Predicate
Note that the head of the prepositional phrase is the object.

~~~ sdparse
Tá duine eile i_mbun peannaireachta \n Someone else is in charge of writing
xcomp:pred(Tá, peannaireachta)
case(peannaireachta, i_mbun)
xcomp:pred(is, charge)
~~~


#### Adverbial Predicate
~~~ sdparse
Tá Mel Gibson go hiontach sa scannán sin \n Mel Gibson is wonderful in that movie
xcomp:pred(Tá, hiontach)
xcomp:pred(Tá, wonderful)
~~~







