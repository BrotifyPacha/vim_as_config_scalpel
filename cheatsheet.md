# Vim шпаргалка

# Движения

|Символ|Действие|
|-|-|
|`h`|⬅️|
|`j`|⬇️|
|`k`|⬆️|
|`l`|➡️| 
|`w`,`W`|Следующее начало слова| 
|`b`,`B`|Предыдущее начало слова| 
|`e`,`E`|Следующий конец слова| 
|`0`|Начало строки|
|`$`|Конец строки|
|`gg`|Начало файла|
|`G`|Конец файла|
|`[N]gg`, `[N]G`|Переместиться на `[N]` строку файла|
|`{`|Предыдущая пустая строка|
|`}`|Следующая пустая строка|
|`*`|Следующее нахождение слова под курсором (поиск слова вперёд)|
|`#`|Предыдущее нахождение слова под курсором (поиск слова назад)|
|`^`|Первый символ на строке не являющийся отступом|
|`g_`|Последний символ на строке не являющийся отступом|
|`g;`|Переместиться на место где в последний раз был введён/изменён текст|

# Действия

|Символ|Действие|
|-|-|
|`u`|Отмена последнего действия|
|`.`|Повтор последнего действие|
|---|---|
|`i`|Войти в режим ввода, поставив курсор перед текущим символом|
|`a`|Войти в режим ввода, поставив курсор после текущего символома|
|`I`|Переместить курсор в начало строки и войти в режим ввода|
|`A`|Переместить курсор в конец строки и войти в режим ввода|
|`x`|Удаляет символ под курсором|
|---|---|
|`dd`|Удаляет всё на строке|
|`D`|Удаляет всё от текущего положения и до конца строки|
|`d[движение]`|Удаляет весь текст покрытый движением|
|---|---|
|`cc`|Замена всего текста на строке (сохраняя отступ)|
|`C`|Замена текста от текущего положения и до конца строки|
|`c[движение]`|Замена текста покрытого движением|
|---|---|
|`yd`|Копирует строку|
|`y[движение]`|Копирует весь текст покрытый движением|
|`p`|Вставляет предыдущий скопированный / удалённый / измененный текст|
|---|---|
|`guu`|Переключает в нижний регистр всю строку|
|`gu[движение]`|Переключает в нижний регистр весь текст покрытый движением|
|---|---|
|`gUU`|Переключает в верхний регистр всю строку|
|`gU[движение]`|Переключает в верхний регистр весь текст покрытый движением|
|---|---|
|`g~~`|Инвертирует регистр всей строки|
|`g~[движение]`|Инвертирует регистр всего текста покрытыго движением|
|---|---|
|`/`|Поиск вперёд|
|`?`|Поиск назад|
|`n`|Следующее совпадение последнего поиска|
|`N`|Предыдущее совпадение последнего поиска|
|---|---|
|`r[символ]`|Заменяет символ под курсорм на `символ`|
|`~`|Переключает регистр символа под курсорм|


# Команды

|Команда|Действие|
|-|-|
|`:w [название_файла]`|Сохранить файл|
|`:q`|Выход (если есть несохранённые изменения - всплывёт ошибка)|
|`:q!`|Принудительный выход|
|`:wq`|Сохранить и выйти|
|`:e [название_файла]`|Открыть файл|
|`:new`|Создать новое окно|

# Окна

|Команда|Действие|
|-|-|
|`Ctrl + w h`|Сфокусить окно слева|
|`Ctrl + w j`|Сфокусить окно снизу|
|`Ctrl + w k`|Сфокусить окно сферху|
|`Ctrl + w l`|Сфокусить окно справа|
|`Ctrl + w H`|Переместить окно налево|
|`Ctrl + w J`|Переместить окно вниз|
|`Ctrl + w K`|Переместить окно наверх|
|`Ctrl + w L`|Переместить окно направо|
|`Ctrl + w =`|Уровнять размеры окон|
