# deep_learning_challenge

Overview of the analysis: Explain the purpose of this analysis.
This analysis attempts to build and train a predictive model for charity funding cases. The model is trained on metrics available in the data set such as funding amount, organization information and application type. The target metric for this model is predicting the "IS_SUCCESSFUL" metric as a 0 or 1 to indicate outcome. 


Results: Using bulleted lists and images to support your answers, address the following questions:

Data Preprocessing

What variable(s) are the target(s) for your model?
Target variable is the "IS_SUCCESSFUL" column.
This target is consistent across all versions.

What variable(s) are the features for your model?
Features are all other columns in the data set, with the exception of identifying columns like "NAME" and "EID"

What variable(s) should be removed from the input data because they are neither targets nor features?
Variables were removed as features in some versions of the model. "SPECIAL_CONSIDERATIONS" and "AFFILIATION" are some variables removed in certain versions of the model in an attempt to optimize by reducing confusion by unhelpful metrics.

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?bn

Model 01:


Were you able to achieve the target model performance?
What steps did you take in your attempts to increase model performance?
Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
