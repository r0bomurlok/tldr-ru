# netstat

> Отображает различную информацию связанную с сетью, такую как открытые соединения, порты и т.д.

- Список всех активных портов:

`netstat -a`

- Список всех портов ожидающих соеденения:

`netstat -l`

- Список активных портов TCP:

`netstat -t`

- Показать идентификаторы процессов и названия программ:

`netstat -p`

- Непрерывно выводить выбранную информацию, с обновлением каждую секунду:

`netstat -c`

- Список маршрутов, отображать только IP хоста, не определяя символьного имени:

`netstat -rn`

- Список прослушивания портов TCP и UDP (+ пользователь и процесс, если вы root):

`netstat -lepunt`