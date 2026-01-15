# Master Projects

## Master-Project 1 : Random Forest and XGBoost Algorithm for Earthquake Analysis and Prediction
## Master Project 2: Tsunami Prediction and Analysis Using XGBoost and Naive Bayes Algorithm

This project focuses on predicting earthquake and tsunami-generating earthquakes using
machine learning techniques, specifically **XGBoost** and **Naïve Bayes**.
The study integrates geoscience knowledge with data science to improve
early-warning capabilities.

## 📌 Objectives
- Perform data preprocessing and exploratory data analysis (EDA)
- Predict tsunami-generating earthquakes using ML models
- Compare XGBoost and Naïve Bayes performance
- Visualize results using an interactive dashboard

## 📊 Dataset
- Source: Kaggle (Global Earthquake Dataset)
- Time Period: 2015–2024
- Features:
  - Magnitude
  - Depth
  - Location (latitude, longitude)
  - Tsunami occurrence (0 / 1)

## ⚙️ Methodology
1. Data Cleaning & Preprocessing
2. Feature Engineering
3. Model Training
   - XGBoost (with hyperparameter tuning)
   - Naïve Bayes (Gaussian NB)
4. Model Evaluation
   - Accuracy
   - Precision
   - Recall
   - ROC-AUC
5. Visualization Dashboard

## 🧠 Models Used
### XGBoost
- Handles nonlinear relationships
- Robust to noise
- Suitable for imbalanced data

### Naïve Bayes
- Simple and fast
- Probabilistic approach
- Baseline comparison model

## 📈 Results
- XGBoost achieved higher Recall (97.6%)
- Better detection of tsunami events compared to Naïve Bayes
- Suitable for early-warning system applications

## 📦 Installation
```bash
pip install -r requirements.txt
