---
## Front matter
lang: ru-RU
title: Отчёт по лабораторной работе №8
author: Дупленских Василий Викторович
institute: РУДН, Москва, Россия
date: 13 мая 2022

## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
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

