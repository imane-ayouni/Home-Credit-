# Home-Credit-Risk assessment

Home Credit is an international consumer finance provider that operates in 9 countries. It provides point of sales loans, cash loans, and revolving loans to underserved borrowers.
They believe that credit history should not be a barrier for the borrowers to fulfill their dreams. Over 22 years of track record, they have accumulated a large amount of borrowers’ behavioral data which they leverage to provide financial assistance to such customers. They have built predictive models that help them to efficiently analyze the risk associated with a given client and to also estimate the safe credit amount to be lent to customers, even with no credit history.
## Data Discription 
![image](https://user-images.githubusercontent.com/81591745/147472346-3f0d64b4-d71c-4860-a9cb-832cb4ef6efb.png)

## Data Source
https://www.kaggle.com/c/home-credit-default-risk/data

## Objectives
The main objective is to identify the potential Defaulters based on the given data about the applicants.
The probability of classification is essential because we want to be very sure when we classify someone as a Non-Defaulter, as the cost of making a mistake can be very high to the company.

## Machine learning problem formulation 
- We can identify that it is a Supervised Learning Classification problem, which contains the training data points along with their Class Labels. Here the Class Labels represent whether a given applicant is a Defaulter or not. Thus, for a given application of a client, using the given features, we have to predict the Class Label associated with that client.
- We also realize that it is a Binary Classification problem, that is it contains just 2 classes, viz. Positive (1) and Negative (0).
- The dataset provided is an imbalanced dataset. Thus, we would need to address this imbalance wherever required, as some ML algorithms are sensitive to data imbalance.

## Classification models used
- Logistic Regression
- Random Forest Classifier
- XGBoost
- SVM

## Evaluation matrices
- Accuracy
- Precision
- Recall
- F1 score
- AUC ROC Curve
- Confusion matrix
