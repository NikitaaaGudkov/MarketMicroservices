# Список сервисов:
1. база данных postgres
2. админер
3. редис (кеширование, но время жизни объектов надо настраивать в редис-коммандере)
4. редис коммандер
5. клиентская база (со своей базой данных)
6. WareHouse (с базой продуктов, категорий и складов, на которых эти продукты расположены)
7. маркет, где совершаются покупки клиентами со склада (со своей базой данных также)