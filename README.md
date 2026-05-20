# ANN Customer Churn Model

This project implements an **Artificial Neural Network (ANN)** to predict customer churn based on historical banking data. The model helps identify customers likely to leave, enabling proactive retention strategies.

---

## Project Overview
- **Goal:** Predict whether a customer will churn (exit) using demographic and account features.
- **Dataset:** `Churn_Modelling.csv` (10,000 customer records with attributes like geography, gender, credit score, balance, etc.)
- **Approach:** 
  - Preprocessing with label encoding, one‑hot encoding, and feature scaling.
  - ANN built with Keras/TensorFlow.
  - Evaluation using accuracy and confusion matrix.

---

## Repository Structure
- `app.py` → Script for running predictions.
- `experiments.ipynb` → Notebook with model training and evaluation.
- `prediction.ipynb` → Notebook for testing predictions on new data.
- `model.h5` → Trained ANN model.
- `scaler.pkl` → StandardScaler object for feature scaling.
- `label_encoder_gender.pkl` → Encoder for gender.
- `onehot_encoder_geo.pkl` → Encoder for geography.
- `requirements.txt` → Dependencies list.

---

## Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/sreerath-srideep/ANN-Churn-Model.git
cd ANN-Churn-Model
pip install -r requirements.txt
```

---

## To run the application
python app.py

---

## Results
- ANN achieves competitive accuracy on the test set.
- Model outputs probability of churn for each customer.




