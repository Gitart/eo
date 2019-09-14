# Список кассовых чеков (retailchecks)
## Описание модели: Cписок кассовых чеков

URL ресурса: https://myaccount.business.ru/api/rest/retailchecks.json

Разрешенные запросы: get(чтение), post(создание), put(изменение), delete(удаление)

|Параметр	|Тип|	Описание|
|---------|---|---------|
|id|int|Идентификатор
|date	|datetime	|	Дата и время документа
|number	|string	|	Номер документа
|cashier_id	|int|	Ссылка на сотрудника-кассира
|retail_point_id|	int|			Ссылка на розничную точку
|kkm_id	|int|		Ссылка на ККМ
|held|	bool|		Флаг (0-документ не проведен, 1-документ проведен)
|retail_shift_id|	int	|		Ссылка на смену
|seller_id	|int|				Ссылка на сотрудника-продавца
|discount_card_id	|int|			Ссылка на дисконтную карту
|pay_cash	|float|			Оплачено наличными
|pay_cashless	|float	|			Оплачено безналичными
|online_pay	|bool	|			TRUE - чек по онлайн-оплатам; FALSE - обычный чек
|affect_on_store	|bool|				TRUE - чек влияет на остатки; FALSE - чек не влияет на остатки
|check_type	|int|				Тип чека: 0 - Приход , 1 - Расход
|nds_include	|int|				Учёт НДС: 1 - Цена включат НДС, 2 - Цена не включат НДС, 3 - без НДС
|updated	|datetime|				Время последнего обновления
|deleted	|bool|				Строка удалена (перемещена в корзину)
