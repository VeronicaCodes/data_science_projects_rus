# Прогнозирование оттока клиентов телекоммуникационной компании

*Описание:*  

Клиенты телекоммуникационной компании, предоставляющей услуги интернета и стационарной связи, постепенно уходят. Маркетологи пришли к выводу, что дешевле сохранить существующих пользователей, чем привлекать новых.
У нас есть данные о прошлом поведении клиентов за последние 6 лет.
Нужно спрогнозировать, покинет ли клиент компанию. И сделать ему спецпредложение, чтобы он остался. 

*Инструменты:*  

Pandas, Matplotlib, Seaborn, Numpy, Sklearn, Imblearn, Lightgbm, Xgboost, Catboost

*Выводы:*  

Всего было проанализировано 6 моделей, среди которых:

|Mодель|AUC-ROC|Accuracy|F1-score|train time (sec)|	
|---|---|---|---|---|
|DecisionTreeClassifier|0.80|0.76|0.59|67 s|
|RandomForestClassifier|0.82|0.77|0.57|46 s|
|LogisticRegression|0.80|0.75|0.59|120 s|
|CatBoostClassifier|0.89|0.83|0.69|210 s|
|XGBClassifier|0.87|0.82|0.65|170 s|
|LGBMClassifier|0.85|0.80|0.63|32 s|

- Лучшая оценка -  'roc_auc' = 0.89, 'accuracy' = 0.84 с моделью Catboost.
________________________________________________________________________________________________________________________________________
# Forecasting customer churn for a telecom company

*Description:*

The customers of a telecommunications company that provides Internet and fixed-line services are gradually leaving. Marketers have come to the conclusion that it is cheaper to retain existing clients than to attract new ones.
We have past customer behavior data for the last 6 years.
It is necessary to predict whether the client will leave the company. And make him a special offer to stay.

*Tools used:*

Pandas, Matplotlib, Seaborn, Numpy, Sklearn, Imblearn, Lightgbm, Xgboost, Catboost

*Findings:*

A total of 6 models were analyzed, including:

|Model|AUC-ROC|Accuracy|F1-score|train time (sec)|
|---|---|---|---|---|
|DecisionTreeClassifier|0.80|0.76|0.59|67 s|
|RandomForestClassifier|0.82|0.77|0.57|46 s|
|LogisticRegression|0.80|0.75|0.59|120 s|
|CatBoostClassifier|0.89|0.83|0.69|210 s|
|XGBClassifier|0.87|0.82|0.65|170 s|
|LGBMClassifier|0.85|0.80|0.63|32 s|

- Best score - 'roc_auc' = 0.89, 'accuracy' = 0.84 with Catboost model.