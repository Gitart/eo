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


## Status
|Name|Description|
|-----|----|
|Plan|плановый|
|Active|активный текущий|
|Wait|ожидание утверждения|
|Close|закрытый|

