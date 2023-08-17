# K-Nearest-Neighbors-KNN-
KNN is a simple supervised machine learning algorithm used for classification and regression tasks. It predicts the label of a data point based on the majority class of its k nearest neighbors.

K-Nearest Neighbors (KNN):
Here is step by step on how to compute K-nearest neighbors KNN algorithm:
1. Determine parameter K = number of nearest neighbors
2. Calculate the distance between the query-instance and all the training samples
3. Sort the distance and determine nearest neighbors based on the K-th minimum distance
4. Gather the category of the nearest neighbors
5. Use simple majority of the category of nearest neighbors as the prediction value of the
query instance

Here's a step-by-step guide to achieving the tasks you've mentioned:
1. Load and Plot Training Data:

Read data from "train.txt".
Plot training points with different colored markers based on the assigned class label.

2. Implement KNN Algorithm:

Implement the KNN algorithm with user-defined K.
Classify the test points from "test.txt".
Plot the test points with different colored markers based on the predicted class label.

3. Write Predictions to "prediction.txt":

For each test data point, calculate distances and store the top K distances along with their class labels.
Write the predictions to "prediction.txt" as described.
