# tron
Бомбер c Top. Пожалуйста поставьте Star.
Запускается немного дольше с Тором, но отлично работает, если жалуется на 64 бита вместо 32, то ниже как исправить, переписывать в точно так как написано.

Как правильно установить СНАЧАЛА ПРОПИСЫВАЕМ ВСЕ ЭТО В Termux, а потом уже исправляем проблему с "64 бит"
1) apt update
2) apt upgrade
3) pkg install git
4) pkg install tsu
5) pkg install python
6) pkg install python2
7) pkg install openssh
git clone https://github.com/ToothlessFox/tron.git
9) cd tron
10) tsu
11) chmod +x ./tron
12) ./tron

Проблема с 64 бит

$ su

$ which su

$ sh -x su

$ sh -x $(which su)

$ unset LD_PRELOAD
После этого пишем./tron и все должно запуститься. После перезапуска прийдется прописывать заново условие
$ which su
$ sh -x su
$ sh -x $(which su)
$ unset LD_PRELOAD
И только потом можно
1) cd tron
2) ./tron

После запуска можно запустить так же командной ./tron 79123456789 3 1 60
- 3 Это режим SMS + Звонок
- 1 Показывать только удачные
- 60 Время в секундах ( Если значение 0 то бесконечно )

Разработчик notBrut0r https://codeby.net/threads/infinite-bomber-sms-call-flud.68693/


