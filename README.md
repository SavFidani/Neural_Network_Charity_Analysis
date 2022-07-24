# Neural_Network_Charity_Analysis

##Overview

The purpose of this analysis was to create a model which was able to predict whether Applicants funded by Alphabet Soup will be successful, or not. By creating a neural network, we sought to analyze relationships and outcomes of these relationships between variables such as Sponsored, Amount, Special Case, etc. Please review the below for a brief overview of findings.

##Results

###Data Processing

The variable that was set as our target was "IS_SUCCESSFUL". This variable indicated whether the applicant had a successful outcome or not. On the other end of our analysis, we have our variables such as "APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "INCOME_AMT", "SPECIAL_CONSIDERATIONS". The goal of setting up our analysis in this way was to look at the effects of all of these features on the outcome of successful applications as indicated by "IS_SUCCESSFUL".

###Compiling, Training and Evaluating

After some attempted adjustments of the model, I found the most accurate to contain 2 hidden layers with 49 and 42 neurons. I maintained the Relu activation function that was utilized in the first model we built. 

Through attempting to adjust the model for higher accuracy, I increased the epochs, increased the hidden layers, and both increased and decreased the neurons. Each of those attempts both individually and in combination reduced the accuracy of the model - this can be seen in my three HDF5 files. Unfortunately, I was unable to achieve the target model performance. 

##Summary

To summarize, the model that I found demonstrates 66% accuracy meaning that some of the variables and structure do contribute to forecasting successful application results. Another model with variables filtered more selectively may prove to be more effective at accurately predicting results of applications.

