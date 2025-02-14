# Определение рыночной стоимости автомобилей 🚗

## Описание проекта

Исследование посвящено разработке модели машинного обучения для оценки рыночной стоимости автомобилей на основе их технических характеристик. Данные включают сведения о пробеге, комплектациях и ценах автомобилей. 

## **Цель исследования:**
Построить модель машинного обучения для точного предсказания рыночной стоимости автомобилей. В качестве критериев выбора лучшей модели должны использоваться: качество предсказания, время обучения и время предсказания.

## Инструменты и навыки
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![Seaborn](https://img.shields.io/badge/-Seaborn-2C5BB4?style=for-the-badge&logo=seaborn&logoColor=white) ![scikit-learn](https://img.shields.io/badge/-Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white) ![LightGBM](https://img.shields.io/badge/-LightGBM-02569B?style=for-the-badge&logo=lightgbm&logoColor=white)  

## Основные этапы исследования

1. **Обзор данных:** анализ структуры, пропусков и типов данных.
2. **Предобработка данных:** устранение пропусков, дубликатов, ошибочных значений.
3. **Исследовательский анализ данных:** подробный анализ всех признаков, выявление аномалий.
4. **Корреляционный анализ данных:** выявление взаимосвязей между признаками.
5. **Обучение моделей:** обучение нескольких моделей машинного обучения с подбором гиперпараметров.
6. **Анализ результатов:** тестирование моделей, выбор наилучшей.

## Выводы и результаты

Наилучшее качество предсказаний с наименьшим значением **RMSE (1565.78 евро)** показала **LGBMRegressor**. Время обучения: **12.3** секунд. Время предсказания: **3.1** секунд. 
Результаты исследования помогут сервису принять обоснованные решения при разработке приложения, обеспечивая высокую точность оценок рыночной стоимости автомобилей.

![Сравнение моделей](car_price_plot.jpg?raw=true "Title")
