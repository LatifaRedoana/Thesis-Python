# ♻️ Time Series Forecasting of Recycling Material Data

This project explores time series analysis and forecasting techniques for predicting material quantities from a recycling plant using both classical statistical models and deep learning.
**"Time Series Forecasting of Material Data from Recycling Plants using Statistical and Deep Learning Techniques."**

📘 **Author:** Latifa Redoana  
🎓 **University:** TU Dortmund, Germany  
🏢 **Company:** REMONDIS SmartRec GmbH

---

## 📌 Objectives

- Preprocess recycling plant data for time series forecasting
- Apply SARIMA and LSTM models for prediction
- Compare model performance using RMSE with rolling cross-validation
- Forecast future material volumes over a 5-year horizon

---

## 📊 Models Implemented

- **SARIMA:** Seasonal Autoregressive Integrated Moving Average
- **LSTM:** Long Short-Term Memory neural network
- (Optional) **FFT:** Fast Fourier Transform for trend extraction

---

## 🧠 Tools & Libraries
- Python (Pandas, NumPy, statsmodels, TensorFlow/Keras, matplotlib)
- Jupyter Notebooks
- Darts (for frequency spectrum)

---

## 📈 Key Results & Insights

- **SARIMA consistently outperformed LSTM** in terms of accuracy and prediction stability.
- SARIMA showed a **better fit to the dataset's characteristics** (seasonality and stationarity).
- **LSTM is capable of modeling complex patterns**, but did not yield better results in this case.
- SARIMA is:
  - Easier to interpret
  - Requires fewer hyperparameters
  - **More computationally efficient**
- **LSTM is computationally expensive**, especially with large datasets or many tuning iterations.
- For this study, **SARIMA was the more practical and effective choice**.

---

## ⚖️ Model Comparison Summary

- While **SARIMA and LSTM showed similar RMSE values**, SARIMA aligned more closely with actual observations.
- When results are close, **model selection depends on data context, business needs, and practical limitations**.
- Key Considerations:
  - **SARIMA**:
    - Requires basic statistical background
    - Fewer parameters and easier interpretation
    - **Low computational demand**
  - **LSTM**:
    - Strong for modeling complex, non-linear patterns
    - **Relies on high computational power**
    - Can be time-consuming with large data or many iterations

---




