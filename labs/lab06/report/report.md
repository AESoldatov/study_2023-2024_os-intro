---
## Front matter
title: "Лабораторная работа №6"
subtitle: "Основы интерфейса взаимодействия пользователя с системой Unix на уровне командной строки"
author: "Солдатов Алексекй"

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

Приобретение практических навыков взаимодействия пользователя с системой посредством командной строки.

# Задание

Выполнение определенных действий описанных в туис

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

Определите полное имя вашего домашнего каталога (рис. [-@fig:001]).

![pwd](image/1.png){#fig:001 width=70%}

Перейдите в каталог /tmp и вывел его содержимое командой ls с различными опциями (рис. [-@fig:002]).

![Содержимое](image/2.png){#fig:002 width=70%}

Определил, есть ли в каталоге /var/spool подкаталог с именем cron, пото перешел в домашний каталог и вывел на экран его содержимое, далее определил, кто является владельцем файлов и подкаталогов (рис. [-@fig:003]).

![Содержимое](image/3.png){#fig:003 width=70%}

В домашнем каталоге создал новый каталог с именем newdir далее в этом каталоге создал новый каталог с именем morefun. Потом в домашнем каталоге создал одной командой три новых каталога с именами letters, memos, misk. Затем удалил эти каталоги одной командой (рис. [-@fig:004]).

![Создание](image/4.png){#fig:004 width=70%}

Попробовал удалить ранее созданный каталог ~/newdir командой rm, проверил, был ли каталог удалён (нет). Удалил каталог ~/newdir/morefun из домашнего каталога. Проверил, был ли каталог удалён (да) (рис. [-@fig:005]).

![Удаление](image/5.png){#fig:005 width=70%}

С помощью команды man определил, какую опцию команды ls нужно использовать для просмотра содержимого не только указанного каталога, но и подкаталогов, входящих в него (рис. [-@fig:006]).

![man](image/6.png){#fig:006 width=70%}

С помощью команды man определил набор опций команды ls, позволяющий отсортировать по времени последнего изменения выводимый список содержимого каталога с развёрнутым описанием файлов (рис. [-@fig:007]).

![man](image/7.png){#fig:007 width=70%}

Использовал команду man для просмотра описания следующих команд: cd, pwd, mkdir, rmdir, rm. Пояснил основные опции этих команд (рис. [-@fig:008]).

![man](image/8.png){#fig:008 width=70%}

Используя информацию, полученную при помощи команды history, выполнил модификацию и исполнение нескольких команд из буфера команд (рис. [-@fig:009]).

![history](image/9.png){#fig:009 width=70%}

# Выводы

Приобрел практические навыки взаимодействия пользователя с системой посредством командной строки.

# Список литературы{.unnumbered}

::: {#refs}
:::
