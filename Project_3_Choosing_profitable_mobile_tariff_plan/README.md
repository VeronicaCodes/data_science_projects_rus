# Исследование наиболее выгодного тарифного плана

*Описание проекта и цели:*

Оператор мобильной связи предлагает своим клиентам два тарифных плана с предоплатой: Surf и Ultimate. Коммерческий отдел хотел бы узнать, какой из планов более прибыльный, чтобы скорректировать рекламный бюджет.  Наша цель - проанализировать данные по тарифам, чтобы компания могла скорректировать рекламный бюджет в сторону одного из тарифов. 

*Инструменты:*

Pandas, Matplotlib, Numpy, Scipy

**Выводы:**

Проверка Гипотезы №1 показала, что велика вероятность, что оба тарифа приносят приблизительно одинаковую выручку. Однако в шаге 4 было выявлено, что *большинство пользователей тарифа "Смарт" склонны превышать лимит в среднем на 400р, а "Ультра" - только на 50р.* , что объясняется более строгими ограничениями в лимитах. А также, сделанная нами pivot_table явно показала, что тарифа "Смарт" приносит в среднем за год более чем на 500 000 рублей больше, чем "Ультра.

|tariff|calls_duration_sum|internet_gb_month|messages_sent_month|revenue_sum|
|---|---|---|---|---|
|smart|880282|36397|74413|2558350|
|ultra|490084|19202|48623|2039100|
|TOTAL|1370366|55599|123036|4597450|

Значение p-value очень близко к нулю (примерное представление для 0.0000000000023), что ниже установленного порога alpha (0.5). Соответственно, мы отвергаем нулевую гипотезу H(0), которая утверждает, что средняя выручка тарифов «Ультра» и «Смарт» равна.  Компании "Мегалайн" следует отдать предпочтение тарифу "Смарт" для распределения рекламного бюджета. Также средняя выручка пользователей из Москвы не отличается от выручки пользователей из других регионов.

________________________________________________________________________________________________________________________________________
# Choosing the most profitable tariff plan

*Description:*

Identifying which of the calling plans is more profitable in order to adjust the advertising budget.

*Tools used:*

Pandas, Matplotlib, Numpy, Scipy

**Findings:**

Testing Hypothesis No. 1 showed that it is highly likely that both tariffs bring approximately the same revenue. However, in step 4, it was revealed that most users of the "Smart" tariff tend to exceed the limit by 400 rubles, and "Ultra" only by 50 rubles on average. Also, the pivot_table we made clearly showed that the "Smart" tariff brings in an average of more than 500,000 rubles more of profit to the company than the "Ultra" per year.

|tariff|calls_duration_sum|internet_gb_month|messages_sent_month|revenue_sum|
|---|---|---|---|---|
|smart|880282|36397|74413|2558350|
|ultra|490084|19202|48623|2039100|
|TOTAL|1370366|55599|123036|4597450|

The p-value is very close to zero (rough representation for 0.0000000000023), which is below the threshold alpha (0.5). Accordingly, we reject the null hypothesis H(0), which states that the average revenue of Ultra and Smart tariffs is equal. The "Megaline" company should give preference to the "Smart" tariff for the distribution of the advertising budget. Also, the average revenue of users from Moscow does not differ from the revenue of users from other regions.