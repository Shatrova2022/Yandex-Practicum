# Yandex-Practicum
Projects completed during the training of the YaP.

| Название проекта                                           | Описание                                                                                                                                                                                                                                                                                                                                                                                                                              | Используемые библиотеки                                                                                        |
|------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------|
| [Исследования надежных заёмщиков — анализ банковских данных](https://github.com/Shatrova2022/Yandex-Practikum/tree/main/%D0%98%D1%81%D1%81%D0%BB%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F%20%D0%BD%D0%B0%D0%B4%D0%B5%D0%B6%D0%BD%D1%8B%D1%85%20%D0%B7%D0%B0%D1%91%D0%BC%D1%89%D0%B8%D0%BA%D0%BE%D0%B2%20%E2%80%94%20%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D0%B1%D0%B0%D0%BD%D0%BA%D0%BE%D0%B2%D1%81%D0%BA%D0%B8%D1%85%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85) | На основе данных кредитного отдела банка исследуется влияние семейного положения и количество детей по факту исключения кредита на срок. Была получена информация о данных. Определенны и обработанны пропуски. Заменены типы данных на соответствующие хранящимся данных. Удалены дубликаты. Категоризованы данные. Один датафрейм декомпозирован на три.                                                                                    | предобработка данных,Python,Pandas                                                                               |
| [Определение выгодного тарифа для телеком компании](https://github.com/Shatrova2022/Yandex-Practikum/tree/main/%D0%9E%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B2%D1%8B%D0%B3%D0%BE%D0%B4%D0%BD%D0%BE%D0%B3%D0%BE%20%D1%82%D0%B0%D1%80%D0%B8%D1%84%D0%B0%20%D0%B4%D0%BB%D1%8F%20%D1%82%D0%B5%D0%BB%D0%B5%D0%BA%D0%BE%D0%BC%20%D0%BA%D0%BE%D0%BC%D0%BF%D0%B0%D0%BD%D0%B8%D0%B8)          | Проведен предварительный анализ использования тарифов на выборке клиентов, проанализировано поведение клиентов при использовании услуг оператора и рекомендованы оптимальные наборы услуг для пользователей. Проведена предобработка данных,и их анализ. Проверены гипотезы о различии выручки абонентов разных тарифов и различия выручки абонентов из Москвы и других регионов.                                                      | Matplotlib,NumPy,Pandas,Python,SciPy,описательная статистика, проверка статистических выводов                  |
| [Анализ оттока клиентов банка](https://github.com/Shatrova2022/Yandex-Practikum/tree/main/%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D0%BE%D1%82%D1%82%D0%BE%D0%BA%D0%B0%20%D0%BA%D0%BB%D0%B8%D0%B5%D0%BD%D1%82%D0%BE%D0%B2%20%D0%B1%D0%B0%D0%BD%D0%BA%D0%B0)                               | Спрогнозирована вероятность оттока; сформированны типичные портреты пользователей: сегментированы по группам, охарактеризованы их основные свойства; проанализированы основные признаки, наиболее сильно влияющие на отток. Проверены гипотезы: о различии среднего уровня заработной платы и о различии среднего возраста клиентов, которые ушли в отток и тех, кто остался.                                                              | Matplotlib, Pandas, Python, Scikit-learn, Seaborn, классификация, кластеризация, Tableau, построение дашбордов |
| [A/B-тестирование новой рекомендательной системы.](https://github.com/Shatrova2022/Yandex-Practikum/tree/main/AB-%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BD%D0%BE%D0%B2%D0%BE%D0%B9%20%D1%80%D0%B5%D0%BA%D0%BE%D0%BC%D0%B5%D0%BD%D0%B4%D0%B0%D1%82%D0%B5%D0%BB%D1%8C%D0%BD%D0%BE%D0%B9%20%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D1%8B)          | В ходе разработки проекта, мной были исследованы аналитики событий. Я построила воронку событий, исследовала пути пользователей до покупки. Проанализировала результаты A/B-теста, связанные с улучшением рекомендательной система. Сравнила 2 контрольных группы между собой, убедилась в правильном разделении трафика, а затем сравнила с тестовой группой. Выявлено, что улучшения не повлияли на поведении пользователей. | A/B-тестирование,Matplotlib,Pandas,Python,SciPy,проверка статистических гипотез                                |
