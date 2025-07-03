
#  NYC East Bike Sharing Analysis

This project analyzes the **NYC East Bike Database**, which provides insights into bike circulation in New York City's east region — including Brooklyn, Manhattan, Williamsburg, and the Queensboro Bridge.

---

## Project Overview

The notebook `Bikes.ipynb` performs:

-  **Exploratory Data Analysis (EDA)** with Seaborn and Matplotlib
-  **Data cleaning and preprocessing**
-  **Correlation and feature importance analysis**
-  **Machine learning modeling** using:
  - Linear Regression
  - Decision Tree Regressor
- **Model evaluation** using MAE, MSE, RMSE, R², and MAPE

---

##  Dataset: NYC East Bike Database

###  Overview

The dataset includes:
- Bike counts recorded in April
- Weather information: temperature and precipitation
- Focused on NYC east areas: Brooklyn, Manhattan, Williamsburg, Queensboro Bridge

###  Purpose

To analyze the relationship between:
-  Bike circulation
-  Temperature
-  Precipitation

The goal is to uncover patterns and trends that explain how weather affects bike usage.

---

## Data Cleaning

Before any analysis:
- Removed duplicate records
- Handled missing values
- Standardized formats for consistent analysis

---

##  Exploratory Data Analysis

Using visualizations and statistical summaries, the project explores:
- How bike usage changes across days
- The influence of weather on bike demand
- Correlations between numerical features

---

##  Dependencies

Install required Python libraries:

```bash
pip install -r requirements.txt
