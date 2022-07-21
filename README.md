# Neural_Network_Charity_Analysis

## Purpose 

Our business team received a file with over 34,000 organizations that have received funding from Alphabet Soup. The purpose of this analysis is to utilize deep machine learning to determine if applicants will be successful if they receive funding in the future.  

## Results 

### Data Preprocessing
What variable(s) are considered the target(s) for your model?
The target variable is "IS_SUCCESSFUL"

What variable(s) are considered to be the features for your model?
The feature variables are "EIN", "NAME", "APPLICATION_TYPE", "AFFILICATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT",	"SPECIAL_CONSIDERATIONS"	and "ASK_AMT"

What variable(s) are neither targets nor features, and should be removed from the input data?
The variable that are neighter targets nor features are "NAME" AND "EIN"

### Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
I selected 100 neurons and three layers because it provided the highest accuracy over 75%.  

Were you able to achieve the target model performance and What steps did you take to try and increase model performance?

Yes, after several attempts and changing the code, layers, and neurons, I was able to achive 79%.  

![Screen Shot 2022-07-21 at 12 02 18 AM](https://user-images.githubusercontent.com/99801608/180127513-c44d45d2-bc6e-403b-8f56-b4152f4baea3.png)


