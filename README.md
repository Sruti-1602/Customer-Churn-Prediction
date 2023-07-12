# Customer-Churn-Prediction
### Churn rate is a critical metric of customer satisfaction. Low churn rates mean happy customers, and high churn rates mean customers are leaving you. 
According to Forbes, it takes a lot more money (up to five times more) to get new customers than to keep the ones you already have. Churn tells you how many existing customers are leaving your business, so lowering churn has a big positive impact on your revenue streams.
#### Reasons for Customer Churn Prediction:

* Identifying at-risk customers,
* Identifying customer pain points,
* Identifying strategy/methods to lower churn and increase customer retention.

#### About our dataset
*  The sample data tracks a fictional telecommunications company, Telco. It’s customer churn data sourced by the IBM Developer Platform.
*  It includes a target label indicating whether or not the customer left within the last month, and other dependent features that cover demographics, services that each customer has signed up for, and customer account information.
*  It has data for 7043 clients, with 20 features.
 
#### Correlation Matrix 
   After performing EDA on the dataset and extracting valuable quantitative data from the dataset, we made a correlation matrix to find out the 2 folowing things: 
   * Which features make customers churn or retain?
   * What are the most important features to train a model with high performance?

We created a baseline model with a **Logistic Regression** algorithm, then predict with other machine learning models like **Support Vector Classifier (SVC)**, **Random Forest Classifier**, **Decision-tree classifier**, and **Naive-Bayes Classifier**.
