---
## Front matter
title: "Индивидуальный проект. Часть 2"
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

Целью данной работы установка DVWA.

# Задание

# Теоретическое введение

# Выполнение лабораторной работы

Обновил пакеты. (рис. @fig:001)

![update](image/1.png){#fig:001 width=70%}

Установил PHP, MariaDB, apache2. (рис. @fig:002, @fig:003, @fig:004, @fig:005)

![MariaDB](image/2.png){#fig:002 width=70%}

![Apache](image/3.png){#fig:003 width=70%}

![PHP](image/4.png){#fig:004 width=70%}

![PHP](image/5.png){#fig:005 width=70%}

Запустил apache и mariadb. (рис. @fig:006)

![Выбор локации](image/6.png){#fig:006 width=70%}

Настройка mysql и установка пароля. (рис. @fig:007, @fig:008)

![Команда mysql_secure_installation](image/7.png){#fig:007 width=70%}

![Команда mysql_secure_installation](image/8.png){#fig:008 width=70%}

Скачал репозиторий DVWA с GitHub. (рис. @fig:009)

![Команда git clone](image/9.png){#fig:009 width=70%}

Изменил разрешения для папки DVWA. (рис. @fig:010)

![Команда chmod](image/10.png){#fig:010 width=70%}

Скопировал файл с шаблоном конфига (рис. @fig:011)

![Копирование](image/11.png){#fig:011 width=70%}

Выполняю несколько запросов в MariaDB и задаю пароль для подключения к базе данных. (рис. @fig:012, @fig:013)

![Команда для mysql для того чтобы отправлять запросы базе данных](image/12.png){#fig:012 width=70%}

![Запросы SQL](image/13.png){#fig:013 width=70%}

Изменил файл конфига DVWA. (рис. @fig:014, @fig:015)

![Открытие конфига с редактором nano](image/14.png){#fig:014 width=70%}

![Изменёный конфиг](image/15.png){#fig:015 width=70%}

Перезапускаю apache. (рис. @fig:016)

![Перезагрузка](image/16.png){#fig:016 width=70%}

Открываю браузер и ввожу локальный ip для подключения к сайту DVWA. (рис. @fig:017, @fig:018)

![IP](image/17.png){#fig:017 width=70%}

![Сайт](image/18.png){#fig:018 width=70%}

# Выводы

В данной лаборатной работе были приобретены практические навыки по установке операционной системы.

# Список литературы{.unnumbered}

::: {#refs}
:::
