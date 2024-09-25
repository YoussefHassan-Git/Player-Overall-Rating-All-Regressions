# Player Overall Rating Prediction using Regression Models ⚽️📊

This project focuses on predicting player overall ratings using various regression models. It encompasses data reading, exploration, preprocessing, visualization, model building, and evaluation.

## 📚 Table of Contents
1. [Importing Libraries](#importing-libraries) 📦
2. [Data Reading](#data-reading) 📖
3. [Data Exploration](#data-exploration) 🔍
4. [Data Visualization](#data-visualization) 📈
5. [Data Preprocessing](#data-preprocessing) 🔧
6. [Models Building](#models-building) 🏗️
7. [Models Evaluation](#models-evaluation) ✅

## Importing Libraries 📦
```python
import pandas as pd
import matplotlib.pyplot as plt
import numpy as np
import seaborn as sns
import plotly.express as px
```
---
## Data Reading 📖
![image](https://github.com/user-attachments/assets/1e7f2842-2ff8-4fc3-be38-d3fc5b636b56)

## Data Exploration 🔍
Dataset Information:  `data.info()`
Descriptive Statistics: `print(data.describe())`
Check for Duplications: `data.duplicated().sum()`
Check for Missing Values:

## Data Visualization 📈
Scatter Plot: sns.scatterplot(data=data, x="national_rating", y="age")
Histogram: sns.histplot(data=data, y='age', kde=True)
Bar Plots for various attributes to visualize relationships.

## Data Preprocessing 🔧
1-Drop Columns
2-Encode Categorical Columns
## Models Building 🏗️
Using multiple regression models including:

* Linear Regression
* KNeighbors Regressor
* SVR
* Random Forest Regressor
* Decision Tree Regressor
* AdaBoost Regressor
* XGBoost Regressor
## Models Evaluation ✅
Evaluate Models: Using R² score, Mean Squared Error, etc.
Top 5 Residuals: Both for training and testing datasets.
---
----------------------- Linear Regression -----------------------
Model Training Peformance: 
R2 Score : 0.9092792076331654
Training Mean Squared Error : 4.374921356109056
Training Square Root Mean Squared Error : 2.091631266765023
Training Mean Absolute Error : 1.6243002581674064
Model Testing Peformance: 
Testing R2 Score : 0.9119714490438211
Testing Mean Squared Error : 4.280444308288803
Testing Square Root Mean Squared Error : 2.06892346602981
Testing Mean Absolute Error : 1.6268842222111695
----------------------- KNeighbors Regressor -----------------------
Model Training Peformance: 
R2 Score : 0.9345065764732263
Training Mean Squared Error : 3.1583562025492795
Training Square Root Mean Squared Error : 1.7771764691637348
Training Mean Absolute Error : 1.3448909939402387
Model Testing Peformance: 
Testing R2 Score : 0.9036848144928799
Testing Mean Squared Error : 4.683387186629527
Testing Square Root Mean Squared Error : 2.1641134874653702
Testing Mean Absolute Error : 1.6329805013927576
----------------------- SVR -----------------------
Model Training Peformance: 
R2 Score : 0.8866281012234682
Training Mean Squared Error : 5.4672487772649365
Training Square Root Mean Squared Error : 2.338214869780991
Training Mean Absolute Error : 1.6533347427510017
Model Testing Peformance: 
Testing R2 Score : 0.8866437635217378
Testing Mean Squared Error : 5.512019134382432
Testing Square Root Mean Squared Error : 2.34776896955012
Testing Mean Absolute Error : 1.6718936372249962
----------------------- Random Forest Regressor -----------------------
Model Training Peformance: 
R2 Score : 0.9961811520800373
Training Mean Squared Error : 0.18416020059901095
Training Square Root Mean Squared Error : 0.4291389059488908
Training Mean Absolute Error : 0.2855276171902209
Model Testing Peformance: 
Testing R2 Score : 0.9730736296303251
Testing Mean Squared Error : 1.3093118941504178
Testing Square Root Mean Squared Error : 1.1442516743052717
Testing Mean Absolute Error : 0.7716350974930363
----------------------- Decision Tree Regressor -----------------------
Model Training Peformance: 
R2 Score : 1.0
Training Mean Squared Error : 0.0
Training Square Root Mean Squared Error : 0.0
Training Mean Absolute Error : 0.0
Model Testing Peformance: 
Testing R2 Score : 0.9292703186361077
Testing Mean Squared Error : 3.439275766016713
Testing Square Root Mean Squared Error : 1.8545284484247506
Testing Mean Absolute Error : 1.2186629526462396
----------------------- XG Boost Regressor -----------------------
Model Training Peformance: 
R2 Score : 0.994337288421197
Training Mean Squared Error : 0.2730787195885235
Training Square Root Mean Squared Error : 0.5225693442869793
Training Mean Absolute Error : 0.38744536971966187
Model Testing Peformance: 
Testing R2 Score : 0.9759703124596631
Testing Mean Squared Error : 1.1684588482343239
Testing Square Root Mean Squared Error : 1.0809527502320921
Testing Mean Absolute Error : 0.7697139017429192
----------------------- Ada Boost Regressor -----------------------
Model Training Peformance: 
R2 Score : 0.9030911254937298
Training Mean Squared Error : 4.673335556413929
Training Square Root Mean Squared Error : 2.161789896454771
Training Mean Absolute Error : 1.7912987639049252
Model Testing Peformance: 
Testing R2 Score : 0.9023102052003553
Testing Mean Squared Error : 4.75022843822796
Testing Square Root Mean Squared Error : 2.1795018784639666
Testing Mean Absolute Error : 1.7950450000458502
---

## Conclusion 🎉
Best Models: XG Boost Regressor and Random Forest Regressor showed the highest performance.
