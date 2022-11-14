# Neural_Network_Charity_Analysis
Module 19

### Overview of the analysis: The purpose of this analysis is to create a binary classified to help predict whether or not applicants will be
successful is funded by Alphabet soup.

### Results: .

##### Data Preprocessing

- What variable(s) are considered the target(s) for your model? The target we are using for this dataset is the column of "IS_SUCCESSFUL".  This
determines whether or not the money was used effectively.  
- What variable(s) are considered to be the features for your model? The feature columns are the rest of the data: APPLICATION_TYPE,
AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS—Active status, INCOME_AMT—Income classification, SPECIAL_CONSIDERATIONS, 
ASK_AMT
- What variable(s) are neither targets nor features, and should be removed from the input data? We removed the ID and the NAME because they had no
bearing on if the venture was successful or not.

##### Compiling, Training, and Evaluating the Model

- How many neurons, layers, and activation functions did you select for your neural network model, and why? For my optimization model I used a total
of 115 neurons over 4 layers with 2 separate activation functions.  I used more neurons and layers in hopes of getting my accuracy score higher.  As you
can see compared to the standard model.  
- Were you able to achieve the target model performance? As you can see from below I was not.  It looks like I actually lost accuracy when I increased
the number of layers and neurons.

- What steps did you take to try and increase model performance? I added 2 additional layers and over 70 neurons over my 3 separate attempts to increase accuracy.

##### Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.