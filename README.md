# Titanic Survival Prediction - Pluto Academy AI/ML Internship

## Project Overview
Machine learning project to predict Titanic passenger survival
using Python and Scikit-learn. Three ML models were built,
trained, and compared.

## Intern Details
- Name: Pruthviraj Vikas Chavan
- Organization: Pluto Academy
- MSME: UDYAM-RJ-06-0057331
- Duration: 1 Month (June 2026)

## Dataset
Titanic - Machine Learning from Disaster
https://www.kaggle.com/c/titanic

## Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Models Built
| Model | Accuracy |
|---|---|
| Logistic Regression | 79.89% |
| Random Forest | 82.68% |
| KNN | 69.83% |

## Best Model
Random Forest with 82.68% accuracy

## What I Did
1. Loaded and explored 891 rows of Titanic passenger data
2. Cleaned missing values in Age, Cabin, Embarked columns
3. Encoded categorical variables (Sex, Embarked)
4. Performed feature engineering and correlation analysis
5. Trained 3 ML models with 80/20 train-test split
6. Evaluated all models using Accuracy, Precision, Recall, F1
7. Plotted confusion matrix and feature importance chart

## Key Findings
- Random Forest was the best performing model at 82.68% accuracy
- Fare, Sex and Age were the top 3 most important features
- Females had significantly higher survival rates than males
- Higher ticket fare strongly correlated with better survival chance
