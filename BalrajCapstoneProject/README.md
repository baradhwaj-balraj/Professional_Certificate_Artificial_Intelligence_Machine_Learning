# Capstone Project: Utilizing Classification Models To Predict Presence of Heart Disease

**Baradhwaj Balraj**

## Executive summary

### Research Question
What are you trying to answer?
s it possible to create a reliable model to predict if a patient will have Cardiovascular Disease and What factors should be frequently observed by healthcare professionals to diagnose Cardiovascular Disease?

### Rationale
Why should anyone care about this question?
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

- [Link to Jupyter Notebook With In-Depth Analysis](https://github.com/baradhwaj-balraj/Professional_Certificate_Artificial_Intelligence_Machine_Learning/blob/e132f97335f5f5a819672f04eab194231e2008cc/BalrajCapstoneProject/BalrajCapstoneFinalipynb.ipynb)
- [Link to Folder With Jupyter Notebook & data used]()


#### Contact and Further Information
Baradhwaj Balraj 
Barad.balraj@gmail.com
(425-495-9958)
