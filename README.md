# DE-DB-2.2-PHYSICAL_STRUCT-PRO
## Необходимо:
- Развернуть спроектированную Вами БД «Библиотека» в docker, используя docker-compose;
- Sql-cкрипт на создание таблиц должен выполняться при развертывании образа docker.
## В репозиторий необходимо внести следующие файлы:
- графическая структура файла БД;
- sql-cкрипт создание таблиц БД;
- файл docker-compose.
## Логика решения:
1. Сформированы срипт для создания БД:
- Скрипт DDL по созданию БД находиться по ссылке: (<code>[./init.sql](https://github.com/La-Haine-0/DE-DB-2.2-PHYSICAL_STRUCT-PRO-/blob/main/ddl-init.sql)</code>)
2. Создан файл docker-compose для автоматического разворачивания БД в контейнере. (<code>[./docker-compose.yml](https://github.com/La-Haine-0/DE-DB-2.2-PHYSICAL_STRUCT-PRO-/blob/main/docker-compose.yml)</code>)