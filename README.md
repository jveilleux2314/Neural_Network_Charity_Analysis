# Neural_Network_Charity_Analysis

## Purpose
We got a list of Chairty data to clean, filter, analyze, and perform a neural network model on the clean set of data to determine the effectivness of which companies donations would be most impactful. 

## Process
- [x] Google Colab
- [x] pandas
- [x] sklearn , model training
- [x] tensorflow
- [x] matplotlib
- [x] OneHotEncoder
- [x] keras 


Data Preprocessing
What variable(s) are considered the target(s) for your model?
- The targets for my model is the "IS_SUCCESSFUL"

What variable(s) are considered to be the features for your model?
- All other columns would be featured : 
NAME
APPLICATION_TYPE 
CLASSIFICATION             
USE_CASE                   
ORGANIZATION                 
STATUS                     
INCOME_AMT                 
SPECIAL_CONSIDERATIONS   
ASK_AMT

What variable(s) are neither targets nor features, and should be removed from the input data?
- Based of the unique variables , I would think that SPECIAL_CONSIDERATIONS and STATUS would be the least effective in modifying the data, also keeping the EIN dropped would be wise because it would confuse the numerical data. 

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
Were you able to achieve the target model performance?
What steps did you take to try and increase model performance?
Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
