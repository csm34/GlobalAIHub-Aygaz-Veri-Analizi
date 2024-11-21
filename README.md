# Retail Transaction Dataset Analysis and Prediction

This project involves analyzing a retail transaction dataset and building a predictive model to forecast the `TotalAmount` of a transaction based on features like `Quantity`, `Price`, and `DiscountApplied(%)`. The project includes handling missing data, exploratory data analysis (EDA), and building a machine learning model using RandomForestRegressor.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset Information](#dataset-information)
- [Data Processing and Cleaning](#data-processing-and-cleaning)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Visualizations](#visualizations)
- [Installation](#installation)
- [License](#license)

## Project Overview
In this project, we focus on the retail transaction dataset, where our goal is to predict the `TotalAmount` of a transaction based on available features. The dataset has some missing values, and the project explores how to handle missing data, perform basic statistical analysis, and train a predictive model.

## Dataset Information
The dataset used in this project is the "Retail Transaction Dataset", which contains information about various retail transactions. Some of the key columns in the dataset include:
- `Quantity`: Number of items bought in the transaction
- `Price`: Price per item
- `DiscountApplied(%)`: Discount applied on the item price
- `TotalAmount`: Total amount of the transaction
- `PaymentMethod`: Method used for payment (e.g., Credit, Debit, etc.)
- `ProductCategory`: Category of the product sold
- `CustomerID`: Unique identifier for the customer

You can find the dataset file at the following path: `/kaggle/input/retail-transaction-dataset/Retail_Transaction_Dataset.csv`.

## Data Processing and Cleaning
1. **Handling Missing Data**:
   - A function was implemented to artificially introduce missing values for testing purposes.
   - The missing values were then imputed using:
     - Median value for numerical columns.
     - Most frequent value for categorical columns.

2. **Feature Selection**:
   - The dataset was split into numerical and categorical columns.
   - Features like `Quantity`, `Price`, and `DiscountApplied(%)` were used to predict the target variable `TotalAmount`.

## Exploratory Data Analysis (EDA)
Exploratory Data Analysis was performed to understand the structure of the dataset and gain insights into key trends:
- **Missing Value Visualization**: A heatmap was generated to show missing data distribution.
- **Statistical Analysis**: Basic descriptive statistics were calculated to summarize the dataset.
- **Distribution of Numerical Variables**: A boxplot and histogram were used to visualize the distribution of key numerical features.
- **Total Sales by Product Category**: A bar plot was used to display the total sales for each product category.
- **Correlation Analysis**: A heatmap was created to show the correlations between numerical variables.

## Visualizations
Several visualizations were created to understand the dataset better and visualize the analysis results:
- **Missing Value Heatmap**: Shows the locations of missing values in the dataset.
- **Boxplot**: Displays the distribution of numerical variables.
- **Countplot**: Shows the distribution of payment methods.
- **Correlation Heatmap**: Visualizes the correlation among numerical features.
- **Distribution of TotalAmount**: A histogram to show the frequency distribution of the total transaction amount.
- **Total Sales by Product Category**: A bar plot to visualize total sales for each product category.

## Installation
To run this project locally, you will need the following Python libraries:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn



### Notes:
- **Project Overview**: This section summarizes the purpose of the project.
- **Dataset Information**: Describes the dataset and its key columns.
- **Data Processing and Cleaning**: Details the steps taken to handle missing data and prepare the dataset for analysis.
- **Exploratory Data Analysis (EDA)**: Explains the visualizations and statistical analysis performed
- **Visualizations**: Lists all the important visualizations created during the analysis.
- **Installation**: Includes instructions on how to install the necessary dependencies.
- **License**: Specifies that the project is open source under the MIT license.

## Kaggle Notebook 
https://www.kaggle.com/code/cisemh/retail-transaction-data-analysis
