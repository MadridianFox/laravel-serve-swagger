# Laravel serve swagger

Пакет позволяет вывести Swagger UI, настроив только пути до ваших openapi3 конфигов

## Установка

1. Зарегистрируйте `ServeSwaggerServiceProvider` в вашем `config/app.php`
2. Скопируйте себе `config/serve-swagger.php` и настройте путь для роутинга и массив ссылок до ваших openapi3 конфигов

## Формат массива urls в конфиге 

```
'urls' => [
    [
        'url' => 'foo.yaml', // Путь, осносительно public
        'name' => 'Название 1' // Название для отображения в интерфейсе
    ],
],
```
