# Home-Loan-Space
As a Data Scientist at Standard Bank, I have implemented Machine Learning model using bespoke and AutoML with SQL, Python to assess the creditworthiness of an applicant and predict if the potential borrower will default on his/her loan or not and do this such that they receive a response within few seconds.

### Agenda

- Data Science Lifecycle
- Project Overview
- Process Overview
- Data 
- Analysis
- Modeling
- Model Evaluation
- Recommendations


### Data Science Lifecycle
- Business Understanding
- Data Understanding
- Data Preparation
- Modelling
- Evaluation
- Deployment


### Project Overview
**Business Problem:** The current home loan applications require loan officers to process manually, which takes 2 to 3 days to make the decision and notified outcome to the applicant.
**Business Objective:** To improve the manual process and reduce the amount of application processing time 
**Hypothesis:** Based on historical data we can use machine learning to predict the loan status of a potential borrower such that the time taken for them to receive their respective statuses is reduced significantly. 


### Process Overview


![Image](https://user-images.githubusercontent.com/25155794/226133042-8f6914bb-8e0a-4770-872d-e318b375598c.png)
An applicant can apply on any device by filling his/her information (Gender, Marital Status, Income etc.). Upon completion the machine learning model will be triggered to make a predict (based on historical data that it has been trained). The prediction will appear on the device as Accept or Decline on the same device within few seconds

### Analysis


![Image](https://user-images.githubusercontent.com/25155794/226133303-80e3edda-9511-4f11-bbb7-5b58eb7dbf73.png)

![Image](https://user-images.githubusercontent.com/25155794/226133344-f54f65ea-d2df-4978-9170-63b73a6e3f25.png)


### Modeling
One machine learning model trained and AutoML used as well. 
-Bespoke model required preprocessing 
-AutoML did not 
-Results fairly similar 

### Evaluation


![Image](https://user-images.githubusercontent.com/25155794/226133513-eee2e670-8041-4dc1-9c05-d19fe8340f2b.png)


### Recommendations
Bespoke ML > AutoML 
We understand/know exactly what went in, how it went in and what algorithm was used to achieve the objective 
Less time training (works in our favour if we train and predict in real time – maybe not applicable in this use case)
AutoML is best used as
