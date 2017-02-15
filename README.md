# Записки программиста

*Принципы проектирования ПО*
* SOLID (https://ru.wikipedia.org/wiki/SOLID_(объектно-ориентированное_программирование)
* DRY (https://ru.wikipedia.org/wiki/Don’t_repeat_yourself)
* KISS (https://ru.wikipedia.org/wiki/KISS_(принцип))
* YAGNI (https://ru.wikipedia.org/wiki/YAGNI)

*MVP. Android. Манифест.*
* Слой бизнес-логики должен быть реализован отдельным JAVA-модулем.
* Все методы Presenter/View должны возвращать void
* Презентер должен общаться только с одним интерактором.
* Интерактор может внутри (Facade) использовать несколько интеракторов/репозиториев.
* Место cервиса (Service) - в Data.
* На каждом из уровней (data, business, ui) должны быть свои модели и мапперы для них.


*Библиотека программиста*
* Джошуа Блох "Java. Эффективное программирование" (http://www.ozon.ru/context/detail/id/21724143)
* Банда четырех "Приемы объектно-ориентированного проектирования. Паттерны проектирования" (http://www.ozon.ru/context/detail/id/2457392)
* Р. Мартин "Чистый код" (http://www.ozon.ru/context/detail/id/28336354)
* С. Макконел "Совершенный код" (http://www.ozon.ru/context/detail/id/3159814)
* Кент Бек "Экстремальное программирование" (...)
* Michael Feathers "Working effectively with Legacy code" (http://www.ozon.ru/context/detail/id/4311012)
* Мартин Фаулер "Рефакторинг" (http://www.ozon.ru/context/detail/id/1308678)
