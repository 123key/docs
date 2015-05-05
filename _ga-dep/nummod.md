---
layout: relation
title: 'nummod'
shortdef: 'numeric modifier'
---

*Numeric modifiers* of a noun or NP, including both cardinal and
ordinal numbers, are marked with the `nummod` dependency type. Quantifiers are also included.

~~~ sdparse
sa bhliain 1975 \n in the year 1975
nummod(bhliain, 1975)
nummod(year, 1975)
~~~

~~~ sdparse
an chéad chéim \n the first year
nummod(chéim, chéad)
nummod(first, year)
~~~

~~~ sdparse
fo-alt (1) \n sub-paragraph (1)
nummod(fo-alt, (1))
nummod(sub-paragraph, (1))
~~~



