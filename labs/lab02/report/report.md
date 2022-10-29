---
## Front matter
title: "Отчёт по лабораторной работе 2"
subtitle: "Приобритение практических навыков с системой git"
author: "Носков В.И. НБИбд-02-22"

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

Изучить идеологию и применение средств контроля
версий. Приобрести практические навыки по работе с системой git.


# Выполнение лабораторной работы

1)Установил VirtualBox
2)Зарегистрировался на github
3)Сделал предварительную конфигурацию git. Открыл терминал и ввёл
следующие команды, указав имя
и email владельца репозитория:
4) Настроил utf-8 в выводе сообщений git:
5) Задал имя начальной ветки (будем называть её master):
6) Параметр autocrlf:
7) Параметр safecrlf:
8) Для последующей идентификации пользователя на сервере
репозиториев сгенерировал пару ключей (приватный и открытый):
9) Далее загрузил сгенерированный открытый ключ. Для этого зайшёл на
сайт http://github.org/ под своей учётной записью и перешёл в меню Setting
. После этого выберал в боковом меню SSH and GPG keys и нажмал
кнопку New SSH key . Скопировав из локальной консоли ключ в буфер
обмена.
10) Создал каталог для предмета “Архитектура компьютера”
11) Перешёл на станицу репозитория с шаблоном курса
https://github.com/yam adharma/course-directory-student-template.
Далее выберал Use this template.
В открывшемся окне задал имя репозитория (Repository name) study_2022–
2023_arh-pc и создал репозиторий (кнопка Create repository from template).
12) Открыл терминал и перешёл в каталог курса:
13) Клонировал созданный репозиторий:
14) Перешёл в каталог курса:
15) Удалил лишние файлы:
16) Создал необходимые каталоги:
17) Отправил файлы на сервер:
18) Проверил правильность создания иерархии рабочего пространства в
локальном репозитории и на странице github.
19) Загрузил отчёт по первой лабораторной работе на github
20) Загрузил отчёт по второй лабораторной работе на github

# Выводы

В ходе выполнения лабораторной работы, я изучил идеологию
и применение средств контроля версий. Приобрел практические
навыки по работе с системой git.
