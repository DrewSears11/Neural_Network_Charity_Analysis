# Neural_Network_Charity_Analysis
Module 19

### Overview of the analysis 

The purpose of this analysis is to create a binary classified to help predict whether or not applicants will be
successful is funded by Alphabet soup.

### Results

### Data Preprocessing

- What variable(s) are considered the target(s) for your model? 

The target we are using for this dataset is the column of "IS_SUCCESSFUL".  This
determines whether or not the money was used effectively.  
- What variable(s) are considered to be the features for your model? 

The feature columns are the rest of the data: APPLICATION_TYPE,
AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, 
ASK_AMT
- What variable(s) are neither targets nor features, and should be removed from the input data? 

We removed the ID and the NAME because they had no
bearing on if the venture was successful or not.

### Compiling, Training, and Evaluating the Model

- How many neurons, layers, and activation functions did you select for your neural network model, and why? 

For my optimization model I used a total of 115 neurons over 4 layers with 2 separate activation functions.  I used more neurons and layers in hopes of getting my accuracy score higher compared to the standard model we used.
- Were you able to achieve the target model performance? 

As you can see from below I was not.  It looks like I actually lost accuracy when I increased the number of layers and neurons.  The screenshot below is my optimized model after three attempts.

![image](https://user-images.githubusercontent.com/108240844/201556288-95addb49-d18e-4d8d-b6d8-d573cd2baf84.png)

Below is our "baseline" model

![image](https://user-images.githubusercontent.com/108240844/201556325-0f448ce6-6b6a-4f6b-8374-871a7ccedbb5.png)


- What steps did you take to try and increase model performance? 

I added 2 additional layers and over 70 neurons over my 3 separate attempts to increase accuracy.

### Summary

In summary, adding more neurons and layers did not help the accuracy of my model.  The accuracy dropped about 5% using additional layers and neurons.  It actually did decrease the amount of loss by about .07 which was good.  To further help with the accuracy I would reccomend dropping a couple columns, perhaps the STATUS and SPECIAL_CONSIDERATIONS tab on this.  This would possibly give us an accuracy score over 75% which is what we are looking for. 

