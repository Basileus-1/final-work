Проект по исследованию и прогнозированию влияния различных параметров и характеристик помещений и объектов на нагрузку (мощность) отопления объекта/помещения и его охлаждения.

За основу взят датасет Energy efficiency Data Set из репозитория UCI.

Для исследования применяются пакеты Python - pandas и scikit-learn.

В датасете собраны следующие параметры помещений/объектов: X1 Относительная компактность, X2 Площадь поверхности, X3 Площадь стен, X4 Площадь крыши, X5 Общая высота, X6 Ориентация, X7 Площадь остекления, X8 Распределение площади остекления

Y1 Нагрузка на отопление, Y2 Нагрузка на охлаждение

Ценность данногоанализа состоит в оценке влияния каждого параметра (весе) на итоговые нагрузки по отоплению и охлаждению. Выявление параметров с наибольшим весом.Как результат - создается основа для планирования мероприятий по повышению энергоэффективности помещений/объектов, их бюджетирование с целью получению наибольшегоэффекта.
