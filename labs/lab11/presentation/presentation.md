---
## Front matter
lang: ru-RU
title: Лабораторная работа №11
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

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором Emacs 

## Задачи

Ознакомиться с теоретическим материалом.  
Ознакомиться с редактором emacs.  
Выполнить упражнения.  
Ответить на контрольные вопросы.

## Создание файла

Откроем emacs и через ctrl x ctrl f создадим новый файл lab07.sh

![Создание файла](image/1.png){height=30%}

## Вставка кода

Вставим в него следующий код 

![Вставка кода](image/2.png){height=30%}

## Вырезка строки

Вырежим строчку через C-k

![Вырезка строки](image/3.png){height=30%}

## Вставка строки

Теперь вставим её через C-y

![Вставка строки](image/4.png){height=30%}

## Выделение кода

Теперь выделим часть кода через C-space

![Выделение кода](image/5.png){height=30%}

## Копирование и вставка

Скопируем выделенный код через M-w и вставим через C-y 

![Копирование и вставка](image/6.png){height=30%}

## Вырезка

Теперь выделим эту область и вырежем её

![Вырезка](image/7.png){height=30%}

## Отмена последнего действия

Теперь отменим последнее действие через C-/

![Отмена последнего действия](image/8.png){height=30%}

## Список буферов

Через C-x C-b выведем список буферов

![Список буферов](image/9.png){height=30%}

## Переключение на другой буфер

Теперь переключимся на другой буфер

![Переключение на другой буфер](image/10.png){height=30%}

## Переход на другой буфер горячими клавишами

Закрытие буфера и переход на другой буфер через горячие клавиши C-x b 

![Переход на другой буфер горячими клавишами](image/11.png){height=30%}

## Деление фрейма

Делим фрейм на 4 части с помощью C-x 3 и C-x 2

![Деление фрейма](image/12.png){height=30%}

## Открытие 4ёх файлов

Создадим 4 файла, откроем их в 4ёх частях фрейма и напишем в них разный текст 

![Открытие 4ёх файлов](image/13.png){height=30%}

## Поиск слов

Поспользуемся поиском C-s 

![Поиск слов](image/14.png){height=30%}

## Замена слова

Перейдём в режим поиска и замены с помощью M-% и заменим слово world на peace

![Замена слова](image/15.png){height=30%}

## Альтернативный поиск

Используем другой режим поиска через M-s o. Он выводит в отдельном окне все вхождения слова

![Альтернативный поиск](image/16.png){height=30%}

## Выводы

В результате выполнения лабораторной работы были получены навыки работы с текстовым редактором emacs
