# Основы REST API

Я научилась делать запросы к API с помощью инструмента Postman.

## Пример 1: Получение списка пользователей (GET)

* **Метод:** GET (запрос на получение данных)
* **URL:** `https://jsonplaceholder.typicode.com/users`
* **Статус-код:** 200 OK (успешный запрос)
* **Формат ответа:** JSON (массив объектов)

**Пример ответа сервера:**
```json
[
  {
    "id": 1,
    "name": "Leanne Graham",
    "username": "Bret",
    "email": "Sincere@april.biz"
  }
]
