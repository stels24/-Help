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

# **Django**

Требования к функционалу вебприложения Список задач.

1. Регистрация и авторизация пользователей с сохранением в базе данных.
   
2. После авторизации пользователь попадает в форму Дашбод.

3. Требования к web-приложению. Список задач.
   - Добавление, редактирование и удаление задач.
   - Отметка задач как выполненных.
   - Фильтрация задач по статусу (все, активные, выполненные).
   - Возможность сортировки по дате создания или приоритету.
   - Возможность создания базы данных через "Admin"- панель
   - Проверка внесенных данных в БД и их редактирование

Структура дериктории django_mike

![](https://github.com/stels24/-Help/blob/main/Структура%20каталога%20файлов%20в%20Django.png)

## 4. Структура сайта.

4.1. После запуска кода в командной строке (python manage.py runserver) перехоим по адресу: http://127.0.0.1:8000/dashboard/ (локально)
где появляется возможность добавлять пользователя и задачи.

![]([https://github.com/stels24/-Help/blob/main/Кнопка%20редактирования.png](https://github.com/stels24/-Help/blob/main/Дашборд%20в%20Django.png))

4.2. Набрав адрес на странице (http://127.0.0.1:8000/admin/) переходим в панель администрирования Django, где появляется возможность добавления одиночных пользователей, групп пользователей, категорий, задач.

![](https://github.com/stels24/-Help/blob/main/Добавление%20задачи%20и%20пользователя%20Django.png)

![](https://github.com/stels24/-Help/blob/main/Заполнение%20полей%20пользователя%20в%20БД%20Django.png)

![](https://github.com/stels24/-Help/blob/main/Создание%20Категории%20Django.png)

![](https://github.com/stels24/-Help/blob/main/Создание%20группы%20пользователей%20Django.png)

![](https://github.com/stels24/-Help/blob/main/Созданные%20ранее%20категории%20Django.png)

4.3 Установив отдельное приложение DB Browser, можем осуществлять просмотр и редактирование информации в БД


![](https://github.com/stels24/-Help/blob/main/Задачи%20в%20БД.png)

![](https://github.com/stels24/-Help/blob/main/Пользователи%20загруженные%20в%20БД.png)
