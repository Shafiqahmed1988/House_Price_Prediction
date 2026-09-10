[![Python](https://img.shields.io/badge/Python-3.x-blue)](https://www.python.org/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Machine%20Learning-orange)](https://scikit-learn.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org/)





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
## Key Results

- Best Model: **Tuned Random Forest Regression**
- R² Score: **80.62%**
- MAE: **0.3268**
- RMSE: **0.5040**
- Most Important Feature: **MedInc**
- Model trained and evaluated using the California Housing dataset
## Project Highlights

- Performed data inspection and preprocessing
- Analyzed relationships between housing features and house prices
- Built a baseline Linear Regression model
- Built a Random Forest Regression model
- Compared model performance using MAE, RMSE, and R²
- Performed hyperparameter tuning using GridSearchCV
- Identified the most important features using feature importance
- Generated predictions for new house data
- Saved and loaded the trained machine learning model using Joblib
## Model Comparison

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Linear Regression | 0.5332 | 0.7456 | 0.5758 |
| Random Forest | 0.3275 | 0.5053 | 0.8051 |
| Tuned Random Forest | **0.3268** | **0.5040** | **0.8062** |

The Tuned Random Forest model achieved the highest R² score and the
lowest MAE and RMSE among the evaluated models.
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
## Project Structure

```text
House_Price_Prediction/
│
├── house_price_prediction.ipynb
├── README.md
├── requirements.txt
└── house_price_model.pkl


With an R² Score of approximately \*\*80.62%\*\*, the tuned model was

selected as the final model for house price prediction.
##How to Run
Install the required Python libraries:
pip install -r requirements.txt
## Project Notebook

The complete machine learning workflow is available in the Jupyter Notebook.

Notebook:

https://github.com/Shafiqahmed1988/House_Price_Prediction/blob/main/house_price_prediction.ipynb
## Author

**Md.Shafikul**

This project was developed as part of my machine learning and data
analytics portfolio.

## Contact
## Feature Importance

The feature importance analysis shows which variables contributed most
to the Tuned Random Forest model's predictions.

[Feature Importance](feature_importance.png)

For professional collaboration or discussion, please connect with me
through GitHub.
