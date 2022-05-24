# Рекомендация тарифов

## Описание: 

Анализ исторических данных о поведении клиентов оператора мобильной связи.
Для построения системы, способной предлагать пользователям новый тариф: «Смарт» или «Ультра».



## Цели исследования: 

Построение модели на основе машинного обучения для задачи классификации. 
Модель должна выбирать подходящий тариф для пользователя.



## Этапы исследования: 

1. Открытие и изучение файла

2. Анализ данных

3. Разделение данных на выборки

4. Исследование моделей, определение лучшей

5. Проверка модели на тестовой выборке

6. Проверка модели на адекватность

7. Вывод



## Используемые библиотеки:
 
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
