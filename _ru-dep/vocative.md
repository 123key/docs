---
layout: relation
title: 'vocative'
shortdef: 'vocative'
---

The `vocative` relation is used to mark dialogue participant addressed in text.
The relation links the addressee's name to its host sentence.
In Russian, the addressee's name can also appear in the vocative [cs-feat/Case]() form.

~~~ sdparse
Мужчина , Вы дурак ! \n Sir , you-are a-fool !
vocative(Вы, Мужчина)
vocative(you-are, Sir)
~~~
