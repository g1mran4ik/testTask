ВАРИАНТЫ САМОСТОЯТЕЛЬНОГО ЗАПУСКА:
1. С использованием скрипта runscript.sh (значение по умолчанию prod)
:~$ /bin/bash ./runscript.sh

2. С использованием invoke. Скрипт запуска прописан в tasks.py. 
:~$ inv up

Для поднятия контейнеров в режиме разработки 
:~$ inv up -d front -d api

Для удаления контейнеров
:~$ inv down

P.S. при первичном запуске база данных будет пуста. 
Чтобы её заполнить, необходимо воспользоваться административной панелью Django.
login: admin
password: admin