****Для GNU/Linux Debian 13 x64****
 
 
*****Установка из файла*****

Во всех случаях до полной установки нужно добавить ключ  ****-y****   в конце / поправить файл при отсутствии пакета итд...

xargs apt-get install < FILENAME.txt


----------
****Сохранение в файл установленных в ОС пакетов*****

 apt-mark showmanual > FILENAME.txt
 
 
----------
 ****Сохранение в файл список подходящих файлов из РЕПОЗИТОРИЯ*****
 
 apt-cache pkgnames music > FILENAME.txt
 
    ( Сохраняет в файл все пакеты в имени с music )



----------
****Deb 2 - Debian 13 repository****

/etc/apt/sources.list

#deb cdrom:[Debian GNU/Linux 13.0.0 _Trixie_ - Official amd64 DVD Binary-1 with firmware 20250809-11:21]/ trixie contrib main non-free-firmware

deb http://deb.debian.org/debian/ trixie main non-free-firmware
deb-src http://deb.debian.org/debian/ trixie main non-free-firmware

deb http://security.debian.org/debian-security trixie-security main non-free-firmware
deb-src http://security.debian.org/debian-security trixie-security main non-free-firmware

deb http://deb.debian.org/debian/ trixie-updates main non-free-firmware
deb-src http://deb.debian.org/debian/ trixie-updates main non-free-firmware
###################################




----------

 
  
