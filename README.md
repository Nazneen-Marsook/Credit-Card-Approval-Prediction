# CREDIT CARD APPROVAL PREDICTION MODEL



## Overview of Problem Statement:

In the contemporary financial landscape, the efficiency and accuracy of credit card application processing are crucial to maintaining competitive advantage and customer satisfaction. To address these needs, a machine learning model for predicting credit card approval status emerges as a powerful tool. This model aims to automate and optimize the decision-making process by classifying credit card applications into two categories: "Approved" or "Rejected."

## Objective:
To develop a machine learning model to predict the likelihood of a credit card application being approved or rejected based on historical applicant data. The model aims to assist banking/financial institutions in automating the credit card approval process, reducing manual workload, and enhancing decision-making accuracy.

## Data Description:
### SOURCE : 
Dataset can be downloaded from the link: https://www.kaggle.com/datasets/caesarmario/application-data/data?select=Application_Data.csv

### FEATURES :
1. Applicant_ID : Unique identifier for each applicant for tracking.
2. Applicant_Gender : Gender of the applicant (Male/Female).
3. Owned_Car : Indicates whether the applicant owns a car (0 for No and 1 for Yes).
4. Owned_Realty : Indicates whether the applicant owns real estate (0 for No and 1 for Yes).
5. Total_Children : Number of children the applicant has.
6. Total_Income : The applicant's total annual income.
7. Income_Type : Type of income the applicant receives.
8. Education_Type : Level of education of the applicant.
9. Family_Status : Family status of the applicant.
10. Housing_Type : Housing type of the applicant.
11. Owned_Mobile_Phone : Indicates whether the applicant owns a mobile phone (0 for No and 1 for Yes).
12. Owned_Work_Phone : Indicates whether the applicant owns a work phone (0 for No and 1 for Yes).
13. Owned_Phone : Indicates whether the applicant owns a phone (0 for No and 1 for Yes).
14. Owned_Email : Indicates whether the applicant owns an email account (0 for No and 1 for Yes).
15. Job_Title : The occupation of the applicant.
16. Total_Family_Members : Number of family members of the applicant.
17. Applicant_Age : Age of the applicant.
18. Years_of_Working : Number of years the applicant has been working.
19. Total_Bad_Debt : Total amount of bad debt the applicant has.
20. Total_Good_Debt : Total amount of good debt the applicant has.
21. Status : The target variable indicating the approval status of the credit card application ( 0 for 'Rejected' and 1 for 'Approved').

## Pre-processing:
* Removed unnecessary columns.
* Handled skewed columns using different transformations.
* Capped outlier columns.
* Addressed data imbalance.

  ## Feature Engineering:
  * Encoded Categorical variables.
  * Included derived columns to gain more insights from the data.
  * Selected top performing features through different methods.
 
  ## Model Development:
  * Developed five different models and evaluated them using three different feature sets.
  * Plotted ROC Curves.
  * Hyper parameters are tuned for the selected model and cross-validation is done.
  * Finally, the model is saved as 'rfclassifier.pkl'
