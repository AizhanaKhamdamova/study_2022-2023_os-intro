---
## Front matter
lang: ru-RU
title: Структура научной презентации
subtitle: Простейший шаблон
author:
  - Хамдамова А. А.
institute:
  - Российский университет дружбы народов, Москва, Россия
  - Объединённый институт ядерных исследований, Дубна, Россия
date: 24 февраля 2023

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

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Хамдамова Айжана
  * студент Нкабд-05-22
  * Российский университет дружбы народов
  * [1032225989"pfur.ru](mailto:1032225989"pfur.ru)
  * <https://github.com/AizhanaKhamdamova/study_2022-2023_os-intro>

:::
::: {.column width="30%"}


:::
::::::::::::::

## Актуальность

- Важно донести результаты своих исследований до окружающих
- Научная презентация --- рабочий инструмент исследователя
- Необходимо создавать презентацию быстро
- Желательна минимизация усилий для создания презентации

## Объект и предмет исследования

- Презентация как текст
- Программное обеспечение для создания презентаций
- Входные и выходные форматы презентаций

## Цели и задачи

- Создать шаблон презентации в Markdown
- Описать алгоритм создания выходных форматов презентаций
- Оформить отчет в Markdown

## Формат `html`

- Используется фреймворк [reveal.js](https://revealjs.com/)
- Используется [тема](https://revealjs.com/themes/) `beige`

## Код для формата `html`

- Тема задаётся в файле `Makefile`

```make
REVEALJS_THEME = beige 
```
# Меняем название лабораторной,автора и дисциплины 

![Пример](image/3.png)

# Прописываем цели, выполнение работы, теоритическое введение

![Пример](image/2.png)

# Вставляем скриншоты в файл 

![Вставка изображения](image/4.png)

# Добавляем ссылки на рисунки

![Добавление ссылок на изображения](image/1.png)



## Получающиеся форматы

- Полученный `pdf`-файл можно демонстрировать в любой программе просмотра `pdf`
- Полученный `html`-файл содержит в себе все ресурсы: изображения, css, скрипты


## Актуальность
- Markdown значительно облегчает оформление работ
- Прост в использовании 


:::

