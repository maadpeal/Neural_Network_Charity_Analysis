# Neural_Network_Charity_Analysis

## Purpose
    - Help Beks create a binary classifier that is capable of predicting whether applicants will 
    be successful if funded by Alphabet Soup.

## Results
    - The variable we want to predict (y) is IS_SUCCESSFUL, which allows us to identify which 
    investments were successful or not.
    - The variables that we will use to predict the success of each investment are: 
    APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT and ASK_AMT.
    - The variables that will be removed are: EIN, NAME, STATUS and SPECIAL_CONSIDERATIONS.
    - For the input layer I used 76 nodes and in the second 58, I used the tanh function, this 
    configuration was used because it generated a hyperparameter function and they were the best 
    ones that performed well according to the algorithm.
    - I didn't get the performance or replicate the acurracy that the hyperparameters function told me.

![](https://github.com/maadpeal/Neural_Network_Charity_Analysis/blob/main/Resources/A-1.png)
 
    - Decrease the number of categories in each column, try multiple neuron configurations, use a 
    function that finds the best configuration solution to get an idea of which ones to use.

## Summary
    - The first thing to do is to know the variables that we have to make the correct classification.
    - Identify which are the objective variables and which ones help us predict this variable.
    - Identify what type of data each variable contains.
    - If a variable is a category, identify the number of unique values it contains.
    - If you have more than 10 categories, find a way to reduce the number to prevent the model 
    from getting confused.
    - Although I used a function to iterate the best result, I couldn't replicate the accuracy that 
    the iteration function indicated.
    - The alternative model that I created was the random forest model in order to obtain the most 
    important variables that the model used, which gave me a better performance accuracy than the rest.

![](https://github.com/maadpeal/Neural_Network_Charity_Analysis/blob/main/Resources/A-2.png)

    - The recommendation is to take these variables and analyze them in greater depth and determine if the accuracy can be improved.
