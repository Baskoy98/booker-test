# Restful Booker API Manual Testing

## 📌 Цель
Провести ручное тестирование REST API сервиса [restful-booker.herokuapp.com](https://restful-booker.herokuapp.com).

## 🧪 Что протестировано
- `/auth` (POST)
- `/booking` (POST, GET с фильтрами)
- `/booking/:id` (GET, PUT, PATCH, DELETE)
- `/ping` (GET)

## ⚠️ Найденные ошибки
Методы PUT, PATCH и DELETE возвращают 403 Forbidden даже при наличии корректного токена.

## 📂 Структура проекта
- `postman/`
  - `Booking.postman_collection.json — экспортированная коллекция Postman
- `docs/`
  - `Тестовое задание для компании ЯСП.xlsx` — таблица с ручными тест-кейсами
  - `Тестовое задание для компании ЯСП.xlsx` — баг-репорты по результатам тестирования

## 🛠 Использовано
- Postman
- Excel
- GitHub
