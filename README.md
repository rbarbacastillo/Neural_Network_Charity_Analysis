# Neural_Network_Charity_Analysis

# Overview
This project tried to predict whether applicants will be successful if funded by the Alphabet Soup Co. Alphabet Soup Co. wants to provide funding to companies but it needs to know in advance whether it will be successful or not. 

# Results

* Data Processing

  * To clean the data I removed the EIN and NAME columns since they have no value to the model.
  * The varibales being considered for my model are as follows: 'STATUS', 'ASK_AMT', 'IS_SUCCESSFUL', 'APPLICATION_TYPE', 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', 'INCOME_AMT'. I dropped "USE_CASE_Other","AFFILIATION_Other" columns.
  * My Dependent varible is "IS_SUCCESFUL" since the purpose is to predict this with high accuracy.

* Compiling, Training, and Evaluating the Model Attempt #1

  * 2 Hidden Layers
  * 80 neurons (Layer1), 30 neurons(Layer2)
  * Used Relu and Sigmoid Activations Functions since sigmoid is best for binary classifcation problems as this and relu is for       nonlinear datasets.
  * Removed "USE_CASE_Other","AFFILIATION_Other" columns.

Attempt #2

  * 3 Hidden Layers
  * 80 neurons (Layer1), 30 neurons(Layer2), 15 neurons(Layer3)
  * Used Relu and Sigmoid Activations Functions since sigmoid is best for binary classifcation problems as this and relu is for       nonlinear datasets.
  * Removed "USE_CASE_Other","AFFILIATION_Other" columns.

Attempt #3

  * 3 Hidden Layers
  * 80 neurons(Layer1), 35 neurons(Layer2), 10 neurons (Layer3)
  * Used Relu and Sigmoid Activations Functions since sigmoid is best for binary classifcation problems as this and relu is for       nonlinear datasets.

Attempt #4

  * 3 Hidden Layers
  * 80 neurons (Layer1), 30 neurons(Layer2), 15 neurons (Layer3)
  * Reordered Relu and Sigmoid Activations

Summary

The models provided around 73% accuracy score which is useful for this purposes, however the model could still be perfectible.

