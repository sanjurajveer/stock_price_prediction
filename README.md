### **README: Stock Price Prediction App**  

#### **Project Overview**  
This project is a **Stock Price Prediction App** deployed on **Streamlit**, using **LSTM (Long Short-Term Memory) Neural Networks** for time-series forecasting. The app fetches real-time stock data, applies technical indicators, and predicts future stock prices for the next 10 days.  

🔗 **Live App:** [Stock Price Predictor](https://stocks-price-predict.streamlit.app)  

---

### **Features**  
✅ **Fetches real-time stock data** using Yahoo Finance (`yfinance`).  
✅ **Applies technical indicators** such as Moving Averages, RSI, Bollinger Bands, and Volatility.  
✅ **Uses LSTM Neural Networks** to predict stock prices based on historical data.  
✅ **Interactive Streamlit UI** for selecting stocks and visualizing predictions.  
✅ **Plots future stock prices** with an interactive Plotly chart.  

---

### **Technologies Used**  
- **Python** (Core Language)  
- **yfinance** (Stock Data API)  
- **Pandas & NumPy** (Data Processing)  
- **Matplotlib & Seaborn** (Data Visualization)  
- **Plotly** (Interactive Graphs)  
- **Keras & TensorFlow** (LSTM Model for Predictions)  
- **Scikit-learn** (Data Normalization & Train-Test Splitting)  
- **Streamlit** (Web App Deployment)  

---

### **Installation & Setup**  
1. **Clone the Repository**  
   ```bash
   git clone https://github.com/yourusername/stocks-price-predict.git
   cd stocks-price-predict
   ```

2. **Create a Virtual Environment** (Recommended)  
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. **Install Dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Streamlit App**  
   ```bash
   streamlit run stocks_prediction.py
   ```

---

### **How It Works**  
1. **Select a stock** (AAPL, MSFT, GOOGL, TSLA, AMZN) from the dropdown.  
2. The app **fetches the last 5 years of stock data** from Yahoo Finance.  
3. It **trains an LSTM model** to analyze past trends and forecast the next 10 days.  
4. The predicted prices are displayed in **a table and an interactive chart**.  

---

### **Example Prediction Output**  
| Date       | Predicted Price ($) |  
|------------|--------------------|  
| 2025-02-01 | 182.45             |  
| 2025-02-02 | 184.32             |  
| 2025-02-03 | 186.12             |  
| ...        | ...                |  

---

### **Future Enhancements**  
🚀 Improve model accuracy with **hyperparameter tuning**.  
📈 Integrate **more advanced financial indicators**.  
🌎 Expand stock selections to **global markets**.  
📊 Add real-time **news sentiment analysis** for better predictions.  

---

### **Contributors**  
👤 **Sanju Raj** – *[Your LinkedIn/GitHub Profile]*  

---

### **License**  
This project is licensed under **MIT License**.  

---
