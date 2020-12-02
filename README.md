# Test-Item-Project-2

Вы – единственный аналитик в компании, на которого легла ответственность за поиск инсайтов в данных продуктовых магазинов вашей компании. На повестке 3 задачи:

Задание 1  
В файле содержится информация о покупках людей.
Воспользуйтесь этими данными и выясните, какие пары товаров пользователи чаще всего покупают вместе. По сути, вам необходимо найти паттерны покупок, что позволит оптимизировать размещение продуктов в магазине, для удобства пользователей и увеличения выручки.  
Другими словами: 2 раза люди покупали одновременно чай и арбуз, 1 раз одновременно покупали арбуз и сгущёнку и 1 раз одновременно были куплены чай со сгущёнкой.  

Напишите код на python для получения нужной таблицы и укажите 5 наиболее распространённых паттернов.     

Задание 2  
К вам поступила информация о числе заказов за прошедшие 3 месяца с разрешением по неделям. Постройте (если это возможно) прогноз продаж на следующие 3 месяца, с учётом того, что в неделю с 2020-02-02 по 2020-02-09 была проведена массивная акция, повысившая число заказов на 7%.


Задание 3  
В базе данных вашей компании присутствуют следующие таблицы:  

city  
city_id – id города, где проходит акция  
client_city_id – id города, где находится покупатель  
city – город  
client_city – город, где находится покупатель  
client  
client_id – id покупателя  
client_city_id – id города, где находится покупатель
birth_date – дата рождения покупателя
registration – дата регистрации покупателя
promotion
promotion_id – id акции
category_id – id категории
promotion_name – акция
category_name – категория
partner_id – id партнёра
partner_name – партнёр
purchase
purchase_id – id покупки
partner_id – id партнёра
client_id – id покупателя
city_id – id города
promotion_id – id акции
category_id – id категории
purchase_date – дата покупки
price – цена за единицу товара
quantity – число проданных единиц
status – статус покупки
Вам нужно написать запрос, чтобы получить такую таблицу

purchase_date – дата покупки
purchase_id – id покупки
client_id – id покупателя
client_age – возраст покупателя
client_registration_age – как долго человек пользуется вашими магазинами
client_category – содержит new или old, если это первая или последующая покупка соответственно
promotion_name – акция
category_name – категория
partner_name – партнёр
client_city – город, где находится покупатель
city – город
revenue – сумма выручки
quantity – число проданных единиц
При этом в таблице должны присутствовать только значения, где в поле status стоит значение 1, и только те, где purchase_date находится в диапазоне от 01.05.2020 до 01.08.2020
