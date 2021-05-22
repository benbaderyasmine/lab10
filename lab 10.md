# Отчет по лабораторной работе №10

----

# Тема:
## Текстовой редактор emacs

----

## Российский Университет Дружбы Народов

### Факультет Физико-Математических и Естественных Наук

*Дисциплина: Операционные системы*

Студент: Бен бадр Ясмин

Группа: НКНбд-01-20

Москва, 2021г.

----

### Цель работы

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором Emacs.

----

### Последовательность выполнения работы
1. Ознакомиться с теоретическим материалом.
2. Ознакомиться с редактором emacs.
3. Выполнить упражнения.
4. Ответить на контрольные вопросы.

----

### Ход работы:

1. Открыла emacs.

![](https://raw.githubusercontent.com/benbaderyasmine/lab10/main/photo/%D0%BB%D0%B0%D0%B110/1.png)

2. Создала файл lab07.sh с помощью комбинаций Ctrl-x Ctrl-f (C-x C-f).

![](https://raw.githubusercontent.com/benbaderyasmine/lab10/main/photo/%D0%BB%D0%B0%D0%B110/2.png)

3. Набрала текст:

![](https://raw.githubusercontent.com/benbaderyasmine/lab10/main/photo/%D0%BB%D0%B0%D0%B110/3.png)

4. Сохранила файл с помощью комбинаций Ctrl-x Ctrl-s (C-x C-s).

![](https://raw.githubusercontent.com/benbaderyasmine/lab10/main/photo/%D0%BB%D0%B0%D0%B110/4.png)

5. Проделала с текстом стандартные процедуры редактирования, каждое действие осуществлял комбинацией клавиш.

* Вырезала одной командой целую строку (С-k).

![](https://raw.githubusercontent.com/benbaderyasmine/lab10/main/photo/%D0%BB%D0%B0%D0%B110/5.png)
* Вставила эту строку в конец файла (C-y).

![](https://raw.githubusercontent.com/benbaderyasmine/lab10/main/photo/%D0%BB%D0%B0%D0%B110/6.png)

* Выделила область текста (C-space).

![](https://raw.githubusercontent.com/benbaderyasmine/lab10/main/photo/%D0%BB%D0%B0%D0%B110/7.png)

* Скопировала область в буфер обмена (M-w).

* Вставила область в конец файла.

![](https://raw.githubusercontent.com/benbaderyasmine/lab10/main/photo/%D0%BB%D0%B0%D0%B110/8.png)

* Вновь выделила эту область и на этот раз вырезала её (C-w).

![](https://raw.githubusercontent.com/benbaderyasmine/lab10/main/photo/%D0%BB%D0%B0%D0%B110/9.png)

![](https://raw.githubusercontent.com/benbaderyasmine/lab10/main/photo/%D0%BB%D0%B0%D0%B110/10.png)

* Отменила последнее действие (C-/).

![](https://raw.githubusercontent.com/benbaderyasmine/lab10/main/photo/%D0%BB%D0%B0%D0%B110/11.png)

1. Научилась использовать команды по перемещению курсора.

* Переместите курсор в начало строки (C-a).

![](https://raw.githubusercontent.com/benbaderyasmine/lab10/main/photo/%D0%BB%D0%B0%D0%B110/12.png)

* Переместите курсор в конец строки (C-e).

![](https://raw.githubusercontent.com/benbaderyasmine/lab10/main/photo/%D0%BB%D0%B0%D0%B110/13.png)

* Переместите курсор в начало буфера (M-<).

![](https://raw.githubusercontent.com/benbaderyasmine/lab10/main/photo/%D0%BB%D0%B0%D0%B110/14.png)

* Переместите курсор в конец буфера (M->).

![](https://raw.githubusercontent.com/benbaderyasmine/lab10/main/photo/%D0%BB%D0%B0%D0%B110/15.png)

1. Управление буферами.

* Вывела список активных буферов на экран (C-x C-b).

![](https://raw.githubusercontent.com/benbaderyasmine/lab10/main/photo/%D0%BB%D0%B0%D0%B110/16.png)

* Переместился во вновь открытое окно (C-x) o со списком открытых буферов и переключился на другой буфер,
* Закрыла это окно (C-x 0).

![](https://raw.githubusercontent.com/benbaderyasmine/lab10/main/photo/%D0%BB%D0%B0%D0%B110/18.png)

* Вновь переключился между буферами, но уже без вывода их списка на экран (C-x b).

![](https://raw.githubusercontent.com/benbaderyasmine/lab10/main/photo/%D0%BB%D0%B0%D0%B110/17.png))

1. Управление окнами.

* Поделила фрейм на 4 части: разделила фрейм на два окна по вертикали (C-x 3), а затем каждое из этих окон на две части по горизонтали (C-x 2)

![](https://raw.githubusercontent.com/benbaderyasmine/lab10/main/photo/%D0%BB%D0%B0%D0%B110/19.png)

![](https://raw.githubusercontent.com/benbaderyasmine/lab10/main/photo/%D0%BB%D0%B0%D0%B110/20.png)

* В каждом из четырёх созданных окон открыла новый буфер (файл) и ввела несколько строк текста.

![](https://raw.githubusercontent.com/benbaderyasmine/lab10/main/photo/%D0%BB%D0%B0%D0%B110/21.png)

1. Режим поиска

* Переключилась в режим поиска (C-s) и нашла несколько слов, присутствующих в тексте.

![](https://raw.githubusercontent.com/benbaderyasmine/lab10/main/photo/%D0%BB%D0%B0%D0%B110/22.png)

* Переключилась между результатами поиска, нажимая C-s.

* Вышела из режима поиска, нажав C-g.

![](https://raw.githubusercontent.com/benbaderyasmine/lab10/main/photo/%D0%BB%D0%B0%D0%B110/23.png)

* Перешела в режим поиска и замены (M-%), ввел текст, который следует найти и заменить, нажал *Enter* , затем ввела текст для замены. После подсвечивания результатов поиска, нажал ! для подтверждения замены.

![](https://raw.githubusercontent.com/benbaderyasmine/lab10/main/photo/%D0%BB%D0%B0%D0%B110/24.png)

![](https://raw.githubusercontent.com/benbaderyasmine/lab10/main/photo/%D0%BB%D0%B0%D0%B110/25.png)
![](https://raw.githubusercontent.com/benbaderyasmine/lab10/main/photo/%D0%BB%D0%B0%D0%B110/26.png)

* Попробовала другой режим поиска, нажав M-s o. Он отличается от обычного режима тем, что при поиске указывает номера строк в которых найдено введённое слово и выделяет их цветом. В обычном режиме выделение цветом появляется, только когда нужно подтвердить замену.

![](https://raw.githubusercontent.com/benbaderyasmine/lab10/main/photo/%D0%BB%D0%B0%D0%B110/27.png)

----

### Вывод

Познакомилась с операционной системой Linux, получила практические навыки работы с редактором Emacs.

----

### Библиография

[Emacs для начинающих](https://alexott.net/ru/writings/altlinux-emacs/)
[GNU Emacs.](https://habr.com/ru/post/248663/)

----

## Ответы на контрольные вопросы:

1. Emacs представляет собой мощный экранный редактор текста, написанный на
языке высокого уровня Elisp.
2. Развитие Emacs в сторону его многогранности послужило причиной того, что и без того интуитивно непонятная программа стала чрезвычайно сложной в применении. В частности, управление осуществляется при помощи различных клавиатурных комбинаций, запомнить которые будет непросто.
3. Буфер – что-то, состоящее из текста. 
Окно – область с одним из буферов.
4. В одном окне можно открыть больше 10 буферов.
5. После запуска emacs без каких-либо параметров в основном окне отображается буфер *scratch*, который используется для оценки выражений Emacs Lisp, а также для заметок, которые вы не хотите сохранять. Этот буфер не сохраняется автоматически.
6. Чтобы ввести следующую комбинацию C-c | я нажму клавиши: Control+c и Shift+\, и для C-c C-|: Control+c и Control+Shift+\.
7. Поделить текущее окно на две части можно двумя комбинациями клавиш: 
C-x 3 или C-x 2.
8. Настроить или расширить Emacs можно написав или изменив файл ~/.emacs.
9. Клавиша  выполняет функцию перемещения курсора в открытом окне также, как и многие другие клавиши её можно переназначить.
10. Редактор emacs показался мне удобнее из-за возможности открытия нескольких окон с буферами и работать комбинациями клавиш в этот редакторе мне было проще.
