# Домашнее задание к занятию  «Защита хоста»


### Задание 1

1. Установите **eCryptfs**.
2. Добавьте пользователя cryptouser.
3. Зашифруйте домашний каталог пользователя с помощью eCryptfs.


*В качестве ответа  пришлите снимки экрана домашнего каталога пользователя с исходными и зашифрованными данными.*  

### Решение 1

[no encrypt](https://github.com/sash3939/Host-Defender/assets/156709540/24fd69b5-c8ae-460d-aacf-517b72750487)

[encrypting](https://github.com/sash3939/Host-Defender/assets/156709540/0b34fd8e-105e-420b-90c7-1e562b58bdd0)

[su](https://github.com/sash3939/Host-Defender/assets/156709540/d19ababa-3132-4e3f-855c-379f3cbed37f)

[encrypted](https://github.com/sash3939/Host-Defender/assets/156709540/42d283d7-bcc7-49fc-94a9-2d54784cdda6)


### Задание 2

1. Установите поддержку **LUKS**.
2. Создайте небольшой раздел, например, 100 Мб.
3. Зашифруйте созданный раздел с помощью LUKS.

*В качестве ответа пришлите снимки экрана с поэтапным выполнением задания.*


### Решение 2

[create partition](https://github.com/sash3939/Host-Defender/assets/156709540/32ce7e0c-a59f-48a9-9524-5acd7625eab8)

[init](https://github.com/sash3939/Host-Defender/assets/156709540/a2942487-d5fe-4af4-9db4-9e9174526d64)

[open and create fs](https://github.com/sash3939/Host-Defender/assets/156709540/95986c72-9585-4fef-a3fa-4ffbcc9ebc6a)

[mount](https://github.com/sash3939/Host-Defender/assets/156709540/970806af-eada-4a94-af30-43e812d2abef)

[lsblk](https://github.com/sash3939/Host-Defender/assets/156709540/043e9f96-5fab-49a1-81d9-de1724388b98)

[unmount encrypt partition](https://github.com/sash3939/Host-Defender/assets/156709540/00da3bad-5e24-468b-b5c4-e073785bf671)

[close encrypt partition](https://github.com/sash3939/Host-Defender/assets/156709540/fda9bbb4-8302-4810-9dff-bd58504aa1df)


## Дополнительные задания (со звёздочкой*)

Эти задания дополнительные, то есть не обязательные к выполнению, и никак не повлияют на получение вами зачёта по этому домашнему заданию. Вы можете их выполнить, если хотите глубже шире разобраться в материале

### Задание 3 *

1. Установите **apparmor**.
2. Повторите эксперимент, указанный в лекции.
3. Отключите (удалите) apparmor.


### Решение 3 *

[status](https://github.com/sash3939/Host-Defender/assets/156709540/8bdafca6-0a6c-4ca3-b7e3-7d296122d542)

[set complain mode](https://github.com/sash3939/Host-Defender/assets/156709540/3b303e3d-a9f2-4eac-bd65-f53424350df6)

[enforce mode](https://github.com/sash3939/Host-Defender/assets/156709540/96f4e5e1-10f6-4740-962d-ee59534d766a)

[proccessors with profiles](https://github.com/sash3939/Host-Defender/assets/156709540/09b66fdd-0a69-41f5-84ee-23d8ce14fe8a)

[ping enforce mode](https://github.com/sash3939/Host-Defender/assets/156709540/bfda8d08-a120-4c91-8331-854c532d9862)

[ping complain mode](https://github.com/sash3939/Host-Defender/assets/156709540/18f42e6c-e835-4a3c-94f5-062dcd56a151)

[bin.ping](https://github.com/sash3939/Host-Defender/assets/156709540/57df0d08-70cc-4a77-b8e8-d99dc0cbb667)

[teardown](https://github.com/sash3939/Host-Defender/assets/156709540/d4474304-6142-4440-94d8-683ae0134f34)


*В качестве ответа пришлите снимки экрана с поэтапным выполнением задания.*
