# Big Mart Sales Prediction and Visualization

This project focuses on predicting sales for Big Mart outlets using historical sales data. By analyzing various features of products and stores, the goal is to build a predictive model that can forecast future sales, aiding Big Mart in strategic decision-making.

## Project Overview

The repository contains:

- **Dataset**: `Train.csv` - The training dataset comprising historical sales data with features such as item identifiers, item weights, item fat content, item visibility, item type, item MRP, outlet identifiers, outlet establishment year, outlet size, outlet location type, outlet type, and item outlet sales.
  
- **Notebook**: `Big_Mart_Sales_Predication.ipynb` - A Jupyter Notebook that includes data preprocessing, exploratory data analysis (EDA), feature engineering, model building, and evaluation.

## Dataset

The dataset used in this project includes the following columns:

- `Item_Identifier`: Unique product ID
- `Item_Weight`: Weight of the product
- `Item_Fat_Content`: Whether the product is low fat or regular
- `Item_Visibility`: The percentage of total display area allocated to this product in the store
- `Item_Type`: The category to which the product belongs
- `Item_MRP`: Maximum Retail Price (list price) of the product
- `Outlet_Identifier`: Unique store ID
- `Outlet_Establishment_Year`: The year in which the store was established
- `Outlet_Size`: The size of the store (small, medium, high)
- `Outlet_Location_Type`: The type of city in which the store is located
- `Outlet_Type`: Whether the outlet is a grocery store or some sort of supermarket
- `Item_Outlet_Sales`: Sales of the product in the particular store (target variable)

## Methodology

1. **Data Preprocessing**: Handling missing values, encoding categorical variables, and scaling numerical features.
2. **Exploratory Data Analysis (EDA)**: Visualizing data distributions, relationships between features, and identifying patterns.
3. **Feature Engineering**: Creating new features and transforming existing ones to improve model performance.
4. **Model Building**: Implementing regression models to predict sales.
5. **Model Evaluation**: Assessing model performance using appropriate metrics.

## How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/Khushi-tw/Sales-Prediction.git
