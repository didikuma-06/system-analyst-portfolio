# Основы SQL (Базовые запросы)

В этом разделе собраны примеры базовых SQL-запросов, которые я освоила.

## 1. Выборка всех данных
Чтобы вывести все столбцы и строки из таблицы `Movies`:
```sql
SELECT * FROM movies;
SELECT * FROM movies WHERE id = 6;
SELECT * FROM movies WHERE year BETWEEN 2000 AND 2010;
SELECT title, year FROM movies LIMIT 5;
