# Домашнее задание 7
**Задача 1** - Выбрать из домашней директории пользователя ubuntu файлы с расширением .py, название которых начинается на букву t.
```
ls | grep '^t.*.py'
```
**Задача 2** - Из всех файлов с расширением .py, расположенных в домашней директории пользователя ubuntu, выбрать строки, содержащие команду print, и вывести их на экран.
```
cat *.* | grep 'print'
```
**Задача 3** - Из результатов работы команды uptime выведите число дней, которое система работает без перезагрузки.
```
uptime | sed 's/.* \([0-9]\+\) \+day.*/\1/'
```
