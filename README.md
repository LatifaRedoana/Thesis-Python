# ♻️ Time Series Forecasting of Recycling Material Data

This project explores time series analysis and forecasting techniques for predicting material quantities from a recycling plant using both classical statistical models and deep learning.
**"Time Series Forecasting of Material Data from Recycling Plants using Statistical and Deep Learning Techniques."**

📘 **Author:** Latifa Redoana  
🎓 **University:** TU Dortmund, Germany  
🏢 **Company:** REMONDIS SmartRec GmbH

---

## 📌 Objectives

- Preprocess recycling plant data to make it suitable for time series forecasting
- Identifying key patterns, trends, and seasonal fluctuations
- Conduct hyperparameter optimization and one-step ahead rolling cross validation approach
- Perform an empirical study on  traditional model SARIMA and deep learning-based algorithms LSTM
- Compare the predictive performance of both models with the accuracy metric RMSE
- Long-term forecasting for enhancing material management, planning, and operational efficiency within the recycling industry.

---

## 📊 Models Implemented

- **SARIMA:** Seasonal Autoregressive Integrated Moving Average
- **LSTM:** Long Short-Term Memory neural network
- (Optional) **FFT/DFT:** Fast Fourier Transform for trend extraction

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

## Thank You! 😊
Thank you for exploring this project! If you have any suggestions or questions, feel free to reach out. Contributions are always welcome!





