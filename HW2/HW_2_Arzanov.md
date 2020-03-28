# Домашнее задание 2
1. Создать каталоги **first** и **second** в домашней директории, а в них — текстовые файлы **first.py** и **second.py**, содержащие программы, выводящие на экран числа 1 и 2 соответственно.
```
mkdir first
mkdir second
echo "print(1)" > first/first.py
echo "print(2)" > second/second.py
```
2. Переместите файл **second.py** в папку **first**.
```
mv second/second.py first/
```
3. Удалите папку **second**.
```
rm -r second/
```
4. Переименуйте папку **first** в **first_second**.
```
mv first/ first_second/
```
5. Удалите папку **first_second** вместе с содержимым.
```
rm -r first_second/
```
