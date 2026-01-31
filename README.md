# 📊 Automatidata ML Analytics

This repository contains an end-to-end **Machine Learning analytics project** built on New York City taxi trip data. The project demonstrates the full ML workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, and model training using **Random Forest** and **XGBoost** classifiers.

---

## 📂 Project Overview

The goal of this project is to analyze large-scale taxi trip data and build predictive machine learning models using structured tabular data. The notebook walks through:

- Loading and cleaning real-world datasets  
- Performing exploratory data analysis (EDA)  
- Feature engineering and data preparation  
- Training and evaluating machine learning models  
- Comparing ensemble-based classifiers  

---

## 🗃️ Datasets

This project uses the following datasets stored in the `data/` folder:

### 1️⃣ `2017_Yellow_Taxi_Trip_Data.csv`
- Contains taxi trip records from New York City.
- The data was collected by the **New York City Taxi & Limousine Commission (TLC)**.
- Published by the **City of New York** as part of the **NYC Open Data** program.
- Originally consists of over **113 million rows**, but a **sampled subset** is used in this project to improve runtime performance and learning efficiency.

### 2️⃣ `nyc_preds_means.csv`
- Contains predictions and derived statistical calculations.
- Generated from prior analytical steps and model outputs.
- Used to support feature engineering and downstream modeling tasks.

> All datasets were cleaned and preprocessed before being used for model training.

---

## 🤖 Machine Learning Models

The notebook implements and evaluates the following classification models:

### 🟢 Random Forest Classifier
- An ensemble learning method that builds multiple decision trees.
- Improves accuracy and reduces overfitting.
- Performs well on large, structured datasets.

### 🔵 XGBoost Classifier
- A gradient boosting algorithm optimized for performance and speed.
- Builds trees sequentially to correct previous errors.
- Known for strong results on tabular data problems.

The performance of both models is evaluated and compared using standard classification metrics.

---

## 📋 Notebook Structure

The main analysis and modeling work is contained in:

- `Automatidata-ML-Analytics.ipynb`

Key sections inside the notebook include:
1. Data loading and inspection  
2. Data cleaning and preprocessing  
3. Exploratory data analysis (EDA)  
4. Feature engineering  
5. Model training (Random Forest & XGBoost)  
6. Model evaluation and comparison  

---

## 📦 Requirements

The project relies on the following Python libraries:

pandas
numpy
matplotlib
scikit-learn
xgboost
