Этот датафрейм содержит данные о характеристиках страхователей (пол, возраст, индекс массы тела, регион и т.д.) и значение страховой премии, которые понесёт клиент.

Задача: Построить оптимальную модель *RandomForestRegressor*, предсказывающую размер страховой премии по характеристикам клиента (страхователя).

В результате:

1) Получена модель, имеющая усреднённые (после кросс-валидации) метрики ошибок:

R²: 0.86

MAE: 2496

RMSE: 4538

MAPE: 28.7 %

2) Выявлено, что наиболее важными признаками для предсказания являются: возраст, индекс массы тела и является ли клиент курильщиком.

3) Полученная модель может быть использована в качестве бота на сайте страховой компании для автоматизации консультирования клиентов.
