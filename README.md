# Capstone Project: Utilizing Classification Models To Predict Presence of Heart Disease

**Baradhwaj Balraj**

## Executive summary

### Research Question - What Are You Trying To Answer?
Is it possible to create a reliable model to predict if a patient will have Cardiovascular Disease and What factors should be frequently observed by healthcare professionals to diagnose Cardiovascular Disease?

### Rationale - Why Should Anyone Care About This Question?
According to the CDC in the year 2022, 702,880 people died from heart disease, which is equivalent to 1 in 5 deaths.  Additionally, according to the CDC, heart disease cost about $252.2 billion from 2019 to 2020 which includes the cost of health care services, medicines, and lost productivity due to death.  This question is important for two reasons. One reason is because if it is possible to know what factors most contribute to heart disease, it would be possible for healthcare professionals to monitor those important factors to determine wether or not patients might be in risk for heart disease and can diagnose them early and get the patients the necessary care.  The second reason is if you can predict wether patients have heart disease using a model it would be possible to test someone who isn’t known to have heart disease and diagnose wether heart disease is prevalent in them or not.  If heart disease is diagnosed early it can help prevent serious complications such as heart attack, strokes, and heart failure by implementing preventative strategies.

### Data Sources
The data source is a database from the UCI ML learning repository that contains 14 features of numerous patients that have and don’t have heart disease in the city of Cleveland.

Link: https://archive.ics.uci.edu/dataset/45/heart+disease  

### Methodology
Plan on utilitizing four different classification models (Logistic Regression, K-Nearest Neighbors, SVM, and Decision Trees) to determine if it is possible to make a model to predict if cancer will be prevalent in patients based on certain features found in data set and which model would do this best. After this will utilize permutation importance on the best model to determine which factors are most important to monitor when attempting to diagnose heart disease in patients.

### Results
It can be deduced from this notebook that it is possible to predict presence of heart disease by using classification models such as K-Nearest Neighbors, Decision Trees, SVM, and Logistic Regression. Additionally, the best overall performing model and best model for predicting presence of heart disease specifically  was the SVM model. Finally, the four most important features (in order of most important to least important) in predicting the presence of heart disease are number of major vessels colored by fluoroscopy, thalac (maximum heart rate achieved in bpm), chest pain type, and sex of the patients.

### Next steps
One area for further exploration should be to see how the features: number of major vessels colored by fluoroscopy, thalac (maximum heart rate achieved in bpm), chest pain type, and sex of the patients impact presence of heart disease in patients.  Additionally, since this model would be used in the healthcare industry it is important to make sure that this model complies with industry relevant regulations such as HIPAA and the FDA before deployment. Additionally, it is also important to continuously improve the model and monitor the metrics to track performance. Possible to do this by periodically retraining the model or improving the model through use of ensemble methods for classification.

### Outline of project

- [Link to Jupyter Notebook With In-Depth Analysis]()
- [Link to Folder With Jupyter Notebook & Data]()


#### Contact and Further Information
Baradhwaj Balraj 

Barad.balraj@gmail.com

(425-495-9958)






#  Practical Application Assignment 17: Comparing Classifiers
## In this practical application, the objective is to explore a marketing dataset from a portugese banking institution. Additionally,in this practical application need to compare and contrast the performance of various classification models (Logistic Regression, K-Nearest Neighbors, SVM, and Decision Trees) to determine which performs best when predicting client churn.
### In the second link there is a folder containing a Jupyter notebook in which the performance of various classification models were evaluated to determine which model would be best for predicting churn. If you want access to look over the notebook in GitHub just open through the folder in this second link.  
### [Jupyter Notebook](http://localhost:8889/notebooks/BalrajModule17PracticalAssignment/BalrajFinalPracticalApplication17.ipynb)
### [Practical Application Assignment 17: Comparing Classifiers](https://github.com/baradhwaj-balraj/Professional_Certificate_Artificial_Intelligence_Machine_Learning/tree/5472e8627afb3b7c90f43482c0cf71088a423796/BalrajPracticalApplication17)
### The Findings Were:
##### 1.) Decision Tree model performed best when it comes to predicting churn and is the model I would reccomend utilizing for this business problem.
##### 2.) K-Nearest Neighbors is a close second and I would suggest using it if training time is a concern. The reason for this is it performs slightly worse than the decision tree model but has the fastest training time. 
##### 3.) Logistic Regression model is good at distinguishing between churn and non-churn but it is important to note that this model will miss many potential churners and as a result I would not suggest using it for this business problem.
##### 4.) SVM model performed the worst at predicting churn. As a result I would avoid using this model for this business problem.
### Some Future Steps Are:
##### 1.) Analyze the specific features to discover which features are most important when predicting churn and explore those features further.  


#  Practical Application Assignment 11.1: What Drives The Price of A Car?
## In this exercise the goal was to take a dataset found on Kaggle regarding used car features and price to determine which factors have an impact on car price.  Upon completion should be able to inform used car dealerships what features consumers value in a car.
### In the second link there is a folder containing a Jupyter notebook in which data analysis was performed to determine which features of used cars impact their prices the most. Use Jupyter Notebook link to access the notebook through Jupyter. If you want access to look over the notebook in GitHub just open through the folder in this second link.  
### [Jupyter Notebook](http://localhost:8889/notebooks/Module11PracticalAssignment/BalrajFinalPracticalApplication11.ipynb)
### [Practical Application Assignment 11.1: What Drives Price of A Car](https://github.com/baradhwaj-balraj/Professional_Certificate_Artificial_Intelligence_Machine_Learning/tree/main/PracticalApplciation11.1WhatImpactsPriceOfCar)
### The Findings Were:
##### The 4 features that most impacted the price of used cars in order were: 
##### 1.) Year of the car model  
##### 2.) Fuel Type (Gas, Diesel, Hybrid)
##### 3.) Number of cylinders in the engine
##### 4.) Number of miles on the odometer
### Some Future Steps Are:
##### 1.) Analyze which year cars are selling for highest price. 
##### 2.) Analyze which Fuel Type is selling for highest price. 
##### 3.) Analyze which cylinder engine is selling for highest price. 
##### 4.) Analyze what range of miles results in highest price. 
##### 5.) Suggest Used Car Dealerships clean up inventory based around these features to have used car inventory that is most desirable for customers to increase sale of dealership. 

#  Practical Application Assignment 5.1: Will The Customer Accept The Coupon?
## This exercise is a deep dive into a dataset that from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios, and then asks people whether they will accept the coupon if they are the driver.
### In the attached folder there is a Jupyter notebook in which data analysis was performed to determine will the driver accept the coupon based on a variety of different variables.  
### [Jupyter Notebook](http://localhost:8890/lab/tree/Project5.1/BalrajPracticalApplicationAssignment.ipynb) 
### [Practical Application Assignment](https://github.com/baradhwaj-balraj/Professional_Certificate_Artificial_Intelligence_Machine_Learning/tree/008c0bd6db680028376316fa39f22b832e7d19d2/BalrajPracticalApplicationAssignment)
###  Some of The Findings Were: 
##### - From data can infer that people who went to the bar 3 or less times were more likely to accept coupons.
##### - From data can infer that people who went to bar more than once a month and are older than 25 tend to accept coupons more that any other group who also went to bar.
##### - From data it is evident that about 88% of people that went for Carry Out accepted coupons.
##### - From data can infer that people who go for Carry Out while being in a relationship tend to accept coupon more than people who are not in relationships.
##### - From data can infer that people who are in a relationship and have a kid tend to accept coupon more than people who are in a relationship and dont have kids.
##### - From data can infer that people who are in a relationship have kids and get Carry Out 4 or more times a month have a higher chance of accepting coupons than same group of people that go less than 4 times a month.
### Some Future Steps Are:
##### - Find out data about drivers that go to different locations where coupons are accepted and analyze coupon data for those locations.
##### - Analyze data regarding people who refuse coupons and see if there is anything in common with the people who refuse coupons.
##### - Analyze if income has any impact on coupons being accepted or rejected.



