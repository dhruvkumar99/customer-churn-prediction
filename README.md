# Customer Churn Prediction

## Problem Statement
Predict whether a telecom customer will churn (leave the company) based on their usage patterns and account information.

## Dataset
- **Source**: Kaggle - Telco Customer Churn
- **Rows**: 7,043 customers
- **Features**: 20 predictor variables
- **Target**: Churn (Yes/No)

## Tech Stack
- Python 3
- Pandas, NumPy (Data manipulation)
- Matplotlib, Seaborn (Visualization)
- Scikit-learn (Machine Learning)

## Results

### Model Performance
| Model | Accuracy | F1 Score |
|-------|----------|----------|
| Logistic Regression | ~80% | ~0.62 |
| Random Forest | ~79% | ~0.58 |

### Top 5 Most Important Features
1. TotalCharges (19.0%)
2. MonthlyCharges (17.8%)
3. Tenure (15.7%)
4. Contract Type (7.7%)
5. Payment Method (5.0%)

## Key Insights
- Customers with month-to-month contracts are more likely to churn
- Higher monthly charges correlate with higher churn rates
- Longer tenure customers are more loyal

## How to Run
1. Download the dataset from Kaggle
2. Open the notebook in Google Colab
3. Upload the CSV file when prompted
4. Run all cells sequentially

## Author
Data Science Project
