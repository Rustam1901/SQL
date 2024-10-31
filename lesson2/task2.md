# Базы данных и SQL. Обучение в записи
### Урок 2. Семинар: Установка СУБД, подключение к БД, просмотр и создание таблиц

Задание 2: Выборка книг по году издания

Имеется таблица (сущность) с книгами books. У сущности имеются следующие поля
(атрибуты):

● id – идентификатор;

● title – название;

● author – автор;

● year – год издания;

● price – цена.

Необходимо вывести название, автора и цену для книг, которые были изданы после
1950 года в порядке возрастания цены

```
SELECT title, author, price
FROM books
WHERE year > 1950
ORDER BY price ASC;
```