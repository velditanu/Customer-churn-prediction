# Customer-churn-prediction
# Customer Churn Prediction for Telecom

## Project Overview
This project aims to build a predictive model for customer churn, helping telecom companies identify at-risk customers and improve retention. We used the Telco Customer Churn dataset, with models including Logistic Regression and Random Forest.

## Objectives
- Predict customer churn using historical customer and service data.
- Identify key features that impact churn.
- Provide actionable insights to reduce customer attrition.

## Data and Methods
- **Dataset**: Telco Customer Churn, with features like customer demographics, service usage, and billing details.
- **Preprocessing**: Handled missing values, encoded categorical variables, and removed leakage-prone features.
- **Models**: Logistic Regression and Random Forest were used to build and evaluate the churn prediction model.

## Key Insights
- High monthly charges and shorter tenure significantly contribute to churn.
- Contract type and service add-ons also play crucial roles in customer retention.

## Results
Both models achieved high AUC scores, with Logistic Regression showing slightly better performance. However, Random Forest provided valuable feature importance insights.

## Visualizations
1. **Feature Importance by Random Forest**
2. **ROC Curves for Model Comparison**

## Recommendations
- Offer incentives for high-risk segments (e.g., customers with high monthly charges or shorter tenure).
- Focus on retaining customers in flexible contracts by offering contract incentives.

## How to Use
To explore the project:
1. Clone this repository.
2. Run the Jupyter notebooks in the `notebooks/` folder to view code and results.

## Conclusion
This project demonstrates the potential for predictive modeling in reducing churn. The analysis highlights key features and provides actionable insights for customer retention.

