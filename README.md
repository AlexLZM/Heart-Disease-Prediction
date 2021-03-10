# MSDS 699 Final Project

## Student: Zhimin Lyu

## Project description
This dataset gives information of patients related to heart disease. Dataset contains 13 features of patients' conditons and test results, target variable is the fact that the patient has heart disease or not. 

In the project, we set the aim to build a decent model to predict the target variable (disease\non disease) by comparing different machine learning algorithms.

<b>Data Attribute Information</b>

Age (age in years)

Sex (1 = male; 0 = female)

CP (chest pain type)

TRESTBPS (resting blood pressure (in mm Hg on admission to the hospital))

CHOL (serum cholestoral in mg/dl)

FPS (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)

RESTECH (resting electrocardiographic results)

THALACH (maximum heart rate achieved)

EXANG (exercise induced angina (1 = yes; 0 = no))

OLDPEAK (ST depression induced by exercise relative to rest)

SLOPE (the slope of the peak exercise ST segment)

CA (number of major vessels (0-3) colored by flourosopy)

THAL (3 = normal; 6 = fixed defect; 7 = reversable defect)

Disease (has heart disease or not: 1 or 0)

## Table of Contents

#### Load Data

#### Fit scikit-learn model

#### Final evaluation on test set

#### Conclusion
Randomized hyperparameter search and bayesian optimization search are very useful to find decent hyperparameters quickly.
 
Tree ensembles are effective in tabular data prediction as it has plenty of mearsures to reduce overfit. And thet worked as expected in this project. Well-tuned Gradient Boost Machine works best in this case.
 
The final model is decent to help doctors to diagnose if a patient has heart disease or not.
And it shows that CP (chest pain type) and EXANG (exercise induced angina (1 = yes; 0 = no)) are the first 2 important factors in the diagnosis.
 

#### Next steps
Other ensembles such as Xgboost, catboost and lightgbm could be attempted in the future.
