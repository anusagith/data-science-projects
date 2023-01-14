
**PROBLEM STATEMENT**

In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.

**BUSINESS GOAL**

Predict what all factors affect customers being at high risk of churn.

**ANALYSIS APPROACH**

1. Reading and understanding data
2. Handling missing values for categorical and continous features
3. dropping unwanted features
4. EDA
5. Data preperation: deriving atleast two features, filtering high value customers based on 70th percentile of avg recharge amnt
6. deleting 9th month features (churn phase)
7. deriving churn

**8. Data model 1: Logistic regression without PCA (handling data imbalance on train data using SMOTE)**

**9. Data model 2: Logistic regression with PCA (using balanced data)**

**10. Data model 3: Decision trees with PCA (using balanced data)**

**11. Data model 4: Random Forest with PCA (using balanced data)**

12. Recommendation Of features that needs to be considered
