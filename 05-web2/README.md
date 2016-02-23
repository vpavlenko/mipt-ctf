Web2
====

## Лекция

[Часть 1](https://github.com/vpavlenko/mipt-ctf/tree/master/04-web).

Часть 2:
[pdf](https://github.com/vpavlenko/mipt-ctf/raw/master/05-web2/slides.pdf),
[online](https://docs.google.com/presentation/d/1yyzmHGmIHnEbWAK33q89TD6w77rNeeXTyEczSemNuT8/edit?usp=sharing),
[screencast](https://www.youtube.com/watch?v=BTk9w6G1KVg).

[Часть 3](https://github.com/vpavlenko/mipt-ctf/tree/master/06-web3).


## Задачи

Задачки взяты с [Security Override](http://securityoverride.org/) (требует регистрации) и [picoCTF 2014](https://picoctf.com/).

В задачках без условия нужно тем или иным образом добыть спрятанный на сайте флаг.

<!--
### injection1

http://web2014.picoctf.com/injection1/

### injection2

http://web2014.picoctf.com/injection2/
-->

### sql0

http://securityoverride.org/challenges/basic/8/

Задачка для разминки, флаг отправлять не нужно.

### sql1

https://2013.picoctf.com/problems/php3/

### sql2*

http://securityoverride.org/challenges/basic/12/index.php?id=1

[Hint 1.](http://securityoverride.org/challenges/basic/12/index.php?id=1 union select 1, 2, 3, 4 --)

[Hint 2.](http://www.mssqltips.com/sqlservertutorial/196/informationschematables/)

### sql3*

http://web2014.picoctf.com/injection3/

Перед тем, как решать эту задачку, рекомендуется решить предыдущую.

### sql4*

http://web2014.picoctf.com/injection4/

[Hint 1.](http://web2014.picoctf.com/injection4/register.phps)

[Hint 2.] (http://www.w3schools.com/sql/sql_like.asp)

### sql5\*\*

https://2013.picoctf.com/problems/php4/

### xss1

http://securityoverride.org/challenges/basic/14/

Флагом является первое\_второе\_и\_третье\_слово в тексте, который показывается после решения задачки.

### xss2

The bad guys have hidden their access codes on an [anonymous secure page service](http://sps.picoctf.com/). Our intelligence tells us that the codes was posted on a page with id 43440b22864b30a0098f034eaf940730ca211a55, but unfortunately it's protected by a password, and only site moderators can view the post without the password. Can you help us recover the codes?


## Флаги

Отправлять флаги на сервер таким образом:
```
$ nc andreyknvl.com 9994
username taskname 73c0487d1b4c9326bc4ec5ac09bf69eb
```
где username - имя для таблицы результатов, а taskname - название задачи.

Доступна [таблица результатов](https://andreyknvl.com/mipt-ctf).


## Дополнительные задачи

https://picoctf.com/problems

http://securityoverride.org/challenges/

https://xss-game.appspot.com/


## Материалы

https://github.com/vpavlenko/ctf-web-tasks

http://www.madit.ie/mutillidae/index.php?page=sqlmap-targets.php

https://www.youtube.com/watch?v=vTB3Ze901pM
