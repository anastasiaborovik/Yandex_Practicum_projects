# Прогнозирование оттока клиентов для оператора связи 📉

## Описание проекта 
Оператор связи запускает инициативу по снижению оттока клиентов. Для этого необходимо построить инструмент, который сможет заранее выявлять пользователей, планирующих разорвать договор. Компания планирует предлагать таким клиентам персонализированные условия и промокоды, чтобы удержать их.

## Цель исследования 
Построить модель машинного обучения для предсказания вероятности расторжения договора клиентом.

## Инструменты и навыки
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/-NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/-Matplotlib-ffffff?style=for-the-badge&logo=matplotlib&logoColor=black) ![Seaborn](https://img.shields.io/badge/-Seaborn-2C5BB4?style=for-the-badge&logoColor=white) ![CatBoost](https://img.shields.io/badge/-CatBoost-ff8c00?style=for-the-badge&logo=catboost&logoColor=white) ![LightGBM](https://img.shields.io/badge/-LightGBM-5DBB63?style=for-the-badge&logo=lightgbm&logoColor=white) ![Scikit-learn](https://img.shields.io/badge/-Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

## Основные этапы исследования

1) **Подготовка данных**: Предварительный анализ, предобработка данных.
2) **Анализ данных**: Выявление закономерностей и корреляций, отбор важных признаков.
3) **Обучение и тестирование моделей**: Обучение нескольких моделей и выбор лучшей на основе метрик.

## Выводы и результаты

В результате тестирования 5 моделей лучшей оказалась **CatBoostClassifier** с **ROC-AUC** на тестовой выборке **0.961**. Были выявлены наиболее важные для модели признаки.
Разработанная модель позволяет оператору выявлять клиентов с высоким риском расторжения договора и предлагать им персонализированные условия, что способствует снижению оттока.
