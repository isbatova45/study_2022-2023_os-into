---
## Front matter
title: "Отчёт по индивидуальному проекту. Этап 4"
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

Целью четвертого этапа индивидуального проекта является добавление к сайту ссылок на научные и библиометрические ресурсы, а также публикация новых постов.

# Задание

1. Добавить к сайту ссылки на научные и библиометрические ресурсы.

2. Сделать пост по прошедшей неделе.
    
3. Добавить пост на тему по выбору:

* Оформление отчёта.
* Создание презентаций.
* Работа с библиографией.

# Выполнение лабораторной работы

1. Для отслеживания изменений на сайте на локальном компьютере переходим в каталог '~/work/blog' и вводим командой 'hugo server' для получения ссылки на локальный сайт. После этого переходим в каталог '~/work/blog/content/authors/admin' и открываем файл '_index.md'.

Переходим к блоку 'social' и размещаем там ссылки на свои ресурсы. Я разместила ссылки на Youtube канал, Google Scholar и Github (рис. @fig:001).

![Размещение ссылок](image/1.png){#fig:001 width=70%}

2. Для создания поста вводим в терминал команду 'hugo new --kind post post/lastweek3' и переходим в каталог '~/work/blog/content/post', где у нас создался каталог с именем 'lastweek3'. Открываем каталог и в нем открываем файл 'index.md'.

Редактируем название, автора (admin), тэги (Academic) и категории (Demo) (рис. @fig:002).

![Информация о посте о прошедшей неделе](image/2.png){#fig:002 width=70%}

В конец файла вводим текст поста (рис. @fig:003).

![Текст поста о прошедшей неделе](image/3.png){#fig:003 width=70%}

3. Для создания поста по теме "Оформление отчета" вводим в терминал команду 'hugo new --kind post post/reportcreate' и переходим в каталог '~/work/blog/content/post', где у нас создался каталог с именем 'reportcreate'. Открываем каталог и в нем открываем файл 'index.md'.

Редактируем название, автора (admin), тэги (Academic) и категории (Demo) (рис. @fig:004).

![Информация о посте об оформлении отчета](image/4.png){#fig:004 width=70%}

В конец файла вводим текст поста (рис. @fig:005).

![Текст поста об оформлении отчета](image/5.png){#fig:005 width=70%}

После всех изменений вводим в каталоге blog 'hugo', после этого вводим последовательность команд 'git add .', 'git commit -am', 'git push' сначала в каталоге ~/work/blog, а потом в каталоге ~/work/blog/public. Заходим на наш сайт и проверяем, что все изменения были сохранены (рис. @fig:006, @fig:007).

![Ссылки на ресурсы](image/6.png){#fig:006 width=70%}

![Посты](image/7.png){#fig:007 width=70%}

# Выводы

В ходе четвертого этапа индивидуального проекта я добавила к сайту ссылки на научные и библиометрические ресурсы, а также опубликовала новые посты.
