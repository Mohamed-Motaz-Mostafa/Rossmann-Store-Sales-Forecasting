# Rossmann-Store-Sales-Forecasting
Welcome to the Time Series Forecasting Project `Rossmann Store Sales Forecasting` This repository contains code and documentation for various time series forecasting methods, including classical statistical models & machine learning models.

# 📝 Table of Contents
Introduction <br>
Data<br>
Models<br>
Contributing<br>

# 📚 Introduction
This project aims to provide a comprehensive comparison of different time series forecasting methods on sales data. The goal is to identify which model performs best in predicting future sales for a given store.


# 📊 Data
The data used in this project consists of sales records from different stores. The datasets are split into training, validation, and test sets.<br>
The data can be found on <a ref="https://www.kaggle.com/competitions/rossmann-store-sales"> Kaggle </a>


train_data.csv: Used to train the models.
validation_data.csv: Used to validate and tune the models.
test_data.csv: Used to evaluate the final model performance.
# 🔮 Models
The project implements the following forecasting models:

**ARIMA Model**: A classical statistical method for time series forecasting.<br>
**Prophet Model**: A model by Facebook designed for forecasting time series data.<br>
**Random Forest Model**: A machine learning approach using ensemble learning techniques.<br>
**AutoML**: Applay a autoML technique using Tpot library, chosen model by Tpot is `XGBRegressor`.<br>

# 🤝 Contributing
I welcome contributions to improve this project! If you have any suggestions or improvements, feel free to open an issue or submit a pull request.
