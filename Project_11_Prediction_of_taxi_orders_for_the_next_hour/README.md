# Прогнозирование количества заказов такси в следующий час

*Описание:*  

Предсказать количество заказов такси на следующий час в аэропорту, чтобы:
- Привлечь большее количество водителей в часы пик.

*Инструменты:*  

Pandas, Matplotlib, Seaborn, Numpy, Sklearn, Time, Lightgbm, Xgboost, Catboost, Statsmodels

*Выводы:*  

Всего было проанализировано 4 модели, среди которых были получены следующие результаты:

|модели|время обучения/сек|качество valid(RMSE)|
|---|---|---|
|LinearRegression|0.00645|42.7|
|RandomForest|0.884|36.9|
|CatBoost|4.91|33.6|
|LightGBM|2.17|34.0|

- Лучшая модель - Catbost. Это модель с наилучшим RMSE, равным 44.6 на тестовой выборке и 33.6 на валидационной. Время обучения в среднем равно 4 секундам.
________________________________________________________________________________________________________________________________________
# Predicting the number of taxi orders for the next hour

*Description:*

Predict the number of taxi orders for the next hour at the airport in order to:
- Attract more drivers during peak hours.

*Tools used:*

Pandas, Matplotlib, Seaborn, Numpy, Sklearn, Time, Lightgbm, Xgboost, Catboost, Statsmodels

*Findings:*

In total, 4 models were analyzed, among which the following results were obtained:

|models|training time/sec|quality valid(RMSE)|
|---|---|---|
|LinearRegression|0.00645|42.7|
|RandomForest|0.884|36.9|
|CatBoost|4.91|33.6|
|LightGBM|2.17|34.0|

- The best model - Catbost. This is the model with the best RMSE of 44.6 on the test set and 33.6 on the validation set. The training time is on average 4 seconds.