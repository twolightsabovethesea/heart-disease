The purpose of this project was to explore how machine learning can be used to predict heart disease. To accomplish this, a dataset containing anonymyzed patient data was obtained from Kaggle in CSV format.

After reading the data into a Pandas dataframe in Jupyter Lab, the project had several steps. First, two basic machine learning models, one Random Forest and one with XGBoost, were created to predict heart disease among patients. The data was split into training and validation data and the target was separated from the features. The models were each trained and then run on the validation data to find their respective mean absolute errors.

After comparing the models and selecting the better one, the limitations of the model were explored. The data was broken down by demographics and the mean absolute error for demographic groups was determined and visualized.

More information on the project can be viewed on this visualization dashboard: https://twolightsabovethesea.github.io/Web-Design-Challenge/
