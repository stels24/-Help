# Graduate-work

# Анализ и сравнение написания web-приложений с использованием разных фреймворков.
==================================================================================
## Разработать простые веб-приложения с использованием Django, Flask и FastAPI. Провести их сравнение.

### Urban University, курс "Разработчик Python", студент Федосов М.А. 

### Содержание

1. Задачи дипломной работы
2. Описание дипломной работы
3. Реализация дипломной работы


## 1. Задачи дипломной работы:
   Целью данной работы является сравнение возможностей web-фреймворков на базе Python: Flask, FastAPI и Django. Реализовать небольшие веб-приложения на каждом фреймворке, провести сравнения, удобство разработки и сопровождения.

## 2. Описание дипломной работы:
  В качестве тем для разработки я выбрал создание баз данных для учета, контроля и соблюдения сроков исполнения входящей корреспонденции так как показывает практика, что соблюдение исполнительской дисциплины значительно влияет на продуктивность деятельности учреждения(компании).
  Разработанные web-приложения должны обеспечивать выполнение следующих функций:
  
  1. Персонализацию приложения при регистрации;
  2. Возможность вносить планируемые задачи c кратким описанием;
  3. Устанавливать сроки исполнения;
  4. Многозадачность;
  5. Возможность просмотра и обновления задачи(при необходимости)

## 3. Реализация дипломной работы

# **Flask**

Требования к функционалу вебприложения Список задач (To-Do List).

1. Регистрация и авторизация пользователей с сохранением в базе данных.
   
2. После авторизации пользователь попадает в форму Дашбод.

3. Требования к web-приложению Список задач (To-Do List).
   - Добавление, редактирование и удаление задач.
   - Отметка задач как выполненных.
   - Фильтрация задач по статусу (все, активные, выполненные).
   - Возможность сортировки по дате создания или приоритету.
     
Структура дериктории flask_mike

![](https://github.com/stels24/-Help/blob/main/Структура%20каталога%20файлов%20в%20Flask.png)


## 4. Структура сайта.
   
  4.1.Главная странца, содержит форму авторизации и ссылку на регистрацию пользователя.
   ![](https://github.com/stels24/-Help/blob/main/Страница%20регистрации.png)
  4.2. Нa дашборд попадаем после авторизации. Дaшборд - таблица со списком задач, блок фильтров (по дате, по названию, по статусу, по приоритету).
  
![](https://github.com/stels24/-Help/blob/main/Пререход%20на%20Dashboard.png)

![](https://github.com/stels24/-Help/blob/main/Страница%20новой%20задачи.png)

![](https://github.com/stels24/-Help/blob/main/Выбираем%20статус.png)

![](https://github.com/stels24/-Help/blob/main/Выбор%20даты%20исполнения%20задачи.png)

   На дашборде есть кнопки Дoбавления, Редактирования, удаления, фильтра  задач.
   
   ![](https://github.com/stels24/-Help/blob/main/Кнопки%20добавления%20задач.png)
   
   ![](https://github.com/stels24/-Help/blob/main/Запись%20сформированной%20задачи.png)
   
   ![](https://github.com/stels24/-Help/blob/main/Просмотр%20задачи.png)

При нажатии на кнопку Редактирования открывается форма редактирования.

![](https://github.com/stels24/-Help/blob/main/Кнопка%20редактирования.png)


Субъективные оценки по шкале от 1 до 5, где 1 - худшая, 5 - лучшая оценка:

Скорость разработки: 4
Удобство добавления данных: 2
Скорость работы приложения: 3
Общие впечатления: удобно работать, импорты не перегружены объектами. Приятно видеть сразу декоратор и обработчик в одном файле. 
Интуитивно легко понять назначение объектов фреймворка по их названию.


# **Fastapi**

Требования к функционалу вебприложения Список задач (To-Do List).

1. Регистрация и авторизация пользователей с сохранением в базе данных.
   
2. После авторизации пользователь попадает в форму Дашборд.

3. Требования к web-приложению Список задач (To-Do List).
   - Добавление, редактирование и удаление задач.
   - Отметка задач как выполненных.
   - Фильтрация задач по статусу (все, активные, выполненные).
   - Возможность сортировки по дате создания или приоритету.
   - Сохранение пользователей и задач в базеданных.

Структура дериктории Fstapi_mike

![](https://github.com/stels24/-Help/blob/main/Структура%20папки%20Fastapi.png)

## 4. Структура сайта.
   
  4.1.Главная странца дашборда To-Do List, содержит форму авторизации и ссылку на регистрацию пользователя.
   ![](https://github.com/stels24/-Help/blob/main/Вход%20в%20дашборд%20To-Do%20List%20или%20регистрация%20нового%20пользователя%20Fastapi_.png)
  4.2. После авторизации переходим на страницу добавления задачи, а также блоку фильтров (по дате, по названию, по статусу, по приоритету).
  
![](https://github.com/stels24/-Help/blob/main/Добавление%20задачи%20Fastapi.png)

   4.3 Создаем лист задачи

   ![](https://github.com/stels24/-Help/blob/main/Создание%20листа%20задач%20Fastapi.png)

   4.4 Проверяем базу данных
   4.1.1 Пользователи

   ![](https://github.com/stels24/-Help/blob/main/База%20данных%20пользователей%20Fastapi.png)
   4.1.2 База данных задач    
        
 ![](https://github.com/stels24/-Help/blob/main/База%20задач%20Fastapi.png)
         

Личные оценки работы приложения на фреймворке Flask по 5-ти бальной системе:

Скорость : 4
Удобство добавления данных: 4
Скорость работы приложения: 5

Общие впечатления: есть как свои плюсы, так и минусы. Плюсом является скорость работы, потому, что фреймворк является полностью асинхронным, но программировать не очень удобно из-за большого количества объектов и классов фреймворка и перегрузки количества импортов в написанном коде. Также к плюсам можно отнести то, что декоратор и обработчик находятся рядом в одном файле. База данный строится на основе моделей SQLAlchemy, что с одной стороны является плюсом, так как позволяет не привязываться к определенной СУБД, но с другой требует дополнительного изучения объектов и методов самой SQLAlchemy которые часто не являются интуитивно понятными. Таким образом, для эффективной работы с данным фреймворком нужен определенный опыт и знания.


# **Django**

Требования к функционалу вебприложения.

1. Регистрация и авторизация пользователей с сохранением в базе данных.
   
2. После авторизации пользователь попадает в форму Дашбод.

3. Требования к web-приложению.
   - Добавление, редактирование и удаление задач.
   - Отметка задач как выполненных.
   - Фильтрация задач по статусу (все, активные, выполненные).
   - Возможность сортировки по дате создания или приоритету.
   - Возможность создания базы данных через "Admin"- панель
   - Проверка внесенных данных в БД и их редактирование

Структура дериктории django_mike

![](https://github.com/stels24/-Help/blob/main/Структура%20каталога%20файлов%20в%20Django.png)

Структура дериктории tempates

![](https://github.com/stels24/-Help/blob/main/Структра%20файлов%20Django%20папки%20templates.png)

## 4. Структура сайта.

4.1. После запуска кода в командной строке (python manage.py runserver) перехоим по адресу: http://127.0.0.1:8000/dashboard/ (локально)
где появляется возможность добавлять пользователя и задачи.


![](https://github.com/stels24/-Help/blob/main/Дашборд%20в%20Django.png)

4.2. Набрав адрес на странице (http://127.0.0.1:8000/admin/) переходим в панель администрирования Django, где появляется возможность добавления одиночных пользователей, групп пользователей, категорий, задач.

![](https://github.com/stels24/-Help/blob/main/Добавление%20задачи%20и%20пользователя%20Django.png)

![](https://github.com/stels24/-Help/blob/main/Заполнение%20полей%20пользователя%20в%20БД%20Django.png)

![](https://github.com/stels24/-Help/blob/main/Создание%20Категории%20Django.png)

![](https://github.com/stels24/-Help/blob/main/Создание%20группы%20пользователей%20Django.png)

![](https://github.com/stels24/-Help/blob/main/Созданные%20ранее%20категории%20Django.png)

4.3 Установив отдельное приложение DB Browser, можем осуществлять просмотр и редактирование информации в БД


![](https://github.com/stels24/-Help/blob/main/Задачи%20в%20БД.png)

![](https://github.com/stels24/-Help/blob/main/Пользователи%20загруженные%20в%20БД.png)

В качестве БД выбран sqlite. В качестве ORM использовалась Django ORM, а в качестве системы по управлению миграциями также используется Django. Никаких дополнительных инструментов для поддержки миграций устанавливать не требуется.

Все основные функции, включая создание проекта, приложения, запуск или работу с миграциями выполняются через системный файл manage.py. Фреймворк требует от разработчика соблюдение определенной дисциплины, поэтому весь написанный код должен находиться в определенных файлах, например модели приложений или отображения (views) должны находиться в файлах models.py и views.py в корне каталога приложения. А файл с маршрутами urls.py должен находиться в корне каталога проекта.

Общие впечатления: основным минусом работы с Django на мой взгляд не самая быстрая скорость работы (FastAPI работает значительно быстрее), но это не перекрывает плюсы фреймворка: наличие четкой структуры проекта. Присутствие Административной панели "из коробки" позволяет удобно манипулировать данными, включая полный CRUD. К минусам возможно отнести стандартный шаблонный язык Django (Django Template Language), который не до конца совместим с Jinja2, хотя и имеет такой же синтаксис. Но если быть до конца честным, Django позволяет настроить Jinja2, но это требует дополнительных манипуляций со стороны разработчика. Другим минусом считаю интуитивно непонятный перевод Django из режима отладки в 'боевой' режим, т.к. это требует изменения не только DEBUG, но и других параметров (ALLOWED_HOSTS, настройки статики и т.д.). Но это мое чисто субъективное мнение.


Выводы по работе приложений:

Каждый фреймворк имеет свою нищу для применения, несмотря на свои плюсы и минусы. Таким образом, можно выделить основные моменты.

Flask:

Плюсы: Легковесный и гибкий, легко осваивается, большое сообщество и много расширений.
Минусы: Ограниченный функционал "из коробки", для сложных проектов требует больше настроек.
Когда использовать: Идеален для небольших проектов, прототипов, микросервисов или простых API.

FastAPI:

Плюсы: Высокая производительность, поддержка асинхронности, автоматическая генерация документации.
Минусы: Новое сообщество, меньше готовых решений.
Когда использовать: Отличен для высоконагруженных API и приложений с большим количеством запросов.

Django:

Плюсы: Полный набор инструментов для разработки веб-приложений, безопасность, быстрое прототипирование.
Минусы: Тяжелый для небольших проектов, сложнее в освоении.
Когда использовать: Подходит для крупных приложений с комплексной бизнес-логикой, таких как интернет-магазины и CRM-системы.
