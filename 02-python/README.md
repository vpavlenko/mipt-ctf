Python
======

## Лекция

Слайды: [pdf](https://github.com/vpavlenko/mipt-ctf/raw/master/02-python/slides.pdf), [online](https://docs.google.com/presentation/d/1IW5U1NL72mr6dadC7Uq5Q3Fo_06dDuvyM_8Zwe3_cvc/edit#slide=id.p).

Часть 1: примеры
[1](https://github.com/vpavlenko/mipt-ctf/blob/master/02-python/examples/examples_1.py),
[2](https://github.com/vpavlenko/mipt-ctf/blob/master/02-python/examples/examples_2.py),
[3](https://github.com/vpavlenko/mipt-ctf/blob/master/02-python/examples/examples_3.py),
[4](https://github.com/vpavlenko/mipt-ctf/blob/master/02-python/examples/examples_4.py).

Часть 2: [скринкаст](https://www.youtube.com/watch?v=O6bT3oEAbfA).

## Задачи

### Simple

Флагом является ввод, при котором [программа](https://github.com/vpavlenko/mipt-ctf/blob/master/02-python/tasks/simple.py) печатает "Success!".

### Bitwise

Флагом является ввод, при котором [программа](https://github.com/vpavlenko/mipt-ctf/blob/master/02-python/tasks/bitwise.py) печатает "Success".

Задача взята из [picoCTF 2013](https://2013.picoctf.com).

### Eval

Набор задачек на эксплуатацию уязвимостей в сервисах, использующих функцию eval.

В задачах 1 и 2 нужно узнать значение переменной flag.
В задачах 3, 4 и 5 нужно получить доступ к консоли и прочитать флаг из файла.


Eval 1: [условие](https://2013.picoctf.com/problems/pyeval/stage1.html), [исходник](https://github.com/vpavlenko/mipt-ctf/blob/master/02-python/tasks/eval1.py), флаг брать здесь:
```
nc python.picoctf.com 6361
```

Eval 2: [условие](https://2013.picoctf.com/problems/pyeval/stage2.html), [исходник](https://github.com/vpavlenko/mipt-ctf/blob/master/02-python/tasks/eval2.py), флаг брать здесь:
```
nc python.picoctf.com 6362
```

Eval 3: [условие](https://2013.picoctf.com/problems/pyeval/stage3.html), [исходник](https://github.com/vpavlenko/mipt-ctf/blob/master/02-python/tasks/eval3.py), флаг брать здесь:
```
nc python.picoctf.com 6363
```

Eval 4: [условие](https://2013.picoctf.com/problems/pyeval/stage4.html), [исходник](https://github.com/vpavlenko/mipt-ctf/blob/master/02-python/tasks/eval4.py), флаг брать здесь:
```
nc python.picoctf.com 6364
```

Eval 5: [исходник](https://github.com/vpavlenko/mipt-ctf/blob/master/02-python/tasks/eval5.py), флаг брать здесь:
```
nc python.picoctf.com 6365
```

Задачи взяты из [picoCTF 2013](https://2013.picoctf.com).

### QR Code

Условие задачи [здесь](https://github.com/vpavlenko/mipt-ctf/tree/master/02-python/tasks/qrcode).


## Флаги

Отправлять флаги на сервер таким образом:
```
$ nc andreyknvl.com 9997
username taskname 73c0487d1b4c9326bc4ec5ac09bf69eb
```
где username - имя для таблицы результатов, а taskname - название задачи.

Доступна [таблица результатов](https://andreyknvl.com/mipt-ctf).


## Дополнительные задачи

### Python

1. [Контест](http://93.175.29.91:8202/cgi-bin/new-register?contest_id=300204).

2. Смотреть задачи [здесь](https://github.com/vpavlenko/startup-engineering/tree/gh-pages/python-bis) и [здесь](https://github.com/vpavlenko/web-programming/tree/gh-pages/03-python).

3. https://projecteuler.net/

4. http://www.pythonchallenge.com/

### CTF

1. Сделать [задачки по башу](https://github.com/vpavlenko/mipt-ctf/tree/master/01-bash) с помощью Питона.

2. Распаковать [архив](https://github.com/vpavlenko/mipt-ctf/blob/master/02-python/tasks/brute.zip). Пароль словарный.

3. Расшифровать [текст](https://github.com/vpavlenko/mipt-ctf/blob/master/02-python/tasks/encrypted.txt). Для зашифровки использовался шифр простой замены.

4. Задачки категории exploit с [Moscow CTF School 2014](http://ctf.cs.msu.ru:9911/index).

5. [Задачка](https://github.com/vpavlenko/mipt-ctf/blob/master/02-python/tasks/exec.py) с [CSAW CTF 2014](https://ctf.isis.poly.edu/).


## Разбор задач

[Тут](https://github.com/vpavlenko/mipt-ctf/wiki/Writeup:-python).


## Материалы

https://docs.python.org/2/library/index.html

https://github.com/vpavlenko/startup-engineering/tree/gh-pages/python-bis

https://github.com/vpavlenko/web-programming/tree/gh-pages/03-python

http://www.slideshare.net/MattHarrison4/learn-90

https://en.wikipedia.org/wiki/Eval#Python
