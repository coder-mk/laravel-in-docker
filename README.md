# Простое окружение для установки laravel в docker


- Запуск контейнеров `docker-compose up -d`
- Остановка контейнеров `docker-compose down`

## Установка Laravel

Переходим в контейнер php

`docker exec -it php_8_1_3 sh`

Идем в src 

`cd src`

Запускаем установку Laravel

`composer create-project --prefer-dist laravel/laravel .`




