# Retail Sales Prediction Using Machine Learning Models 🛒📊

## Overview

This project analyzes retail transaction data and applies Machine Learning techniques to predict sales behavior.

The main objective was to build regression models capable of predicting the total sales amount based on customer, product and transaction information. Additional classification analysis was also performed to explore sales category prediction.

The project includes data exploration, preprocessing, model development, optimization, feature engineering and business insights.


---

## Dataset

The dataset contains retail sales transactions including:

- Customer demographic information
- Product categories
- Quantity purchased
- Product prices
- Transaction dates
- Total sales amount

The target variable for the regression analysis was:

**Total Amount**


---

## Project Workflow

### 1. Exploratory Data Analysis (EDA)

- Dataset structure analysis
- Missing values verification
- Duplicate detection
- Descriptive statistics
- Numerical and categorical variable analysis
- Correlation analysis
- Outlier detection using IQR


### 2. Data Preprocessing

- Date feature extraction
- Categorical variable encoding
- Feature selection
- Train/Test split preparation


### 3. Machine Learning Models

Regression models developed:

- Decision Tree Regressor
- Random Forest Regressor

Models were evaluated using:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R2 Score


---

## Modeling Strategy

### Baseline Model

The first models achieved perfect prediction results.

Further analysis using correlation and feature importance showed a strong dependency between price-related variables and the target variable.

### Adjusted Model

A second approach removed the strongest predictor to evaluate model dependency and generalization.

GridSearchCV was applied for hyperparameter optimization.

### Feature Engineering Model

Price information was transformed into categorical features to preserve useful information while reducing direct dependency.

This approach provided the best balance between predictive performance and feature representation.


---

## Additional Classification Analysis

A classification approach was developed to predict sales categories.

Evaluation included:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC-AUC Curve


---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn


---

## Key Insights

- Price and quantity were the strongest factors influencing sales value.
- Feature importance analysis helped explain model behavior.
- Hyperparameter optimization improved model generalization.
- Feature engineering provided a better approach than removing important information completely.


---

## Business Recommendations

- Use pricing and quantity patterns to support sales strategies.
- Include additional customer behavior information for future improvements.
- Apply predictive models as support tools for inventory and business planning.


---

## Author

**Makarena Ampuero**

Environmental professional expanding into Data Science, Machine Learning and applied analytics.