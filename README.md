# Heart_Disease_Prediction--Machine_Learning
This Supervised Machine Learning Model predicts the likelihood of a patient having heart disease based on given features. The project was built using Python.

## Processes
1. Importation of required libraries
2. Data Importation and Assessment
3. Exploratory Data Analysis
4. Feature Engineering and Data Pre-Processing
5. Machine Learning Model Building
6. Machine Learning Model Evaluation

## Libraries Importation
Python libraries for the following were imported: Data Analysis, Data Visualization, Data Pre-Processing, Classifiers, and Metrics Evaluation

## Data Importation and Assessment
- The dataset was in a CSV format and imported in JupyterLab using Pandas
- Assessment for the following was carried out: statistical description of features, datatypes of features, presence of duplicates and missing data

## Exploratory Data Analysis
- The dataset was analyzed using univariate, bivariate, and multivariate techniques in the analysis
  From the analysis:
- Outliers were detected in the dataset
- Ages of patients were grouped into 4 buckets and heart disease among the groups analyzed
- Heart disease among the male and female genders was analyzed
- Chest Pain types were analyzed and heart disease among patients with the chest pain type was looked at
- Correlation among the various features and heart disease was analyzed with exercise_induced_angina having the strongest relationship with heart disease

## Feature Engineering and Data Pre-Processing
- The dataset was segmented into predictor variables and target variables for the machine-learning modeling
- Some features in the dataset were normalized using MinMaxScaler

## Model Building
- The data was split into training and testing sets
- Logistic Regression algorithm and Random Forest Classifier was fitted on the dataset to build a machine learning model that predicts the likelihood of patients having heart disease

## Model Evaluation
The models built were evaluated using the following metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC Score, and Confusion Matrix
