\# House Price Prediction using Machine Learning



\## Project Overview



This project focuses on predicting house prices using machine learning

techniques. The California Housing dataset was used to build, evaluate,

and compare multiple regression models.



\## Objective



The main objective is to develop a machine learning model capable of

predicting median house prices based on housing, demographic, and

geographical features.



\## Dataset



The California Housing dataset contains:



\- 20,640 records

\- 8 input features

\- 1 target variable



\### Features



\- MedInc

\- HouseAge

\- AveRooms

\- AveBedrms

\- Population

\- AveOccup

\- Latitude

\- Longitude



\### Target



\- Price



\## Machine Learning Models



The following models were evaluated:



1\. Linear Regression

2\. Random Forest Regression

3\. Tuned Random Forest Regression



\## Model Performance



| Model | MAE | RMSE | R² Score |

|---|---:|---:|---:|

| Linear Regression | 0.5332 | 0.7456 | 0.5758 |

| Random Forest | 0.3275 | 0.5053 | 0.8051 |

| Tuned Random Forest | 0.3268 | 0.5040 | 0.8062 |



\## Best Model



The \*\*Tuned Random Forest Regression\*\* model achieved the best overall

performance.



\- R² Score: \*\*80.62%\*\*

\- MAE: \*\*0.3268\*\*

\- RMSE: \*\*0.5040\*\*



\## Feature Importance



The most important features were:



1\. MedInc — 52.59%

2\. AveOccup — 13.81%

3\. Latitude — 8.86%

4\. Longitude — 8.83%



\## Technologies Used



\- Python

\- Pandas

\- NumPy

\- Matplotlib

\- Seaborn

\- Scikit-learn

\- Joblib

\- Jupyter Notebook



\## Project Workflow



Data Collection → Data Cleaning → Exploratory Data Analysis →

Feature Analysis → Model Training → Model Evaluation →

Hyperparameter Tuning → Final Prediction → Model Saving



\## Conclusion



The Tuned Random Forest model performed significantly better than

Linear Regression and the initial Random Forest model.



With an R² Score of approximately \*\*80.62%\*\*, the tuned model was

selected as the final model for house price prediction.

