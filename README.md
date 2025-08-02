# esg-risk-analysis
Analyzing ESG risk and governance trends using data science tools

A complete data science pipeline to analyze and predict **Total ESG Risk Scores** of S&P 500 companies using ethical ML practices and advanced feature engineering.

**🧭 Goals:**  
- Predict ESG risk without circular inputs (i.e., avoid direct env/soc/gov score use).  
- Discover high-risk sectors and ESG patterns through explainable models.

**🛠️ Techniques Used:**  
- Data Cleaning & Storage: Handled missing values, type conversions, and stored in MySQL.  
- SQL + EDA: Used queries and visualizations to uncover sector-wise and controversy-related risk trends.  
- Feature Engineering: Created risk ratios, outlier flags, and custom ESG metrics (e.g., `governance_deficit_ratio`).  
- Dimensionality Reduction: Applied **PCA** to remove multicollinearity.  
- Association Rule Mining: Extracted rules like `controversy_high ⇒ soc_high` via **Apriori**.  
- Regression Modeling: Trained **XGBoost** (R² = 0.87, MAE = 1.80) using non-circular features.

**📌 Outcome:**  
A transparent, ethical, and domain-driven ML model for ESG risk prediction and interpretation.
