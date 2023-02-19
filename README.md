# Site-hack-
Реализованная функциональность:
Аутентификация;
Демо-версия сайта;
Демо-версия карты прогресса;
Bootstrap;

Особенность проекта в следующем:
Гид - Киллерфич;
Телеграм-бот;
Безопасность продукта;
Карта-прогресса;
Ачивменты;
Баллы;
Конструктор задач;
Роли;
E-mail рассылка;

Основной стек технологий:
Python, Django, Sqlite, Bootstrap, aiogram, Html, CSS

Демо
Демо сервиса доступно по адресу: https://disk.yandex.ru/d/lS5RzDG8Q9qnbw

Реквизиты тестового пользователя: email: admin, пароль: admin

УСТАНОВКА

Установка пакета name
Выполните

sudo apt-get update
sudo apt-get upgrade
sudo apt-get install name1
sudo apt-get install mariadb-client mariadb-server
git clone https://github.com/Sinclear/default_readme
cd default_readme
...
База данных
Необходимо создать пустую базу данных, а подключение к базе прописать в конфигурационный файл сервиса по адресу: папка_сервиса/...

sudo systemctl restart mariadb
sudo mysql_secure_installation
mysql -u root -p
mypassword
CREATE DATABASE mynewdb;
quit
Выполнение миграций
Для заполнения базы данных системной информацией выполните в корневой папке сервиса:

mysql -u root -p -f mynewdb < папка_сервиса/...
mypassword
и согласитесь с запросом

Установка зависимостей проекта
Установка зависимостей осуществляется с помощью Composer. Если у вас его нет вы можете установить его по инструкции на getcomposer.org.

После этого выполнить команду в директории проекта:

composer install

РАЗРАБОТЧИКИ

Дмитрий Попов backend, frontend Telegram: @lorell1n
Артем Масеев backend, creator Telegram: @Artemed22
Артем Стрельчук frontend, design Telegram: @arteom_ya
Юрий Хомич frontend, design Telegram: @luintore
Олег Коваленко design, creator Telegram: @FredReh_nam
