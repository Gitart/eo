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

# Task
|Field|Type|Description
|-----|----|-----------|
|Id|int|Уникальный первичный ключ
|Name|string|Наименование|
|Resp|int|Отвественный|
|HourPlan|int|Плановые часы|
|HourFact|int|Фактические часы|
|Approve|int|Утврежденные часы|
|Status|int|Статус Ид проекта|
|Task_type_id|int|Ссылка на тип задачи
|description|	string|Описание задачи
|Author_employee_id|int|	Ссылка на сотрудника, автора документа
|participants_ids	|int[]|	Массив ссылок на участников
|performer_id	|int|	Ссылка на сотрудника-исполнителя
|partner_id	|int|	Ссылка на контрагента
|partner_phone_id	|int	|Ссылка на контактную информацию (телефон) контрагента
|partner_employee_id|	int|Ссылка на контактное лицо контрагента
|partner_employee_phone_id|	int|Ссылка на контактную информацию (телефон) контактного лица контрагента
|date_time_begin|	datetime|	Дата и время начала
|date_time_end	|datetime	|	Планируемые дата и время окончания
|result|	string|	Результат выполнения задачи
|deal_id|	int|Ссылка на сделку
|done|	bool|	Флаг "Задача выполнена"
|date_time_done	|datetime	|			Фактические дата и время окончания
|vdone_employee_id|	int	|	Ссылка на сотрудника, закрывщего задачу
|allday|	bool|	Флаг "Задача на весь день"
|private|	bool|	Флаг "Личное"
|where|	string|	Место встречи
|status_id|	int| на статус задачи
|updated	|datetime|Время последнего обновления
|deleted|	bool	|Строка удалена (перемещена в корзину)















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
















