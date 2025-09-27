---
# Front matter
lang: ru-RU
title: "Лабораторная работа №2"
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

Познакомиться с языком LaTeX и освоить основные команды.

# Задание

1. Реализовать основные команды

# Выполнение лабораторной работы

 
Создадим свой первый документ. Для этого повторим код из лабораторной (рис. [-@fig:001] ) 

![Первый документ](image/1.png){ #fig:001 width=70% }

В данной программе мы подключаем соответствующий формат, открываем командой begin и пишем текст. Завершаем командой end.

Далее представлен результат работы программы (рис. [-@fig:002] ) 

![Вывод программы 1](image/2.png){ #fig:002 width=70% }

Как видно, программа работает верно.

Теперь напишем другой код. Сравним вывод. (рис. [-@fig:003] )  (рис. [-@fig:004] ) 

![Программа](image/3.png){ #fig:003 width=70% }

![Вывод программы 2](image/4.png){ #fig:004 width=70% }

В данной программе мы добавили знак процента, посмотрели, что он преобразует всю следующую строку в комментарий. Так же посмотрели как работает перенос на другую строку (пустая строка) и посмотрели на работу символа ~. Попробовали экранирование и написали в кавычки как часть текста, а не команду. Посмотрели на разные классы документов.

Программа работает верно. 

# Выводы

Познакомилась с языком LaTeX и освоить основные команды.

# Список литературы

Лабораторная работа №2
Практикум по научному письму [Электронный ресурс]. URL: https://esystem.rudn.ru/pluginfile.php/2862317/mod_folder/content/0/Practical-scientific-writing.pdf

