# Выбор локации для скважины

## Описание: 

В таблице с данными хранятся записи о пробах нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов.
Исследование заключается в выборе параметров, по которым можно будет спрогнозировать лучший регион для добычи нефти. 



## Цели исследования: 

1.Построить модель на основе машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль при наименьшем риске.

2.Проанализировать возможную прибыль и риски техникой Bootstrap.



## Этапы исследования: 

1. Загрузка и подготовка данных

2. Расчет среднего запаса сырья в регионе

3. Подготовка к расчёту прибыли

4. Расчёт прибыли и рисков

5. Вывод



## Используемые библиотеки:
 
import pandas as pd

from sklearn.linear_model import LinearRegression

from sklearn.metrics import f1_score

from sklearn.model_selection import train_test_split

from sklearn.linear_model import LinearRegression

from sklearn.metrics import mean_squared_error

import numpy as np

from scipy import stats as st

from pandas.plotting import scatter_matrix 

import matplotlib.pyplot as plt
