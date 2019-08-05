# Credit-Card-Fraud-Detection
### Abstract
The goal for this analysis is to predict credit card fraud in the transactional data by applying Machine Learning Models. I will be using tensorflow to build the predictive model, and t-SNE (t-Distributed Stochastic Neighbor Embedding for dimension reduction) to visualize the dataset in two dimensions at the end of this analysis.

### Dataset
The dataset for this project is available at Kaggle.com 
https://www.kaggle.com/mlg-ulb/creditcardfraud
The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.
It contains only numerical input variables which are the result of a PCA transformation. The only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

### Tasks
#### Exploratory Data Analysis
#### Data Preprocessing
    * Feature Elimination
    * Data Normalization
    * Balancing the Skewed Dataset using
    1) Undersampling Techniques
    2) Oversampling using SMOTE Technique
    
#### Machine Learning Models
1) Auto Encoder Artificial Neural Networks
2) Random Forest
3) Logistic Regression

#### Performance Evaluation
1) Cross validation
2) Confusion Matrix
3) Precision Recall's Curve
4) Cohens's Kappa Statistics
5) AUC - ROC Curves
    
