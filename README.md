# Prudential-Life-Insurance-Assessment
In this project, models are developed with Machine Learning Algorithms for predicting the insurance rating.
The Code is in Python and I have used Scikit Learn and Keras Library for training the models.
The Project includes:
1. Data Wrangling and EDA.
2. Transformer Class to take care of outliers. The benefit is that the learnt values for imputation of outliers can be directly applied to test data. It can also be a included as a step in the Preprocessing pipeline.
3. Preprocessing pipeline to take care of Missing values and Feature Scaling.
4. First model uses Random Forest Classifier to train the data. The Model attained an accuracy of 100% on train set and validation set.
5. Second is a  Sequential model of Deep neural network, using keras. The Stochastic Gradient Descent is used to optimise the loss function. The model converged to the minimum for both train set and validation set.


