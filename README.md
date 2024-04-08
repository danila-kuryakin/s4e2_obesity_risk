Требовалось спрогнозировать риск ожерения по табличным данным (мультиклассовая классификация). Для проверки использовалась метрика Accuracy.
Задача решалась с помощью трех параллельно прогнозирующих моделей LightGBM, XGBoost и Histogram Gradient Boosting.
Для повышения точности использовалась предобработка фич, кроссвалидация и параллельное пргнозирование с нахождением среднего.

Репозиторий был создан при участии в конкурсе [Multi-Class Prediction of Obesity Risk](https://www.kaggle.com/competitions/playground-series-s4e2) на Kaggle.
