### Design AB testing

Выявление особенностей данных. Здесь наша основная цель — составить общее представление о данных. Нет точного алгоритма, который покажет вам все нужные метрики по данным, но попробуйте отталкиваться от того, что вы хотите сделать дальше. Если вы работаете с уже знакомыми данными, то, скорее всего, для вас этот пункт не особо важен. Если же нет, можете опираться на следующие базовые вопросы:

- За какой период представлены данные?
- Какое уникальное количество каждой сущности? Какие у них распределения?
- Если мы имеем дело с транзакциями, то какое в среднем количество покупок с каким средним чеком совершают пользователи за некоторый период времени?
- если имеем дело с мобильными приложениями и подписками, то какой у них retention и с каким чеком?

Сбор необходимых метрик. Обычно мы работаем с гипотезами, которые растят какую-то часть нашей воронки, поэтому на данном этапе мы будем её восстанавливать в разных разрезах/сегментах/когортах.

Оценка возможного влияния. На этом этапе наша задача состоит в том, чтобы оценить сверху и снизу, насколько предполагаемое решение может изменить ключевую метрику. Тут можно брать значения, которые точно не вписываются в адекватную картину мира :)

Подведение итогов. Здесь мы принимаем решение о том, стоит ли точно принять/отвергнуть придуманную гипотезу, либо однозначного ответа не было найдено, и надо проводить А/B-тест.