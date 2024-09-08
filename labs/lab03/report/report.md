---
## Front matter
title: "Лабораторная работа №3"
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

Научиться оформлять отчёты с помощью легковесного языка разметки Markdown. [@tuis]

# Задание

Сделать отчёт по предыдущей лабораторной работе в формате Markdown.  
В качестве отчёта предоставить отчёты в 3 форматах: pdf, docx и md (в архиве,
поскольку он должен содержать скриншоты, Makefile и т.д.)

# Выполнение лабораторной работы

Для начала необходимо открыть файл отчёта "report.md" для заполнения (рис. [-@fig:001])

![Открытие файла report.md](image/0.png){#fig:001}

Поменяем титульный лист, указав автора отчёта и его название (рис. [-@fig:002])

![Написание титульного листа](image/1.png){#fig:002}

Добавим в файл цель работы и задания (рис. [-@fig:003])

![Написание цели и задач](image/2.png){#fig:003}

И начнём копировать текст из предыдущего отчёта в файл markdown. При этом мы подписываем скриншоты, и иногда меняем их ширину и высоту. Также, мы обозначаем идентификаторы картинок (Решётка + fig:XXX), и ссылки на них ("-" + "@" + fig:XXX) (рис. [-@fig:004])

![Написание раздела "Выполнение лабораторной работы"](image/3.png){#fig:004}

Теперь откроем файл "cite.bib", в котором хранятся источники информации (рис. [-@fig:005])

![Открытие файла "cite.bib"](image/3_1.png){#fig:005}

Заполним его, указав в нём список литературы. В данном случае я укажу ссылку на ресурс в ТУИСе (рис. [-@fig:006])

![Заполнение файла с библиографией](image/4.png){#fig:006}

И добавим перекрёстную ссылку в тексе (рис. [-@fig:007])

![Добавление перекрёстных ссылок](image/5.png){#fig:007}

# Выводы

В результате выполнения лабораторной работы были получены навыки создания отчётов в формате .md

# Список литературы{.unnumbered}

::: {#refs}
:::
