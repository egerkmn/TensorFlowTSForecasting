# TensorFlowTSForecasting

In this project, I will build an end-to-end machine learning solution using a recurrent neural network(RNN) for electricity demand prediction problem via TensorFlow.
The dataset contains 2,075,259 measurements gathered in a house in France between Dec 2006 and Nov 2010. The aim is to predict the electricity demand of the next hour using past measurements. Since it is a regression problem, Mean Squared Error(MSE) and Mean Absolute Error(MAE) are used as evalution metrics. I will also try to share the reasoning behind my choices.

We will go through 5 steps:
1) Preparing Libraries and Data: Obtaining the training and test datasets
2) Preprocessing the Data: Dealing with pixels and scaling the target
3) Building the Recurrent Neural Network for Regression: Implementing TensorFlow RNN model
4) Model Results and Evaluation: Making comments on the model results
5) Model Improvement with Date Information Addition: Adding date information to improve the model results

More details are given in the Jupyter Notebook.
