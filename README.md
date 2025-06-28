# Bank Customer Churn Prediction
Predicting customer churn in the banking sector using Logistic Regression implemented from scratch with comprehensive hyperparameter optimization.

## Project Overview
This project analyzes bank customer data to predict churn likelihood using a **Logistic Regression algorithm implemented from scratch**. The binary classification determines whether a customer will leave the bank based on their demographics, account information, and banking behavior.

## Features
- **Custom Logistic Regression Implementation**: Built from scratch using NumPy
- **Hyperparameter Tuning**: Systematic optimization of learning rate and classification threshold
- **Business Impact Analysis**: Financial cost-benefit analysis with realistic business metrics
- **Data Preprocessing**: One-hot encoding and feature standardization
- **Performance Visualization**: Training cost monitoring and metric comparisons

## Dataset
**Source**: [Kaggle - Bank Customer Churn Dataset](https://www.kaggle.com/datasets/gauravtopre/bank-customer-churn-dataset)

The dataset contains bank customer information including:
- **Features**: Credit score, geography, gender, age, tenure, balance, products, credit card, active member status, estimated salary
- **Target**: Binary classification (1 = churned, 0 = retained)
- **Size**: 10,000 customers with 11 features
- **Class Distribution**: ~20% churn rate (imbalanced dataset)

**Download**: Place the CSV file as `bank-churners.csv` in the project directory

## Key Results
- **72% recall** in identifying churning customers (vs 9% baseline)
- **€836,550 business value** generated through ML optimization
- **28% miss rate** (down from 100% without ML intervention)
- Achieved optimal performance with learning rate 0.1 and optimized threshold

## Technologies Used
- **Python 3.12**
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computations and algorithm implementation
- **Matplotlib**: Data visualization and performance plotting
- **Scikit-learn**: Data preprocessing only (StandardScaler, train_test_split)

## Usage
1. Download the dataset: https://www.kaggle.com/datasets/gauravtopre/bank-customer-churn-dataset
2. Place the `bank-churners.csv` file in the project directory
3. Install required packages: `pip install -r requirements.txt`
4. Run the Jupyter notebook: `jupyter notebook bank_churner.ipynb`

## Project Structure
```
├── bank_churner.ipynb              # Main analysis notebook
├── README.md                       # Project documentation
├── requirements.txt                # Python dependencies
└── bankchurners.csv                # Dataset (not included in repo)
```

## Business Impact
The optimized model delivers significant business value:
- Reduces churn losses by 82% compared to no intervention
- Enables proactive retention campaigns for 72% of at-risk customers
- Provides clear financial justification for ML investment

## Author
Marlon Krüger - Medieninformatik Student at Berliner Hochschule für Technik
