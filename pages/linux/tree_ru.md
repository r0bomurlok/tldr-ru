# tree

> Выводит содержимое текущего каталога в виде дерева.

- Вывести файлы и каталоги, вложенные не глубже уровня 'num' (1 соответствует текущему каталогу):

`tree -L {{num}}`

- Вывести только каталоги:

`tree -d`

- Добавить к выводу скрытые файлы:

`tree -a`

- Вывести дерево с полными путевыми именами, а не с выравнивающими линиями (ключ `-N` отключает экранирование пробельных и специальных символов):

`tree -i -f`

- Вывести рядом с именем узла его размер в удобочитаемом формате:

`tree -s -h`

- Ограничить вывод glob-шаблоном:

`tree -P {{*.txt}}`