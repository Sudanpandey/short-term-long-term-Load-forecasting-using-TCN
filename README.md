**📊 Short-Term and Long-Term Load Forecasting using TCN and DWT.**
A deep learning-based solution to forecast electrical power consumption using Temporal Convolutional Networks (TCN). This research performs sequence modeling on time series energy data, incorporating cyclical encoding, feature scaling, and wavelet-preprocessed inputs to predict future load demand accurately.
🔍 Problem Statement
Efficient energy management requires accurate load forecasting. This research addresses both short-term (next 24 hours) and long-term (up to 168 hours) predictions of electricity consumption using historical data and environmental features.

**🗃️ Dataset**
The dataset includes the following columns:
English Date, Hour, Weekday, Festivals
Temperature, Radiation
System Down, Power(MW)
Time-based sine/cosine encodings



**📈 Results**
| Forecast Horizon    | RMSE   | MAPE    | R² Score |
| ------------------- | ------ | ------- | -------- |
| ⏳ 1 Day (24 hrs)    | 5.3862 | 2.1160% | 0.9876   |
| 📆 1 Week (168 hrs) | 6.9756 | 2.5582% | 0.9788   |
