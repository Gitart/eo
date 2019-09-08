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
|Fistname|str|Фамилия
|Middlename|str|Имя
|Lastname|str|Отчество
|Email|str|Почта
|Mob|str|Мобильный телефон
|Workmob|str|Рабочий моб телефон
|Position|str|Должность
|Department|int|Отдел
|Branch|int|Филиал
|Company|id|Компания
|Status|str|Статус

















