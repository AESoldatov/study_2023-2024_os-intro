---
## Front matter
title: "Индивидуальный проект"
subtitle: "Часть 1"
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

Скачал необходимый архив с сайта (рис. [-@fig:001]).

![Скачивание](image/1.png){#fig:001 width=70%}

Перешел в папку "Загрузки", распаковал архив, проверил наличие файла и перенес его в папку "usr/local/bin" (рис. [-@fig:002]).

![Распаковка](image/2.png){#fig:002 width=70%}

Перешел в репозиторий по ссылке в туис и сделал его копию (назвал Project) (рис. [-@fig:003]).

![Создание репозитория](image/3.png){#fig:003 width=70%}

Копировал его ссылку (рис. [-@fig:004]).

![Копирование ссылки](image/4.png){#fig:004 width=70%}

Создал клон репозитория на устройстве (рис. [-@fig:005]).

![Клонировал](image/5.png){#fig:005 width=70%}

Запустил сервер (рис. [-@fig:006]).

![Запуск серрвера](image/6.png){#fig:006 width=70%}

Копировал адрес сервера и вставил в адресную строку браузера, чтоб проверить правильность действий (рис. [-@fig:007]).

![Проверка сайта](image/7.png){#fig:007 width=70%}

Создал новый репозиторий (рис. [-@fig:008]).

![Создание нового репозитория](image/8.png){#fig:008 width=70%}

Клонировал новый репозиторий и перешел в него (рис. [-@fig:009]).

![Клонирование нового репозитория](image/9.png){#fig:009 width=70%}

В этом каталоге я создал главную ветку, создал файл "README.md" и закоммитил (рис. [-@fig:010]).

![Работа с каталогом](image/10.png){#fig:010 width=70%}

Отправляю все по главной ветке (рис. [-@fig:011]).

![git push](image/11.png){#fig:011 width=70%}

Перехожу в папку проекта и ввожу команду, чтоб соединить репозитории (рис. [-@fig:012]).

![Работа с репозиториями](image/12.png){#fig:012 width=70%}

В появившейся папке "public" редактирую файл ".gitignore" (рис. [-@fig:013]).

![Редактирование файла](image/13.png){#fig:013 width=70%}

После редактирования снова ввожу команду, чтоб синхронизировать репозитории (рис. [-@fig:014]).

![Редактирование файла](image/14.png){#fig:014 width=70%}

Пишу команду "hugo" (рис. [-@fig:015]).

![hugo](image/15.png){#fig:015 width=70%}

Перехожу в "puclic" и прописываю команды (рис. [-@fig:016]).

![Работа с каталогом](image/16.png){#fig:016 width=70%}

Отправляю в гитхаб (рис. [-@fig:017]).

![git push](image/17.png){#fig:017 width=70%}

Проверяю правильность действий (рис. [-@fig:018]).

![Проверка](image/18.png){#fig:018 width=70%}

# Выводы

Выполнил первый этап индивидуального проекта

# Список литературы{.unnumbered}

::: {#refs}
:::
