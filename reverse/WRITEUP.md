# Totally not a REverse task: Write-up

Totally **not** a reverse?) Очень похоже на намек пореверсить. Но это не тот реверс, где мы получаем ассемблерный код.

А реверс в прямом смысле слова — разворот файла. Развернем его.

Получаем файл, первые байты (в hex) которого равны `98 05 E4 74`. Хмммм, что же это напоминает? Это конечно же напоминает
сигнатуру PNG: `89 50 4E 47`! Развернем ещё и сами байты.

Получили [картинку](private/pic.png), которую можно открыть и посмотреть.
Привет, [РКН](https://habr.com/post/282087/).

Флаг: **uctf_r3411y_n0t_a_rev**

