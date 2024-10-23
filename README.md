## Пустой проект
Создан следующими командами:
```shell
composer self-update
cd tepk-it.ru
composer create-project laravel/laravel .
php artisan install:api
php artisan config:publish cors
php artisan storage:link
```
В корне проекта создан файл .htaccess
```php
RewriteEngine on
RewriteRule ^(.*)$ public/$1 [L]
```
