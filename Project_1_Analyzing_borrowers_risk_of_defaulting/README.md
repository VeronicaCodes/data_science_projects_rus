# Исследование кредитоспособности заёмщиков в банке

*Описание и цели:*  

Необходимо подготовить отчет для кредитного отдела банка. У нас есть данные о платежеспособности клиентов.
Целью проекта является выяснить влияет ли семейное положение и количество детей клиента на выплату кредита. 
Отчет будет учтен при построении кредитного рейтинга потенциального клиента в банке.

*Инструменты:*  
Pandas, pymystem3

*Выводы:*  

- Семейное положение и количество детей клиента не влияют на выплату кредита, процент должников в каждой группе разделенной по количеству детей - около 9% (за исключении группы с 5ю детьми). При этом, среди женатых/замужних клиентов без детей должников в 2 раза больше, чем у любых других категорий. 

|family_status/children|0|1|2|3|4|5|  
|---|---|---|---|---|---|---|
|Не женат / не замужем|210.0|52.0|10.0 |1.0|1.0|0  |
|в разводе | 55.0 |21.0  |  8.0|   1.0 | 0.0|  0   |
|вдовец / вдова   |       53.0   | 7.0  |  3.0 |  0.0 | 0.0|  0|     
|гражданский брак   |     229.0 | 118.0  | 33.0|  8.0 | 0.0 |   0 |   
|женат / замужем   |      517.0  |246.0 | 148.0  |17.0|  3.0  |  0   |

- Также не обнаружена связь между целями кредита и своевременным погашением кредита.
________________________________________________________________________________________________________________________________________

# Analyzing borrowers' risk of defaulting

*Description:*

Finding out if a customer’s marital status and number of children has an impact on whether they will default on a loan. Report will be considered when building a credit scoring of a potential customer.

*Tools used:*

Pandas, pymystem3

*Findings:*

- The marital status and the number of children of the client do not affect the loan repayment, the percentage of debtors in each group divided by the number of children is about 9% (excluding the group with 5 children). At the same time, there are 2 times as many debtors among those who have a spouse *and* do not have children than among any other categories.

|family_status/children|0|1|2|3|4|5|
|---|---|---|---|---|---|---|
|Single/Single|210.0|52.0|10.0 |1.0|1.0|0 |
| Divorced | 55.0 |21.0 | 8.0| 1.0 | 0.0| 0 |
| widower / widow | 53.0 | 7.0 | 3.0 | 0.0 | 0.0| 0|
| Civil marriage | | 229.0 | 118.0 | 33.0| 8.0 | 0.0 | 0 |
| married / married | 517.0 |246.0 | 148.0 |17.0| 3.0 | 0 |

- Also, no relationship was found between the clients' reasons for the loan and the timely repayment of the loan.