# SHB-Stock-Prediction-using-LSTM
Predicting Stock Price using LSTM
## **📌 Overview**

- **Goals:** Forecast stock prices using One Step Moving Average and Long Short-Term Memory (LSTM)
- **Data:** Historical Prices of SHB - Ngan Hang TMCP Sai Gon
- **Tools:** Python (TensorFlow, Pandas, Matplotlib)
- **Key Deliverables:** Model architecture, Prediction chart, and performance metrics

## **🛠️ Methodology**

1️⃣ Get Stock Data from Techcombank Securities database

- **Extracted daily stock prices**

2️⃣ **Fit One Step Moving Average model**

**3️⃣ Fit LSTM Model and tuning**

- Constructed LSTM Model from Tensorflow
- **Architecture: 1 layer (modifiable), 161000 parameters**
    - `sequence_length = 200`
    - `activation = ‘relu’`
    - `Dropout(0.1) # drop out rate 10%`
    - `tf.keras.optimizer.Adam(learning_rate=0.0005)`

