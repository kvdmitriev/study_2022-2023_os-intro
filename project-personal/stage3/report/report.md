---
## Front matter
title: "Отчёт по индивидуальному проекту"
subtitle: "Часть 3"
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

Создать индивидуальный сайт, постепенно его заполняя [@tuis; @github]

# Задание

Добавить к сайту достижения.  
Добавить информацию о навыках (Skills).  
Добавить информацию об опыте (Experience).  
Добавить информацию о достижениях (Accomplishments).  
Сделать пост по прошедшей неделе.  
Добавить пост на тему по выбору.

## Выполнение работы

Заполним информацию о навыках в файле _index.md (рис. [-@fig:001])

![Заполнение информации о навыках](image/1.png){#fig:001}

Так это будет выглядеть на сайте (рис. [-@fig:002])

![Вид информации о навыках](image/2.png){#fig:002}

Добавим там же информацию об опыте (рис. [-@fig:003])

![Заполнение информации об опыте](image/3.png){#fig:003}

Так это выглядит (рис. [-@fig:004])

![Вид информации об опыте](image/4.png){#fig:004}

Заполним информацию о достижениях (рис. [-@fig:005])

![Заполнение информации о достижениях](image/5.png){#fig:005}

Так это выглядит на сайте (рис. [-@fig:006])

![Вид информации о достижениях](image/6.png){#fig:006}

Напишем пост о прошедшей неделе (рис. [-@fig:007])

![Пост о прошедшей неделе](image/7.png){#fig:007}

И пост о LaTeX (рис. [-@fig:008])

![Пост о LaTeX](image/8.png){#fig:008}

# Выводы

В результате работы была добавлена информация о навыках и опыте автора, а также написано 2 поста

# Список литературы{.unnumbered}

::: {#refs}
:::
