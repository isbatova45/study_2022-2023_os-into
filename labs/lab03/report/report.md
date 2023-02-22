---
## Front matter
title: "Отчёт по лабораторной работе №3"
subtitle: "Дисциплина 'Операционные системы'"
author: "Батова Ирина Сергеена, НММбд-01-22"

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

Целью данной лабораторной работы является научиться оформлять отчёты с помощью легковесного языка разметки Markdown.

# Выполнение лабораторной работы

Для создания отчета по лабораторной работе №2 переходим в соответствующий каталог и открываем файл 'report.md'.

В начале файла вносим номер лабораторной работы, по которой мы делаем отчет, в следующей строке указываем дисциплину "Операционные системы, в третье строке свои ФИО с номером группы (рис. @fig:001).

![Формирования титульного листа](image/1.jpg){#fig:001 width=70%}

Далее под заголовком "Цель работы" обозначаем нашу цель (рис. @fig:002).

![Цель работы](image/2.jpg){#fig:002 width=70%}

Далее под заголовком "Выполнение лабораторной работы" пошагово описываем наши действия, делая ссылки на изображения и вставляя их в файл (рис. @fig:003).

![Выполнение лабораторной работы](image/3.jpg){#fig:003 width=70%}

Важно проверить, что все необходимые изображения лежат в соответствующей папке 'image'.

После описания выполнения лабораторной работы под заголовком "Выводы" пишем вывод по данной лабораторной работе, который согласуется с целью работы (рис. @fig:004).

![Выводы](image/4.jpg){#fig:004 width=70%}

Последним шагом создаем заголовок "Контрольные вопросы" и, нумеруя их, отвечаем на поставленные в лабораторной работе вопросы (рис. @fig:005).

![Контрольные вопросы](image/5.jpg){#fig:005 width=70%}

Для создания неупорядоченного списка используем символ '*' (рис. @fig:006).

![Неупорядоченный список](image/6.jpg){#fig:006 width=70%}

# Выводы

В данной лабораторной работе я научилась оформлять отчёты с помощью легковесного языка разметки Markdown.
