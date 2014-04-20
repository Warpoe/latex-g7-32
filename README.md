latex-g7-32
===========

Стиль LaTeX для расчётно-пояснительной записки к курсовым и дипломным работам (ГОСТ 7.32-2001). Ориентирован на студентов IT специальностей.

## Установка

### Зависимости

#### LaTeX пакеты
mathtext, amssymb, amsmath, icomma, longtable, graphicx, underscore, cmap, hyperref

Для придания таймовского вида нужно установить соотв. шрифты (пакет `cyrtimes.sty`), в Debian/Ubuntu это пакет `scalable-cyrfonts-tex`. Если этого пакета нет, оно использует стандартную гарнитуру CM.

#### Программы
inkscape dia pgf context 

## Использование
После изменения РПЗ запустите `make` в корне. Результатом будет `rpz.pdf`.

### Редактор
Можно исползьзовать любой редактор, например, Kile. На комманду `cd .. && make` вешается горячая клавиша и создаётся проект с корректным главным докукментом.

Авторы
------
В порядке участия:

Алексей Томин

[Михаил Конник](http://mydebianblog.blogspot.ru/2008/09/732-2001-latex.html)

|[Всеволод Крищенко](http://sevik.ru/latex/)|
-------------------

[Иван Коротков](https://vk.com/ikorotkov)

Студенты кафедры [ИУ7](http://iu7.bmstu.ru)

[Роман Инфлянскас](https://github.com/rominf/latex-g7-32)
