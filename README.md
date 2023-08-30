# docker_php_nginx_mysql

**Набор контейнеров изпользуется для docker-compose**

Данный набор включает 4 контейнера, работающих совместно:

1. nginx
2. mysql
3. phpmyadmin (для удобства)
4. php-fpm 8 c pdo драйвером для работы с MS SQL

**Структура директорий**

- [db] - физически вынесеная БД из контейнера
- [mysql] - содержит конфиг субд MySQL
- [nginx/conf.d] - конфиг nginx
- [nginx/log] - логи веб-сервера
- [src] - можно расположить будущие веб-приложение на php
