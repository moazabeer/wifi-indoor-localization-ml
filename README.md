<p align="center">
  <img src="results/banner.png" width="100%">
</p>

# 📡 WiFi Indoor Localization using Machine Learning

A machine learning-based indoor localization system that estimates a user's position using WiFi RSSI fingerprinting. The project builds a fingerprint database from WiFi scans and compares multiple regression models to accurately predict indoor coordinates.

---

## 🚀 Features

- 📶 WiFi RSSI fingerprint generation
- 📍 Indoor position prediction (X, Y coordinates)
- 📊 Exploratory Data Analysis (EDA)
- 🌲 Tree-based machine learning models
- 🤖 K-Nearest Neighbors baseline
- 📈 Model performance comparison
- 💾 Trained model saving with Joblib
- 📍 Live prediction demonstration

---

## 📂 Project Structure

```text
wifi-indoor-localization-ml/
│
├── notebooks/
├── data/
├── models/
├── results/
│   ├── figures/
│   └── metrics/
├── README.md
├── requirements.txt
└── LICENSE
```

---

## 📊 Dataset

The dataset consists of WiFi scan sessions collected using the **WiFi Heatmap Analyzer** application.

Dataset Statistics:

| Item | Value |
|------|-------|
| Total WiFi Records | 40,783 |
| Scan Sessions | 5,461 |
| Unique Positions | 1,063 |
| Unique SSIDs | 47 |
| Unique BSSIDs | 49 |

Each scan contains:

- RSSI (Signal Strength)
- BSSID
- SSID
- Channel
- Security
- X Position
- Y Position
- Timestamp

---

## 🧠 Machine Learning Pipeline

1. Data Loading
2. Data Preprocessing
3. Exploratory Data Analysis
4. Fingerprint Generation
5. Feature Engineering
6. KNN Baseline
7. Tree-Based Models
8. Model Comparison
9. Live Prediction

---

## 📈 Model Performance

| Model | MAE | RMSE |
|------|------:|------:|
| KNN | 4.322 | 5.514 |
| Decision Tree | 4.176 | 5.174 |
| Random Forest | **4.162** | **5.139** |
| Extra Trees | 4.174 | 5.168 |

**Best Model:** Random Forest

---

## 📷 Results

Example outputs include:

- Signal Strength Distribution
- Indoor Scan Locations
- KNN Prediction
- Random Forest Prediction
- Model Comparison Charts
- Live Prediction

---

## 🛠 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib

---

## ▶️ Installation

```bash
git clone https://github.com/moazabeer/wifi-indoor-localization-ml.git
cd wifi-indoor-localization-ml
pip install -r requirements.txt
```

---

## 👨‍💻 Author

**Moaz Abeer**

GitHub:
https://github.com/moazabeer

---

## 📄 License

This project is licensed under the MIT License.
