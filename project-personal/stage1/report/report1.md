---
## Front matter
title: "Первый этап проекта"
subtitle: "Операционные системы"
author: "Хамдамова Айжана НКАбд-05-22"

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

Цель работы- создание своего сайта и привязка его к репозиторию. 


# Выполнение лабораторной работы

Скачиваем файл hugo_extended_Linux_64bit.tar.gz (рис. @fig:001).

![необходимый файл hugo](image/1.png){#fig:001 width=70%}

Разархивируем данный файл(рис. @fig:002).

![Шаг2](image/2.png){#fig:002 width=70%}

Создание папки(рис. @fig:003).

![шаг3](image/3.png){#fig:003 width=70%}

Создаем еще одну папку в домашнем каталоге и задем название (рис. @fig:004).

![Шаг4](image/4.png){#fig:004 width=70%}

Создаем новый репозиторий (рис. @fig:005).

![Шаг5](image/5.png){#fig:005 width=70%}

Копируем и клонируем (рис. @fig:006).

![Шаг6](image/6.png){#fig:006 width=70%}

Клонируем в консоли(рис. @fig:007).

![Шаг7](image/7.png){#fig007: width=70%}

Запускаем файл хьюго в терминале (рис. @fig:008).

![Шаг8](image/8.png){#fig:008 width=70%}

Вводим команду ~/bin/hugo(рис. @fig:009).

![Шаг9](image/9.png){#fig:009 width=70%}

Запускаем сервер(рис. @fig:010).

![Шаг10](image/10.png){#fig:010 width=70%}

Создаем еще один репозиторий для нашего сайта(рис. @fig:011).

![Шаг11](image/11.png){#fig:011 width=70%}

Коммитнем наш репозиторий и нашу папку, создадим файл(рис. @fig:012).

![Шаг12](image/12.png){#fig:012 width=70%}

Создаем новую папку public(рис. @fig:013).

![Шаг13](image/14.png){#fig:013 width=70%}

запускаем и снова устанавливаем хьюго(рис. @fig:014).

![Шаг14](image/15.png){#fig:014 width=70%}

Вводим в поисковик наше имя репозитория(рис. @fig:015).

![Шаг15](image/16.png){#fig:015 width=70%}

Должен появиться наш сайт, который мы видели ранее(рис. @fig:016).

![Шаг16](image/17.png){#fig:016 width=70%}
# Выводы

За данный этап работы я приобрела навыки в работе с репозиториями на гитхабе, а так же с запуском файлов в рабочей папке

# Список литературы{.unnumbered}

::: {#refs}
:::
