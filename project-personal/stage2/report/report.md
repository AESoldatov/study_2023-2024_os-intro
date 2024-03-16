---
## Front matter
title: "Индивидуальный проект"
subtitle: "Часть 2"
author: "Солдатов Алексей"

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

# Актуальность

Сайт с портфолио нужен для дальнейшего продвижения в научной сфере

# Выполнение проекта

Запускаю hugo server через терминал (рис. [-@fig:001]).

![hugo server](image/1.png){#fig:001 width=70%}

Перехожу в папку "~/work/Project/content/authors/admin" и обновляю аватар (рис. [-@fig:002]).

![avatar](image/2.png){#fig:002 width=70%}

В файле "_index.md" расписываю информацию о себе (рис. [-@fig:003], [-@fig:004]).

![_index.md](image/3.png){#fig:003 width=70%}

![_index.md](image/4.png){#fig:004 width=70%}

Перехожу в папку "~/work/Project/content/post" и добавляю два поста по заданию из туис (рис. [-@fig:005]).

![post](image/5.png){#fig:005 width=70%}

Прописываю первый пост (Как прошла неделя) (рис. [-@fig:006]).

![Описание недели](image/6.png){#fig:006 width=70%}

Прописываю второй пост (Управление версиями git) (рис. [-@fig:007]).

![Управление версиями git](image/7.png){#fig:007 width=70%}

Прописываю команду hugo в терминале, добавляю, коммичу и отправляю файлы из папки проекта (рис. [-@fig:008]).

![hugo](image/8.png){#fig:008 width=70%}

Добавляю, коммичу и отправляю файлы из папки public (рис. [-@fig:009]).

![public](image/9.png){#fig:009 width=70%}

Проверяю на правильность выполнения (рис. [-@fig:010]).

![Проверка](image/10.png){#fig:010 width=70%}

# Выводы

Выполнил второй этап индивидуального проекта

# Список литературы{.unnumbered}

::: {#refs}
:::
