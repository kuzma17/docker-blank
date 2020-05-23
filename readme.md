# Заготовка для php проектов в докере    
Добавить папку `storage/docker/mysql`

# Как создать php-cli
- скопировать `php-fpm` файл    
- заменить `php-fpm` на `php-cli`

# docker env 
https://docs.docker.com/compose/env-file/   

```

# Сборка
docker-compose build

# запуск / стоп
docker-compose up -d
docker-compose down
```

# 
docker-compose up --build

## Сиды для временых записей
```
php artisan db:seed --class=ProductsSeeder
```
