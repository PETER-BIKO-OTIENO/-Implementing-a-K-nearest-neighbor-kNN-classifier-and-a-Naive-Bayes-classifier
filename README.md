
This project requires us to implement a K-nearest neighbor (kNN) classifier and a Naive Bayes classifier. Once we conduct the experiments, we will calculate the resulting metrics:

Download the two datasets from the given links:

Dataset 1 Source:

[Train Dataset Source: Link (https://archive.org/download/train5_202002/train%20%285%29.csv),

Test Dataset Source: Link (https://archive.org/download/test1_202002/test%20%281%29.csv)]

Dataset 2 Source:

[Link (https://archive.ics.uci.edu/ml/datasets/Spambase)]


Experimental Procedure:

Randomly partition each dataset into two parts i.e 80 - 20 sets.

For dataset 1, because we don't have the label for the test set, we will use the train set to create train and test data (i.e. splitting further), then perform K-nearest neighbor classification.

For dataset 2, perform classification of the testing set samples using the Naive Bayes Classifier.

Compute the accuracy (percentage of correct classification).

Report the confusion matrix of each classifier.

Repeat step 1 to step 3 twice, each time splitting the datasets differently i.e. 70-30, 60-40, then note the outcomes of your modeling.

Suggest and apply at least one of the optimization techniques that you learned earlier this week.

Provide further recommendations to improve both classifiers.

Create a notebook for each project.
