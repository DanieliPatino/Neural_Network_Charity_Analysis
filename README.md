# Neural_Network_Charity_Analysis

## Overview of the analysis: 

The purpose of this analysis is to use the features in the dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

## Results: 

***Data Preprocessing***

**What variable(s) are considered the target(s) for your model?**

The ‘IS_SUCCESSFUL’ is considered the target model.

**What variable(s) are considered to be the features for your model?**

The following variables are considered to be the features for the model: ‘APPLICATION_TYPE’, ‘AFFILIATION’, ‘CLASSIFICATION’, ‘USE_CASE’, ‘ORGANIZATION’, ‘INCOME_AMT’, and ‘SPECIAL_CONSIDERTIONS’.

**What variable(s) are neither targets nor features, and should be removed from the input data?**

‘EIN’ and ‘NAME’ are removed from the input. I also removed ‘STATUS’ on one of my attempts.


***Compiling, Training, and Evaluating the Model***

**How many neurons, layers, and activation functions did you select for your neural network model, and why?**

For each attempt I tried to change the hidden node layers, change the activation under the Dense hidden and output layers to increase the accuracy of the model. 

For my Deliverable 2 attempt, please see the image below for details. 

![Deliverable 2 outcome](https://user-images.githubusercontent.com/92958939/166133076-9522f787-c7e0-4611-9f81-59368d188ae2.png)


For my first attempt on Deliverable 3, please see the image below for details.

![Deliverable 3- 1st attempt](https://user-images.githubusercontent.com/92958939/166133080-6e6e730f-628c-40ed-9cf0-b48859858dba.png)

For my second attempt on Deliverable 3, please see the image below for details.

![Deliverable 3- 2nd attempt](https://user-images.githubusercontent.com/92958939/166133084-2f928c15-fd0a-4501-b87e-c3b921f2896f.png)

For my third and final attempt on Deliverable 3, please see the image below for details.

![Deliverable 3- 3rd attempt](https://user-images.githubusercontent.com/92958939/166133088-5f11da30-616d-489f-b80d-3113afdb6a91.png)


**Were you able to achieve the target model performance?**

I was not able to achieve the target model performance of 75%. The highest I got was able to obtain was a 73%.

**What steps did you take to try and increase model performance?**

The steps I took to increase the model’s performance was to increase the hidden node layer numbers and increase the hidden layers on top of changing the activations.


## Summary: 

After my numerous attempts I noticed that adding too many layers and getting rid of too many columns will decrease the accuracy. I also noticed due to the randomization,  a specific patter with the hidden nodes and the hidden layers will give you a high output the first time, but if you run it again, it will change to either a similar accuracy score, or it will decrease significantly.

I would suggest using the Random Forest Classifier due to it being able to prevent overfitting better than other models. 

