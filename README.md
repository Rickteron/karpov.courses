## Описание:
В репозитории представлены проекты курса [Аналитик данных](https://karpov.courses/analytics) (karpov.courses).

## Основные инструменты и навыки, полученные при обучении:
- Языки: Python, SQL
- Анализ данных: библиотеки Pandas, NumPy, SciPy, Statsmodels
- Построение запрсов на языке (Выгрузка и предобработка данных при помощи SQL): ClickHouse (Tabix), PostgreSQL (Redash)
- Визуализация: Matplotlib, Plotly, Seaborn
- Построение дашбордов: Tableau, Redash
- Метрики юнит-экономики, когортный анализ
- А/В-тестирование
- Работа с гипотезами


Проекты:
Питон:
1. 


## Проекты:
| №| Название и ссылка | О чем проект                                                     | Навыки и инструменты           |  
|-----------|-------------------|------------------------------------------------------------------|-----------------------------------|
|1              |[Финальный проект. Аналитика мобильных игр](mobile_games/)|1. Необходимо написать функцию удобного расчёта такого важного показателя как retention. 2. Посчитать А/В тест и проанализировать его показатели. 3.Разработать систему метрик для оценки результатов последнего прошедшего тематического события в игре|`Python` `Pandas` `Matplotlib` `Seaborn` `A/B-тестирование` `проверка статистических гипотез` `продуктовые метрики`|
|2              |[Аналитика e-commerce](e-com/)|Детализация по причинам возврата товаров, Retention когорт пользователей, PFM-сегментация пользователей| `Python` `Pandas` `исследовательский анализ данных` `визуализация данных` `RFM-сегментация`|
|3              |[A/A-тест. Проверка качества системы сплитования.](AA-test/)|Проверка метрик качества системы сплитования (FPR). Проверка работы системы на разных группах, выявление проблемной версии продукта|`Python` `Pandas` `Matplotlib` `SciPy` `A/A-тестирование`|
|4              |[Исследование данных о бронировании отелей](Hotel_booking/)|EDA и предобработка данных. Отработка основных навыков по работе с таблицами в pandas: группировка, аггрегация, фильтрация, сортировка,  изменения столбцов| `Python` `Pandas` `предобработка данных` `исследовательский анализ данных`|
|5              |[Работа с датой и временем](telemarketing/)|Нужно проверить подключения продуктов определенным пользователям, соединив файлы о продажах с логами по подключениям в системе|`Python` `Pandas` `предобработка данных` `исследовательский анализ данных`|
|6              |[ETL (PYTHON + SQL)](SQL/)|Выгружаем нужные данные из ClickHouse и анализируем их в python. |`SQL` `ClickHouse` `Python` `Pandas` `Seaborn` `визуализация`|
|7              |[Дашборд для HR отдела.](Dashboard/)|Сбор требований от заказчика и построение дашборда в Tableau.|`Tableau` `построение дашбордов` `визуализация данных`|
|14             |[Выпускной проект](graduation_project/). [Банки — cегментация пользователей по потреблению продуктов](https://github.com/ovalentinka/Data_analyst/blob/c2e103c7f7d92711fbd40179cdc8134f6d8eccca/graduation_project/yandex_ex1_bank_karpova_new.ipynb), [Презентация](https://github.com/ovalentinka/Data_analyst/blob/3bf2397fe88cd31b36c5b31d4de416e04f80fd63/graduation_project/yandex_ex1_bank_prez_ovkarpova.pdf) и [Дашборд](https://public.tableau.com/app/profile/oxana3540/viz/product_activity/Dashboard1); [А/B тестирование](https://github.com/ovalentinka/Data_analyst/blob/c2e103c7f7d92711fbd40179cdc8134f6d8eccca/graduation_project/yandex_ex2_ab_karpova_new.ipynb), [SQL](https://github.com/ovalentinka/Data_analyst/blob/3e4272acf1b22cbf9e49706375ad128ead6b89b8/graduation_project/yandex_ex3_SQL_karpova_new.ipynb)|Анализируем заемщиков банка (результат оформляем в виде Презентации), проверяем результаты А/B тестирования и подтверждаем гипотезы, разрабатываем дашборд в Tableau Public. изучаем мобильное приложение посредством SQL-запросов. |`SQL` `PostgreSQL` `Python` `Pandas` `Scikit-learn` `Matplotlib` `Seaborn` `машинное обучение` `классификация` `кластеризация` `Tableau` `продуктовые метрики` `построение дашбордов` `A/B-тестирование` `проверка статистических гипотез`|
