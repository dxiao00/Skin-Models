# About:
These are a collection of models created for my applied regression and time series class. The models include a linear regression model, a 2-way ANOVA with interaction model, and a time series model. 

# Model Goals: 
## Linear Regression Model
This model had the goal of predicting the survival time in months from diagnosis for deadly melanoma cases. 
Melanoma is a type of skin cancer that is mostly caused by exposure to UV light. In many cases, we can treat melanoma successfully if it is caught early [(more info on melanoma)](https://www.mayoclinic.org/diseases-conditions/melanoma/symptoms-causes/syc-20374884). 
In the event that we do not detect the symptoms of melanoma early, causing treatment to be delayed, we can imagine that the cancer can become a cause of death. If we have strong reason to believe that a particular case of melanoma is deadly, then it may be important for the patient or family members of the patient to know how much time they have left to live. Thus, the goal of this regression model is to predict the time in months from diagnosis that a patient has to live for cases of melanoma where the cause of death is the cancer itself. 

The data was collected from the [SEER Cancer Database](https://seer.cancer.gov/) by filtering for melanoma cases where the cause of death can be attributed to the cancer itself. The SEER program tracks cancer incidents from all over the United States starting from 1973. The data was cleaned to remove rows with missing values. The final dataset has 3431 rows and 11 variables, including the response.
