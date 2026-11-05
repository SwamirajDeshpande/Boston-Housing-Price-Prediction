# Boston Housing Price Prediction - ML Practical

<div align="center">

[![Python](https://img.shields.io/badge/Python-3.12%2B-blue.svg)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.5%2B-orange.svg)](https://scikit-learn.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626.svg)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

</div>

---

## 📌 Overview
This repository contains an end-to-end Machine Learning practical workflow implemented in a Jupyter Notebook (`Boston_Housing.ipynb`). The project covers data ingestion, missing value imputation, feature scaling, and comparative regression modeling on the classic Boston Housing dataset.

---

## 📂 Project Structure & Workflow
1. **Data Ingestion & Inspection**: Loads the housing dataset (`housingData.csv`) and performs initial exploratory checks for missing attributes[cite: 1].
2. **Data Cleaning**: Imputes missing values feature-wise using respective column means (`fillna(boston.mean())`)[cite: 1].
3. **Train-Test Split**: Separates features (`X`) and target variable (`y`), followed by an 80-20 train-test split (`random_state=42`)[cite: 1].
4. **Feature Scaling**: Standardizes input features using Scikit-Learn's `StandardScaler` to optimize distance-sensitive and linear estimators[cite: 1].
5. **Model Training & Evaluation**: Evaluates four distinct machine learning regression models using **$R^2$ Score** and **Mean Squared Error (MSE)**[cite: 1].

---

## 📊 Models & Performance Comparison

| Model | Evaluation Metrics |
| :--- | :--- |
| **1. Linear Regression** | $R^2$: `0.6589` \| MSE: `25.02`[cite: 1] |
| **2. K-Nearest Neighbors (KNN)** | $R^2$: `0.6949` \| MSE: `22.37`[cite: 1] |
| **3. Decision Tree Regressor** | $R^2$: `0.7242` \| MSE: `20.23`[cite: 1] |
| **4. Random Forest Regressor** | $R^2$: `0.8878`[cite: 1] |

---

## 🚀 Getting Started & Installation

### Prerequisites
Ensure you have Python installed along with the required scientific computing and machine learning libraries:
```bash
pip install numpy pandas matplotlib scikit-learn
```
## Running the Notebook
1. Clone the repository or download the project files.

2. Place your dataset file (housingData.csv) in the root directory[cite: 1].

3. Launch Jupyter Notebook:
   ```bash
jupyter notebook Boston_Housing.ipynb
``` 
4. Execute all notebook cells sequentially to reproduce the end-to-end results.
