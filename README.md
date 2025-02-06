# Credit Risk Modeling

## Predictive Modeling of Credit Line Defaults

Using Python to explore and analyze a dataset on borrower data and loan default status. Notebook includes: 
- Visualizing underlying relationships between various features
  * Histograms
  * Barplots
  * Boxplots
  * Univariate Logistic Regression curve
- Preprocessing data for machine learning application
  * Implementing train-test split
  * Imputing missing data
  * Encoding categorical features
  * Scaling numerical features
- Fitting machine learning models to predict loan defaults
  * Multivariate Logistic Regression
  * Random Forest
  * XGBoost 
- Visualizing feature importance to determine which features are most influential in predicting defaults, according to each model

### Future directions: 

I would love to get my hands on another related dataset, but with the added information of 

1. What was the initially-agreed lifetime of the loan (months)?
2. If the loan defaulted, how many months into the lifetime was it?
3. What was the outstanding principle value of the loan?

These data would be helpful to understand how much revenue was accrued or lost by the lender as a function of the default. Loans that default at different times pose varying degrees of loss to the lender, and in addition to predicting the binary default response we can also model how much the lender stands to profit or lose as a function of when a loan may default. Enhancing our modeling in this manner could provide added value to the lender.
