# Population Growth Analysis and Forecasting

## Project Overview

This project performs data cleaning, exploratory data analysis (EDA),
visualization, advanced analysis, and population forecasting using the
**UN World Population Prospects 2024** dataset.

The objective is to analyze historical population trends and build a
forecasting model to estimate future population values for selected
countries.

## Project Scope

-   Historical analysis period: **1950--2023**
-   Population unit: **Persons**
-   Geographic level: **Country/Area**
-   UN scenario: **Medium**
-   Forecasting method: **Linear Regression**
-   Forecast horizon: **2024--2033**

## Technologies Used

-   Python
-   Jupyter Notebook
-   Pandas
-   NumPy
-   Matplotlib
-   Scikit-learn

## Project Workflow

1.  Data Loading
    -   Import population dataset
    -   Inspect dataset structure and variables
2.  Data Cleaning and Preprocessing
    -   Handle missing values
    -   Prepare data for analysis
    -   Filter required countries and years
3.  Exploratory Data Analysis
    -   Analyze population trends
    -   Identify growth patterns
    -   Compare countries and time periods
4.  Data Visualization
    -   Generate population trend charts
    -   Present analytical insights using graphs
5.  Population Forecasting
    -   Build separate Linear Regression models for selected countries
    -   Use year as input feature
    -   Predict future population values

## Machine Learning Approach

### Model

Linear Regression

### Features

-   Year (Independent Variable)

### Target

-   Population (Dependent Variable)

### Training and Testing

-   Training period: 2005--2018
-   Testing period: 2019--2023
-   Forecast period: 2024--2033

### Evaluation Metrics

-   Mean Absolute Error (MAE)
-   Root Mean Squared Error (RMSE)
-   R² Score

## How to Run the Project

### 1. Clone the repository

``` bash
git clone <repository-url>
```

### 2. Install dependencies

``` bash
pip install -r requirements.txt
```

### 3. Open Jupyter Notebook

``` bash
jupyter notebook
```

### 4. Run the notebook

Open:

    data-analytics-final-project.ipynb

## Limitations

The Linear Regression model provides an interpretable baseline forecast
but does not consider demographic factors such as: - Fertility rate -
Mortality rate - Migration - Economic changes - Policy changes -
Unexpected events

## Author

Data Analytics Final Project
