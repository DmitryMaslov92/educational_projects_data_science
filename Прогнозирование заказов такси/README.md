# Прогнозирование заказов такси

## Описание: 

Служба такси собрала исторические данные о заказах такси в аэропортах. Для ривлечения большего количества водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час.


## Цели исследования: 


Создать признаки для предсказания целевого признака задачи. 

Построить модель на основе машинного обучения для прогноза количества заказов такси на следующий час.



## Этапы исследования: 

1. Загрузка и просмотр данных

2. Подготовка данных

3. Анализ данных

4. Создание и обучение моделей

5. Тестирование моделей, выбор лучшей

6. Вывод


## Используемые библиотеки:
 
import pandas as pd

import numpy as np

from sklearn.model_selection import train_test_split

from sklearn.linear_model import LinearRegression

from sklearn.metrics import mean_squared_error

import matplotlib.pyplot as plt

from sklearn.ensemble import RandomForestRegressor

from catboost import CatBoostRegressor

from lightgbm import LGBMRegressor

from statsmodels.tsa.seasonal import seasonal_decompose
