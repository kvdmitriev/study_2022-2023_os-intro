---
## Front matter
lang: ru-RU
title: Лабораторная работа №10
subtitle: Презентация
author:
  - Дмитриев В. К.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 12 марта 2024

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
 
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Дмитриев Владимир Константинович
  * Студент
  * Российский университет дружбы народов
  * [1132239400@pfur.ru](mailto:1132239400@pfur.ru)

:::
::: {.column width="30%"}

:::
::::::::::::::

## Цель

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах

## Задачи

Выполнить 2 задачи из файла лабораторной работы

## Создание каталога и файла в нём с помощью vi

Создадим каталог lab10, в котором с помощью vi создадим скриптовый файл hello.sh

![Создание каталога и файла в нём с помощью vi](image/1.png)

## Редактирование файла в vi

Файл сразу же откроется в vi. Перейдём с помощью клавиши i в режим вставки и вставим следующий текст. Далее, нажмём ":" и напишем wq для сохранения файла и выхода

![Редактирование файла в vi](image/2.png){height=50%}

## Задание исполняемости файла

Сделаем файл исполняемым 

![Задание исполняемости файла](image/3.png)

## Открытие файла

Снова откроем через vi наш файл

![Открытие файла](image/4.png)

## Изменение слова

С помощью стрелочек перейдём на конец слова HELLO и перейдём в режим вставки. Допишем букву "O"

![Изменение слова](image/5.png){height=50%}

## Замена слова

Теперь перейдём на 4ую строку, где заменим LOCAL на local

![Замена слова](image/6.png){height=50%}

## Вставка строки

Вствим в конец файла строчку

![Вставка строки](image/7.png){height=50%}

## Стирание слова

Теперь сотрём её 

![Стирание слова](image/8.png){height=50%}

## Отмена действия

Теперь перейдём в командный режим и нажмём "u", чтобы отменить последнее действие (стирание). Теперь сохраним с помощью :wq наш файл

![Отмена действия](image/9.png){height=50%}

## Выводы

В результате выполнения лабораторной работы были получаны навыки работы с текстовым редактором vi
