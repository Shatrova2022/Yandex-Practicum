# Анализ оттока клиентов банка «Метанпром».

## Описание проекта
Датасет содержит данные о клиентах банка «Метанпром». Банк располагается в Ярославле и областных городах: Ростов Великий и Рыбинск.Заказчиком является отдел маркетинга.

## Описание данных:
* userid — идентификатор пользователя,
* score — баллы кредитного скоринга,
* City — город,
* Gender — пол,
* Age — возраст,
* Objects — количество объектов в собственности,
* Balance — баланс на счёте,
* Products — количество продуктов, которыми пользуется клиент,
* CreditCard — есть ли кредитная карта,
* Loyalty — активный клиент,
* estimated_salary — заработная плата клиента,
* Churn — ушёл или нет.

## Цель исследования:
* сформулировать основные выводы и предложите рекомендации для стратегии взаимодействия с клиентами и их удержания(выделить целевые группы клиентов,предложить меры по снижению оттока,определить другие особенности взаимодействия с клиентами);
* спрогнозировать вероятность оттока для каждого клиента;
* сформировать типичные портреты клиентов: эффективно выделить сегменты;
* проанализировать основные признаки, наиболее сильно влияющие на отток;
* предотвратить отток.

## Описание работы.
Спрогнозирована вероятность оттока; сформированны типичные портреты пользователей: сегментированы по группам, охарактеризованы их основные свойства; проанализированы основные признаки, наиболее сильно влияющие на отток. Проверены гипотезы: о различии среднего уровня заработной платы и о различии среднего возраста клиентов, которые ушли в отток и тех, кто остался.	

## Рекомендации для стратегии взаимодействия с клиентами и их удержания:

Необходимо исследовать филиал в Ростове Великом, провести анализ качества предоставляемых услуг т.к. отток клиентов в данном филиале выше, чем в Ярославле или Рыбинске.

Разобраться с пропусками в столбце баланса. Это может быть результатом того, что система так распознает тех, у кого нет дебетовой карты. Такие случаи выявлены только в в Ярославле и Рыбинске.Нужно проверить способы сбора информации и выгрузки данных.

Провести акцию по удержанию и увеличения лояльности клиентов женского пола, например повысить кешбек на категории услуг и товаров для женщин (салоны красоты и пр.) 

Возраст оказал наибольшее влияние на тех, кто ушёл в отток. Для удержания клиентов в возрасте от 41 до 65 лет, можно предложить продукты, для обеспечения стабильного финансового положения (# подарить акции или другие финансовые инструменты).

Провести анализ оттока клиентов по каждому продукту, а не просто по их количеству. Выявить какой продукт дает 100% оттока, т.к. при анализе было выявлено, что если человек пользуется 4 продуктами, он точно уйдет из банка.
