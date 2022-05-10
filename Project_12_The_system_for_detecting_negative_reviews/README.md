# Система определения негативных рецензий

*Описание:*  

Разработать систему фильтрации и категоризации рецензий фильмов, чтобы:  
- Научить модель автоматически обнаруживать негативные отзывы, используя набор данных рецензий фильмов IMBd с маркировкой полярности.

*Инструменты:*  

Pandas, Matplotlib, Numpy, Math, Seaborn, Sklearn, Tqdm, Nltk, Lightgbm

*Выводы:*  

Всего было проанализировано 3 модели, среди которых:

|модели|время обучения|качество valid(F1_score)|
|---|---|---|
|LogisticRegression|5.49s|0.77|
|DecisionTree|31.6s|0.65|
|CatBoost|3m 27s|0.68|

- Лучшая оценка на модели Logistic Regression - модель с наилучшим значением F1, равным 0.77 на тестовой выборке и на валидационной. Время обучения в среднем равно 0.5 секундам.
________________________________________________________________________________________________________________________________________
# The system for detecting negative reviews

*Description:*

Develop a system for filtering and categorizing movie reviews in order to:
- Train the model to automatically detect negative reviews using the polarity-labeled IMDb movie review dataset.

*Tools used:*

Pandas, Matplotlib, Numpy, Math, Seaborn, Sklearn, Tqdm, Nltk, Lightgbm

*Findings:*

A total of 3 models were analyzed, including:

|models|training time|quality valid(F1_score)|
|---|---|---|
|LogisticRegression|5.49s|0.77|
|DecisionTree|31.6s|0.65|
|CatBoost|3m 27s|0.68|

- The best estimate on the Logistic Regression model is the model with the best F1 value equal to 0.77 on the test set and on the validation one. The training time is on average 0.5 seconds.

