# Projects

|Field|Type|Description
|-----|----|-----------|
|Id|int|Уникальный первичный ключ
|Name|str|Наименование 
|Description|string|Описание проекта
|Code|str|Уникальный код внутри организации
|Date|date|Дата старта
|DateEnd|date|Дата финиша
|DeadLine|date|Дата сдачи проекта
|ManagerId|int|Ид менеджера
|Descript|str|Описание
|Sum|int|Сумма проекта
|Status|int|Статус Ид проекта
|Remark|string|Примечание



## Status
|Field|Type|Description
|-----|----|-----------|
|Id|int|Уникальный первичный ключ
|Name|str|Наименование


## Описание статусов проекта
|Name|Description|
|-----|----|
|Plan|Плановый|
|Active|Активный текущий|
|Wait|Ожидание утверждения|
|Close|Закрытый|
|Archive|Архивный|

# Teams
|Field|Type|Description
|-----|----|-----------|
|Id|int|Уникальный первичный ключ
|ProjectId|int|Id проекта
|UserId|int|Id пользователя 
|Remark|string|Примечание



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


## Описание статусов пользователей
|Name|Description|
|-----|----|
|Plan|Соискатель|
|Active|Активный|
|Faire|Уволен|
















