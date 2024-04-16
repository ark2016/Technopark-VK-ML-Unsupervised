# Technopark-VK-ML-Unsupervised
## Description
Вам предоставлен набор данных — некоторых вещественно значных признаков. Вам нужно проставить метки классов, другими словами кластеризовать данные.
## Evaluation
Метрика оценки качества — Adjusted Rand Score.\
\
Ваш файл решения должен иметь следующий вид:
```
ID,TARGET
0,0
1,1
2,2
3,3
4,4
etc.
```
Данные — sparse матрица размера (14590, 77888).

## Files
_train.npz_ - набор данных, по которым необходимо предсказать метки.\
_sample_submission.csv_ - пример файла решения

## Загрузка данных
```py
from scipy import sparse

train = sparse.load_npz("train.npz")
```
