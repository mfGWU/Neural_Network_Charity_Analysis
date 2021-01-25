# Neural_Network_Charity_Analysis
Create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

# Overview of the analysis: 
The purpose of this analysis is to leverage neural network using the features in the provided dataset to create binary classifier.  The binary classifier will be capable of predicting whether applicants will be successfully if funded by Alphabet Soup.

# Results: 
### Data Preprocessing
+ What variable(s) are considered the target(s) for your model? In this analysis, IS_SUCCESSFUL variable was the target.
+ What variable(s) are considered to be the features for your model? APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT—Income, SPECIAL_CONSIDERATIONS, ASK_AMT were the features used in the model.
+ What variable(s) are neither targets nor features, and should be removed from the input data? EIN and NAME were neither targets nor features, and should be removed from the input data.
### Compiling, Training, and Evaluating the Model
+ How many neurons, layers, and activation functions did you select for your neural network model, and why?  
+ Were you able to achieve the target model performance?  With 72.3% accuracy, I missed the target model performance by 3.0%.
+ What steps did you take to try and increase model performance?  I increase the hidden_nodes_layer1 by 20 from 80 and increase the  hidden_nodes_layer2 = 30 by 20 as well.

# Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.

