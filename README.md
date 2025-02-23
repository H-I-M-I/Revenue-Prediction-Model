# Advertising Sales Prediction

This project demonstrates a simple linear regression model to predict sales based on advertising spending. The dataset used is `Advertising.csv`, which contains data on advertising expenditures across different media channels and their impact on sales.

## Dataset
- **Advertising.csv**: Contains columns representing different advertising channels and their corresponding sales.
  - `TV`: Advertising budget for TV (in thousands of dollars)
  - `Radio`: Advertising budget for radio (in thousands of dollars)
  - `Newspaper`: Advertising budget for newspapers (in thousands of dollars)
  - `Sales`: Resulting sales (in thousands of units)

## Key Features
- Data loading and preprocessing
- Exploratory data analysis (EDA)
- Training a simple linear regression model using `sklearn`
- Visualizing regression results

## How Prediction Works?
- The model finds a mathematical equation to describe the relationship between ad spending and sales.
- The equation looks like this for **Simple Linear Regression** (if using just TV ads for simplicity):  
  ```
  Sales = m * TV Budget + b
  ```
  where `m` is the slope (how much sales increase per unit of TV budget), and `b` is the intercept.
- Once trained, if you input a new **TV advertising budget**, the model will output a predicted **sales value**.

## Results
The model predicts sales based on advertising budgets, showcasing the relationship between marketing expenditures and sales performance.
