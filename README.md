# Задание 1
Составить модели классов SQLAlchemy по схеме:
Интуитивно необходимо выбрать подходящие типы и связи полей.

# Задание 2
Используя SQLAlchemy, составить запрос выборки магазинов, продающих целевого издателя.

Напишите Python-скрипт, который:

- подключается к БД любого типа на ваш выбор, например, к PostgreSQL;
- импортирует необходимые модели данных;
- принимает имя или идентификатор издателя (publisher), например, через input(). Выводит построчно факты покупки книг этого издателя:

название книги | название магазина, в котором была куплена эта книга | стоимость покупки | дата покупки
