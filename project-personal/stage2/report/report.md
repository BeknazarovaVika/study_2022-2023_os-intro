---
## Front matter
title: "Индивидуальный проект"
subtitle: "Второй этап"
author: "Бекназарова Виктория Тиграновна"

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


Добавит к сайту данные о себе.


# Выполнение лабораторной работы

1. Размещаем фотографию владельца сайта,краткое описание владельца сайта, информацию об интересах и образовании (рис. @fig:001). (рис. @fig:002) (рис. @fig:003) (рис. @fig:004) (рис. @fig:005) (рис. @fig:006) (рис. @fig:007)

![Добавили имя](image/1.png){#fig:001 width=90%}


![Добавляем фотографию](image/2.png){#fig:002 width=90%}


![Информация об образовании](image/3.png){#fig:003 width=90%}


![Информация об интересах](image/4.png){#fig:004 width=90%}


![Информация о себе](image/5.png){#fig:005 width=90%}


![Информация о себе](image/6.png){#fig:006 width=90%}


![Информация о моих интересах](image/7.png){#fig:007 width=90%}

2. Делаем пост по прошедшей неделе (рис. @fig:008) (рис. @fig:009)


![файл md](image/8.png){#fig:008 width=90%}


![сайт](image/9.png){#fig:009 width=90%}


3. Делаем пост на тему " Управление версиями. Git." (рис. @fig:010) (рис. @fig:011)

![сайт](image/10.png){#fig:010 width=90%}


![файл md](image/11.png){#fig:011 width=90%}


# Выводы

Мы внесли изменения в личный сайт.


