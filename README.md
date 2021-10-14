# Credit-card-fraud-detection-using-ML
Used some Data Analytics techniques and sorted out the fraud cases and non-fraud cases and make a future prediction and think how to reduce the fraud cases  



The data set has 31 features, 28 of which have been anonymised and are labelled 
V1 through V28. The remaining three features are the time and the amount of the 
transaction as well as whether that transaction was fraudulent or not. The data set 
contains 284,807 transactions. The mean value of all transactions is $88.35 while 
the largest transaction recorded in this data set amounts to $25,691.16. However, 
as you might be guessing right now based on the mean and maximum, the 
distribution of the monetary value of all transactions is heavily right-skewed. The 
vast majority of transactions are relatively small and only a tiny fraction of 
transactions comes even close to the maximum.


The time is recorded in the number of seconds since the first transaction in the data 
set. Therefore, we can conclude that this data set includes all transactions recorded 
over the course of two days. As opposed to the distribution of the monetary value 
of the transactions, it is bimodal. This indicates that approximately 28 hours after 
the first transaction there was a significant drop in the volume of transactions. 
While the time of the first transaction is not provided, it would be reasonable to 
assume that the drop in volume occurred during the night.

And generally this is a very relevant problem that demands the attention of 
communities such as machine learning and data science where the solution to this 
problem can be automated. This problem is particularly challenging from the 
perspective of learning, as it is characterized by various factors such as class 
imbalance. The number of valid transactions far outnumber fraudulent ones. Also, 
the transaction patterns often change their statistical properties over the course of 
time. These are not the only challenges in the implementation of a real-world fraud
detection system, however. In real world examples, the massive stream of payment 
requests is quickly scanned by automatic tools that determine which transactions 
to authorize. Machine learning algorithms are employed to analyse all the 
authorized transactions and report the suspicious ones. These reports are 
investigated by professionals who contact the cardholders to confirm if the 
transaction was genuine or fraudulent. The investigators provide a feedback to
The automated system which is used to train and update the algorithm to eventually 
improve the fraud-detection performance over time
