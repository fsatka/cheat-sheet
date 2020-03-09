# Data Bases

## Mongo db
основные определения

+ поле документа ~ ячейка таблицы;
+ документ ~ строка в таблице;
+ коллекция ~ таблица.

-------------------------------------

Проверка, что _MongoDB_ установлена:

`ps aux | grep mongo`

-------------------------------------

### [Выборка(оператор find)](https://docs.mongodb.com/manual/reference/method/db.collection.find/#db.collection.find)

+ `show dbs - показать сущ базы`

+ `use name_db - использовать name_db`

+ `show collections - показать коллекциив db`
-------------------------------------
Оператор find:

`db.collection_name.find({запрос}, {оператор проекции})`




