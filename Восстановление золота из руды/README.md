# Восстановление золота из руды

## Описание: 

Предоставлены данные по технологическому процессу восстановления золота из золотосодержащей руды. Эти данные содержат параметры добычи и очистки золота.
Нужно оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.


## Цели исследования: 


Проверить расчет эффективности обогащения с помощью формулы, сравнить с табличным занчением. 

Написать функцию для вычисления итоговой sMAPE.

Построить модель, которая будет предсказывать коэффициент восстановления золота из золотосодержащей руды на двух основных этапах.




## Этапы исследования: 

1  Описание данных

2  Подготовка данных

3  Проверка recovery

4  Анализ данных

5  Построение моделей, выбор лучшей

6  Тест на адекватность

7  Вывод


## Используемые библиотеки:
 
import pandas as pd

from sklearn.metrics import mean_absolute_error

import matplotlib.pyplot as plt

from sklearn.model_selection import cross_val_score

from sklearn.linear_model import LinearRegression

from sklearn.metrics import make_scorer

from sklearn.model_selection import train_test_split

from sklearn.ensemble import RandomForestRegressor
