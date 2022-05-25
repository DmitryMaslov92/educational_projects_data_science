# Проект по классификации тональности текстов

## Описание: 

Есть база данных интернет-магазина с комментариями на английском языке, каждому комментарию присвоена метка 0 или 1, где 0 - комментарий позитивный, 1 - комментарий негативный. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.


## Цели исследования: 


Обучить модель классифицировать комментарии на позитивные и негативные.



## Этапы исследования: 

1. Загрузка и просмотр данных

2. Обработка данных

3. Функция создания Tf-idf признаков

4. Обучение и проверка моделей, выбор лучшей

5. Вывод


## Используемые библиотеки:
 
from tqdm import tqdm

import pandas as pd

import nltk

from nltk.corpus import stopwords as nltk_stopwords

from sklearn.feature_extraction.text import TfidfVectorizer 

import numpy as np

from sklearn.linear_model import LogisticRegression

from sklearn.model_selection import train_test_split

from sklearn.metrics import accuracy_score

pd.options.mode.chained_assignment = None

from sklearn.metrics import f1_score

from pymystem3 import Mystem
m = Mystem()

import re

from sklearn.tree import DecisionTreeClassifier

from sklearn.ensemble import RandomForestClassifier

import spacy

from sklearn.svm import SVC

from sklearn.preprocessing import StandardScaler

from sklearn.datasets import make_classification

from sklearn.pipeline import Pipeline

from sklearn.model_selection import cross_val_score

from sklearn.feature_extraction.text import CountVectorizer

import matplotlib.pyplot as plt
