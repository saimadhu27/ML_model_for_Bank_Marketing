# Strategies for Bank Marketing Using Machine Learning
The dataset is obtained from : https://archive.ics.uci.edu/dataset/222/bank+marketing

## About the project
The State bank wants to improve it's marketing strategies to reach more members. The State bank has given it's past marketing data to the data team to resolve this problem. So, the data team will use a Machine Learning model to predict if the customer has subscribed to the term deposit based on the data and analyse the past data to get the important features which will influence the subscription of the term deposit.

In this project we will use the bank marketing dataset which is availabe in UCI Machine Learning repository and the dataset consists of 
1. Bank Cilent Data
2. The contact information of the customers that came through campaign
3. Other attributes

Here, our dependent variable will be y- has the client subscribed a term deposit? (binary: 'yes','no'). We have used an classification algorithm called Random Forest Classifier to predict the variable y.

## Insights from the project
* We have acheived an accuracy of 73% using hyperparameter tuning. <br />
* The three most important features which will influence the result of our dependent variable are :
  1. Balance - Balance of an individual
  2. Age - Age of the individual
  3. Day - Last Contact Day in the month to the Customer

## Recommendations for the future marketing campaigns:
* The customer's account balance has a huge influence on the campaign's outcome. People with account balance above 1490$ are more likely to subscribe for term deposit, so future address those customers.
* The future marketing campaign should focus more on people whose age is 30 years and below, and 60 years and above.
  
