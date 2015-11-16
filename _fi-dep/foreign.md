---
layout: relation
title:  'foreign'
shortdef : 'foreign'
---

The dependency relation `foreign` is used to label sequences
of unanalyzed foreign words. These are annotated without regard
to internal structure, marking all words in the sequence direct
dependents of the head. The head is the first word of the foreign phrase.

Note that `foreign` does not apply to foreign *names*, which
are annotated using [name](), or to sequences of *analyzed* words
of foreign origin (such as established loanwords), which are
annotated with their full syntactic structure.

~~~ sdparse
Opimme fyysikoiden Let's assume a spherical cow -lähestymistavan .
dobj(Opimme-1, -lähestymistavan-8)
nmod:poss(fyysikoiden-2, -lähestymistavan-8)
compound:nn(Let's-3, -lähestymistavan-8)
foreign(Let's-3, assume-4)
foreign(Let's-3, a-5)
foreign(Let's-3, spherical-6)
foreign(Let's-3, cow-7)
punct(Opimme-1, .-9)
~~~

