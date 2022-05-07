---
## Front matter
title: " Отчёт по индивидуальному проекту №2"
subtitle: "Добавление к сайту данных о себе"
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

Научиться добавлять данные в сайт.

# Задание

1. Список добавляемых данных:
1.1. Разместить фотографию владельца сайта.
1.2. Разместить краткое описание владельца сайта (Biography).
1.3. Добавить информацию об интересах (Interests).
1.4. Добавить информацию от образовании (Education).

2. Сделать пост по прошедшей неделе.

3. Добавить пост на тему по выбору:
3.1. Управление версиями. Git.
3.2. Непрерывная интеграция и непрерывное развертывание (CI/CD).

# Выполнение лабораторной работы

1. Я захожу через Домашний каталог в папку work ,затем в папку gelya, после в content , затем в authors и наконец в admin.

2. Открываю _index.md и начинаю редактировать его под себя.
- поменяла имя
- поменяла роль
- поменяла место учёбы
- зашла в интернет и скопировала ссылку своего университета
- начала писать свою автобиографию
- написала про свои интересы

![](image/1.png)

![](image/2.png)

![](image/5.png)

3. Вышла из текстового редактора и поменяла аватарку для своего сайта

![](image/3.png)

4. По ходу работы я создала папку lastweek-post

![](image/4.png)
4.1. Начала создавать пост о том, как я провела прошлую недедю

![](image/16.png)

5. Создала папку Git-post

![](image/4.png)

5.1. Готовые материалы я скопировала с интернета и вставила в текстовый документ _index.md

![](image/6.png)

6. После всего, я открыла терминал и ввела необходимые команды, для реализации готовой ссылки

![](image/7.png)

![](image/8.png)

![](image/9.png)

![](image/10.png)

7. перехожу по ссылки, заходя в Гитхаб, и убеждаюсь в корректности выполнения рботы.

![](image/11.png)

![](image/12.png)

![](image/13.png)

![](image/14.png)

![](image/15.png)

Убедилась, что у меня всё получилось и выхожу с сылки.

# Выводы

Я научилась добавлять данные в свой сайт.
