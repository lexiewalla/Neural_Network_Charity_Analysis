# Neural_Network_Charity_Analysis
Module 19 Neural Networks


## Overview 

In this module we used neural networks to analyze applicants for Alphabet Soup. We did this by creating a binary classifier to predict which applicants would be successful. We did this in three steps, preprocessing the data, next, complie, train and evaluate the data and last, optimized the model. 

## Results

### Data Preprocessing
What variable(s) are considered the target(s) for your model?
 - IS_SUCCESSFUL column is the one that was the target and contains the binary data which told us if the charity donation was succesful.
 
What variable(s) are considered to be the features for your model?
 - AFFILIATION, CLASSIFICATION, APPLICATION_TYPE, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT, USE_CASE, ORGANIZATION, STATUS are all features of the model

What variable(s) are neither targets nor features, and should be removed from the input data?
 - EIN and NAME were dropped because they will not provide any information if the charity donation would be successful or not.

### Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
 - The model has two hidden layers. The first layer has 80 neurons and the second has 30. ReLu was used as the activation function. 

Were you able to achieve the target model performance?
 - Close but not quite 75% my model performance came out to be 73%.

What steps did you take to try and increase model performance?
 - I tried to increase model performance by increasing the number of neurons in the first hidden layers. I tried using a different activation function, tanh and tried using a a third hidden layer. 

## Summary 

The model turned out to be 73% accruate. I know the target was 75% but given we were only 2% away it wasn't bad. There are several different models out there that we could try in place of this to get it closer to 75% like Random Forest Classifier or an Adaboost Classifier or we could try to gather more data before analyzing. 



   
