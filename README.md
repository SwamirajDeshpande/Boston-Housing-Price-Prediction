# 🏡 Boston Housing Price Prediction

A Machine Learning project that predicts the median value of houses in Boston (Capital city of the state Massachusetts in USA) using various housing and neighborhood-related features. This project demonstrates the complete workflow of a regression-based Machine Learning application, including data preprocessing, exploratory data analysis, model training, evaluation, and price prediction.

## 📌 Project Overview

Boston Housing Price Prediction is a supervised Machine Learning project designed to estimate housing prices based on different characteristics of residential areas.

The project uses regression algorithms to learn relationships between housing features and their corresponding prices, helping understand how factors such as location, property characteristics, and neighborhood conditions influence housing values.

## 🎯 Objectives

- Understand and analyze the Boston Housing dataset.
- Perform Exploratory Data Analysis (EDA).
- Identify important features influencing housing prices.
- Apply data preprocessing and feature engineering techniques.
- Train and evaluate regression models.
- Predict housing prices using Machine Learning.
- Understand the practical implementation of a regression problem.

## 📊 Dataset

**Dataset:** Boston Housing Dataset

**Target Variable:** `MEDV`

The target represents the median value of owner-occupied homes in a Boston census tract, historically measured in thousands of US dollars.

### Features Description

| Feature | Description |
|---|---|
| CRIM | Per capita crime rate by town |
| ZN | Proportion of residential land zoned for large lots |
| INDUS | Proportion of non-retail business acres |
| CHAS | Charles River dummy variable |
| NOX | Nitric oxide concentration |
| RM | Average number of rooms per dwelling |
| AGE | Proportion of owner-occupied units built before 1940 |
| DIS | Weighted distances to employment centers |
| RAD | Accessibility to radial highways |
| TAX | Property tax rate |
| PTRATIO | Pupil-teacher ratio by town |
| B | Historical demographic transformation feature |
| LSTAT | Percentage of lower-status population |
| MEDV | Median house value (Target) |

> **Note:** The original Boston Housing dataset has documented ethical and methodological limitations, including the `B` feature, which reflects historical racialized assumptions. It should be used for educational purposes rather than real-world housing decisions.

## 🛠️ Tech Stack

- **Programming Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Development Environment:** Jupyter Notebook / VS Code
- **Version Control:** Git & GitHub

## ⚙️ Machine Learning Workflow

1. **Data Collection** – Load the Boston Housing dataset.
2. **Data Preprocessing** – Inspect missing values, data types, and data quality.
3. **Exploratory Data Analysis** – Analyze distributions, correlations, and relationships between features.
4. **Feature Selection** – Identify relevant input variables.
5. **Train-Test Split** – Divide the dataset into training and testing sets.
6. **Model Training** – Train regression algorithms.
7. **Model Evaluation** – Evaluate performance using regression metrics.
8. **Prediction** – Generate predictions for unseen housing data.

## 🤖 Algorithms Used

The project can be implemented using the following regression algorithms:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

The models can be compared to identify the best-performing algorithm based on evaluation metrics.

## 📈 Evaluation Metrics

| Metric | Description |
|---|---|
| MAE | Mean Absolute Error |
| MSE | Mean Squared Error |
| RMSE | Root Mean Squared Error |
| R² Score | Coefficient of Determination |

These metrics help evaluate prediction accuracy and the overall performance of regression models.

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Boston-Housing-Prediction.git
```

### 2. Navigate to the Project Directory

```bash
cd Boston-Housing-Prediction
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

Activate the environment:

**Windows**
```bash
venv\Scripts\activate
```

**Linux / macOS**
```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the Project

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Or run the training script:

```bash
python src/train.py
```

## 🔮 Future Improvements

- Implement hyperparameter tuning using GridSearchCV or RandomizedSearchCV.
- Perform advanced feature engineering.
- Add feature importance visualization.
- Develop an interactive Streamlit web application.
- Deploy the prediction model using Streamlit Cloud.
- Explore modern datasets for real-world housing price prediction.

## 🎓 Learning Outcomes

- Practical understanding of supervised Machine Learning.
- Experience with regression algorithms.
- Knowledge of Exploratory Data Analysis.
- Understanding of model evaluation techniques.
- Hands-on experience with Scikit-learn.
- Experience building an end-to-end Machine Learning project.

## 👨‍💻 Author

**Swamiraj Deshpande**

B.Tech Computer Science Engineering (AI & ML)

Vishwakarma Institute of Technology, Pune

## ⭐ Support

If you find this project useful, consider giving it a ⭐ on GitHub!

---

*Built with Python and Machine Learning.*
