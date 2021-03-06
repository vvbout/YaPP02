# YaPP02

## Real estate ads on apartment sale research (SPB region 2014-2019)

## Продажа квартир в Санкт-петербурге - анализ рынка недвижимости

**Задача:** установить типичные параметры квартир, влияющие на стоимость объекта недвижимости

Предобработка данных, исследовательский анализ данных, визуализация данных

**Язык:** Python

**Библиотеки:** Pandas, Matplotlib

**Выводы:**

Исследование данных, предоставленных сервисом Яндекс.Недвижимость за период 2014 - 2019 гг., показало, что:
* такие параметры, как: количество комнат, общая площадь, высота потолков, практически не имеют влияния на стоимость м2.
* Этаж с точки зрения этажа традиционно самое низкое ценовое предложение соответствует первому этажу, затем идет последний. Выше всего ценятся другие этажи.
* Ключевым параметром, влияющим на ценообразование, является принадлежность к населенному пункту. Анализ рейтинга ТОП 10 списка по количеству объявлений показал, что разница между средним предложением по г. Санкт - Петербургу и ближайшим вторым городом списка (г. Пушкин) составляет 5%, разница с поледним городом списка ТОП 10 (г. Выборг) составляет 45%.
* В рамках мегаполиса (г. Санкт - Петербург) ключевым параметром является удаленность от центра. Для г. Санкт - Петербург центральная зона была определена радиусом 5 км и совпала с границами Центрального района + 2 км застройки премиум класса. В среднем цена за м2 в центре на 14% превышает цену по городу.
* Влияние периода размещения объявлений (год, месяц, день недели) на ценообразование имеет общие тренды, которые совпадают с трендами развития экономики и деловой активности.

В качестве рекомендаций по результатм исследования следует отметить:
* повысить полноту данных, получаемых автоматически из сервисов Яндекса: предоставленные данные содержат от 23,28% до 65,91% пропущенных значений.
* Разработать алгоритм действий по отношению к объявлениям, которые переходят в категорию экстремально долгих продаж, которые составили 1 674 объявления: необычно долгие продажи происходят в период свыше 512 дней.
* Разработать алгоритм действий по отношению к объявлениям, которые остаются не закрытыми - 3 181 объявление.
* Добавить в объявления параметры, которые действительно влияют на стоимость м2: год постройки дома, тип постройки (кирпич, панель, монолит....)
