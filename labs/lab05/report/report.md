---
## Front matter
title: "Лабораторная работа №5"
subtitle: "Настройка рабочей среды"
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

# Цель работы

Настроить рабочую среду

# Задание

Настроить рабочую среду

# Теоретическое введение

Здесь описываются теоретические аспекты, связанные с выполнением работы.

Например, в табл. [-@tbl:std-dir] приведено краткое описание стандартных каталогов Unix.

: Описание некоторых каталогов файловой системы GNU Linux {#tbl:std-dir}

| Имя каталога | Описание каталога                                                                                                          |
|--------------|----------------------------------------------------------------------------------------------------------------------------|
| `/`          | Корневая директория, содержащая всю файловую                                                                               |
| `/bin `      | Основные системные утилиты, необходимые как в однопользовательском режиме, так и при обычной работе всем пользователям     |
| `/etc`       | Общесистемные конфигурационные файлы и файлы конфигурации установленных программ                                           |
| `/home`      | Содержит домашние директории пользователей, которые, в свою очередь, содержат персональные настройки и данные пользователя |
| `/media`     | Точки монтирования для сменных носителей                                                                                   |
| `/root`      | Домашняя директория пользователя  `root`                                                                                   |
| `/tmp`       | Временные файлы                                                                                                            |
| `/usr`       | Вторичная иерархия для данных пользователя                                                                                 |

Более подробно про Unix см. в [@tanenbaum_book_modern-os_ru; @robbins_book_bash_en; @zarrelli_book_mastering-bash_en; @newham_book_learning-bash_en].

# Выполнение лабораторной работы

Установил/обновил пакеты pass и gopass (рис. [-@fig:001]).

![Установка](image/1.png){#fig:001 width=70%}

Просмотрел списки ключей и создал новый (рис. [-@fig:002]).

![Работа с ключами](image/2.png){#fig:002 width=70%}

Итоговые хар-ки ключа (рис. [-@fig:003]).

![Ключ](image/3.png){#fig:003 width=70%}

Инициализировал хранилище, создал структуру git, задал адрес и синхронизировал (рис. [-@fig:004]).

![Структура](image/4.png){#fig:004 width=70%}

Вручную закоммитил изменения и выложил их (рис. [-@fig:005]).

![Работа с изменениями](image/5.png){#fig:005 width=70%}

Подключился и установил browserpass (рис. [-@fig:006]).

![browserpass](image/6.png){#fig:006 width=70%}

Добавил, отобразил и заменил пароль (рис. [-@fig:007]).

![parol](image/7.png){#fig:007 width=70%}

Установил дополнительное программное обеспечение (рис. [-@fig:008]).

![ПО](image/8.png){#fig:008 width=70%}

Установил шрифты (рис. [-@fig:009]).

![Шрифты](image/9.png){#fig:009 width=70%}

Установил бинарный файл (рис. [-@fig:010]).

![Бинарный файл](image/10.png){#fig:010 width=70%}

Создадал свой репозиторий для конфигурационных файлов на основе шаблона, инициализировал chezmoi с оим репозиторием dotfiles и проверил, какие изменения внесёт chezmoi в домашний каталог (рис. [-@fig:011]).

![Работа с файлами](image/11.png){#fig:011 width=70%}

# Выводы

Настроил рабочую среду

# Список литературы{.unnumbered}

::: {#refs}
:::
