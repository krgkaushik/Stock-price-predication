# 📈 Stock Price Prediction using LSTM

A deep learning-based Stock Price Prediction system that forecasts future stock prices using historical market data. This project leverages Long Short-Term Memory (LSTM) neural networks implemented in PyTorch to learn temporal patterns from stock market data obtained through Yahoo Finance.

---

## 📌 Project Overview

Stock markets generate sequential time-series data that is challenging to model using traditional machine learning techniques. This project uses an LSTM network to capture long-term dependencies in stock price movements and predict future closing prices.

The workflow includes:

- Fetching historical stock data
- Data preprocessing and normalization
- Creating sequential datasets
- Training an LSTM model
- Predicting future stock prices
- Evaluating model performance
- Visualizing actual vs predicted prices

---

## 🚀 Features

- Historical stock data collection using Yahoo Finance
- Data preprocessing with feature scaling
- Sequence generation for time-series forecasting
- Multi-layer LSTM model built with PyTorch
- Model training using Adam Optimizer
- Mean Squared Error (MSE) Loss
- Prediction visualization
- Performance evaluation using RMSE

---

## 🛠 Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| PyTorch | Deep Learning Framework |
| NumPy | Numerical Computing |
| Pandas | Data Processing |
| Matplotlib | Data Visualization |
| Scikit-Learn | Data Scaling & Evaluation |
| yFinance | Historical Stock Data |

---

## 📂 Project Structure

```
Stock-Price-Prediction/
│
├── Stock Price Predicter Proj 8.ipynb
├── requirements.txt
├── README.md
└── outputs/
      ├── prediction_graph.png
      └── trained_model.pth (optional)
```

---

## 📊 Dataset

The project retrieves real-time historical stock market data using the **Yahoo Finance API (yFinance)**.

Example information includes:

- Open Price
- High Price
- Low Price
- Close Price
- Adjusted Close
- Volume

Users can modify the ticker symbol to predict prices for different companies.

Example:

```python
ticker = "AAPL"
ticker = "TSLA"
ticker = "MSFT"
ticker = "GOOGL"
```

---

## ⚙ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Stock-Price-Prediction.git
```

Move into the project folder

```bash
cd Stock-Price-Prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶ Running the Project

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
Stock Price Predicter Proj 8.ipynb
```

Run all notebook cells sequentially.

---

## 🧠 Model Architecture

The prediction model consists of:

- Multi-layer LSTM Network
- Hidden Layer
- Fully Connected Output Layer

Architecture:

```
Input Sequence
       │
       ▼
  LSTM Layer
       │
       ▼
  Dropout Layer
       │
       ▼
 Fully Connected Layer
       │
       ▼
 Predicted Stock Price
```

---

## 📈 Training Process

The model training pipeline includes:

1. Download historical stock prices
2. Normalize data using StandardScaler
3. Generate sequential time-series windows
4. Split into training and testing datasets
5. Train the LSTM network
6. Calculate loss using MSE
7. Optimize parameters using Adam Optimizer
8. Generate predictions
9. Evaluate using RMSE

---

## 📉 Evaluation Metric

The project uses **Root Mean Squared Error (RMSE)** to evaluate prediction accuracy.

Lower RMSE indicates better prediction performance.

---

## 📷 Sample Output

The notebook generates graphs showing:

- Historical Stock Prices
- Training Loss
- Actual vs Predicted Closing Prices

---

## 📦 Dependencies

```
numpy
pandas
matplotlib
scikit-learn
tensorflow
torch
yfinance
```

---

## 🔮 Future Improvements

- Support multiple stock prediction
- Add GRU architecture
- Compare LSTM with ARIMA and Prophet
- Hyperparameter tuning
- Attention-based LSTM
- Real-time prediction dashboard
- Deploy using Streamlit
- Save and load trained models

---

## 🎯 Learning Outcomes

Through this project, you will gain experience in:

- Time-Series Forecasting
- Deep Learning with PyTorch
- LSTM Networks
- Data Normalization
- Model Evaluation
- Financial Data Analysis
- Data Visualization

---

## 👨‍💻 Author

**Kaushik Gunjkar**

Data Science & Machine Learning Enthusiast

---

## 📜 License

This project is intended for educational and research purposes.
