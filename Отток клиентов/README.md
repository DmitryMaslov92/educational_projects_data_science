# Отток клиентов

## Описание: 

Анализ исторических данных о поведении клиентов банка и расторжении договоров с банком.
Решение задачи прогноза факта ухода клиента из банка. 



## Цели исследования: 

Нужно построить модель на основе алгоритмов машинного обучения, которая спрогнозирует отток клиентов банка.



## Этапы исследования: 

1. Получение данных и их оценка

2. Предобработка данных

3. Подготовка признаков, целевого признака и разбиение на выборки

4. Построение моделей, исследование и подбор гиперпараметров

5. Тестирование лучшей модели

6. Вывод



## Используемые библиотеки:
 
import pandas as pd

import numpy as np

%matplotlib inline

import matplotlib.pyplot as plt

from sklearn.tree import DecisionTreeClassifier

from sklearn.ensemble import RandomForestClassifier

from sklearn.metrics import accuracy_score

from sklearn.dummy import DummyClassifier

from sklearn.model_selection import train_test_split

from sklearn.preprocessing import StandardScaler

from sklearn.metrics import f1_score

from sklearn.utils import shuffle

from sklearn.linear_model import LogisticRegression

from sklearn.metrics import precision_score, recall_score

from sklearn.metrics import roc_auc_score

from sklearn.metrics import roc_curve 
