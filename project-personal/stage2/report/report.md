---
## Front matter
title: "Второй этап индивидуального проекта по дисциплине "
subtitle: "Операционные системы"
author: "Хамдамова Айжана"

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

Добавить к сайту информацию о себе.
Разместить фотографию владельца сайта, краткое описание о себе и о своих интересах.
Сделать пост о прошедшей неделе и пост на тему по выбору.


# Выполнение лабораторной работы

Фото должно находиться в папке "admin"

![фото для аватарки](image/1.png)

Заходим в папку blog и набираем команду 'hugo server', чтобы запустить файл hugo
В треминале появится ссылка на localhost

![команда hugo server](image/2.png)

Открываем и меняем информацию в _index.md

![Редактирование](image/5.png)

![Редактирование информации о себе](image/3.png)

Запускаем команду git в 2х папках.

![public](image/6.png)

Пишем 2 поста в соответсвующих маркдауновсих файлах. 

![пост о прошедшей неделе и github](image/7.png)

Cобирается сайт

![hugo](image/8.png)

Коммитнем все на гитхаб

![](image/9.png)


Заходим на наш сайт и видим изменения. 


![результат](image/10.png)

![пост о прошедшей неделе и github](image/11.png)



# Выводы

Я научилась редактировать информацию на сайте, смогла редактировать файлы и коммитнуть на гитхаб

# Список литературы{.unnumbered}

::: {#refs}
:::
