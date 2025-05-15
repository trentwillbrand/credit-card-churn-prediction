# Credit Card Customer Churn Prediction

This project simulates a real-world data science engagement for a **credit card provider** aiming to reduce customer attrition. It demonstrates how I would approach a business-critical classification problem from start to finish using customer behavior and demographic data.

While this README provides a project summary, all detailed outputs, interpretations, and personal insights are documented throughout the Jupyter notebooks. I highly recommend going through each notebook to fully understand the project and overall process. They include:

- In-depth exploratory data analysis and visualizations
- Step-by-step preprocessing and modeling decisions
- Interpretations of model performance and feature importance
- Expanded findings and business-focused recommendations

Each notebook is clearly labeled and structured to reflect a real-world data science workflow.

## Business Objective
To develop a machine learning model that predicts whether a customer will churn (attrite) so that the company can take proactive steps to retain high-risk customers.

## What This Project Demonstrates
- Real-world data cleaning, transformation, and preparation
- Exploratory data analysis to uncover patterns in churn
- Application of machine learning techniques to solve a classification problem
- Communication of insights and strategic recommendations
- Documentation and portfolio-ready presentation

## Dataset Summary
- **Source**: [Kaggle - Credit Card Customers](https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers)
- **Size**: 10,127 records × 23 columns
- **Target**: `Attrition_Flag` (binary: Attrited vs. Existing Customer)
- **Features**: Demographics, credit behavior, transaction patterns

## Tools & Technologies Used
- Python: pandas, numpy, matplotlib, seaborn
- Scikit-learn (machine learning)
- Jupyter Notebooks (exploration, modeling, and presentation)

## Folder Structure
```
credit-card-churn-prediction/
│
├── data/                         # Raw and processed datasets
│   ├── raw_data.csv
│   ├── X_train_clean.csv
│   ├── X_test_clean.csv
│   ├── y_train_clean.csv
│   └── y_test_clean.csv
│
├── notebooks/                    # Jupyter notebooks by stage
│   ├── 01_data_overview_eda.ipynb
│   ├── 02_data_cleaning_preprocessing.ipynb
│   ├── 03_modeling_evaluation.ipynb
│   └── 04_insights_recommendations.ipynb
│
├── README.md                     # Project summary and documentation
└── requirements.txt              # Environment setup (optional)
```

## Project Breakdown
- `01_data_overview_eda.ipynb`: Understand dataset and explore churn patterns
- `02_data_cleaning_preprocessing.ipynb`: Prepare features, encode variables, and split datasets
- `03_modeling_evaluation.ipynb`: Build and evaluate ML models
- `04_insights_recommendations.ipynb`: Interpret results, recommend actions

## Key Findings
- **Transaction Behavior (Amount & Count)** were the strongest predictors of churn.
- **Revolving Balance & Utilization Ratio** highlighted financial stress patterns, which correlated with higher churn.
- **Inactivity & Behavior Change** (e.g., declining usage over time) were clear red flags for disengagement.

## Strategic Recommendations
- **Re-engage low-activity users**: Identify customers with declining transaction volume and target them with incentives like bonus points or special offers.
- **Support financially strained customers**: Monitor those with high utilization and revolving balances; offer flexible payment options or credit reviews.
- **Increase relationship depth**: Encourage adoption of additional products (e.g., savings, loans) to build loyalty and reduce churn risk.

---

## About The Author

Thanks for checking out this project! Feel free to reach out with questions, feedback, or just to connect in general.

- trentonwillbrand@gmail.com
- https://github.com/trentwillbrand
- https://www.linkedin.com/in/trentwillbrand/

---
