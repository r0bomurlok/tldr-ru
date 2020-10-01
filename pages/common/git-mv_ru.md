# git mv

> Перемещение или переименование файлов и обновление индекса git.

- Перемещение файла внутри РЕПО и добавление его в следующий коммит:

`git mv {{path/to/file}} {{new/path/to/file}}`

- Переименование файла и добавление переименования к следующему коммиту:

`git mv {{filename}} {{new_filename}}`

- Перезаписывание файла по целевому пути, если он существует:

`git mv --force {{file}} {{target}}`