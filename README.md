# 🌞 Solar Energy Forecasting using Deep Time-Series Models

This project demonstrates how to forecast solar energy production using deep learning models—specifically LSTM (Long Short-Term Memory) networks—trained on synthetic solar data.

---

## 📊 Project Overview

- **Objective**: Predict future solar energy output based on historical irradiance and temperature data.
- **Approach**: Use synthetic time-series data to train an LSTM model.
- **Tools**: Python, TensorFlow/Keras, NumPy, Pandas, Matplotlib.

---

## 🛠️ Features

- Synthetic data generation for:
  - Solar irradiance
  - Ambient temperature
  - Solar energy output
- Time-series sequence creation for supervised learning
- LSTM-based deep learning model for forecasting
- Data normalization, model evaluation, and visualization
- Export of the dataset to Excel

---

## 📁 Files

- `solar_forecasting_lstm.py`: Python script for data generation, model training, and forecasting.
- `synthetic_solar_energy_data.xlsx`: Synthetic dataset exported to Excel format.
- `README.md`: Project documentation.

---

## 📈 Sample Output

- Forecast visualization comparing predicted vs. actual solar energy production
- Training and validation loss over epochs

---

## 🚀 Getting Started

### 1. Install dependencies
```bash
pip install numpy pandas matplotlib scikit-learn tensorflow
2. Run the script
bash


python solar_forecasting_lstm.py
3. Open the dataset
You can explore the synthetic dataset in synthetic_solar_energy_data.xlsx using Excel or any spreadsheet software.

📌 Notes
This project uses synthetic data. For real-world applications, replace the data generator with actual sensor or weather data.

You can extend the model to support:

Multi-step forecasting

Weather forecast integration

Transformer or TCN models


👨‍💻 Author
Tarinabo williamtarinabo@gmail.com
