# esphome-pump-r2
Прошивка управления насосом для реле Sonoff mini R2. Используется ESPHome. 

Статья на Хабре [Прокачиваем насос с помощью ESPHome и реле от Sonoff](https://habr.com/ru/post/699008/).

Как использовать:
1. Установите docker и загрузите образ esphome: `docker pull esphome/esphome`.
2. Перейдите в каталог с файлами .yaml.
3. Запустите ESPHome в режиме дашборда: `docker run --rm --net=host -v "${PWD}":/config -it esphome/esphome`
4. Перейдите в веб-интерфейс ESPHome по адресу `localhost:6052`.

[Подробная инструкция по установке ESPHome](https://esphome.io/guides/getting_started_command_line.html)
