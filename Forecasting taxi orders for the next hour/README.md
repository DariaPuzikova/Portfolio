# Прогнозирование количества заказов такси на следующий час #

## Описание проекта ##
При помощи исторических данных о заказах такси в аэропортах нужно построить модель определяющую их загруженность на следующий час. Эта модель поможет оптимизировать привлечение достаточного количества водителей как во время пиковых нагрузок, так и в более пустые периоды.

## Навыки и инструменты ##
- pandas
- numpy
- matplotlib
- timeit
- statsmodels.**seasonal_decompose**
- sklearn.ensemble.**RandomForestRegressor**
- catboost.**CatBoostRegressor**
- sklearn.linear_model.**LinearRegression**
- sklearn.model_selection.**train_test_split**
- sklearn.metrics **mean_absolute_error, import mean_squared_error**
- sklearn.preprocessing
- sklearn.pipeline
- sklearn.model_selection **GridSearchCV, TimeSeriesSplit**

## Вывод ##
Работая над этим проектом, я провела предобработку данных, проанализировала предоставленный датасет, изучив сезонность и тренды, обучила 3 модели и протестировала лучшую из них.

