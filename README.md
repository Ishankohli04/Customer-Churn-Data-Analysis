# Customer Churn Analysis

(https://github.com/Ishankohli04/Customer-Churn-Data-Analysis/blob/main/Customer%20churn%20analysis.png)





## Overview

This project analyzes customer churn using a dataset that includes various customer attributes such as tenure, contract type, and service usage. The goal is to identify patterns and factors contributing to customer churn and provide actionable insights for retention strategies.

## Dataset

The dataset includes:

- Customer demographic information
- Subscription details (contract type, services used, tenure, etc.)
- Churn status (whether the customer has left or stayed)

## Key Findings

- **Tenure & Churn**: Customers with shorter tenure (1-2 months) have a **75% churn rate**, whereas customers with tenure exceeding 24 months have a **15% churn rate**.
- **Contract Type**: Customers with month-to-month contracts have a churn rate of **60%**, while those with annual or bi-annual contracts have a churn rate of **20%**.
- **Service Impact**: Churn is influenced by the presence or absence of specific services:
  - **OnlineSecurity & TechSupport**: Customers without these services have a **55% churn rate** compared to **20% for those with them**.
  - **StreamingTV & StreamingMovies**: Customers with these services have a churn rate of **40%**, indicating possible dissatisfaction with entertainment options.
- **Senior Citizen Influence**: A higher percentage of senior citizens churn, with a churn rate of **45%**, compared to **25% for non-senior customers**.

## Data Processing

- Missing tenure values were replaced with 0.
- `SeniorCitizen` values were converted to Yes/No for better readability.
- Various data visualizations were created to analyze trends and correlations.
- Data was cleaned and transformed for better analysis.

## Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

## How to Use

1. Clone the repository:
   ```sh
   git clone <repo_url>
   ```
2. Install required dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```sh
   jupyter notebook Customer_churn_analysis.ipynb
   ```

## Future Improvements

- Implement machine learning models for churn prediction.
- Enhance feature engineering for better insights.
- Develop an interactive dashboard for visualization.
- Conduct customer segmentation to tailor retention strategies.

## Author

Ishan Kohli

## License

This project is licensed under the MIT License
