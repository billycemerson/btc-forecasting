# Forecasting BTC Price using Historical Price Data

This research focuses on implementing several deep learning models for time series forecasting:
- LSTM  
- Bi-LSTM  
- CNN-LSTM  
- CNN-BiLSTM  

To improve model performance, a **Rolling Window Cross-Validation** approach is used in two different BTC market scenarios (Bear and Bull).  
The dataset covers the period from **2022 to 2025**, divided into:
- **2022–2023:** Bear Market  
- **2024–2025:** Bull Market  

The **Optuna framework** is used for hyperparameter optimization in each model.