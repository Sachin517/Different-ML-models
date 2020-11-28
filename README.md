# Different-ML-models (Decision tree, Random Forest, PCA, Regularisation technique)

Telcomm company wants to know all those customers who will churn for the Prepaid phones
- Basic data check and doing th outlier and the null values checking(replacing with median and the mode values) 
- Filtering the high value customers (i.e customers who recharged more than 70% in the last 2 months)
- Analyzed the data with different plots predicting with churn and other variables(i.e variables affecting the churn)
- After that performed Models 
	1. Logistic Regression for interpretability
	2. PCA with different models like Logistic regression, Decision Tree, Random Forest
	3. The following will also be performed with Hyper parameter tuning and class imbalancing 
- Class Imbalancing was done using SMOTE(Synthetic Minority Over Sampling Technique)
- In all the models Random Forest was the one who was giving the higher recall values since we are worried more about at the risk of customers who are most likely to churn
- Finally predicting the varibles affecting the churn values 
