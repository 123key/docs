---
layout: relation
title: 'det:poss'
shortdef: 'possessive determiner'
---

Whenever there is a possessive determiner, we must use the subtype of <code>det</code> <code>det:poss</code>. Possessive determiners have the feature <code>Possessive</code> set on <code>Yes</code>.

~~~ sdparse
Sarà mia cura verificare . 
det:poss(cura, mia)
~~~
~~~ sdparse
Ha da poco annunciato le proprie dimissioni . 
det:poss(dimissioni, proprie)
~~~
