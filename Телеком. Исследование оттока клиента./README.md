# Телеком. Исследование оттока клиента.

## Описание: 

У оператора связи находится база данных клиентов и база данных услуг. По историческим данным нужно научиться предсказывать то состояние, когда клиент собирется прекратить сотрудничество с компанией.


## Цели исследования: 


Построить модель для бинарной классификации состояния клиента компании на текущее время (собирается уйти или нет). 



## Этапы исследования: 

1. План работы

2. Импорт данных и их обработка

3. Финальная таблица для машинного обучения, разделение признаков

4. Машинное обучение и подбор моделей, выявление лучшей модели

5. Вывод

6. Отчет по решению


## Используемые библиотеки:
 
!pip install category_encoders

import pandas as pd

from sklearn.model_selection import train_test_split

from catboost import CatBoostClassifier

from sklearn.metrics import roc_auc_score

import category_encoders as ce

from statsmodels.stats.outliers_influence import variance_inflation_factor

import numpy as np

import matplotlib.pyplot as plt

from sklearn.preprocessing import OrdinalEncoder 

from sklearn.metrics import roc_curve

from sklearn.ensemble import RandomForestClassifier

from sklearn.model_selection import GridSearchCV

import seaborn as sns


