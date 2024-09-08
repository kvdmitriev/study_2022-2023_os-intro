---
## Front matter
title: "Лабораторная работа №13"
subtitle: "Отчёт"
author: "Дмитриев Владимир Константинович"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Изучить основы программирования в оболочке ОС UNIX. Научится писать более сложные командные файлы с использованием логических управляющих конструкций и циклов. [@tuis]

# Задание

1. Используя команды getopts grep, написать командный файл, который анализирует командную строку с ключами, а затем ищет в указанном файле нужные строки, определяемые ключом -p.
2. Написать на языке Си программу, которая вводит число и определяет, является ли оно больше нуля, меньше нуля или равно нулю. Затем программа завершается с помощью функции exit(n), передавая информацию в о коде завершения в оболочку. Командный файл должен вызывать эту программу и, проанализировав с помощью команды $?, выдать сообщение о том, какое число было введено.
3. Написать командный файл, создающий указанное число файлов, пронумерованных последовательно от 1 до N (например 1.tmp, 2.tmp, 3.tmp,4.tmp и т.д.). Число файлов, которые необходимо создать, передаётся в аргументы командной строки. Этот же командный файл должен уметь удалять все созданные им файлы (если они существуют).
4. Написать командный файл, который с помощью команды tar запаковывает в архив все файлы в указанной директории. Модифицировать его так, чтобы запаковывались только те файлы, которые были изменены менее недели тому назад (использовать команду find).

# Выполнение лабораторной работы

Напишем код первой программы (рис. [-@fig:001]).

![Код первой программы](image/1.png){#fig:001}

И проверим работу (рис. [-@fig:002]).

![Проверка работы первой программы](image/2.png){#fig:002}

Напишем код второй программы на С (рис. [-@fig:003]).

![Код второй программы на С](image/3.png){#fig:003}

И напишем код второй программы (рис. [-@fig:004]).

![Код второй программы](image/4.png){#fig:004}

И проверим работу (рис. [-@fig:005]).

![Проверка работы второй программы](image/5.png){#fig:005}

Напишем код третьей программы (рис. [-@fig:006]).

![Код третьей программы](image/6.png){#fig:006}

И проверим работу (рис. [-@fig:007]).

![Проверка работы третьей программы](image/7.png){#fig:007}

Напишем код четвёртой программы (рис. [-@fig:008]).

![Код четвёртой программы](image/8.png){#fig:008}

И проверим работу (рис. [-@fig:009]).

![Проверка работы четвёртой программы](image/9.png){#fig:009}

# Выводы

В результате лабораторной работы появились навыки обработки аргументов командной строки и написаны 4 программы

# Список литературы{.unnumbered}

::: {#refs}
:::
