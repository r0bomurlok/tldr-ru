# fping

> Более мощная утилита позволяющая пинговать несколько хостов.

- Список отвечаюших на пинг хостов в сети в подсети по заданой маске:

`fping -a -g 192.168.1.0/24`

- Список отвечаюших на пинг хостов в сети в подсети по заданому деапазону:

`fping -a -g 192.168.1.1 192.168.1.254`

- Список не отвечаюших на пинг хостов в сети в подсети по заданой маске:

`fping -u -g 192.168.1.0/24`