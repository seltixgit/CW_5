Проект для получения данных о компаниях и вакансиях с сайта hh.ru, создания БД PostgreSQL на основе полученных данных.

Описание проекта: 
Для получения данных о компаниях и вакансиях используется публичный API hh.ru и библиотека requests. Для этого выбираются интересующие компании, от которых будет получена информация о вакансиях.

Проектирование БД: 
Создаются таблицы в базе данных PostgreSQL для хранения информации о компаниях и их вакансиях.

Загрузка данных: 
Реализуется код, который заполняет созданные таблицы данными о работодателях и их вакансиях.

Анализ данных: 
Создается класс DBManager для работы с данными в базе данных. В этом классе реализуются методы для получения различной статистической информации о вакансиях и компаниях.

Структура проекта main.py: Основной исполняемый файл проекта, в котором реализованы основные шаги проекта. 
DB_Manager.py: Модуль с классом DBManager для работы с данными в базе данных PostgreSQL. 
config.py: Файл с конфигурацией для подключения к базе данных (хост, порт, пользователь, пароль). 
requirements.txt: Файл с перечислением зависимостей проекта. 
README.md: Файл с описанием проекта, инструкциями по запуску и работе с ним.
