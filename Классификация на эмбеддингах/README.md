# Классификация на эмбеддингах

## Описание: 

Исследование заключается в классификации текстов с помощью создания признаков - эмбеддингов.

Для анализа нам предоставлен корпус текстов твитов с размеченной тональностью.



## Цели исследования: 

1. Сравнить две "усеченные" модели RuBERT (rubert-tiny и rubert от DeepPavlov), с помощью которых исходные тексты токенизируются и создаются эмбеддинги. Сравнить скорость их работы.

2. Сравнить качество предсказания на эмбеддингах нескольких простых моделей классификации. Выбрать лучший скорр accuracy.




## Этапы исследования: 

1. План работы

2. Загрузка и просмотр данных

3. Исследовательский анализ данных

4. Создание эмбеддингов

5. Разделение на выборки и признаки

6. Машинное обучение

7. Анализ моделей

8. Вывод



## Используемые библиотеки:
 
import numpy as np

import pandas as pd

import torch

import transformers

from tqdm import notebook

from sklearn.model_selection import train_test_split

from sklearn.metrics import accuracy_score

from transformers import AutoTokenizer, AutoModel

import matplotlib.pyplot as plt

import seaborn as sns

import time

from sklearn.model_selection import GridSearchCV

from sklearn.linear_model import LogisticRegression

import lightgbm as lgb

from sklearn.ensemble import RandomForestClassifier

from catboost import CatBoostClassifier

pd.options.mode.chained_assignment = None

import warnings

warnings.filterwarnings("ignore")

