# Tourism Revenue Prediction in Ireland Using Machine Learning

## Project Overview

Tourism is a significant contributor to Ireland's economy, generating revenue, supporting employment, and contributing to Gross Domestic Product (GDP). This project investigates the factors that influence tourism expenditure and develops machine learning models to predict tourism revenue based on travel behavior.

Using tourism data from the Central Statistics Office (CSO) covering the period from 2012 to 2019, the study examines the relationship between tourism expenditure, the number of overseas trips, and the average number of nights spent in Ireland. Multiple supervised machine learning regression models were developed and compared to identify the most accurate approach for predicting tourism revenue.

The project follows the CRISP-DM (Cross-Industry Standard Process for Data Mining) framework to guide the data science workflow from business understanding through model evaluation.

## Business Problem

Tourism expenditure is a key driver of economic growth. Understanding the factors that influence tourism spending can help policymakers and tourism organizations develop strategies to increase revenue and improve tourism performance.

This project aims to answer the following question:

**Can tourism expenditure be accurately predicted using the number of overseas trips and the average number of nights stayed in Ireland?**

## Dataset

**Source:** Central Statistics Office (CSO), Ireland

**Period:** 2012–2019

### Features

* Number of Overseas Trips
* Average Number of Nights Stayed
* Tourism Expenditure (€)

### Target Variable

* Tourism Expenditure (€)

## Objectives

* Analyze historical tourism trends in Ireland.
* Explore relationships between tourism expenditure and travel activity.
* Develop predictive models for tourism revenue estimation.
* Compare the performance of multiple regression algorithms.
* Identify the factors that most strongly influence tourism expenditure.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

## Methodology

The project follows the CRISP-DM framework:

### 1. Business Understanding

Define the business objective and identify key tourism indicators.

### 2. Data Understanding

Explore tourism expenditure, trip volume, and average stay duration.

### 3. Data Preparation

* Data cleaning
* Feature selection
* Data transformation
* Train-test split

### 4. Modeling

The following machine learning models were implemented:

* Linear Regression
* Polynomial Regression
* Random Forest Regression
* ElasticNet Regression

### 5. Evaluation

Model performance was evaluated using:

* Mean Absolute Error (MAE)
* R² Score (Coefficient of Determination)

### 6. Deployment & Insights

Interpret model results and generate recommendations for tourism stakeholders.

## Results

The analysis revealed a strong positive relationship between tourism expenditure and the number of overseas trips. Among the evaluated machine learning models, the best-performing model demonstrated strong predictive capability for estimating tourism revenue.

The findings suggest that increasing the number of international visitors is likely to have a significant positive impact on tourism revenue generation in Ireland.

## Key Insights

* Tourism expenditure increases as the number of overseas visitors increases.
* Travel volume is a strong predictor of tourism revenue.
* Machine learning models can effectively estimate tourism expenditure using historical tourism indicators.
* Data-driven forecasting can support tourism planning and policy development.

## Future Improvements

* Incorporate seasonal and monthly tourism trends.
* Include economic indicators such as inflation and exchange rates.
* Integrate flight, accommodation, and event data.
* Explore advanced machine learning techniques such as XGBoost and Gradient Boosting.
* Build an interactive dashboard for tourism forecasting and reporting.
