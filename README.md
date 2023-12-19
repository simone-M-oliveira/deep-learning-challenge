# deep-learning-challenge

Overview of the analysis:
The objective of this task was to analyze around 34,000 past funding initiatives to discern whether certain project characteristics influence their outcomes, either success or failure. To achieve this goal, I established a set of neural network models to assess the available dataset.

Results:
(AlphabetSoupCharity.h5/AlphabetSoupCharity.ipynb)
This endeavor resulted in a model accuracy of 0.7328.

Model Target?

IS_SUCCESSFUL

Model Features?
APPLICATION_TYPE
AFFILIATION
CLASSIFICATION
USE_CASE
ORGANIZATION
INCOME_AMT
ASK_AMT

Variables Removed?
EIN
NAME
STATUS
SPECIAL_CONSIDERATIONS

Layers/Neurons/Activation Function? Why?

Layers = 3
Neurons = 80/80/80
Activation Function = relu

Achieve 75% Accuracy?

No - 71.22%

Summary
In general, the endeavor achieved an accuracy score exceeding 70%, which is considered good but falls short of being excellent.
