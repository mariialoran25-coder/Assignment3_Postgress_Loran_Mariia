# Assignment3_Postgress_Loran_Mariia
Creating a small database system for managing orders in an online store.

My repository
https://github.com/mariialoran25-coder/Assignment3_Postgress_Loran_Mariia

Моя робота включає всі необіхдні виконані обов'язкові та додаткові завдання .
Спершу я створила свою БД.   Експортувала дані з ПАйтона. А далі вже створювала потрібні завдання.

1 Завдання треба було за допомогою ф-ції обчислити кількість замовлень
2 Завдання треба було за допомогою процедури створити нове замовлення
3 Завдання треба було за допомогою процедури добавити продукт до замовлення
4 Завдання треба було за допомогою тригера оновити кількість замовлення 
5 Завдання треба було за допомогою тригера зробила журнал замовлень
6 Завдання тестуання всіх попередніх завдань 







BONUS TASK 3
Planning Time: 0.313 ms
Execution Time: 0.129 ms

- a short explanation of how PostgreSQL executes the query;
він обирає потрібні поля які я йому вказала у SELECT
Вказую звідки я беру ці дані 
Далі об'єднує таблиці store.products і order_items
І обчислює та фільтрує значення з цієї таблиці виводить рядок де order_id = 1
- 
- identification of whether PostgreSQL uses a Sequential Scan, Index Scan, Hash Join, Nested Loop, or another operation.
Спочатку Index SCAN по таблиці order_items для знаходження замовлення.
До кожного зайденого потрібно запису БД дивиться в таблиці products щоб отримати назву товару за ід
І обчислює та фільтрує 
Вппринципі якщо в таблицях мало записів то планувальник може обрати повне сканування 


  
