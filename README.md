# Neural_Network_Charity_Analysis

## Overview
The purpose of the analysis was to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. In order to accomplish this, a CSV file obtained from Alphabet Soup’s business team was used. 

## Results
The following can be observed from this analysis:

### Data Preprocessing
- The target is held in IS_SUCCESSFUL field
- The following variable(s) should be considered on features model
    - ORGANIZATION
    - STATUS
    - INCOME_AMT
    - SPECIAL_CONSIDERATIONS
    - ASK_AMT
    - APPLICATION_TYPE
    - AFFILIATION
    - CLASSIFICATION
    - USE_CASE
- The following variable(s) are neither targets nor features, and should be removed from input and data:
    - NAME
    - EIN

### Compiling, Training, and Evaluating the Model
- The first hidden layer has 12 nodes while the second hidden layer has 6 nodes. The activation function I used for both the first and second hidden layers is the 'relu' function, while I used the sigmoid function as the activation function for the output layer.
- The above model obtained an accuracy of 73.54%.
- <img width="433" alt="Screen Shot 2022-07-20 at 11 43 21 AM" src="https://user-images.githubusercontent.com/86126331/180025492-5571ff9a-5fb1-4569-beaa-18e2fcc652dc.png">
- In order to increase the model performance, I tried the following:
    - Increasing the number of hidden nodes in layer 1
    - Adding a third hidden layer
    - Changing the activation functions: tried linear, tanh, sigmoid for a combination of hidden layers and output layer

## Summary
Despite the various attempts, an accuracy of 75% was not achieved. Moving forward, I would further change the number of hidden layers and the number of nodes in each layer, as well as the type of activation function I use, in an attempt to get a more accurate result.

