## Запросы 

### Вопрос: Какой запрос(-ы) отправляется на сервер для получения списка типов товаров в шторке "Каталог"?

Ответ:
POST	https://sbermegamarket.ru/api/mobile/v1/catalogService/catalog/menu

### Вопрос: Какой запрос(-ы) отправляется на сервер при использовании поиска товаров в каталоге?

Ответ: 
POST https://sbermegamarket.ru/api/mobile/v1/catalogService/catalog/search

POST https://sbermegamarket.ru/api/mobile/v1/catalogService/filters/search

POST https://sbermegamarket.ru/api/mobile/v3/catalogService/catalog/searchSuggest

### Вопрос: Какой запрос(-ы) отправляется на сервер при поиске региона или города в модалке выбора вашего региона?

Ответ:
POST https://sbermegamarket.ru/api/mobile/v1/addressSuggestService/address/suggest
