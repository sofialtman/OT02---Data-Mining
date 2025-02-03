# Data Mining Project
Predicting a Starcraft 2 player based on a set of behavioral traces. 
## Group members
ALTMAN VOGL, Sofía Paula 
KÉDE LIMA JALLAD, Julia
STEINFELD, Teresa

## Requirements
Python version 3.13.1
Numpy
Pandas
scikit-learn version 1.3.0
sklearn
matplotlib
Shap 
RandomForest Classifier
seaborn

`` bash
pip install numpy
pip install pandas
pip install --upgrade scikit-learn==1.3.0
pip install sklearn
pip install sklearn.ensemble   
pip install matplotlib
pip install shap
pip install RandomForestClassifier
pip install mlxtend
pip install seaborn
``
## For Early Data Analysis
1. data_expl.ipynb
2. plots.ipynb

## Building
In order to build the model, the correct order to run the notebooks and train the model is:
1. features-creation.ipynb
2. Features-Felection.ipynb
3. model.ipynb
4. translation.ipynb

## Diferrent models analysis
1. forward_selection.ipynb
2. multiclass_model.ipynb
3. model_Shapley.ipynb 

## Different testing models 
Not necessary for the main model, they are just notebooks that were made for different tests
1. main_features.ipynb
2. testing.ipynb
3. shapley.ipynb