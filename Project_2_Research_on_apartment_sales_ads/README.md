# Исследование объявлений о продаже квартир

*Описание и цели:*  

Мы имеем данные из агентства недвижимости. Это архив объявлений о продаже недвижимости в Санкт-Петербурге и близлежащих районах, собранных за последние несколько лет. 
Цель - научиться определять рыночную стоимость недвижимости, определить самые важные параметры, влияющие на неё. Это позволит построить автоматизированную систему, способную обнаруживать аномалии и мошенническую деятельность.

*Инструменты:*  

Pandas, Matplotlib, Numpy

*Выводы:*  

- Основной параметр, влияющий на стоимость недвижимости - total_area (общая площадь). Он имеет сильный коэффициент корреляции Пирсона. Таким образом, total_area оказывает наибольшее влияние на цену квартиры.
- "floor_level" и "rooms" также имеют влияние. Между "total_area" и "rooms" существует тесная связь. "total_area" увеличивается, "rooms" также увеличивается.
- "cityCenters_nearest" имеет влияние, но это не имеет значения, когда мы рассматриваем центр города.
- "total_area", "ceiling_height" больше в центре города. Также здесь есть квартиры от 2-х комнат и выше.
________________________________________________________________________________________________________________________________________

# Research on the apartment sales ads

*Description:*

Determining the market value of real estate in Saint Petersburg, Russia, and defining parameters that make it possible to create an automated system capable of detecting anomalies and fraudulent activity.

*Tools used:*

Pandas, Matplotlib, Numpy

*Findings:*

- The main parameter that affects the value of real estate - "total_area". It has a strong Pearson correlation coefficient value. Thus, total_area has the biggest impact on the price of an apartment.
- "floor_level" and "rooms" also have an effect. There is a close relationship between "total_area" and "rooms". "total_area" is incremented, "rooms" is also incremented.
- "cityCenters_nearest" has an effect, but it doesn't matter when we consider the city center.
- "total_area", "ceiling_height" more in city center. There are also apartments from 2 rooms and above.