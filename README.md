# Enhancing Metro Rail Efficiency: A Predictive Maintenance Approach

## Overview
This project presents a **predictive maintenance system** for **air production units (APU)** in metro rail systems, leveraging **machine learning (ML) and deep learning (DL)** to detect potential failures in advance. The system aims to improve maintenance efficiency, reduce downtime, and enhance passenger safety by utilizing **sensor data analysis**.

## Features
- **Predictive failure detection** using ML and DL models
- **Real-time alert system** for maintenance personnel
- **Comparative analysis** of various models, including **LSTM, BiLSTM, and Adaptive Boosting**
- **Automated email notifications** for detected anomalies
- **Evaluation metrics** for model performance validation

## Dataset
- **Source:** Metro Rail APU Sensor Data (2020)
- **Size:** 15 million+ data points
- **Attributes:** 15 features (7 analog + 8 digital sensors)
- **Collected parameters:**
  - **Analog sensors:** Temperature, pressure, motor current, oil temperature, airflow
  - **Digital sensors:** Compressor status, valve conditions, air-drying tower operations

## Implementation
### Data Processing
- **Preprocessing:** Handling missing values, normalizing sensor data
- **Binary Classification:** Failure (`1`) vs. Normal (`0`)
- **Feature Engineering:** Extracting key signals for anomaly detection

### Model Architecture
- **Machine Learning Models:**
  - **Naïve Bayes, Logistic Regression, Random Forest, Adaptive Boosting**
- **Deep Learning Models:**
  - **LSTM, BiLSTM, ANN, SimpleRNN, Hybrid LSTM + Random Forest**
- **Custom Neural Network Model**
  - Multiple linear layers with **ReLU activations**
  - **Adam optimizer** for training efficiency

### Predictive Maintenance System
- **Failure Prediction:** Identifies faults based on **historical sensor data**
- **Alert Mechanism:** Sends notifications for **early intervention**
- **Scheduled Maintenance:** Reduces unplanned breakdowns

## Results
- **Best performing model:** LSTM (**99.83% accuracy**)
- **High recall and precision** for deep learning models
- **Effective reduction in downtime** using predictive analytics
- **Improved maintenance scheduling** with anomaly detection

## Applications
- **Real-time predictive maintenance for metro rail APUs**
- **Reduction of downtime and operational costs**
- **Enhanced safety and passenger comfort**
- **Scalability to other industrial predictive maintenance systems**

## Future Work
- **Adaptive learning models** that evolve with new data
- **Explainable AI** for better interpretability of model predictions
- **GAN-based data augmentation** for improved training
- **Integration with IoT systems** for real-time analytics
