````markdown
# 🌤️ Weather Prediction using LSTM

This project implements a **temperature prediction model** using **Long Short-Term Memory (LSTM)** neural networks. It uses historical weather data to predict future temperature trends over a period of days.

---

## 📊 Overview

The goal of this project is to forecast temperature using time series data. The project:
- Loads and cleans real-world weather data
- Preprocesses temperature values using Min-Max normalization
- Trains an LSTM-based deep learning model
- Predicts future temperature for the next 30 days
- Visualizes the predicted vs actual temperature trends

---

## 📁 Dataset

- **Source**: `testset.csv`
- **Target column**: `_tempm` (temperature in °F)
- **Index**: `datetime_utc`

---

## 🧠 Model Architecture

- **3 stacked LSTM layers**
- **1 Dense output layer**
- **Loss function**: Mean Squared Error
- **Optimizer**: Adam
- **Trained on**: 300 epochs

---

## 🔧 Tech Stack

- Python
- Pandas, NumPy
- Seaborn & Matplotlib (for plotting)
- TensorFlow / Keras (for LSTM model)

---

## 🚀 How to Run

### 1. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn tensorflow
````

### 2. Place your CSV file

Ensure `testset.csv` is placed in the root directory of your project.

### 3. Run the script

You can run the entire script in a **Jupyter Notebook** or in a **Python environment**.

---

## 📈 Output

The project produces the following visualizations:

* Line plot of original temperature data
* LSTM model predictions vs true values (on test set)
* Forecast of the next 30 days’ temperature
* Combined plot of historical and future predictions

---


---

## 📦 Folder Structure

```
weather_prediction/
├── testset.csv                 # Dataset file
├── weather_prediction.ipynb    # Notebook 
├── README.md                   # This file
├── assets/                     # Images or plots
└── requirements.txt            # Python packages
```

---

## 🙋 Author

* 👨‍💻 **Aryan Ahnaf**
  📧 [aryan420175@gmail.com](mailto:aryan420175@gmail.com)
  🔗 [LinkedIn](https://www.linkedin.com/in/aryan-ahnaf-440a87363/)
  🌐 [Facebook](https://www.facebook.com/aryanahnafabeg)

---



---

## ⭐ Support

If you found this project helpful, feel free to ⭐ it on [GitHub](https://github.com/aryanahnaf06/weather_prediction)!

```
