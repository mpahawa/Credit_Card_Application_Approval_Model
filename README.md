# Credit_Card_Application_Approval_Model
Credit Card Application Approval Model done as part of Assignment given by IITM  

# Problem Statement
An MNC financial organisation operates in multiple geographies in various product segments (liabilities as well as credit). In the past few years, the bank has been on an expansion spree. As part of this expansion drive, it is looking to grow its customer base who purchase credit products. So, the bank is looking to push credit cards to new customers in one of the markets in which it is operating. Now, since this market is not mature in terms of data governance and reporting, the credit bureau (such as CIBIL and Experian) does not have data on all the existing card customers.

 

In order to expand its credit card portfolio, the bank is looking to build a credit card application approval model. Normally, banks process credit card applications based on credit bureau scores. Since this market does not have a credit bureau score for the majority of the customers, building such an application approval model becomes tricky. As the bank has some presence in the credit card space in the region, the data available to build the model contains the application data and performance of these customers. For a good understanding of the data set, you can go through the data description given below.

#Data Source 

The data set lies in AWS S3, so you need to connect to S3 and read the data to a Spark data frame. You can find the data set in the following public S3 links:

https://s3.amazonaws.com/sqoop.oozie.ml/credit_record.csv

https://s3.amazonaws.com/sqoop.oozie.ml/application_record.csv

Once the data is successfully loaded, perform EDA (Exploratory data analysis) on it to understand the data set and use well-considered visualisations to unwrap the insights. (You may use Python libraries for any necessary plots and visualisations).

Perform any required checks such as variable exploration, outlier treatment, missing value imputation, variable transformation and correlation check.

Apply the concepts of Weight of Evidence and Information Value to perform variable exploration and variable transformations. (You will learn more about these concepts in the next segment.) 

Once the data preprocessing is complete, build a credit card application approval model.

Fine-tune the model and then evaluate the model by considering various metrics such as precision, recall, F1-score, AUC score and KS statistic, and finally, create a small write-up to explain the different model tuning techniques that you have applied and the details of the performance of the model in each scenario.

#Solution 
 Use notebook on EMR Machine with 50GB storage  
