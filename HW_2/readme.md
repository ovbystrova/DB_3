Мы - мебельный магазин. К нам поступают претензии на изделия, нам надо передавать их производителям:
=====================================



Для работы с Базой данных нужно: импортировать бд fur_shop.sql; заменить USER и PASSWORD на логин и пароль от вашего сервера; заменить NAME если импортировали бд под другим именем.
---
Запускать файл: bd_init.py

БД: fur_shop.sql
http://127.0.0.1:5000/
---

**Таблицы БД:**

items: id , name, description, price.


customers: id, name, phone, email


purchases: id, item_id, customer id, date


complaints: id, text, item_id, purchase_id

**Функции:**

Добавлять данные в таблицы

Сложный запрос с JOIN

Запрос с WHERE

Показ таблицы
