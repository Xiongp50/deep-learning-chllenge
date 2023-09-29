# Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images to support your answers, address the following questions:

# Data Preprocessing

What variable(s) are the target(s) for your model?
- The target variable is the 'IS_SUCCESSFUL' column. 
What variable(s) are the features for your model?
- The feature variables consist of all the columns in application_df except for the 'IS_SUCCESSFUL' column, which was excluded by removing it from the original dataframe.
What variable(s) should be removed from the input data because they are neither targets nor features?
- Both the 'EIN' and 'NAME' columns were eliminated since they did not serve as either target or feature variables for the dataset.

# Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
For the initial attempt, I selected 80 hidden nodes for layer 1 and 30 hidden nodes for layer 2 as arbitrary choices.

Were you able to achieve the target model performance?
- I was not able to achieve the 75% model accuracy target

What steps did you take in your attempts to increase model performance?
- In an effort to improve the model's accuracy, I introduced additional layers, excluded more columns, incorporated extra hidden nodes, and altered the activation functions for each layer.

# Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

In summary, the deep learning model achieved approximately 72% accuracy in handling the classification problem. Enhancing prediction accuracy could be attained by improving the correlation between input and output. This might involve more thorough initial data preprocessing and employing a model with different activation functions, followed by iterative refinement until a higher accuracy threshold is reached.