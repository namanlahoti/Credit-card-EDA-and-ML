# Credit-card-EDA-and-ML

**Introduction**

The credit_card_df data frame contains client information from a large U.S. bank which has the data of over 4000 customers having certain financial information and personal information like age, marital status, employment status, card type etc., The bank is looking to see if it can determine the factors that lead to customers canceling their credit card account and whether it can predict if a customer will cancel their account in the future.

**Problem Statement**

Large amount of customers leaving the credit card services of a bank is a major problem for the bank as it ruptures the credit line service and the profits of a reputed bank. Retention of customers is a major task that is to be carried out by banks and this is possible by observing the past data of the bank and the financial behavior of the customer based on the age and other crucial characteristics like dependents, income and the number of transactions made by the customer in the past.

To solve this problem, there is a need to analyze the root cause of why the customers are leaving the bank or being inactive for a larger period. Initially, we'd like to look at the company's financial losses using factor variables like education, marital status, employment status, and the card type they're using in relation to numeric variables like transactions made last year, total money spent last year, utilization ratio, and total accounts a customer has, as well as their impact on customer status.

This project is carried out in a sequence of steps, the first of which consists of an exploratory analysis, where the objective is to know the behavior of the variables and to analyze attributes that indicate a strong relationship with the cancellation of credit card service customers. Then the last step consists of applying a machine learning algorithm to find the best resources for building the model. 

**Key Findings**

The major discovery from the exploratory data analysis reveals several intriguing indicators that aid in determining the credit card status of clients. According to the research, there are a few aspects that have been identified as influential determinants in the customer's card status.

It can be found that there is no such huge difference between the expenditure of married and divorced customers, where the average expense of married customers is 3797.010 and divorced customers are 3678.593 respectively. We can say that single customers have spent more when compared to the other two categories.  Most of the customers having active accounts are married, however single customers also do have a large part between the customer's marital status. We can say that there are more chances that customers who are single are more likely to maintain their account active when compared to the other set of customers.
It has also been observed that there are more customers who have completed their master’s degree followed by Associates, Bachelor's and then doctorate customers. The insights define that a greater number of customers who hold a master’s degree have an active account followed by customers with associates degree. But interestingly, it is also seen that a greater number of customers (126 customers) with doctorate degree have closed account meaning they are inactive. In conclusion, reason should be found out that why there are a greater number of inactive accounts with customers holding a doctorate/PhD degree.

From the data, it has been observed that divorced customers having a full-time job have the highest average credit amount among all the other customers. And customers who are divorced and do some part-time jobs are the ones with the lowest average credit amount. It was analyzed from the plots that customers who are single and married do not use their credit line more when compared to the divorced customers.

The data also defines that the average total months inactive for each customer in the last 12 months of both types of customers is fluctuating (because it’s a discrete data) with some outliers in the inactive/closed customers distribution. It is noticed that customers who have a closed account have been more inactive when compared to the customers with an active account.

It is depicted that married customers (97 customers) having an active account have made more than 100 transactions in the last 12 months. While on the other hand, only 14 customers having marital status as divorced and have an active account have made more than 100 transactions in the last 12 months.

-------------------------------------------------------------------------------
Model    | Logistic Regression |       KNN      | QDA |
-------------------------------------------------------------------------------
Accuracy |     0.8711303    	 |   0.8538517    |   0.8833693  |
------------------------------------------------------------------------------
roc_auc  |     0.9437214       |   0.9307649 	|   0.9537380  |
-----------------------------------------------------------------------------
F1 score |     0.8430421      |   0.8364222 	|   0.8699839   |
-----------------------------------------------------------------------------


When comparing the performance of the above models, the Quadratic Discriminant Analysis (QDA) model appears to be the best, with the highest accuracy, the area under the ROC curve, and the F1 score.

The simplest intuitive performance metric is accuracy, which is just the ratio of properly predicted observations to all observations. This suggests that the analysis we conducted by forecasting the elements that influence consumers' decision to cancel their cards is 88% accurate with respect to other aspects, i.e., the factors that influence customer status. We can see how vital it is for the organization to keep track of, analyze, and improve these elements.

**Recommendations **

Self-employed consumers are problematic because they are more likely to cancel their credit card services. Since the number of cancellations were more in the blue card holders, schemes or discounts or low/no APR blue cards should be provided to retain such customers. It is also necessary to analyze such customers and understand the cause of blue card holders’ cancellation of accounts.

It is also advised to the bank to focus more on full-time working customers as they generate huge revenues for the organization by using the credit. Self-employed customers are problematic as they are more likely to cancel their credit card services.

By solving the above problems using the key findings and recommended solutions, the bank can function smoothly without any bottlenecks and there are also chances that customers might be retained.

Since retaining credit card customers is a necessity for banks, banks should initiate new schemes or offers to customers based on the customers portfolio and credit score. Accurate predictions are possible with the credit score of a particular customer.

![image](https://user-images.githubusercontent.com/37064981/158218752-482a2bd0-2bee-4cd3-8843-fab1693c7211.png)
