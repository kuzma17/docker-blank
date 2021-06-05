# Заготовка для php проектов в докере   
 

# Как создать php-cli
- скопировать `php-fpm` файл    
- заменить `php-fpm` на `php-cli`

# docker env 
https://docs.docker.com/compose/env-file/   

# Проект
Необходимо создать папку <strong>public</strong>
и туда положить файлы вашего проекта.


# Сборка
```
docker-compose build
```

# запуск / стоп
```
docker-compose up -d
docker-compose down
```

Альтернативный вариант, сборки и запуска : docker-compose up --build


После запуска проект доступен по адресу: <strong>localhost:8080</strong><br>
phpMyAdmin: <strong>localhost:8000</strong>

Порты можно поменять в файле .env


## Сиды для временых записей
```
php artisan db:seed --class=ProductsSeeder
```