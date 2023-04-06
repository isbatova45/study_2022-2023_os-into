---
## Front matter
title: "Отчёт по индивидуальному проекту. Этап 3"
subtitle: "Дисциплина: Операционные системы"
author: "Батова Ирина Сергеевна, НММбд-01-22"

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

Целью третьего этапа индивидуального проекта является добавление к сайту навыков, опыта и достижений. 

# Задание

1. Список достижений:
* Добавить информацию о навыках (Skills).
* Добавить информацию об опыте (Experience).
* Добавить информацию о достижениях (Accomplishments).
    
2. Сделать пост по прошедшей неделе.
    
3. Добавить пост на тему по выбору:
* Легковесные языки разметки.
* Языки разметки. LaTeX.
* Язык разметки Markdown.

# Выполнение работы

1. Для отслеживания работы переходим в каталог '~/work/blog' и вводим командой 'hugo server' для получения ссылки на локальный сайт. После этого переходим в каталог '~/work/blog/content' и открываем файл '_index.md'.

Сначала добавляем информацию о навыках в блоке 'features' (рис. @fig:001).

![Навыки](image/1.png){#fig:001 width=70%}

Затем добавляем информацию об опыте в блоке 'experience' (рис. @fig:002).

![Опыт](image/2.png){#fig:002 width=70%}

После этого добавляем информацию о достижениях в блоке 'accomplishments' (рис. @fig:003).

![Достижения](image/3.png){#fig:003 width=70%}

2. Для создания поста вводим в терминал команду 'hugo new --kind post post/lastweek2' и переходим в каталог '~/work/blog/content/post', где у нас создался каталог с именем 'lastweek2'. Открываем каталог и в нем открываем файл 'index.md'.

Редактируем название, автора (admin), тэги (Academic) и категории (Demo) (рис. @fig:004).

![Информация о посте о прошедшей неделе](image/4.png){#fig:004 width=70%}

В конец файла вводим текст поста (рис. @fig:005).

![Текст поста о прошедшей неделе](image/5.png){#fig:005 width=70%}

3. Для создания еще одного поста вводим в терминал команду 'hugo new --kind post post/markdown' и переходим в каталог '~/work/blog/content/post', где у нас создался каталог с именем 'markdown'. Открываем каталог и в нем открываем файл 'index.md'.

Редактируем название, автора (admin), тэги (Academic) и категории (Demo) (рис. @fig:006).

![Информация о посте о языке разметки Markdown](image/6.png){#fig:006 width=70%}

В конец файла вводим текст поста (рис. @fig:007).

![Текст поста о языке разметки Markdown](image/7.png){#fig:007 width=70%}

# Выводы

В ходе третьего этапа индивидуального проекта я добавила к сайту навыки, опыт и достижения. 


