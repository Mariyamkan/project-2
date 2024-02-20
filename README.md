# Исследование продаж в онлайн-магазине 
### Цель данного исследования: 
Определить взаимосвязь и влияние Пола и Возраста на количество и суммы покупок. 
## Задачи

1) Посчитаем количество покупателей по полам и визуализируем подсчеты на круговой диаграмме (Pie Chart).

2) Построим график, который будет отображать количество покупателей по возрастам и покажет частоту встречающихся значений.

3) Построим график сумм продаж по датам, чтобы показать динамику выручки по месяцам.

4) Построим график по количествам продаж, сгруппированных по полам. Данный график должен показывать динамику количества продаж по полам в течение определенного периода.

5) Проверим следующие гипотезы:

- H1 - Возраст статистически значимо влияет на количество продаж.

- H0 - Возраст статистически значимо не влияет на количество продаж.

Гипотеза 2:

- H1 - Пол статистически значимо влияет на количество продаж.

- H0 - Пол статистически значимо не влияет на количество продаж.

 ## Описание данных
1. client_id: уникальный идентификатор клиента или пользователя в наборе данных
2. age: возраст            
3. gender: пол (male and female)             
4. product: товары в интернет магазине (TV, case, games, laptop, smart-watches, smartphone)
5. product_category: Категорий товаров в интернет магазине  (TV, case, games, laptop, smart-watches, smartphone)
6. purchased_quantity: количество приобретенных товаров
7. pricе: цена
8. purchase_date:  дата, когда был совершен определенная покупка или транзакция
## Финальный вывод
- Распределение покупателей между мужчинами и женщинами приблизительно равномерное. Это говорит о том, что данный бизнес привлекает внимание и интерес как у женской, так и у мужской аудитории в равной степени. (Female-249815, Male-250185)
- Интернет магазин привлекает клиентов из разных возрастных категорий в равной степени от 15 до 50 лет.
- Существует некоторая сезонность или вариативность в продажах электроник. Пики продаж в июле-августе могут объяснять, что многие готовяться к началу нового учебного года и покупают электронику в этот промежуток времени. Пики продаж в декабре-январе могут быть связаны с сезонными покупками, связанными с праздниками и подарками на Новый Год. Спад в феврале может быть связан с тем, что многие покупатели завершают свои покупки в декабре и январе в период распродаж (затишье после праздников). Спад в ноябре может быть связан с ожиданием распродаж в период "Черной пятницы" и "Киберпонедельника".
1. Гипотеза 1
- Исходя из коэффициента корреляции Спирмена и p-value, мы можем сделать следующие выводы: 
- Коэффициент близок к нулю, что указывает на отсутствие явной монотонной связи между возрастом и количеством покупок.
- P-value 0.542 значительно превышает уровень значимости 0.05, что означает, что нет статистически значимого влияния возраста на количество продаж.
- На основе проведенного анализа, у нас нет достаточных оснований для отклонения нулевой гипотезы, что возраст не оказывает статистически значимого влияния на количество продаж.

2. Гипотеза 2
- Результаты теста Манна-Уитни указывают на то, что у вас есть статистически значимые различия между группами мужчин и женщин в отношении количества продаж. P-значение равно 0.0319, что меньше обычного уровня значимости 0.05. Таким образом, мы можем отвергнуть нулевую гипотезу, которая утверждает, что пол не влияет на количество продаж. Результаты говорят о том, что пол имеет статистически значимое влияние на количество продаж в вашем наборе данных.
