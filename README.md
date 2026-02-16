# demand-forecasting-linear-regression
# Demand Forecasting Using Linear Regression

## Project Overview

This project develops a demand forecasting model to predict product sales using pricing, promotional, and seasonal features. The objective is to support data-driven inventory planning and revenue optimization.

Accurate demand prediction enables businesses to:
- Reduce stockouts
- Lower inventory holding costs
- Improve pricing strategy
- Enhance revenue forecasting accuracy

---

## Dataset

Retail sales dataset sourced from Kaggle, containing historical sales transactions across multiple stores and products.

---

## Methodology

### 1. Exploratory Data Analysis (EDA)
- Distribution analysis of sales
- Correlation analysis
- Missing value handling
- Outlier detection

### 2. Feature Engineering
- Seasonal features (month, day of week)
- Promotional indicators
- Temporal features
- Scaling for optimization

### 3. Modeling

Implemented and compared:

- Simple Linear Regression
- Multiple Linear Regression
- Gradient Descent (implemented from scratch)

---

## Model Evaluation

Performance metrics:
- R² Score
- RMSE (Root Mean Squared Error)

Findings:
- Multiple Linear Regression significantly improved predictive accuracy over simple regression.
- Feature engineering enhanced model performance.
- Gradient descent converged efficiently with proper learning rate selection.

---

## Key Insights

- Price negatively impacts demand.
- Promotional periods significantly increase sales.
- Seasonality plays a critical role in forecasting accuracy.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn

---

## Future Improvements

- Regularization (Ridge / Lasso)
- Cross-validation
- Tree-based models
- Model deployment

---

## Author

Krina Patel  
Data Analyst | Aspiring Data Scientist
