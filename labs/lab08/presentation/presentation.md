---
## Front matter
title: "Лабораторная работа № 8."
subtitle: "Текстовый редактор vi"
author: "Дупленских Василий Викторович"

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

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах.

# Задание 1

1. Создаю каталог с именем ~/work/os/lab06.

2. Перехожу во вновь созданный каталог.
![lab06](image/1.png)

3. Вызываю vi и создаю файл hello.sh
![vi hello.sh](image/2.png)

4. Нажимаю клавишу i и ввожу следующий текст.
![i](image/3.png)

5. Нажимаю клавишу Esc для перехода в командный режим после завершения ввода текста.
![Esc](image/4.png)

1. Нажимаю [:] для перехода в режим последней строки и внизу моего экрана появилось
приглашение в виде двоеточия.
![:](image/5.png)

7. Нажимаю [w] (записать) и [q] (выйти), а затем нажимаю клавишу [Enter] для сохранения
моего текста и завершения работы.
![wqEnter](image/6.png)

8. Делаю файл исполняемым.
![chmod](image/7.png)

## Задание 2
1. Вызываю vi на редактирование файла
![vi hello](image/8.png)

2. Устанавливаю курсор в конец слова HELL второй строки
![HELL](image/9.png)

3. Перехожу в режим вставки и замените на HELLO. Нажимаю [Esc] для возврата в командный режим.
![HELLO](image/10.png)

4. Устанавливаю курсор на четвертую строку и стираю слово LOCAL.
![LOCAL](image/11.png)

1. Перехожу в режим вставки и набираю следующий текст: local, нажимаю [Esc] для возврата в командный режим.
![local](image/12.png)

6. Устанавливаю курсор на последней строке файла. Вставляю после неё строку, содержащую следующий текст: echo $HELLO.
![echo $HELLO](image/13.png)

7. Нажимаю [Esc] для перехода в командный режим.
![Escape](image/14.png) 

8. Удаляю последнюю строку
![del](image/15.png) 

9. Ввожу команду отмены изменений [u] для отмены последней команды.
![u](image/16.png) 

10. Ввожу символ [:] для перехода в режим последней строки. Записываю произведённые изменения и выхожу из vi.
![u](image/17.png)   

# Выводы

В ходе выполнения лабораторной работы №8 я познакомился с операционной системой Linux и получил практические навыки работы с редактором vi.

