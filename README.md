# House-Price-Prediction

This project focuses on predicting house prices in **King County**, which includes Seattle, using a dataset from [Kaggle](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction). It includes home sales between May 2014 and May 2015.

## Dataset

* **Source**: [House Sales in King County, USA – Kaggle](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction)
* **Description**: This dataset includes house sale prices along with 21 house attributes such as number of bedrooms, bathrooms, square footage, location coordinates, etc.

## Project Objectives

* Perform data cleaning and preprocessing
* Conduct exploratory data analysis (EDA) to understand patterns
* Build regression models to predict house prices
* Evaluate and refine models for better accuracy

## Technologies Used

* Python (Pandas, NumPy, Matplotlib, Seaborn)
* Scikit-learn (Linear Regression, Ridge Regression, StandardScaler, etc.)
* Jupyter Notebook
* Google Colab compatible

## 📊 Project Structure

1. **Data Wrangling**: Handle missing values, drop irrelevant features, type conversion
2. **Exploratory Data Analysis**: Visualize distributions, correlations, outliers
3. **Feature Engineering**: Normalize and transform data
4. **Model Development**: Linear and Ridge regression models using pipelines
5. **Model Evaluation**: R-squared, plotting predictions vs. actuals

## Insights

* Houses with waterfront views have significantly higher prices
* Living area and number of bedrooms are positively correlated with price
* Polynomial features improved prediction performance in some models
