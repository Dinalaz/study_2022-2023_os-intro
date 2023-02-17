---
## Front matter
title: "Лабораторная работа №2"
subtitle: "Операционные системы"
author: "Лазева Диана Анатольевна НБИбд-04-22"

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

Изучить идеологию и применение средств контроля версий.
Освоить умения по работе с git.


# Выполнение лабораторной работы


Задание

Создать базовую конфигурацию для работы с git.

Создать ключ SSH.

Создать ключ PGP.

Настроить подписи git.

Зарегистрироваться на Github.

Создать локальный каталог для выполнения заданий по предмету.

Последовательность выполнения работы

Базовая настройка git (рис. [-@fig:001])

![Зададим имя и email владельца репозитория](image/name.png){#fig:001 width=90%}

![Настроим utf-8 в выводе сообщений git] (image/kod.png){#fig:002 width=90%}

![Зададим имя начальной ветки (будем называть её master)] (image/master.png){#fig:003 width=90%}

![Параметр autocrlf и параметр safecrlf] (image/parametry.png) {#fig:004 width=90%}

Создаем ключи ssh

![SSH] (image/keys.png) {#fig:005 width=90%}

Создаем ключи pgp

![PGP] (image/gpg.png) {#fig:006 width=90%}

Добавление PGP ключа в GitHub

![Выводим список ключей и копируем отпечаток приватного ключа] (image/dobavl1.png) {#fig:007 width=90%}

![Перейдите в настройки GitHub, нажмите на кнопку New GPG key и вставьте полученный ключ в поле вводa] (image/dobavl2.png) {#fig:008 width=90%}

Настройка автоматических подписей коммитов git

![Используя введёный email, укажите Git применять его при подписи коммитов:] (image/podpisi.png) {#fig:009 width=90%}

Настройка gh

![авторизация] (image/auth/png) {#fig:010 width=90%}

Создание репозитория курса на основе шаблона

![создание репозитория] (image/sozdanie/png) {#fig:011 width=90%}

Настройка каталога курса

![настройка каталога курса] (image/last.png) {#fig:012 width=90%}



# Выводы
Я изучила идеологию и применение средств контроля версий, а так же освоила умения по работе с git.


# Список литературы{.unnumbered}

::: {#refs}
:::
