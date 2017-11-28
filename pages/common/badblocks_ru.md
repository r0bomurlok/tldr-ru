# badblocks

> Ищет на устройстве битые блоки.
> Использование `badblocks` может вести к разрушительным последствиям, например, к стиранию всех данных на диске, включая разметку разделов.

- Ищет битые блоки на диске неразрушающим методом с использованием только чтения:

`sudo badblocks {{/dev/sda}}`

- Ищет битые блоки на размонтированном диске неразрушающим методом с использованием чтения-записи:

`sudo badblocks -n {{/dev/sda}}`

- Ищет битые блоки на размонтированном диске разрушающим методом с использованием записи:

`sudo badblocks -w {{/dev/sda}}`