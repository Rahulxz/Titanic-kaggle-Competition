# Titanic-kaggle-Competition
These are the different models and different types of ways of implementation of the models for the Kaggle competition on Titanic DataSet. 
The first one is created without using column transformers and the model used is DecisionTreeClassifier when uploaded the score on kaggle was 0.34
**Libarires used**
Pandas 

Numpy

Sklearn

OneHotEncoder

SimpleImputer

MinMaxScaler

The Second one is created usiing columntransformers and the pipeline is used here also the model used is RandomForestClassifier. When uploaded on kaggle the score on it was 0.66 a increase in score of about 100%.

**Extra Libarires used** 

ColumnTransformer

Pipeline

SelectKBest, chi2 : For feature selection of best feaures.

