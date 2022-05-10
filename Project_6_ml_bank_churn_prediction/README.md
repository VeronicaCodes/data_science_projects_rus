# Прогнозирование оттока клиентов банка

*Описание и цели:*

Клиенты банка постепенно уходят, и банк пришел к выводу, что дешевле сохранить существующих клиентов, чем привлекать новых. У нас есть данные о прошлом поведении клиентов и расторжении договоров с банком. Нужно спрогнозировать, скоро ли клиент покинет банк. 

*Инструменты:*

pandas, numpy, sklearn, DecisionTreeClassifier, RandomForestClassifier, LogisticRegression, GradientBoostingClassifier

*Выводы:*

|model|f1_valid|AUC ROC|
|---|---|---|
|DecisionTree|0.56|0.82|
|RandomForest|0.60|0.86|
|LogisticRegression|0.45|0.71|
|GradientBoosting|0.60|0.83|

Лучшая оценка - f1_score = 0.60, auc_roc = 0.85 с моделью RandomForest.
________________________________________________________________________________________________________________________________________
# Bank customer churn prediction

*Goals:*

The goal was to predict whether a customer will leave the bank soon. The Bank had provided us with the historical data on clients’ past behavior and termination of contracts with the bank.
It was necessary to build a model with the maximum possible F1 score. The bank's requirement for F1 score was it being equal to at least 0.59 

*Tools used:*

pandas, numpy, sklearn, DecisionTreeClassifier, RandomForestClassifier, LogisticRegression, GradientBoostingClassifier

*Conclusion:*

|model|f1_valid|AUC ROC|
|---|---|---|
|DecisionTree|0.56|0.82|
|RandomForest|0.60|0.86|
|LogisticRegression|0.45|0.71|
|GradientBoosting|0.60|0.83|

'Random Forest Classifier' with max_depth=5 and n_estimators=10 is the best model, with f1 score equal to 0.50, and AUC ROC equal to 0.85.