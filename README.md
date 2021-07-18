# Neural_Network_Charity_Analysis

## Purpose
We got a list of Chairty data to clean, filter, analyze, and perform a neural network model of data to determine the effectivness of which companies donations would be most impactful. 

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

<img width="530" alt="Screen Shot 2021-07-13 at 4 17 42 PM" src="https://user-images.githubusercontent.com/78769464/126061600-8a52afb0-6add-4f8e-b870-5510babacb40.png">

<img width="596" alt="Screen Shot 2021-07-13 at 4 17 53 PM" src="https://user-images.githubusercontent.com/78769464/126061616-f366fb65-7f13-4f3b-91ef-4ce2fcb57769.png">

<img width="561" alt="Screen Shot 2021-07-13 at 4 18 00 PM" src="https://user-images.githubusercontent.com/78769464/126061617-477e7ab1-fb04-44a9-9197-25fa19473a30.png">

<img width="622" alt="Screen Shot 2021-07-13 at 4 18 16 PM" src="https://user-images.githubusercontent.com/78769464/126061621-6cdc66dd-1adf-4bab-aad0-e30c3e695190.png">

<img width="550" alt="Screen Shot 2021-07-13 at 4 18 23 PM" src="https://user-images.githubusercontent.com/78769464/126061623-26d61ce8-0819-472b-84fc-84a6d0ddeaf7.png">


What variable(s) are neither targets nor features, and should be removed from the input data?
- Based of the unique variables , I would think that SPECIAL_CONSIDERATIONS and STATUS would be the least effective in modifying the data, also keeping the EIN dropped would be wise because it would confuse the numerical data. 

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?

I had experimented and tried adding additional layers & taking away layers but neither seemed to give me better results, one gave me close to the same and the other actually decreased my performance. 

<img width="775" alt="Screen Shot 2021-07-13 at 4 19 28 PM" src="https://user-images.githubusercontent.com/78769464/126061352-758db109-e04b-4d76-99f1-89b03190eb5d.png">

Were you able to achieve the target model performance?

I was not able to acheive the target model performance.

What steps did you take to try and increase model performance?

I tried adding and removing hidden layers, changing the activation types, in addition to changing which columns I had originally dropped. I had no luck with increasing my performance but instead in some circumstances, I actually made my performance worse so I quickly went back to the beginning and tried a different step. 

Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.

I think the concept of this learning model has very good intentions and has the potential to help in many ways, in many different coorporations. I do beleive we need more data to be able to ultimately determine which donations would be most impactful but the concept is present and has great potential. 

