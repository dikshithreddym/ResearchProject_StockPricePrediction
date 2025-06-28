# 📈 Stock Price Prediction Using AI/ML on High-Frequency Data

This project explores **short-term stock price forecasting** using high-frequency 2-minute interval data for Apple Inc. (AAPL). It compares the performance of three machine learning models: **Linear Regression**, **XGBoost**, and **LSTM**.

## 📂 Project Structure

| File Name                                                | Description                                 |
|----------------------------------------------------------|---------------------------------------------|
| `ResearchProject_Final.ipynb`                            | Jupyter Notebook with full implementation   |
| `Research Project - Stock Price Prediction Model.pdf`    | Final research paper with results & analysis|

---

## 🧠 Models Used

- **Linear Regression**  
- **XGBoost (Gradient Boosted Trees)**  
- **LSTM (Long Short-Term Memory Neural Network)**  

---

## 📊 Key Features

- High-frequency intraday data (2-minute intervals)
- Technical indicators (RSI, MACD, EMA, Bollinger Bands, etc.)
- Rolling statistics and lag-based features
- Performance evaluation using:
  - RMSE, MAE, R²
  - Directional Accuracy
- Feature importance analysis (XGBoost)

---

## 🔍 Summary of Findings

| Model              | MSE     | MAE     | R² Score | Directional Accuracy |
|-------------------|---------|---------|----------|-----------------------|
| Linear Regression | 0.0502  | 0.1376  | 0.9778   | 52.74%                |
| XGBoost           | 0.0588  | 0.1584  | 0.9740   | 51.52%                |
| LSTM              | 0.2490  | 0.3332  | 0.8932   | 52.60%                |

🔹 **Linear Regression** surprisingly performed best overall.  
🔹 **XGBoost** provided insights into feature importance.  
🔹 **LSTM** struggled due to noise in high-frequency data.

---

## 🛠️ Technologies Used

- Python (Pandas, NumPy, scikit-learn, XGBoost, TensorFlow/Keras)
- Jupyter Notebook
- `yfinance` API for real-time stock data
- `ta` Python package for technical indicators

---

## 📌 Future Improvements

- Add sentiment analysis (news or social media)
- Include order book or macroeconomic data
- Apply deep learning hybrid models (e.g., CNN-LSTM, Transformers)
- Test on different time intervals and stocks

---

## 👨‍💻 Authors

- Dikshith Reddy Macherla  
- Uchechukwu Obinwanne  
- Dr. Wenying Feng (Supervisor)  

_This research was conducted as part of the 2025 Summer Research Project at Trent University._

---

## 📄 License

This project is for academic and educational purposes only.
