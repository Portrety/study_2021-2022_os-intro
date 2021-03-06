---
# Front matter
lang: ru-RU
title: "Отчёт по лабораторной работе №9"
subtitle: "Дисциплина: Операционные системы"
author: "Дупленских Василий Викторович"

# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы:

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором Emacs.

# Выполнение лабораторной работы:

## 1. Открываю emacs:
![Открытие emacs](image/1.png)

## 2. Создаю файл lab07.sh с помощью комбинации Ctrl-x Ctrl-f:
![Создание файла](image/2.png)

## 3. Набираю текст:
![Текст](image/3.png)

## 4. Сохраняю файл с помощью комбинации Ctrl-x Ctrl-s:
![Сохранение](image/4.png)

## 5. Проделываю с текстом стандартные процедуры редактирования, каждое действие осуществляю комбинацией клавиш.
### 5.1 Вырезаю одной командой целую строку:
![Вырез](image/5.1.png)

### 5.2. Вставляю эту строку в конец файла:
![Вставка](image/5.2.png)

### 5.3. Выделяю область текста:
![Выделение](image/5.3~4.png)

### 5.4. Копирую область в буфер обмена:
![Вставка](image/5.3~4.png)

### 5.5. Вставляю область в конец файла:
![Вставка 2](image/5.5.png)

### 5.6. Вновь выделяю эту область и на этот раз вырезаю её:
![Выделение + вырез](image/5.6.png)

### 5.7. Отменяю последнее действие:
![Отмена](image/5.7.png)

## 6. Использую команды по перемещению курсора:
### 6.1. Перемещаю курсор в начало строки:
![Начало строки](image/6.1.png)

### 6.2. Перемещаю курсор в конец строки:
![Конец строки](image/6.2.png)

### 6.3. Перемещаю курсор в начало буфера:
![Начало буфера](image/6.3.png)

### 6.4. Перемещаю курсор в конец буфера:
![Конец буфера](image/6.4.png)

## 7. Управляю буферами:
### 7.1. Вывожу список активных буферов на экран:
![Список активных буферов](image/7.1.png)

### 7.2. Перемещаюсь во вновь открытое окно со списком открытых буферов
и переключаюсь на другой буфер:
![Перемещение и переключение буферов](image/7.2.png)

### 7.3. Закрываю это окно:
![Закрытие](image/7.3.png)

### 7.4. Теперь вновь переключаюсь между буферами, но уже без вывода их списка на экран:
![Переключение без вывода](image/7.4.png)

## 8. Управляю окнами:
### 8.1. Поделите фрейм на 4 части: разделите фрейм на два окна по вертикали,
а затем каждое из этих окон на две части по горизонтали:
![Делёжка окон](image/8.1.png)

### 8.2. В каждом из четырёх созданных окон открываю новый буфер (файл) и ввожу несколько строк текста:
![Новый буфер + ввод](image/8.1.png)

## 9. Режим поиска:
### 9.1. Переключаюсь в режим поиска и ищу несколько слов, присутствующих в тексте:
![Режим поиска](image/9.1.png)

### 9.2. Переключаюсь между результатами поиска:
![Переключение](image/9.2.png)

### 9.3. Выхожу из режима поиска:
![Выход из режима Поиска](image/9.3.png)

### 9.4. Перехожу в режим поиска и замены, ввожу текст, который следует найти
и заменить, нажимаю Enter , затем ввожу текст для замены. После того как будут подсвечены результаты поиска, нажимаю ! для подтверждения замены:
![Поиск и замена](image/9.4.png)

### 9.5. Отпробываю другой режим поиска:
![Другой режим поиска](image/9.5.png)

# Ответы на вопросы:
1. Кратко охарактеризуйте редактор emacs. Ответ: Emacs представляет собой мощный экранный редактор текста, написанный на языке высокого уровня Elisp.

2. Какие особенности данного редактора могут сделать его сложным для освоения новичком? Ответ: Сложным освоение данной программы для новичка может сделать незнание комбинации клавиш или английского.

3. Своими словами опишите, что такое буфер и окно в терминологии emacs’а Ответ: Моими словами буфер это динамическая память, а окно- то, что мы видим

4. Можно ли открыть больше 10 буферов в одном окне? Ответ: Можно если нет ограничений на систему.

5. Какие буферы создаются по умолчанию при запуске emacs? Ответ: Буферы, которые открываются по умолчанию: GNU Emacs, scratch, Messages, Quail Completions

6. Какие клавиши вы нажмёте, чтобы ввести следующую комбинацию C-c | и C-c C-|? Ответ: Сtrl+c, Shift+\ и Ctrl+c Ctrl+\

7. Как поделить текущее окно на две части? Ответ: Нажать C-x 3, или C-x 2.

8. В каком файле хранятся настройки редактора emacs? Ответ: Настройки хранятся в файле ~/.emacs.

9. Какую функцию выполняет клавиша Backspace и можно ли её переназначить? Ответ: Перемещение курсора

10. Какой редактор вам показался удобнее в работе vi или emacs? Поясните почему. Ответ: Редактор emacs ,потому что на нем можно работать сразу с несколькими файлами.

# Вывод:
Я познакомился с операционной системой Linux. Получил практические навыки работы с редактором Emacs!
