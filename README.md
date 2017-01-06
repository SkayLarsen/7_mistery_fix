# Quadratic Equations Solver

Файл quadratic_equation.py содержит функцию решения квадратных уравнений. tests.py - набор тестов к ней.

# Quickstart

Скрипт требует для своей работы установленный интерпретатор Python версии 3.5



Описанная в файле quadratic_equation.py функция get_roots принимает три параметра - коэффициенты уравнения (a, b, c) и возвращает пару его корней. Если корень только один, вместо второго возвращается None. При отсустствии корней возрващается None вместо обоих корней. Для использования функции в стороннем файле, её необходимо предварительно импортировать (что и сделано в файле с тестами):
```
from quadratic_equation import get_roots
```
Запуск на Linux:

```#!bash

$ python tests.py

```
Запуск на Windows происходит аналогично.

Пример вывода скрипта:
```
....
----------------------------------------------------------------------
Ran 4 tests in 0.000s

OK
```

# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
