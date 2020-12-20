# Проект: «Проект 42. Мобильное приложение»

Группа, ответственная за backend для приложения.

Ссылка на сайт для проекта: http://pd-2020-1.std-826.ist.mospolytech.ru/

## Задачи на проект

## Участники

| Учебная группа | Имя пользователя | ФИО                      | Роль                       |
|----------------|------------------|--------------------------|----------------------------|
| 181-352        | @Facassanxt      | Стебло А.С.              | Разработчик django сервера |
| 181-352        | @TimurChikishev  | Чикишев Т.В.             | Разработчик django сервера |

## Личный вклад участников

### Стебло А.С. 
- Ознакомился с работой прошлой команды - 5 часа
- Ознакомился с использованием Django и Django REST, ORM Django, структурой проекта  Django - 5 часов

####        Общий объем работы оценивается в 10 - часов
------------------------------
### Чикишев Т.В.
- Ознакомился с работой прошлой команды - 5 часа
- Поставил и настроил centos 8 на VirtualBox (т.к. вся разработка будет под эту ОС) - 5 часов
- Ознакомился с использованием Django и Django REST, ORM Django, структурой проекта  Django - 10 часов
- Настроил виртуальное окружение: - 10 часов
  - Установил postgresql-13 
  - Установил и настроил pgadmin4
  - Создал и настроил django api server
- Реализация API - 25
  - Создал множество get запросов (пример: получение списка пользователей, редактирование пользователей...)
  - Столкнулся с проблемой расширения основного класса User 
    - В результате исселедования принял решение создать модель профиля с помощью связи один-к-одному
  - Для авторизации использовал библиотеку djoiser
    - Взял ее т.к. по требованию мобильных разработчиков нужен было токен.
      djoiser позволяет работать с несколькими видами токенов одновременно.
  - Для регистрации возникла потребность автоматически добавлять данные в таблицу профиля
  - Реализовал кастомные сообщения о ошибках
  - Добавил разграничение доступа 
- Исправление багов - 5
    
####        Общий объем работы оценивается в 60 - часа 
------------------------------
