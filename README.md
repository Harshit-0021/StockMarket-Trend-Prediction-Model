# 📈 Stock Market Trend Prediction App

An **AI-powered web application** built with **Streamlit** that predicts **future stock prices** using a **Long Short-Term Memory (LSTM) deep learning model** trained on historical market data.  

---

## 🚀 Demo
🔗 [Live App on Streamlit](https://stockmarket-trend-prediction-model-21h.streamlit.app/)  

---

## 📌 Features
- Predicts **future stock closing prices** using an **LSTM model**.  
- User-friendly **Streamlit interface**.  
- Upload a CSV file with historical stock data.  
- Generates predictions for **1–30 days ahead**.  
- Provides interactive **charts for historical + predicted prices**.  
- Includes an **About Me** sidebar with portfolio links.  

---

## 🔍 Usage
1. Open the app in your browser.  
2. Upload a CSV file containing **historical stock data**.  
   - Must contain a column: `Close` (or `Adj Close`).  
3. Choose the **number of days** you want predictions for.  
4. Click **Predict**.  
5. Get results:  
   - 📊 Table of predicted prices.  
   - 📈 Graph combining **historical + predicted trends**.  

---

## 📊 Dataset
The app works with **stock market historical data**.  

- You can fetch stock data using **Yahoo Finance API (`yfinance`)** or download from any trusted source.  
- Columns required:  
  - `Date`  
  - `Open`  
  - `High`  
  - `Low`  
  - `Close` or `Adj Close`  
  - `Volume`  

---

## ⚙️ Tech Stack
- **Python 3.9+**  
- **Streamlit** (Frontend Web App)  
- **NumPy & Pandas** (Data Processing)  
- **Matplotlib & Plotly** (Visualizations)  
- **Scikit-learn** (Preprocessing & Scaling)  
- **TensorFlow / Keras** (LSTM Deep Learning Model)  

---

## 📸 Screenshots
### 🏠 Home Page
<img width="1338" height="564" alt="image" src="https://github.com/user-attachments/assets/bed01495-8804-4a9e-bafa-ca382af47c75" />

### 📊 Prediction Results
<img width="1223" height="533" alt="image" src="https://github.com/user-attachments/assets/244fe73f-dbaa-47b3-adef-7a604c5b0b5c" />

### 📊 Prediction Results
<img width="1353" height="613" alt="image" src="https://github.com/user-attachments/assets/03d3b393-7d17-49ed-9522-881b255b1ce0" />

### 📊 Prediction Results
<img width="1256" height="614" alt="image" src="https://github.com/user-attachments/assets/a87b56e5-beac-4544-9afe-dc99e8d6fa51" />


---

## 👨‍💻 Author
**Harshit**  

- 💼 [LinkedIn](https://www.linkedin.com/in/harshit-21y/)  
- 💻 [GitHub](https://github.com/Harshit-0021)  

---

## ❤️ Acknowledgements
- [Yahoo Finance API (`yfinance`)](https://pypi.org/project/yfinance/)  
- [Streamlit Documentation](https://docs.streamlit.io/)  
- [Scikit-learn](https://scikit-learn.org/stable/)  
- [TensorFlow/Keras](https://www.tensorflow.org/)  

---

## ⚠️ Disclaimer
This project is for **educational and research purposes only** and should **NOT** be considered as financial advice. Always do your own research before investing in the stock market.  

---
