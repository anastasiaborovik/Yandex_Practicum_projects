# Прогнозирование заказов такси на следующий час 🚖

## Описание проекта
Исследование направлено на разработку модели машинного обучения для точного прогноза количества заказов такси на следующий час. Используемые данные содержат временные ряды с информацией о количестве заказов такси в аэропортах. Прогнозирование спроса позволит компании оптимизировать количество водителей, доступных в периоды пиковых нагрузок, что улучшит качество обслуживания клиентов.

## Цель исследования
Построить модель машинного обучения для предсказания количества заказов такси на следующий час.

## Инструменты и навыки
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![Matplotlib](https://img.shields.io/badge/-Matplotlib-ffffff?style=for-the-badge&logo=matplotlib&logoColor=black) ![Seaborn](https://img.shields.io/badge/-Seaborn-2C5BB4?style=for-the-badge&logo=seaborn&logoColor=white) ![CatBoost](https://img.shields.io/badge/-CatBoost-F5B42B?style=for-the-badge&logo=catboost&logoColor=black) ![Scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white) ![Statsmodels](https://img.shields.io/badge/-Statsmodels-8E2DF5?style=for-the-badge&logo=statsmodels&logoColor=white)

## Основные этапы исследования
1. **Обзор данных:** загрузка и первичный анализ данных.
2. **Исследовательский анализ данных:** выявление закономерностей, трендов и выбросов.
3. **Создание признаков:** генерация временных признаков для улучшения точности модели.
4. **Обучение моделей:** обучение нескольких моделей и выбор наилучшей по метрике RMSE.
5. **Анализ результатов:** тестирование модели, оценка её точности и проверка на адекватность.

## Выводы и результаты
В ходе исследования была разработана модель для прогнозирования количества заказов такси на следующий час. Наилучшие результаты показала модель **CatBoostRegressor** с метрикой RMSE тестовой выборке **39.1100**.
Разработанная модель позволит компании:
- Привлекать больше водителей в периоды пиковых нагрузок.
- Оптимизировать логистику, улучшая клиентский сервис.

![Сравнение реальных и прогнозных значений](time_series_plot.jpg?raw=true "Title")
