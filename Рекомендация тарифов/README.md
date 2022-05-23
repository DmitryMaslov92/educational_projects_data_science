# Рекомендация тарифов

## Описание: 

Оператор мобильной связи на основе данных о поведение клиентов хочет предложить пользователям один из двух новых тарифов.
В нашем распоряжении находятся данные о поведении клиентов, которые уже перешли на эти тарифы.
Данные уже предобработаны. 

## Цели исследования: 

Построить модель для классификации, которая выберет подходящий тариф.
Метрика точности предсказания - accuracy (должна быть больше 0.75).

## Этапы исследования: 

1. Открытие и изучение файла

2. Исследовательский анализ данных

3. Разделение данных на выборки

4. Исследование моделей машинного обучения, подбор гиперпараметров

5. Выявление модели с лучим качество предсказания

6. Проверка модели на тестовой выборке

7. Проверка модели на адекватность

8. Вывод



## Используемые библиотек:
 
import pandas as pd

%matplotlib inline

import matplotlib.pyplot as plt

import datetime

from pandas.plotting import scatter_matrix 

from sklearn.tree import DecisionTreeClassifier

from sklearn.ensemble import RandomForestClassifier

from sklearn.linear_model import LogisticRegression

from sklearn.model_selection import train_test_split

from sklearn.metrics import accuracy_score

from sklearn.dummy import DummyClassifier

import warnings
