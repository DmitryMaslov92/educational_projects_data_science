# Определение стоимости автомобилей

## Описание: 

В вашем распоряжении исторические данные сервиса по продаже автомобилей: технические характеристики, комплектации и цены автомобилей.
С помощью этих данных нужно автоматически научиться определять рыночную стоимость "новых" автомобилей.


## Цели исследования: 


Построить модель на основе машинного обучения для определения стоимости автомобиля.

Оценить качество и скорость моделей, выбрать лучшую.



## Этапы исследования: 

1. Загрузка и просмотр данных

2. Предобработка данных

3. Исследовательский анализ данных

4. Построение моделей на основе машинного обучения

5. Анализ моделей

6. Вывод


## Используемые библиотеки:
 
import pandas as pd

from sklearn.model_selection import train_test_split

from sklearn.preprocessing import OrdinalEncoder

from sklearn.preprocessing import StandardScaler 

from sklearn.metrics import mean_squared_error

from sklearn.linear_model import LinearRegression

from sklearn.ensemble import RandomForestRegressor

from catboost import CatBoostRegressor

from lightgbm import LGBMRegressor

import matplotlib.pyplot as plt

import time
