# Indoor WiFi Localization using Machine Learning

This project implements an indoor positioning system using WiFi fingerprinting and machine learning. It processes WiFi scan data collected with the WiFi Heatmap Analyzer application, generates WiFi fingerprints, trains multiple machine learning models, and predicts indoor locations.

## Features

- WiFi fingerprint generation
- Data preprocessing and cleaning
- Exploratory data analysis
- Multiple ML models
  - K-Nearest Neighbors (KNN)
  - Random Forest
  - XGBoost
- Model comparison
- Indoor location prediction
- Model export for deployment

## Project Structure

```text
data/
models/
results/
notebooks/
src/
```

## Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib

## Dataset

The dataset consists of WiFi scans collected using the WiFi Heatmap Analyzer application.

Each scan contains:

- Timestamp
- SSID
- BSSID
- RSSI
- Channel
- Security
- X coordinate
- Y coordinate
  
## Related Project

This dataset was collected using **WiFi-Heatmap-Analyzer**, a desktop application for collecting and visualizing WiFi fingerprints.

Repository:
https://github.com/moazabeer/WiFi-Heatmap-Analyzer

## Status

🚧 Under development.
