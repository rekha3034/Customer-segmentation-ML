**CUSTOMER SEGMENTATION – CREDIT DATA**

Customer segmentation is the process of dividing a customer base into groups of individuals that are similar in certain ways relevant to marketing, such as age, gender, interests, and spending habits. Customer segmentation is a powerful marketing tool that helps you understand customers better and target them accordingly. It can help improve sales, increase customer retention and reduce costs associated with customer acquisition.

**Machine Learning for Customer Segmentation:**

The advantage of using machine learning for customer segmentation is its ability to process vast amounts of data in real time. This allows companies to quickly identify new trends and patterns in customer behaviour, allowing them to make more informed marketing decisions. Using machine learning for customer segmentation eliminates the need for manual data analysis, can be a time-consuming and error-prone process, particularly when working with large datasets.

**Data Source:**
https://www.kaggle.com/datasets/arjunbhasin2013/ccdata

Dataset summarizes the usage behaviour of about 9000 active credit card holders during the last 6 months. The file is at a customer level with 18 behavioural variables.

“We are required to develop a customer segmentation to define marketing strategy.”

**Feature descriptions for Credit Card dataset:**

CUST_ID: Identification of Credit Card holder (Categorical).

BALANCE: Balance amount left in their account to make purchases.
 
BALANCE_FREQUENCY: How frequently the Balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated).

PURCHASES: Amount of purchases made from account.

ONEOFF_PURCHASES: Maximum purchase amount done in one-go.

INSTALLMENTS_PURCHASES: Amount of purchase done in instalments.

CASH_ADVANCE: Cash in advance given by the user.

PURCHASES_FREQUENCY: How frequently the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased).

ONEOFF_PURCHASES_FREQUENCY: How frequently Purchases are happening in one-go (1 = frequently purchased, 0 = not frequently purchased).

PURCHASES_INSTALLMENTS_FREQUENCY: How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done).

CASH_ADVANCE_FREQUENCY: How frequently the cash in advance being paid.

CASH_ADVANCE_TRX: Number of Transactions made with "Cash in Advanced".

PURCHASES_TRX: Number of purchase transactions made.

CREDIT_LIMIT: Limit of Credit Card for user.

PAYMENTS: Amount of Payment done by user.

MINIMUM_PAYMENTS: Minimum amount of payments made by user.

PRC_FULL_PAYMENT: Percent of full payment paid by user.

TENURE: Tenure of credit card service for user.

Exploratory Data Analysis is done to uncover the underlying structure/trends/pattern of the dataset. It helps in understanding the distribution of variables and the relationship between the various features.

**Machine Learning for Segmentation/Classification:**

For this classification a machine algorithm named as k-means clustering algorithm is used and based on the behavioural characteristics, customers are classified. Formed clusters help the company to target individual customer and advertise the content to them through marketing campaign and social media sites which they are really interested in.

**K-means Clustering Algorithm **

 K-means Clustering is a clustering Algorithm in which we are given with data points 
with its data set and features and the mechanism is to categories those data points into 
clusters as per their similarities. 
The algorithm forms K clusters based on its similarity. To calculate the similarity K-
means uses Euclidean distance measurement method. 
Steps 
 
i. In first step, we randomly initialize k points. 
ii. K-means classifier categorizes each data point to its nearest mean and rewrite 
the mean’s coordinates. 
iii. Iteration is continuing up till all data points are classified. 

**Conclusions:**

Customer segmentation is performed on the company's customers data and with the help of K-means clustering machine learning algorithm, customers are divided using various features. This study also proves that the dividing customers on the  basis  of  behavioural  characteristics  is  a  better  solution  for  existing customer  segmentation  problem  and  K-means  clustering algorithm  is  identified  as  a good choice for this approach.
