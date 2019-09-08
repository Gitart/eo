# Project

|Field|Type|Description
|-----|----|-----------|
|Id|int|Уникальный первичный ключ
|Name|str|Наименование
|Code|str|Уникальный код 
|Date|date|Дата старта
|DateEnd|date|Дата финиша
|ManagerId|int|Ид менеджера
|Descript|str|Описание
|Status|int|Статус Ид проекта
|Sum|int|Сумма проекта


## Status
|Field|Type|Description
|-----|----|-----------|
|Id|int|Уникальный первичный ключ
|Name|str|Наименование


## Описание статусов
|Name|Description|
|-----|----|
|Plan|Плановый|
|Active|Активный текущий|
|Wait|Ожидание утверждения|
|Close|Закрытый|
|Archive|Архивный|


# Users

|Field|Type|Description
|-----|----|-----------|
|Id|int|Уникальный первичный ключ
|Login|str|Логин
|Password|str|Hash Passwords
|Fist_name|str|Фамилия
|Middle_name|str|Имя
|Last_name|str|Отчество
|Email|str|Почта
|Mob|str|Мобильный телефон
|Workmob|str|Рабочий моб телефон
|Position|str|Должность
|Departments_id|int|Отдел
|Branch_id|int|Филиал
|Оrganization_id|id|Компания
|Status_id|str|Статус


## Описание статусов
|Name|Description|
|-----|----|
|Plan|Соискатель|
|Active|Активный|
|Faire|Уволен|
















