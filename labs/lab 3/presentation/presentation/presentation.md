---
## Front matter
lang: ru-RU
title: Лабораторная работа № 1
subtitle: Основы информационной безопасности
author:
  - Перегудов А.В.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 22 февраля 2025

## i18n babel
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
---

# Информация

## Докладчик

  * Перегудов Александр Вадимович
  * Студент группы НКАбд-03-23
  * Российский университет дружбы народов
  * [1132239659@pfur.ru]
  * <https://github.com/magister6239/study_2024-2025_infosec-intro>

# Вводная часть

Установка операционной системы на виртуальную машину и подготовка её к работе

## Актуальность

- Установка операционной системы базовый навык.
- Первичная настройка необходима для работы с операционной системой.

## Объект и предмет исследования

- Rocky 9.5
- dmesg
- grep

## Цели и задачи

Получение навыков установки операционной системы и первичной настройки.

## Материалы и методы

- Процессор `pandoc` для входного формата Markdown
- Результирующие форматы
	- `pdf`
	- `html`
- Автоматизация процесса создания: `Makefile`

## hydra

Запустил apache для работы сайта DVWA. (рис. @fig:001, @fig:005)

![Запуск сервиса для apache](image/1.png){#fig:001 width=70%}

![Форма для брутфорса сайта DVWA](image/5.png){#fig:005 width=70%}

Перешёл в папку со списком распростронённых паролей и разархивировал этот список. (рис. @fig:002)

![Разархивация](image/2.png){#fig:002 width=70%}

Запустил hydra с нужными параметрами для брутфорса и получил правильный пароль. (рис. @fig:003, @fig:004)

![Запуск и работа hydra](image/3.png){#fig:003 width=70%}

![Результат работы и правильные данные для входа](image/4.png){#fig:004 width=70%}

