---
## Front matter
lang: ru-RU
title: Отчет по лабораторной работе №2
subtitle: Дисциплина "Операционные системы"
author:
  - Батова Ирина Сергеевна
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 18 февраля 2023

## i18n babel
babel-lang: russian
babel-otherlangs: english

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

# Вводная часть

## Цель работы

Целью данной лабораторной работы является изучение идеологии и применение средств контроля версий, а также освоение умения по работе с git.

# Основная часть

## Установка git и gh 

- Для начала устанавливаем git и gh.
![](./image/1.jpg)
![](./image/2.jpg)

## Базовая настройка git

- Задаем имя и email владельца репозитория, далее настраиваем utf-8 в выводе сообщений git, а также задаем имя начальной ветки, параметр autorclf и параметр saferclf.
![](./image/3.jpg)

## Создание ssh-ключа

- Для этого используется команда “ssh-keygen -C”.
- В терминале вводим команду “cat ~/.ssh/id_rsa.pub | xclip -sel clip”, чтобы скопировать ключ и загружаем его на сайт через веб-браузер.
![](./image/5.jpg)

## Создание gpg-ключа

- Для этого заходим в терминал и вводим команду 'gpg --full-generate-key'. Выбираем необходимые опции и задаем пароль.
- После аналогично копируем ключ и загружаем на сайт.
![](./image/10.jpg)

## Настройка автоматических подписей коммитов git

![](./image/19.jpg)

## Создание репозитория и каталога курса

- Создаем необходимые каталоги
![](./image/22.jpg)

## Создание репозитория и каталога курса

- Создаем и клонируем репозиторий
![](./image/23.jpg)
![](./image/24.jpg)

## Создание репозитория и каталога курса

![](./image/26.jpg)

# Вывод

## Вывод

В данной лабораторной работе мной были изучены идеологии и применение средств контроля версий, а также освоены умения по работе с git.