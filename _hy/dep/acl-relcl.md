---
layout: relation
title: 'acl:relcl'
shortdef: 'relative clause modifier'
udver: '2'
---

The `acl:relcl` relation is used for relative clauses modifying
a nominal. The relation points from the head of the nominal to the
head of the relative clause.

~~~ sdparse
Տեսա նրան , ով սիրում է քեզ ։ \n I saw the man , who loves you .
acl:relcl(նրան, սիրում)
acl:relcl(man, loves)
nsubj(սիրում, ով)
nsubj(loves, who)
obj(սիրում, քեզ)
obj(loves, you)
~~~

~~~ sdparse
Տեսա նրան , ում սիրում ես դու ։ \n I saw the man , who you love .
acl:relcl(նրան, սիրում)
acl:relcl(man, love)
nsubj(սիրում, դու)
nsubj(love, you)
obj(սիրում, ում)
obj(love, who)
~~~

~~~ sdparse
Հիշում եմ այն օրերը , երբ սովորում էի դպրոցում ։ \n I remember the days , when I-was studying at-school .
acl:relcl(օրերը, սովորում)
acl:relcl(days, studying)
obl(սովորում, երբ)
obl(studying, when)
~~~

~~~ sdparse
Կուզեի լինել լեռներում , ուր անց եմ կացրել իմ մանկությունը ։ \n I-would like to-be in-the-mountains , where I have passed my childhood .
acl:relcl(լեռներում, կացրել)
acl:relcl(in-the-mountains, passed)
obl(կացրել, ուր)
obl(passed, where)
~~~

~~~ sdparse
քաղաքը , որի մասին շատ եմ լսել \n the-city , that I-have heard about much 
acl:relcl(քաղաքը, լսել)
acl:relcl(the-city, heard)
obj(լսել, որի)
obj(heard, that)
case(որի, մասին)
case(that, about)
~~~