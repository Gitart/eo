## Справочник товаров и услуг (goods)
Описание модели: Cправочник товаров и услуг

URL ресурса: https://myaccount.business.ru/api/rest/goods.json

Разрешенные запросы: get(чтение), post(создание), put(изменение), delete(удаление)

|Field|Type|Description
|-----|----|-----------|
|Id|int|Уникальный первичный ключ
|name|int|Наименование товара
|full_name|string|Полное наименование товара, используемое в печатных документах
|full_name|string|Ссылка на НДС


nds_id	int		nds		
group_id	int		groupsofgoods		Ссылка на группу товаров
part	string				Артикул
store_code	string				Код товара на складе
type	int				Тип позиции (1-товар, 2-услуга)
archive	bool				Флаг (0-товар не перемещен в архив, 1-товар перемещен в архив)
description	string				Описание товара
country_id	int		countries		Ссылка на страну производителя
gtd	string				Грузовая таможенная декларация
allow_serialnumbers	bool				Флаг (0-учет по серийным номерам запрещен, 1-учет по серийным номерам разрешен)
weight	float				Вес товара
volume	float				Объем товара
code	string				Идентификатор товара
store_box	string				Код ячейки на складе
remains_min	float				Минимально допустимый остаток товара на складе
partner_id	int		partners		Ссылка на поставщика
responsible_employee_id	int		employees		Ссылка на сотрудника, ответственного за товар
images	images				Изображения товара
feature	int				Особенность учёта: 1-весовой, 2-Алкоголь, 3-Пиво
departments_ids	int[]				Массив ссылок на отделы
cost	float				Себестоимость
measure_id	int		measures		Ссылка на основную еденицу измерения товара
[deleted]	bool				Строка удалена (перемещена в корзину)
