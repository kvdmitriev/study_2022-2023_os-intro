---
## Front matter
title: "Отчёт по индивидуальному проекту"
subtitle: "Часть 6"
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

Добавить англоязычную версию сайта

# Выполнение лабораторной работы

Создадим в папке content 2 папки с разными языками, куда скопируем все файлы (рис. [-@fig:001]).

![Папки](image/1.png){#fig:001}

Скачаем файлы конфигурации и переместим их в эти папки (рис. [-@fig:002]).

![Перемещение файлов конфигурации](image/2.png){#fig:002}

Редактирование конфига (рис. [-@fig:003]).

![Редактирование конфига](image/3.png){#fig:003}

Напишем пост о прошедшей неделе (рис. [-@fig:004]).

![Пост о прошедшей неделе](image/4.png){#fig:004}

Напишем пост про Linux (рис. [-@fig:003]).

![Пост про Linux](image/5.png){#fig:005}

Так выглядит англоязычная версия сайта (рис. [-@fig:006]).

![Англоязычная версия сайта](image/6.png){#fig:006}

Так выглядят посты (рис. [-@fig:007]).

![Вид постов](image/7.png){#fig:007}

# Выводы

В результате работы была добавлена англоязычная версия сайта

# Список литературы{.unnumbered}

::: {#refs}
:::
