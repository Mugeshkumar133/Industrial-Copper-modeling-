# Industrial-Copper-modeling-
This project deals with an industrial copper modeling problem typically involves the development of mathematical, statistical, or machine learning models to predict or optimize various aspects related to the production, utilization, or market behavior of copper in an industrial context and showcasing it in the streamlit application.
# Problem Statement:
a) The copper industry deals with less complex data related to sales and pricing. However, this data may suffer from issues such as skewness and noisy data, which can affect the accuracy of manual predictions. Dealing with these challenges manually can be time-consuming and may not result in optimal pricing decisions.

b) A machinelearning regression model can address these issues by utilizing advanced techniques such as data normalization, feature scaling, and outlier detection, and leveraging algorithms that are robust to skewed and noisy data.

c) Another area where the copper industry faces challenges is in capturing the leads. A lead classification model is a system for evaluating and classifying leads based on how likely they are to become a customer .

d) You can use the STATUS variable with WON being considered as Success and LOST being considered as Failure and remove data points other than WON, LOST STATUS values.

# Solution
The solution includes the following steps:

i)   Exploring skewness and outliers in the dataset.

ii)  Transforming the data into a suitable format and performing any necessary cleaning and pre-processing steps.

iii) Developing a machine learning regression model which predicts the continuous variable 'Selling_Price' using the decision tree regressor.

iv)  Developing a machine learning classification model which predicts the Status: WON or LOST using the decision tree classifier.

v)   Creating a Streamlit page where you can insert each column value and get the Selling_Price predicted value or Status (Won/Lost).
