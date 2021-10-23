# Neural_Network_Charity_Analysis

## Overview of Project
Bek’s come a long way since her first day at that boot camp five years ago—and since earlier this week, when she started learning about neural networks! Now, she is finally ready to put her skills to work to help the foundation predict where to make investments.

With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, Beks received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:

EIN and NAME—Identification columns
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special consideration for application
ASK_AMT—Funding amount requested
IS_SUCCESSFUL—Was the money used effectively

## Deliverables
### Deliverable 1: Preprocessing Data for a Neural Network Model
![alt tag](https://github.com/elrvra/Neural_Network_Charity_Analysis/blob/main/Resources/Images/Deliverable1.png)
![alt tag](https://github.com/elrvra/Neural_Network_Charity_Analysis/blob/main/Resources/Images/Deliverable1-2.png)

### Deliverable 2: Compile, Train, and Evaluate the Model
![alt tag](https://github.com/elrvra/Neural_Network_Charity_Analysis/blob/main/Resources/Images/Deliverable2.png)
![alt tag](https://github.com/elrvra/Neural_Network_Charity_Analysis/blob/main/Resources/Images/Deliverable2-2.png)

### Deliverable 3: Optimize the Model
- Optimize 1st round
![alt tag](https://github.com/elrvra/Neural_Network_Charity_Analysis/blob/main/Resources/Images/Deliverable3.png)

- Optimize 2nd round
![alt tag](https://github.com/elrvra/Neural_Network_Charity_Analysis/blob/main/Resources/Images/Deliverable3-2.png)

- Optimize 3rd round
![alt tag](https://github.com/elrvra/Neural_Network_Charity_Analysis/blob/main/Resources/Images/Deliverable3-3.png)

### Deliverable 4: A Written Report on the Neural Network Model (README.md)

1. Overview: Explain the purpose of the analysis.
A nueral network is a powerful machine learning technique that is modeled after neurons in the brain. Neural networks can rival the performance of the robust statistical algorithims without having to worry about any statistical theory. Because of this neural networks are one of the most in demand skills for any data scientist. In this analysis, it is disovered how neural networks are designed and the neural network effectiveness. With neural networks, we can combine the performance of multiple statistical and machine learning models with minimal effort. In sum, the purpose is to learn how to design, train, evaluate, and export neural networks to use in any scenario.

2. Results: 

Data Preprocessing
-  What variable(s) are considered the target(s) for your model?
IS_SUCCESSFUL

-  What variable(s) are considered to be the features for your model?
ORGANIZATION
STATUS
INCOME_AMT
SPECIAL_CONSIDERATIONS
ASK_AMT
APPLICATION_TYPE
AFFILIATION
CLASSIFICATION
USE_CASE

-  What variable(s) are neither targets nor features, and should be removed from the input data?
NAME
EIN

Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model?
number_input_features = 43
hidden_nodes_layer1 = 80
hidden_nodes_layer2 = 30
#hidden_nodes_layer3 = 10

- Were you able to achieve the target model performance?
Increasing the number of hidden nodes in layer 1 (3 X number of input features)
Increasing the number of hidden layers to include a 3rd

- What steps did you take to try and increase model performance?
Changing the activation functions: tried linear, tanh, sigmoid for a combination of hidden layers and output layer

3. Summary: 
- The analysis and deep learning model results, although not achieving the target 75% accuracy, could be altered by changing any numbers of items, such as the features or epochs, which could solve this classification and result in better accuracy.