---
## Front matter
title: "Презнтация №1"
subtitle: "Git"
author: "Рытов Алексей Константинович"
lang: ru-RU


## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc-depth: 2
lof: true # List of figures
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

# **Цель работы**

– Изучить идеологию и применение средств контроля версий.
– Освоить умения по работе с git.

---

# Выполнение лабораторной работы


В этой лабораторной работе мы начились: 
1.     -индексировать изменения, и коммититить их. 
2.     -Добавлять тэги и индексировать их.
3.     -Отменять локальные измененения.
4.     -Создавать ветки.
5.     -Перемещаться по веткам.
6.     -Делать Merge.
7.     -Разрешать конфликты.
8.     -Делать Rebase.
9.     -Клонировать репозитории.
10.     -Удалять ветки.
11.     -Добавлять удаленные репозитории.

---

# Вывод

Мы изучили идеологию и применение средств контроля версий, а также освоили умения по работе с git.</br>

---
