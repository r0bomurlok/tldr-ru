# unexpand

> Конвертирует пробелы в символы табуляции в файлах.

- Конвертирует пробелы в табы из файла, результат выводит на стандартный поток вывода (stdout):

`unexpand {{file}}`

- Конвертирует пробелы в табы со стандартного потока ввода (stdin), результат выводит на стандартный поток вывода (stdout):

`unexpand`

- Конвертирует все проблеы, включая те, что находятся внутри строки, а не только перед строками кода:

`unexpand -a {{file}}`

- Конвертирует только начальные пробелы (перед строкой кода). Переопределяет ключ `-a`:

`unexpand --first-only {{file}}`

- Установить определённое количество символов пробела, которые будут считаться одним символом табуляции. По умолчанию - 8:

`unexpand -t {{number}} {{file}}`