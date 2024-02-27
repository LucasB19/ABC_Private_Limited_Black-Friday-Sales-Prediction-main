# Machine Learning Model Optimization Project for ABC Private Limited

### Overview

This project aims at predicting customer purchase behavior for "ABC Private Limited." It leverages a dataset that includes purchase summaries of selected high-volume products, along with customer demographics, product details, and total purchase amounts from the last month. The primary objective is to develop a predictive model that can forecast the purchase amounts of customers for various products, thereby aiding the company in refining its marketing strategies.

### Tasks Performed

#### Data Preprocessing
1. Checked basic statistics and the presence of missing values in the dataset.
2. Examined unique values across different columns.
3. Managed missing values, renamed columns for clarity, and filled NaN values appropriately.
4. Mapped categorical data to integers and range variables to corresponding integer values (e.g., 'Age' column).

#### Exploratory Data Analysis (EDA)
1. Conducted univariate and bivariate analyses with respect to the Purchase column.
2. Analyzed the distribution of purchase amounts and identified outliers.
3. Investigated purchase behaviors across various demographics such as gender, marital status, occupation, city category, and age group.
4. Dropped unnecessary fields for model efficiency.

#### Data Visualization
1. Visualized distributions and relationships within individual columns and between variables and purchase amounts.
2. Created visualizations including Age vs. Purchase, Occupation vs. Purchase, Product Categories vs. Purchase, and a pie chart for City Category.

#### Machine Learning Modeling
1. Split the dataset into training and testing sets.
2. Implemented and evaluated several regression models: Linear Regression, Decision Tree Regressor, Random Forest Regressor, and XGBoost Regressor.
3. Utilized metrics such as MAE, MSE, RMSE, and R-squared for model performance evaluation.
Setup Instructions

To set up and run this project:

Clone the Repository
```bash
git clone <repository-url>
cd <repository-directory>
```
Install Dependencies
```bash
pip install -r requirements.txt
```
Run the Project
Modify the dataset path and target variable in the scripts as necessary, then execute:

### Dependencies

pandas
numpy
scikit-learn
xgboost
matplotlib (optional for visualization)

### Conclusion

This project encapsulates a comprehensive approach to understanding and predicting customer purchase behaviors, employing a variety of data preprocessing techniques, exploratory data analysis, visualization strategies, and machine learning models to achieve its objectives.

### License

This project is licensed under the MIT License 
