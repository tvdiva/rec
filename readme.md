Скрипт для записи IPTV потока.

Примеры:

rec "Р24" 66 --folder "Р24" --url "udp://@233.2.12.56:4444" --fpm 3 --copy-to "/mnt/storage/capture/.arc-Р24"

Записывает поток с URL "udp://@233.2.12.56:4444" с названием "Р24" в папку "Р24" продолжительностью 66 минут с созданием скринлиста с тремя кадрами в минуту с последующим копированием записанного файла в архивную папку "/mnt/storage/capture/.arc-Р24"

rec "ТВЦ-PEER" 200 --fpm 1 --scr "get-tvc-hd-peers" --folder "ТВЦ"

Записывает поток с источника, получаемого скриптом "get-tvc-hd-peers" с названием "ТВЦ-PEER" в папку "ТВЦ" продолжительностью 200 минут с созданием скринлиста с одним кадром в минуту

Для создания скринлиста используется программа https://github.com/OlegKochkin/screengen
