# Определение возраста покупателей

## Описание: 

Сетевой супермаркет внедряет систему компьютерного зрения для определения возраста покупателей в прикассовой зоне с помощью фотофиксации.
Доступен размеченный датасет с фотографиями покупателей и их возрастом. 


## Цели исследования: 


Построить модель, по фотографии определяющую приблизительный возраст человека. 



## Этапы исследования: 

1. Загрузка данных

2. Исследовательский анализ данных

3. Обучение модели

4. Анализ обученной модели (вывод)


## Используемые библиотеки:
 
from tensorflow.keras.applications.resnet import ResNet50

from tensorflow.keras.preprocessing.image import ImageDataGenerator

from tensorflow.keras.layers import Conv2D, Flatten, Dense, MaxPooling2D, GlobalAveragePooling2D

from tensorflow.keras.models import Sequential

from tensorflow.keras.optimizers import Adam

import numpy as np

import pandas as pd 

from PIL import Image

import matplotlib.pyplot as plt


