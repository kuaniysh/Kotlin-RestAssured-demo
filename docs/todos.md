
[← back️](../readme.md)

#  Что улучшить

- Схемы сгенерировал на коленке через [app.quicktype.io](https://app.quicktype.io/)
- Было бы круче извлекать из swagger-а перед запуском тестов, но простого способа не нашел
- На реальных данных обойти все аккаунты будет невозможно, нужно придумывать компромисс
- К сожалению, matchesJsonSchemaInClasspath обрывается на первой ошибке, и неочевидно какие еще несоответствия есть, можно было бы прокачать, но лапки.
- Аналогичная проблема с проверкой body, авторы rest-assured предлагают использовать [ResponseSpecBuilder](https://github.com/rest-assured/rest-assured/issues/711), но не сообразил как DateMatcher-ы прикрутить.
- Возможно пригодилось бы вкрутить функционал множественных проверок, например [assertK](https://www.kotlinresources.com/library/assertk/)
- Поленился проверять отказы на `POST, PUT, PATCH, DELETE`
- Также не добавлял проверки через https, но вижу что работает
