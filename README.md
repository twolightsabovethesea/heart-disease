# Predicting Heart Disease

This project explores how machine learning can be used to predict heart disease. 

## Description
The goal of this project was to compare the use of two different types of machine learning models to predict the presence of heart disease based on patient data.

## Resources
A [dataset](https://www.kaggle.com/johnsmith88/heart-disease-dataset) containing anonymized patient data was obtained from Kaggle in CSV format.

## Method

After reading the data into a Pandas dataframe in Jupyter Lab, the project had several steps. First, two basic machine learning models, one Random Forest and one with XGBoost, were created to predict heart disease among patients. The data was split into training and validation data and the target was separated from the features. The models were each trained and then run on the validation data to find their respective mean absolute errors.

After comparing the models and selecting the better one, the limitations of the model were explored. The data was broken down by demographics and the mean absolute error for demographic groups was determined and visualized.

## Results
Overall, the XGBoost model performed significantly better than the Random Forest model.

![Image](https://github.com/twolightsabovethesea/heart-disease/blob/main/images/Random_Forest_VS_XGBoost.png)

More information on the project, including exploration by demographics, can be viewed on this visualization dashboard: https://twolightsabovethesea.github.io/Web-Design-Challenge/
