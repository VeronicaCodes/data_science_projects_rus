# Построение модели определения стоимости автомобиля

*Описание:*  

Построение модели для определения стоимости автомобиля для службы продажи подержанных автомобилей, чтобы:
- В дальнейшем разработать приложение для привлечения новых клиентов.

*Инструменты:*  

Pandas, Matplotlib, Seaborn, Numpy, Sklearn, Time, Lightgbm, Xgboost, Catboost

*Выводы:*  

Всего было проанализировано 5 моделей, среди которых были получены следующие результаты:

|модели|время обучениясек|время предсказания|качество(RMSE)|
|---|---|---|---|
|LinearRegression|9с|167 мс|0.59|
|Gradient Boosting|1ч 35м 13с|294 мс|0.4|
|XGBoost|12м 43с|294 мс|0.4|
|LightGBM|13с|0.3 с|0.4|
|CatBoostRegressor|22c|0.5|0.4|

- Лучшая оценка - RMSE = 1889.2 с моделью LightGBM.
________________________________________________________________________________________________________________________________________
# Building an ML model for determining the cost of a car

*Description:*

Building a model for determining the cost of a car for a used car sales service in order to:
- Further develop an application to attract new customers.

*Tools used:*

Pandas, Matplotlib, Seaborn, Numpy, Sklearn, Time, Lightgbm, Xgboost, Catboost

*Findings:*

In total, 5 models were analyzed, among which the following results were obtained:

|models|training timesec|prediction time|quality(RMSE)|
|---|---|---|---|
|LinearRegression|9s|167ms|0.59|
|Gradient Boosting|1h 35m 13s|294ms|0.4|
|XGBoost|12m 43s|294ms|0.4|
|LightGBM|13s|0.3s|0.4|
|CatBoostRegressor|22c|0.5|0.4|

- Best estimate - RMSE = 1889.2 with LightGBM model.
