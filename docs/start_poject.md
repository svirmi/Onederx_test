# Инструкция к запуску проекта

## Настройка проекта.

1. Создать файл `.env`. Или скопировать его: `cp .env.example .env`
2. Заполнить полня в `env` файле.
- - `POSTGRES_DB` --  Имя Базы Данных(БД)
- - `POSTGRES_USER`-- Имя пользователя БД
- - `POSTGRES_PASSWORD` -- Пароль БД
- - `PG_HOST` -- Хот БД взят из docker `db`
- - `PG_PORT` -- Порт БД  `5432`


## Запуск проекта
Выполнить `docker-compose up`
Сайт будет доступен адресу `0.0.0.0:8080`

