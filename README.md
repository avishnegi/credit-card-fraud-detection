# credit-card-fraud-detection
 
PROBLEM STATEMENT:<br>

Credit card fraud detection is challenging task for the user.Online payment does not require physical card and if anyone who know the details of card can make the transactions. Currently,card holder comes to know only after the fraud transaction is carried out. No proper mechanism are there to track the fraud transaction.<br>

ABSTRACT:<br>

Financial fraud is an ever growing menace with far consequences in the financial industry. Data mining had played an imperative role in the detection of credit card fraud in online transactions. Credit card fraud detection, which is a data mining problem, becomes challenging due to two major reasons - first, the profiles of normal and fraudulent behaviours change constantly and secondly, credit card fraud data sets are highly skewed. The performance of fraud detection in credit card transactions is greatly affected by the sampling approach on dataset, selection of variables and detection technique(s) used.<br>

OBJECTIVE:<br>

The overall objective of this project is listed below:<br>
• To reduce number of fraud transaction.<br>
• To use credit card safely for online transaction.<br>
• To add layer of security.<br>

DATASET:<br>

In this project we analyze a dataset of credit card transactions made over a two-day period in September 2013 by European cardholders. The dataset contains 284,807 transactions, of which 492 (0.17%) are fraudulent.
Each transaction has 30 features, all of which are numerical. The features V1, V2, ..., V28 are the result of a PCA transformation. To protect confidentiality, background information on these features is not available. The Time feature contains the time elapsed since the first transaction, and the Amount feature contains the transaction amount. The response variable, Class, is 1 in the case of fraud, and 0 otherwise.<br>

SOFTWARE AND LIBRARIES<br>
This project uses the following software and Python libraries:<br>

Language:Python 3.7<br>
NumPy<br>
pandas<br>
seaborn<br>
sklearn<br>
matplotlib<br>
Software:Google colab<br>

MODEL IMPLEMENTED<br>

Logistic Regression<br>

PROCEDURE FOLLOWED:<br>
The dataset for this project is taken from the kaggle . <br>
Then comes the preprocessing phase . In this dataset not much preprocessing was required as the data was already ckeaned. But I have to divide the dataset into two classes:<br>
     1. fraud<br>
     2. not fraud<br>

Now to reveal patterns and structure in data , I have performed data visualization.<br>
Then the splitting of the dataset is done into training and testing data in the ratio 70:30.<br>
After this model making is done using Logistic regression.<br>

RESULT<br>

Sensitivity/Recall for Logistic Regression Model : 0.57<br>
F1 Score for Logistic Regression Model : 0.68<br>

CONCLUSION:<br>

Credit card fraud is without a doubt an act of criminal dishonesty.This project has also explained in detail, how machine learning can be applied to get better results in fraud detection along with the algorithms.<br>

FUTURE ENHANCEMENT:<br>

While I couldn’t reach out goal of 100% accuracy in fraud detection, I did end up creating a system that can, with enough time and data, get very close to that goal. The very nature of this project allows for multiple algorithms to be integrated together as modules and their results can be combined to increase the accuracy of the final result.  




