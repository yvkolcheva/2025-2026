---
# Front matter
lang: ru-RU
title: "Лабораторная работа №8"
subtitle: "Практикум по научному письму"
author: "Колчева Юлия Вячеславовна"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Познакомиться с языком LaTeX, продолжить изучение его возможностей. 

# Задание

1. Запустить несколько различных программ, изучить новый пакет для работы с графикой и новые команды языка.


# Выполнение лабораторной работы

 
Начинаем работать с новым пакетом. График состоит из нескольких точек и линий. Мы начинаем построение графика с определения координат точек. (рис. [-@fig:001] ) 

![Программа 1](image/1.png){ #fig:001 width=70% }

 
Помимо рисования прямых линий, мы можем создавать и другие типы линий, которым можно задать цвет, толщину или узор. (рис. [-@fig:002] )

![Программа 2](image/2.png){ #fig:002 width=70% }

Мы можем рисовать не только прямые, но и изогнутые линии. (рис. [-@fig:003] ) 

![Программа 3](image/3.png){ #fig:003 width=70% }

Следующим шагом на пути к вёрстке графика являются метки, фрагменты текста и числа, содержащиеся в рисунке. (рис. [-@fig:004] ) 

![Программа 4](image/4.png){ #fig:004 width=70% }

Узлам также можно присвоить математические формулы, и, как уже было сказано, их можно обвести простой линией. (рис. [-@fig:005] ) 

![Программа 5](image/5.png){ #fig:005 width=70% }

Попробуем создать сложный график с большим количеством разных элементов (рис. [-@fig:006] ) 

![Программа 6](image/6.png){ #fig:006 width=70% }

В TikZ также можно использовать циклы for с помощью команды foreach  (рис. [-@fig:007] ) 

![Программа 7](image/7.png){ #fig:007 width=70% }


Программы работают верно. 

# Выводы

Познакомилась с языком LaTeX, продолжила изучение его возможностей.

# Список литературы

Лабораторная работа №8
Практикум по научному письму [Электронный ресурс]. URL: https://esystem.rudn.ru/pluginfile.php/2862317/mod_folder/content/0/Practical-scientific-writing.pdf

