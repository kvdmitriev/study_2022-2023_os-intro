---
## Front matter
title: "Лабораторная работа №5"
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

Научиться пользоваться pass и chezmoi [@tuis]

# Задание

Настроить ОС, синхронизируя её с данной.  
Научиться использовать программы для управления паролями 

# Выполнение лабораторной работы

Для начала необходимо скачать pass и pass-opt (рис. [-@fig:001])

![Установка pass и pass-opt](image/1.png){#fig:001}

Уставновим gopass (рис. [-@fig:002])

![Установка gopass](image/2.png){#fig:002}

Выведем список pgp ключей (рис. [-@fig:003])

![Список ключей](image/3.png){#fig:003}

Проинициализируем pass, указав свой email (рис. [-@fig:004])

![Инициализация pass](image/4.png){#fig:004}

Проинициализируем репозиторий в git для pass (рис. [-@fig:005])

![Инициализация репозитория pass](image/5.png){#fig:005}

Создадим репозиторий pass (рис. [-@fig:006])

![Создание репозитория pass](image/6.png){#fig:006}

Пробуем получить данные (рис. [-@fig:007])
 
![Неудачный git pull](image/7.png){#fig:007}

Но не получаем, так как репозиторий пуст. Выложим изменения на Github (рис. [-@fig:008])
 
![Пушим данные на Github](image/8.png){#fig:008}

Теперь снова пробуем получить данные (рис. [-@fig:009])
 
![Проверяем актуальность](image/9.png){#fig:009}

Сделаем пустой коммит и выложим его (рис. [-@fig:010])
 
![Делаем пустой коммит и пушим](image/10.png){#fig:010}

Проверим статус pass репозитория (рис. [-@fig:011])
 
![Проверяем состояние pass](image/11.png){#fig:011}

Подключим репозиторий для скачивания browserpass (рис. [-@fig:012])
 
![Подключение репозитория пля скачивания](image/12.png){#fig:012}

Установим browserpass (рис. [-@fig:013])
 
![Скачивание browserpass](image/13.png){#fig:013}

и установим его в браузере (рис. [-@fig:014])
 
![Установка browserpass в браузере](image/14.png){#fig:014}

Создадим файл с паролем (рис. [-@fig:015])
 
![Создание файла с паролем](image/15.png){#fig:015}

И установим дополнительные пакеты (рис. [-@fig:016])
 
![Установка дополнительных пакетов](image/16.png){#fig:016}

Подключим репозиторий для скачивания шрифтов (рис. [-@fig:017])
 
![Подключение репозитория пля скачивания](image/17.png){#fig:017}

Найдём шрифты (рис. [-@fig:018])
 
![Поиск шрифтов](image/18.png){#fig:018}

И установим (рис. [-@fig:019])
 
![Установка шрифтов](image/19.png){#fig:019}

Установим chezmoi (рис. [-@fig:020])
 
![Установка Chezmoi](image/20.png){#fig:020}

Создадим репозиторий из шаблона (рис. [-@fig:021])
 
![Создание репозитория](image/21.png){#fig:021}

проинициализируем chezmoi, указав только что созданный репозиторий (рис. [-@fig:022])
 
![Инициализация Chezmoi](image/22.png){#fig:022}

Посмотрим на изменения (рис. [-@fig:023])
 
![Проверка изменений](image/23.png){#fig:023}

И согласимся с ними (рис. [-@fig:024])
 
![Соглашение с изменениями](image/24.png){#fig:024}

Проинициализируем Chezmoi на второй машине (рис. [-@fig:025])
 
![Инициализация Chezmoi на второй машине](image/25.png){#fig:025}

Посмотрим на изменения (рис. [-@fig:026])
 
![Проверка изменений](image/26.png){#fig:026}

И согласимся с ними (рис. [-@fig:027])
 
![Соглашение с изменениями](image/27.png){#fig:027}

Обновим изменения (рис. [-@fig:028])
 
![Обновление изменений](image/28.png){#fig:028}

Согласимся с ними (рис. [-@fig:029])
 
![Соглашение с изменениями](image/29.png){#fig:029}

Извлечём изменения из репозитория (рис. [-@fig:030])
 
![Извлечение изменений из репозитория](image/30.png){#fig:030}

И отредактируем конфигурационный файл, чтобы автоматически фиксировать и отправлять изменения в исходный каталог в репозиторий (рис. [-@fig:031])
 
![Редактирование конфигурационного файла](image/31.png){#fig:031}

# Выводы

В результате выполнения лабораторной работы были настроены программы для управления паролями, а также появился навык синхронизации настроек ОС

# Список литературы{.unnumbered}

::: {#refs}
:::
