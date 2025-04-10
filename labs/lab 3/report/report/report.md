---
## Front matter
title: "Индивидуальный проект. Часть 3"
subtitle: "Основы информационной безопасности"
author: "Перегудов Александр Вадимович"

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

Целью данной работы - приобретение навыков по использованию hydra.

# Задание

# Теоретическое введение

# Выполнение лабораторной работы

Запустил apache для работы сайта DVWA. (рис. @fig:001, @fig:005)

![Запуск сервиса для apache](image/1.png){#fig:001 width=70%}

![Форма для брутфорса сайта DVWA](image/5.png){#fig:005 width=70%}

Перешёл в папку со списком распростронённых паролей и разархивировал этот список. (рис. @fig:002)

![Разархивация](image/2.png){#fig:002 width=70%}

Запустил hydra с нужными параметрами для брутфорса и получил правильный пароль. (рис. @fig:003, @fig:004)

![Запуск и работа hydra](image/3.png){#fig:003 width=70%}

![Результат работы и правильные данные для входа](image/4.png){#fig:004 width=70%}

# Выводы

В данной лаборатной работе были приобретены практические навыки по использованию hydra.

# Список литературы{.unnumbered}

::: {#refs}
:::
