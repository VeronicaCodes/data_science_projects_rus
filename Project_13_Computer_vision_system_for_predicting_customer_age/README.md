#  Система компьютерного зрения для прогнозирования возраста покупателей

*Статус проекта:*  
Проект завершен.

*Описание и цели:*  
Система компьютерного зрения для обработки фотографий клиентов, которая поможет определить возраст, чтобы:
- Анализировать покупки и предлагать товары, которые могут заинтересовать покупателей в определенных возрастных группах.
- Контролировать продавцов алкоголя.

*Инструменты:*  
Pandas, Matplotlib, Numpy, PIL, Keras, Tensorflow

*Выводы:*  
- У нас есть набор данных с 7591 изображением людей в возрасте от 1 до 100 лет. Некоторые фотографии цветные, некоторые черно-белые. Где-то люди изображены лицевой стороной, где-то - видом сбоку. 
- По итогам 20 эпох обучения средняя абсолютная ошибка на тестовой выборке лежит в пределах 5 лет.