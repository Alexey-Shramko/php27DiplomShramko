# Сервис вопросов и ответов

## Инструкция по установке и первому запуску

1. Клонировать репозиторий в папку проекта. Команда: git clone https://github.com/Alexey-Shramko/php27DiplomShramko.git
2. Установить библиотеки, выполнив в папке проекта команду: composer install
3. В корне проекта скопировать файл .env.example и перемименовать его в .env
4. В файле .env подсоединить пустую базу данных
5. В папке проекта выполнить следующие команды: php artisan key:generate | php artisan migrate | php artisan db:seed

****************************************************************

## В проекте использованы следующие технологии:
1. Bootstrap 3.3.7
2. Laravel 5.4
3. PHP 7.2
5. phpMyAdmin 4.7.7
5. Встроенный шаблонизатор Blade.
6. Архитектура MVC
