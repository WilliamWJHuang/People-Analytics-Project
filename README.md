# People-Analytics-Project
The purpose of this modeling task is to predict whether income exceeds 50k/yr based on census data. It's a classification problem as the target variable is binary (whether income exceeds 50k/yr or not). 

**Why this analysis matters**: 
<br>Predicting the income level of citizens is one of the key problems for the government as it helps the government to evaluate the impact on policies in many fields, such as education and immigration. I constructed a logistic regression classifier with an AUC of 0.91, which implies a fairly high predictability. With such as powerful tool, the government can make better decisions based on census data.

**Data Source**: <br>The dataset is from UCI Machine Learning Repository. The dataset contains a training set and a test set. 
- The training set contains 32561 observations with 15 columns. 
- The test set contains 16281 observations with 15 columns.

**The representation of variables are as below**:
- age: the age of an individual
- workclass: a general term to represent the employment status of an individual
- fnlwgt: final weight
- education: the highest level of education achieved by an individual
- education_num: the highest level of education achieved in numerical form
- marital_status: marital status of an individual
- occupation: the general type of occupation of an individual
- relationship: represents what this individual is relative to others
- race: Descriptions of an individual’s race
- sex: the biological sex of the individual
- capital_gain: capital gains for an individual
- capital_loss: capital loss for an individual
- hours_per_week: the hours an individual has reported to work per week
- native_country: country of origin for an individual
- class_: whether or not an individual makes more than $50,000 annually.
