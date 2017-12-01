# Healthifyme Assignment

## Problem 1: Word Polysemy Detection
The proposed approach for this problem is described in the document "polysemy-detection" 
## Problem 2: Message Classification
To solved this problem I used supervised classification approach. Following are the steps
- Target messages classes were not very clear and complete. So, first I determined a set of closed classes for the output message categories. The classes are {diet related, workout related, fitness expert related, plan and subscription related, fitness concern and queries, generic statement}
- Training data creation: Tagged the 300 messages with target class.
- Building the model: Used SGD classifer for building the message classification model. Details of the model building steps are described in jupyter notebook.
- Testing and model evaluation: Used 80:20 random splitting for training and test data creation. To evaluate the model performance I calculated precision, recall and f-measure. The overall model performance and the class level accuracy of the model (confision matrix) are given in the notebook.