# AI-Based-Predictive Maintenance for Equipment using Machine Learning

## 📌 Overview

This repository contains a research-backed implementation of a **Predictive Maintenance (PdM) System** designed to minimize unplanned equipment downtimes and optimize asset performance. Using real-time sensor data and machine learning techniques, this system detects early signs of failure in equipment—specifically APU compressors used in metro trains.

## 🧠 Key Features

- Real-time monitoring of equipment health
- Integration of multiple sensors (temperature, pressure, vibration, acoustic, current)
- Preprocessing and cleaning of time-series sensor data
- Fault prediction using ML algorithms like SVM, Random Forest, and Logistic Regression
- Anomaly detection using K-Means Clustering and LSTM models
- NLP-powered preventive suggestions using GPT-2
- Alert system integrated with push notifications (Firebase/APNS)
- GUI for live alerts and user feedback

## 📊 Dataset

- **Total Instances:** 15,169,480
- **Sensor Types:** Pressure, Temperature, Motor Current, Oil Temperature, Voltage, etc.
- **Attributes:** 15 real-world parameters recorded every second
- **Period:** February to August 2020
- **Application:** APU compressor units in metro trains

## 🧪 Methodology

### 1. Sensor Deployment
- Installed on mechanical parts for continuous data collection.

### 2. Data Preprocessing
- Handled missing values, normalization, encoding, and dimensionality reduction.

### 3. Model Development
- Classification using:
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Random Forest
- Time-series modeling using LSTM for Remaining Useful Life (RUL)
- Fault diagnosis using NHPP and Proportional Hazards Models

### 4. Real-Time Alert System
- GUI interface displays alerts

### 5. Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- AUC (Area Under Curve)

## 🛠 Technologies Used

- Python
- Scikit-learn
- TensorFlow / Keras (for LSTM models)
- GPT-2 (for AI recommendations)
- Firebase/APNS (for push notifications)
- Streamlit / Tkinter (for GUI)

## 📈 Results

The trained models achieved high accuracy in detecting compressor faults and provided real-time alerts. NLP-generated preventive actions further improved maintenance scheduling and reduced machine failure rates.


## 📄 License

This project is intended for **educational and research purposes** only.

