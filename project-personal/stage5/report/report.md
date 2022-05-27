---
## Front matter
title: "Отчёт по индивидуальному проекту часть 5."
subtitle: " Добавление к сайту остальных элементов "
author: "Егина Ангелина НБИбд-01-21"

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

Научиться добавлять элементы

# Задание

Сделать записи для персональных проектов.
Сделать пост по прошедшей неделе.
Добавить пост на тему по выбору.
-Языки научного программирования.

# Выполнение лабораторной работы

![](image/1.png)

Захожу в папку для создания постов, и начинаю добавлять новую папку с названием языка программирования С++.
Редактирую и сохраняю.

![](image/2.png)

Добавила картинку. 

Снова создаю новую папку в папке постов, которая будет называться "Моя прошедшая неделя". Редактирую и сохраняю.

![](image/3.png)

Добавляю картинку по главной теме о моей неделе.

![](image/4.png)

После я захожу в папку где создаются проекты. И начинаю менять название папки example на Спорт и ЗОЖ. Захожу в файл мд и начинаю редакцию, добавляю картинку, сохраняю.

![](image/5.png)

Захожу в главную папку и открываю её в терминале, нажимаю команду hugo server для обновления и выдачи ссылки на мой сайт.

![](image/6.png)

Захожу на сайт, убеждаюсь, что всё получилось:

![](image/7.png)

![](image/8.png)

![](image/9.png)

# Выводы

Я научилась добавлять элементы на сайт.
