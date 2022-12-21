# Оптимизация затрат на внепечную обработку стали

[HTML](https://github.com/shishkoedoff/DS-professional-training-course-at-Yandex.Praktikum/blob/main/16%20-%20Predicting%20the%20temperature%20of%20steel%20after%20processing/Portfolio%20-%20Project%2016.html)     [ipynb](https://github.com/shishkoedoff/DS-professional-training-course-at-Yandex.Praktikum/blob/main/16%20-%20Predicting%20the%20temperature%20of%20steel%20after%20processing/Portfolio%20-%20Project%2016.ipynb)

## Описание проекта

Требуется математическая модель для прогнозирования итоговой температуры стали после обработки.

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- sklearn.model_selection.**train_test_split**
- sklearn.preprocessing.**MinMaxScaller**
- sklearn.model_selection.**cross_val_score**
- sklearn.metrics.**mean_absolute_error**
- sklearn.metrics.**make_scorer**
- sklearn.linear_model.**LinearRegression**
- sklearn.tree.**DacisionTreeRegressor**
- sklearn.ensemble.**RandomForestRegressor**
- sklearn.dummy.**DummyRegressor**
- **matplotlib**

## 

## Общий вывод

В качестве прогнозной модели рекомендуется использовать модель "Случайного леса" с глубиной деревьев 12 и количеством оценщиков 95 на ненормированных данных, очищенных от признаков, имеющих парные высококоррелирующие (более 0,7). Точность прогноза составила 6,04 градусов на тестовой выборке, что для температур более 1500 градусов составляет менее 0,4%.

После накопления экспериментальных данных по применению сыпучих и проволочных материалов, имеющих незначительные количества замеров на момент настоящего исследования, рекоментдуется повторить аналогичной исследование.
