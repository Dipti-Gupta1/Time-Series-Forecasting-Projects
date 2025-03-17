
# ⏳ Time Series Forecasting Projects  

This repository contains multiple **Time Series Forecasting** projects implemented using different models, including **LSTM, Temporal Fusion Transformer (TFT), and Prophet**. Each project follows a structured approach for **data preprocessing, feature engineering, hyperparameter tuning, and model evaluation**.  

---

#### 📚 Course Information  
These projects are part of the **Udemy course**:  
📌 **Course Name:** [Time Series Forecasting with Python](https://www.udemy.com/course/forecasting-python/learn/lecture/45931761?start=510#questions)  
📌 **Platform:** Udemy  

📊 What is Time Series Forecasting?

Time series forecasting is the process of predicting future values based on past observations. It is widely used in:

📈 Stock market & financial forecasting
🔋 Energy demand prediction
🛒 Retail sales forecasting
🚛 Supply chain optimization
📊 Weather forecasting


Traditional methods like ARIMA and Exponential Smoothing are useful, but deep learning models like LSTM and TFT can handle complex patterns, dependencies, and large datasets more effectively.


---

### 📂 Project Structure  

Each forecasting method is organized in a separate folder:  

### Repository Structure

```plaintext
Time-Series-Forecasting-Projects/
│── LSTM_Forecasting/            # LSTM-based forecasting
│   ├── lstm_forecasting.py
│   ├── hyperparameter_tuning.py
│   ├── README.md
│   ├── data/
│── TFT_Forecasting/             # Temporal Fusion Transformer (TFT)
│   ├── tft_forecasting.py
│   ├── README.md
│── Prophet_Forecasting/         # Prophet model for forecasting
│   ├── prophet_forecasting.py
│   ├── README.md
│── README.md  <-- Main repo overview
```

### Projects Overview

#### 📌 1️⃣ LSTM Forecasting
Method: Long Short-Term Memory (LSTM)
Library: Darts (PyTorch-based)

Key Features: ✅ Deep learning-based sequence modeling
* ✅ Feature engineering with time attributes
* ✅ Hyperparameter tuning with Grid Search
* ✅ GPU acceleration for faster training
* ✅ Cross-validation with rolling forecasting
* 📂 Go to LSTM Project

#### 📌 2️⃣ Temporal Fusion Transformer (TFT) Forecasting
Method: Temporal Fusion Transformer (TFT)
Library: Darts
Key Features: 
* ✅ Multi-horizon forecasting
* ✅ Attention mechanisms for interpretability
* ✅ Dynamic feature embeddings
📂 Go to TFT Project

#### 📌 3️⃣ Prophet Forecasting
Method: Facebook Prophet
Library: Prophet
Key Features: 
* ✅ Automatic handling of seasonality & holidays
* ✅ Best for business forecasting applications
📂 Go to Prophet Project

### Getting Started

#### Installation
Ensure you have Python installed, then install dependencies:
```bash
pip install -r requirements.txt
```

#### Usage
Run the desired forecasting model script:
```bash
python LSTM_Forecasting/lstm_forecasting.py
```

### Contributing
Feel free to fork this repository and contribute improvements or new forecasting models!








