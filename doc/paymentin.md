# Список документов (paymentin)
## Описание модели: Cписок документов "Платежное поручение входящее"

URL ресурса: https://myaccount.business.ru/api/rest/paymentin.json

Разрешенные запросы: get(чтение), post(создание), put(изменение), delete(удаление)

|Параметр	|Тип	|Описание|
|-----------|-------|----------|
|id	    |int|Идентификатор
|number	|string				Номер документа
|date	|datetime				Дата документа
|author_employee_id	|int|	Ссылка на сотрудника, автора документа
|organization_id	|int	|Ссылка на организацию, оформившей документ
|payment_type	|int				Флаг вида платежа (1-запланированный, 2-совершенный)
|operation_id	|int	post	paymentinoperations		Ссылка на вид операции
|current_account_id	|int		currentaccounts		Ссылка на расчетный счет
|sum	|float	|			Сумма
|nds_id	|int|				Ссылка на НДС
|nds_sum|	float|				Сумма НДС
|currency_value	|float|				Текущий курс валюты
|partner_id	|int|		Ссылка на контрагента
|partner_current_account_id||Ссылка на расчетный счет контрагента
|income_number|string|Номер входящий
|income_date|date|Дата входящая
|target	|string|Назначение платежа
|departments_ids	|int[]|	Массив ссылок на отделы
|owner_employee_id	|int|Ссылка на сотрудника - владельца
|[deleted]	        |bool|Строка удалена (перемещена в корзину)
