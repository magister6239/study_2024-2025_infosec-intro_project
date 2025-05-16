---
## Front matter
lang: ru-RU
title: Лабораторная работа № 5
subtitle: Операционные системы
author:
  - Перегудов А.В.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 16 марта 2024

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
  * <https://github.com/magister6239/study_2024-2025_infosec-intro_project>


## Объект и предмет исследования

- Burp Suite

## Цели и задачи

Целью данной работы - приобретение навыков по использованию Burp Suite.

## Материалы и методы

- Процессор `pandoc` для входного формата Markdown
- Результирующие форматы
	- `pdf`
	- `html`
- Автоматизация процесса создания: `Makefile`

![firefox proxy](image/1.png){#fig:001 width=70%}

Запустил Burp Suite. (рис. @fig:002, @fig:003, @fig:004, @fig:005)

![Запуск](image/2.png){#fig:002 width=70%}

![Burp Suite](image/3.png){#fig:003 width=70%}

![Burp Suite](image/4.png){#fig:004 width=70%}

![Запуск проекта Burp Suite](image/5.png){#fig:005 width=70%}

История запросов и ответов. (рис. @fig:006)

![История](image/6.png){#fig:006 width=70%}

Перехватил один из запросов для изменения перед отправкой дальше. (рис. @fig:007)

![Данные запроса и сам запрос](image/7.png){#fig:007 width=70%}

При перехвате запросов браузер будет ждать прокси. Таким образом страница будет загружатся бесконечно, пока прокси не отправит пакет дальше. (рис. @fig:008)

![Бесконечная загрузка](image/8.png){#fig:008 width=70%}

Intruder позволяет создавать и отправлять разные версии одного запроса. Это достигается заменой некоторых частей запроса. Нужно для того чтобы посмотреть как сервер реагирует на разную информацию (например, можно заменять мета данные или пароли в пост запросе.) (рис. @fig:009)

![Работа Intruder](image/9.png){#fig:009 width=70%}
