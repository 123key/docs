---
layout: relation
title: 'obl:mod'
shortdef: 'oblique modifier'
udver: '2'
---

**UD_French-Spoken** uses  the `obl:mod` relation for nominal adjuncts. They can be (but are not always) introduced by a preposition.

Here is an example from **UD_French-Spoken** :

~~~ sdparse
oui oui je prends le métro le matin à huit heures et demie \n yes i take the underground in the morning at eight thirty
obl:mod(prends, heures)
obl:mod (prends, matin)
~~~

For prepositional phrases which are required by the verb (or the adjective), the [obl:comp]() relation is used.
For non-core nominal dependents of a verb, we can use the [obl:periph]() relation.
