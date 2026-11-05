# Boston Housing Price Prediction 
A end-to-end Machine Learning pipeline implemented in Jupyter Notebook (Boston_Housing.ipynb) demonstrating data preprocessing, feature scaling, model training, and performance evaluation on the classic Boston Housing dataset.  
📌 Overview
The objective of this project is to build and evaluate multiple regression models to predict the median value of owner-occupied homes (MEDV) in $1,000s.   
🛠️ Project Structure & Workflow
Data Ingestion & Inspection: Loading the dataset (housingData.csv) and examining missing values.   
Data Cleaning: Imputing missing values using feature-wise mean values (fillna(boston.mean())).   
Data Splitting: Splitting features (X) and target (y) into 80% training and 20% testing sets (random_state=42).  
Feature Scaling: Standardizing input features using Scikit-Learn's StandardScaler.   
Model Evaluation: Training Linear Regression, KNN, Decision Tree, and Random Forest models using $R^2$ Score and Mean Squared Error (MSE).   
📊 Models & Performance
ModelEvaluation MetricsLinear Regression$R^2$: 0.6589 | MSE: 25.02   K-Nearest Neighbors (KNN)$R^2$: 0.6949 | MSE: 22.37   Decision Tree Regressor$R^2$: 0.7242 | MSE: 20.23   Random Forest Regressor$R^2$: 0.8878   🚀 Getting StartedPrerequisitesEnsure you have Python 3.x installed along with the following libraries:Bashpip install numpy pandas matplotlib scikit-learn
Running the NotebookClone the repository and place housingData.csv in the project root directory.   Launch Jupyter Notebook:Bashjupyter notebook Boston_Housing.ipynb
Run all cells sequentially to execute data preprocessing, model fitting, and evaluation.
