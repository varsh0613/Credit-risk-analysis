# Credit-risk-analysis
Objective:
To build a machine learning model capable of predicting the likelihood of a borrower defaulting on a loan, enabling financial institutions to assess creditworthiness and minimize risk exposure.

Key Features:

1. Data Preprocessing:
  - Cleaned and standardized customer data, addressing missing values and encoding categorical variables such as gender, marital status, and occupation.
  - Performed outlier detection and normalization to ensure consistent feature scaling.
2. Exploratory Data Analysis (EDA):
  - Analyzed demographic and financial attributes including income, loan amount, credit history, and employment stability.
  - Visualized correlations between income, credit history, and default probability to uncover risk patterns.
3. Feature Engineering:
  - Created new metrics such as Debt-to-Income Ratio and Credit Utilization Score to strengthen model prediction.
  - Applied correlation and variance thresholding to remove redundant features.
4. Model Development:
  - Trained and compared multiple models — Logistic Regression, Random Forest, and XGBoost — to identify the most accurate predictor of default risk.
  - Evaluated performance using accuracy, precision, recall, F1-score, and ROC-AUC metrics.
  - Selected Random Forest as the final model for its balance between accuracy and interpretability.
5. Visualization and Insights:
  - Developed interactive dashboards in Power BI to display:
  - Loan approval vs. default rates
  - Customer risk segmentation (low, medium, high)
  - Correlations between demographic features and loan outcomes
  - Helped visualize key decision-driving factors for credit approval.

Outcome:
- Achieved a model accuracy of approximately 85–90% on the test set.
- Identified credit history, income stability, and loan amount as top predictors of default risk.
- The final dashboard provides a comprehensive, data-driven view for financial analysts to make informed lending decisions.

Technology Stack:
- Python (pandas, NumPy, scikit-learn, Matplotlib, Seaborn)
- Power BI for visualization
- GitHub for version control and documentation
