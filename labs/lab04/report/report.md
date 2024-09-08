---
## Front matter
title: "Лабораторная работа №4"
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

Получение навыков правильной работы с репозиториями git [@tuis]

# Задание

Выполнить работу для тестового репозитория.
Преобразовать рабочий репозиторий в репозиторий с git-flow и conventional commits.

# Выполнение лабораторной работы

Для начала подключим репозиторий, из которого можно скачать gitflow (рис. [-@fig:001]).

![Подключение репозитория](image/1.png){#fig:001}

После этого установим сам gitflow (рис. [-@fig:002]).

![Установка gitflow](image/2.png){#fig:002}

Теперь установим NodeJs (рис. [-@fig:003]).

![Установка NodeJs](image/3.png){#fig:003}

Установим pnpm (рис. [-@fig:004]).

![Установка pnpm](image/4.png){#fig:004}

Запустим pnpm (рис. [-@fig:005]).

![Запуск pnpm](image/5.png){#fig:005}

И установим с помощью него Commitizen (рис. [-@fig:006]).

![Установка Commitizen](image/6.png){#fig:006}

Создадим тестовый репозиторий git-extended (рис. [-@fig:007]).

![Создание тестового репозитория](image/7.png){#fig:007}

И клонируем его себе на компьютер (рис. [-@fig:008]).

![Клонирование репозитория](image/8.png){#fig:008}

Создадим какой-нибудь файл и проиндексируем его с помощью git add (рис. [-@fig:009]).

![Создание файла в репозитории и индексирование](image/9.png){#fig:009}

Теперь сделаем соответствующий коммит (рис. [-@fig:010]).

![Создание коммита](image/10.png){#fig:010}

И добавим ветку (рис. [-@fig:011]).

![Добавление ветки](image/11.png){#fig:011}

Теперь запушим её обратно на гитхаб (рис. [-@fig:012]).

![Загрузка изменений на ГитХаб](image/12.png){#fig:012}

Теперь проинициализируем pnpm (рис. [-@fig:013]).

![Инициализация pnpm](image/13.png){#fig:013}

После инициализации создастся файл package.json, который нужно изменить следующим образом (рис. [-@fig:014]).

![Редактирование файла package.json](image/14.png){#fig:014}

Сделаем коммит, но уже с помощью cz (рис. [-@fig:015]).

![Создание коммита с помощью cz](image/15.png){#fig:015}

Загрузим изменения на гитхаб (рис. [-@fig:016]).

![Загрузка изменений на GitHub](image/16.png){#fig:016}

Теперь проинициализируем gitflow. Укажем названия веток и префикс для версий (рис. [-@fig:017]).

![Инициализация GitFlow](image/17.png){#fig:017}

Выведем список веток и убедимся, что мы находимся в develop, и запушим изменения на сервер (рис. [-@fig:018]).

![Просмотр веток и загрузка изменений](image/18.png){#fig:018}

Переключимся на ветку develop, после чего создадим ветку релиза, где создадим changelog (рис. [-@fig:019]).

![Смена ветки и создание ветки релиза, и создание Changelog](image/19.png){#fig:019}

Проиндексируем changelog и сделаем коммит (рис. [-@fig:020]).

![Создание коммита с changelog](image/20.png){#fig:020}

Теперь сольём ветку release с веткой develop (рис. [-@fig:021]).

![Слияние веток](image/21.png){#fig:021}

Загрузим изменения в гитхаб (рис. [-@fig:022]).

![Загрузка изменений на GitHub](image/22.png){#fig:022}

Создадим релиз из changelog'а (рис. [-@fig:023]).

![Создание релиза](image/23.png){#fig:023}

Создадим ветку feature и сразу сольём её с develop (рис. [-@fig:024]).

![Создание ветки feature и её слияние](image/24.png){#fig:024}

Создадим ветку релиза (рис. [-@fig:025]).

![Создание ветки релиза](image/25.png){#fig:025}

И в package.json сменим версию (рис. [-@fig:026]).

![Изменение версии](image/26.png){#fig:026}

Теперь создадим журнал изменений, проиндексируем его и сольём ветку с ним в ветку develop (рис. [-@fig:027]).

![Создание журнала изменений, его индексация и объединение с основной веткой](image/27.png){#fig:027}

Загрузим изменения в гитхаб и создадим релиз (рис. [-@fig:028]).

![Загрузка изменений в гитхаб и создание релиза](image/28.png){#fig:028}

# Выводы

В результате выполнения лабораторной работы были получены навыки работы с расширенными возможностями git, а также были созданы релизы к репозиторию и дополнительные ветки, которые автор научился сливать воедино

# Список литературы{.unnumbered}

::: {#refs}
:::
