# Проект Django.
## Создадим свой первый проект Django.
## Добавим в него 3 статические странички.
## Для каждой странички учтем следующие особенности:
1) На одной из страниц контент повторяется 2 раза без изменения content (два раза прописано {{ flatpage.content }}).
2) Одна из страниц на сайте доступна только админу (только вошедшему пользователю).
3) На одной из страниц изменены шрифты и размеры текста.
## Сайт представляет собой оформленный Bootstrap-шаблон со встроенными пользовательскими данными.
## Статические файлы Bootstrap загружаются через теги {% load static %} и {% static %}.
