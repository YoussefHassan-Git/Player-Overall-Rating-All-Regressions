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
## Conclusion 🎉
Best Models: XG Boost Regressor and Random Forest Regressor showed the highest performance.
