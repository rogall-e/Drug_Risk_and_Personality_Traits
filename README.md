# Drug Risk and Personality Traits

Authors: [Drenizë Rama](https://drenize.github.io/) & Eike Rogall

This project is still **in progress**

![alt text](https://cdn.sanity.io/images/0vv8moc6/drugtopics/f68b395a07eacef111246f6f7a120139cefb8145-1000x667.jpg?auto=format)

## Overview 

This project aims at examining the relationship between personality traits and drug consumption based on the [Drug consumption (quantified) Data Set](https://archive.ics.uci.edu/ml/datasets/Drug+consumption+%28quantified%29). The Dataset contains 35 variables of 1885 people.. First, the normalized data is coded into more apprehensible, numeric categories. Then further features are engineered to highlight deeper data structures. The engineered variables are: soft drug consumption, hard drug consumption, legal drug consumption, illegal drug consumption, synthetic and nonsynthetic drug consumption, recent consumtion, hard score and hardliners.

The hard score (hard_score) is build of the mean of neuroticism, extraversion, impulsiveness and sensation seeking. The hardliner variable, however, comprises only the 10% highest hard scores.
Business Case

A drug prevention organization is interested in the use frequency of illegal drugs of hardliner personalities versus other people. Furthermore, they want to predict the use of illegal drugs.

The project was part of a data science bootcamp and should cover all stages of the data science cycle:

## Data Science Lifecycle

- 1 Business Understanding
- 2 Data Mining
- 3 Data Cleaning
- 4 Data Exploration
- 5 Feature Engineering
- 6 Predictive Modeling
- 7 Data Visualization

## Python Modules used:
Pandas / NumPy / Matplotlib / Seaborn / Plotly / sklearn
 
## Used ML Models
Models were applied and compared for recall and accuracy scores

- XGBClassifier
- AdaBoost
- RandomForestClassifier
- Support Vector Machine
- DecisionTreeClassifier
 
## Conclusions
- reliable prediction of hardliners is not possible with current data
- reliable prediction of illegal drug users on the other hand is possible based on: sensation seeking, ethnicity, openness to new experiences, country, conscientiousness, age
- illegal drug use is a widespread issue throughout society

## Future Work
**Data related implications:**

- collect data on socioeconomic status
- collect data on amount of drug doses
- collect data on clinical diagnoses
- collect data on abuse and addiction
- collect timeline data to identify co-morbidity of diverse substance abuse or/and addiction

**Model related implications:**

- try unsupervised machine learning models
- apply regression models on continuous data
- new model for hardliner prediction

## Files and Folders

- Drug_Risk_and_Personality_Traits.ipynb : jupyter notebook with Exploratory Data Analysis (EDA), python code, visualizations and documentation
- Drugs_and_Personality_Traits_DataScience_Project.pdf : Presentation of the results of the Data Visualization
- Drug_Risk.xls : Dataset
