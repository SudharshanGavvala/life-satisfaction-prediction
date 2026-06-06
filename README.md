# Life Satisfaction Prediction using Linear Regression

This repository contains a Jupyter Notebook that demonstrates how to build a simple linear regression model to predict life satisfaction based on a country's GDP per capita.

## Project Overview

The goal of this project is to explore the relationship between GDP per capita and life satisfaction. We use a dataset containing these metrics for various countries, perform basic exploratory data analysis, train a linear regression model, and visualize the model's predictions.

## Dataset

The dataset used is `lifesat.csv`, which includes:
- `Country`: Name of the country.
- `GDP per capita (USD)`: Gross Domestic Product per capita in US Dollars.
- `Life satisfaction`: A measure of life satisfaction (e.g., from surveys).

## Key Steps

1.  **Data Loading**: The `lifesat.csv` dataset is loaded into a pandas DataFrame.
2.  **Exploratory Data Analysis (EDA)**: Basic checks like `head()`, `shape`, and `info()` are performed to understand the data structure and types. A scatter plot visualizes the relationship between 'GDP per capita (USD)' and 'Life satisfaction'.
3.  **Model Training**: A `LinearRegression` model from scikit-learn is trained on the data, with 'GDP per capita (USD)' as the feature (`x`) and 'Life satisfaction' as the target (`y`).
4.  **Prediction and Visualization**: The trained model's regression line is plotted over the scatter plot to visually represent the linear relationship. The model is also used to make predictions for new GDP per capita values.

## Technologies Used

-   Python
-   Pandas (for data manipulation)
-   NumPy (for numerical operations)
-   Matplotlib (for plotting)
-   Scikit-learn (for linear regression)

## How to Run

1.  Clone this repository:
    ```bash
    git clone <https://github.com/SudharshanGavvala/life-satisfaction-prediction>
    cd <life-satisfaction-prediction>
    ```
2.  Open the Jupyter Notebook (or Google Colab):
    ```bash
    jupyter notebook life_satisfaction_prediction.ipynb
    ```
    or upload the notebook to Google Colab.
3.  Run all cells in the notebook.

This will execute the data loading, model training, and visualization steps, displaying the plots and model predictions.
