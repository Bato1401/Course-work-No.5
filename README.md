# Курсовой проект по ООП “Работа с базами данных”
Исполнитель: Балданов Бато

## Задание:

В рамках проекта вам необходимо получить данные о компаниях и вакансиях с сайта hh.ru, 
спроектировать таблицы в БД PostgreSQL и загрузить полученные данные в созданные таблицы. 


### Что сделано

- Получены данные о работодателях (не менее 10) и их вакансиях с сайта [hh.ru](http://hh.ru/) 
  через публичный API [hh.ru](http://hh.ru/) и библиотеку `requests`.
- Спроектированы таблицы в БД Postgres для хранения полученных данных о работодателях 
  и их вакансиях (с использованием библиотеки `psycopg2`).
- Реализован код, для заполнения таблиц данными.
- Создан класс `DBManager` для работы с данными в БД.

### Особенности проекта

- Сначала происходит парсинг сайта по компаниям, у которых более 10 открытых вакансий.
- Потом парсинг вакансий по найденным раннее компаниям

### Как пользоваться программой

- в файле main.py методы для работы с БД запускаем попеременно
- каждый метод выводит в консоль запрашиваемые данные


