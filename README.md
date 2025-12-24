# Sleep Quality Prediction using Artificial Neural Network (ANN)

This project focuses on predicting sleep quality using an Artificial Neural Network (ANN).  
The model classifies sleep quality into three categories: **Poor, Average, and Good** based on lifestyle and health-related features.

## 📘 Project Overview

The project is implemented entirely in **Jupyter Notebook** using Python.  
It includes data preprocessing, ANN model training, evaluation, and visualization of results.

## 📊 Dataset Description

The dataset contains the following features:

- Sleep Duration (hours)
- Stress Level
- Physical Activity (minutes per day)
- Heart Rate (BPM)
- Quality of Sleep (Target Variable)

The target variable **Quality of Sleep** is mapped into three classes:
- 0 → Poor
- 1 → Average
- 2 → Good

## 🧠 Model Details

- Model Type: Artificial Neural Network (ANN)
- Hidden Layers:
  - Dense layer with 64 neurons (ReLU)
  - Dense layer with 32 neurons (ReLU)
- Output Layer:
  - 3 neurons with Softmax activation
- Optimizer: Adam
- Loss Function: Sparse Categorical Crossentropy

## ⚙️ Libraries Used

- Pandas
- NumPy
- TensorFlow / Keras
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib
- Gradio

## 📈 Model Evaluation

The model performance is evaluated using:
- Classification Report
- Confusion Matrix (visualized using heatmap)

## 🖥️ User Interface

A simple Gradio interface is included to allow users to input sleep-related data and get real-time predictions of sleep quality.

## 📂 Files Included

- `Sleep_Quality_ANN.ipynb` – Jupyter Notebook containing full implementation
- `sleep_dataset.csv` – Dataset used for training and testing
- `README.md` – Project documentation

## 👨‍🎓 Author

**Wajih Ur Rehman**

---

