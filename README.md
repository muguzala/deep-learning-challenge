# deep-learning-challenge
Overview of the analysis: Explain the purpose of this analysis.

Answer: The purpose of the analysis was to predicit if a charity was successful or not

Results: Using bulleted lists and images to support your answers, address the following questions:

Data Preprocessing

What variable(s) are the target(s) for your model?
Answer: IS_SUCCESSFUL was used as the target variable.

What variable(s) are the features for your model?
Answer: 

Following features were used for the base line model (AlphabetSoupCharity):

APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT

What variable(s) should be removed from the input data because they are neither targets nor features?
Answer: EIN and NAME

How many neurons, layers, and activation functions did you select for your neural network model, and why?

Answer:

For the baseline model:

Hidden Layers: 2
Hidden Nodes layer 1: 80
Hidden Nodes layer 2: 30

Hidden layer activation function: ReLu
Output layer activation function: Sigmoid


Were you able to achieve the target model performance?

Answer: I was not able t achieve target performance.

Baseline Accuracy: 72.5
Optimization Attempt 1: 73.2
Optimization Attempt 2: 72.9
Optimization Attempt 3: 72.6


What steps did you take in your attempts to increase model performance?
Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
Depending on system resources, we cold have one hot encoded the NAME column, maybe that would have increased the accuracy