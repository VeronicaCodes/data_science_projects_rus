# Разработка алгоритма преобразования данных

*Описание и цели:*  
Создать алгоритма преобразования данных (маскирование данных на основе обратимой матрицы) для страховой компании, который:
- затруднит восстановление личной информации из конвертированных данных, защитив их.

*Инструменты:*  
Pandas, Matplotlib, Seaborn, Numpy, Sklearn, Scipy

*Выводы:*  
-После обучения моделей до и после шифрования оригинальных данных методом умножения на обратимую матрицу, и сравнениях результатов их RMSE, видно, что RMSE (то есть, качество самой модели) в обеих матрицах одинаково.  Когда мы умножаем наши характеристики на обратимую матрицу, у нас все равно остается та же оценка R2, w0 (intercept), но w (вектор) отличается, потому что мы использовали замаскированные функции для вычисления w (вектора). Алгоритм хорошо работает вручную и со sklearn.
________________________________________________________________________________________________________________________________________
# Development of the data transformation algorithm

*Description:*

Create a data transformation algorithm (data masking based on an invertible matrix) for an insurance company that:
- make it difficult to recover personal information from the converted data, protecting them.

*Tools used:*

Pandas, Matplotlib, Seaborn, Numpy, Sklearn, Scipy

*Findings:*

-After training the models before and after encrypting the original data by reversible matrix multiplication, and comparing the results of their RMSE, it can be seen that the RMSE (that is, the quality of the model itself) in both matrices is the same. When we multiply our features by an invertible matrix, we still have the same R2 score, w0 (intercept), but w (vector) is different because we used masked functions to compute w (vector). The algorithm works well by hand and with sklearn.