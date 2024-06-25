# Описание исследования

**Цель проекта** - разработка модели для предсказания цены молока на основе данных о цене и прочих показателей за прошлые периоды (2010-2022 гг.).

В рамках данного исследования будут использованы различные методы прогнозирования временного ряда: Prophet, Prophet с добавлением значимых регрессоров, ARIMA, ARIMAX, SARIMA, SARIMAX, VARIMA, VARIMAX, а также концептуально иной подход прогнозирования временных рядов с использованием библиотеки tsfresh, позволяющей автоматически рассчитать новые числовые характеристики из первоначального набор данных.

# Описание приложенных файлов
- **milk_forecasting_tsfresh.ipynb** - Jupyter-ноутбук, содержащий модели предсказания цены на молоко с предварительной генерацией признаков с использованием библиотеки tsfresh;
- **milk_forecasting_sarimax (varimax).txt** - ссылка на Google Colab с предсказанием цены молока с использованием моделей SARIMAX, VARIMAX и т.д;
- **milk_forecasting_prophet.txt** - ссылка на Google Colab с предсказанием цены молока с использованием библиотеки Prophet.
