### Оптимальный размер выборки
------------------------------
1. Уронь значимости 0,05 <= p >= 0,01  [подробно](http://www.perfendo.org/docs/BayesProbability/twelvePvaluemisconceptions.pdf)
2. Показатель мощности 0,8
3. Выборка содержит все основные факторы
----


### Поиск значимых переменных для регрессией
----
1. Биндинг переменной 
2. WOE
3. IV ( < 0,02 - плохая, 0,02 < 0.1 - слабая, 0,1 < 0,3 - нормальная, 0,3 < 0,5 - сильная, 0,5 - слишком хорошая, что бы быть правдой)
4. PCI ( > 0,1 - стабильная, 0,1 > 0,25 - небольшие изменения, проверяем, 0,25 - большие изменения )


### Правильное определение числа групп (выборок) для группировки
----
1. По формуле Стерджесса:

    ![bins](https://github.com/NameArtem/papers/blob/master/bins_Stredg.gif), где n - количество данных (exp: len of numpy.array)

2. Определение величины интервала:

     ![bins](https://github.com/NameArtem/papers/blob/master/Value_of_Interval.gif), где k - кол-во группировок


