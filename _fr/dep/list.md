---
layout: relation
title: 'list'
shortdef: 'list'
udver: '2'
---

The `list` relation is used for chains of comparable items.
It is not currently attested in any French treebank.

Web text often contains passages which are meant to be interpreted as lists but are parsed as single sentences.
Email signatures in particular contain these structures, in the form of contact information:
the different contact information items are labeled as `list`;
 the key-value pair relations are labeled as [appos]().

In lists with more than two items, all items of the list should modify the first one.

~~~ sdparse
Steve Jones GSM: 555-9814 Email: jones@abc.edf
name(Steve-1, Jones-2)
list(Steve-1, GSM:-3)
list(Steve-1, Email:-5)
appos(GSM:-3, 555-9814-4)
appos(Email:-5, jones@abc.edf-6)
~~~
