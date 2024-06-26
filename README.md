The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

EIN and NAME—Identification columns
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special considerations for application
ASK_AMT—Funding amount requested
IS_SUCCESSFUL—Was the money used effectively



Overview: The purpose of this project was to utilize deep learning and neural networks to predict the success rate for funding of a non profit organization. The goal is to create a model with an accuracy score of 75% or greater. 

Data Preprocessing
What variable(s) are the target(s) for your model? The target for the model is "IS_SUCCESSFUL"
What variable(s) are the features for your model? All columns except for the target are features for the model. 
What variable(s) should be removed from the input data because they are neither targets nor features? EIN and Name

Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
Were you able to achieve the target model performance? I was unable to achieve the target model performance after 4 attempts. 
What steps did you take in your attempts to increase model performance? I modified the neuron layers up and down to achieve target model but was unsuccesful. 

SUMMARY: After numerous attempts at optimizing the model, i was unsuccesful in achieving the targer performance. While the target was not achieved, the model was still somewhat succesful with a accuracy score of 73%. Other considerations to improve accuracy in the future would be to utilize Random forest model to identify the most influential features that contribute to an effective model 
