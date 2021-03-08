# Curneu-Assessment: KNN Classifier
Scatter plots are plotted for the four variables.
Then the data is splitted into test data and training data.
Confusion matrix is generated an also the classification report.
Applying the KNN Classifier, the graph has between for k value and error rate

#Curneu Assessment- Random Forest Classifier
Import the dataset.
split the independent and dependent variables in an array.
split the data into test and training dataset.
Implement ID3 algorithm to generate the decision tree.
Calculate the entropy of the total dataset
Calculate the values and the corresponding counts for the split attribute 
Calculate the weighted entropy
Calculate the information gain
Define the stopping criteria 
If all target_values have the same value, return this value
If the dataset is empty, return the mode target feature value in the original dataset
If none of the above holds true, grow the tree!
Set the default value for this node --> The mode target feature value of the current node
Select the feature which best splits the dataset
Create the tree structure. The root gets the name of the feature (best_feature) with the maximum information
Remove the feature with the best inforamtion gain from the feature space
Grow a branch under the root node for each possible value of the root node feature
Split the dataset along the value of the feature with the largest information gain and therwith create sub_datasets
Call the ID3 algorithm for each of those sub_datasets with the new parameters and do it recursively.
Add the sub tree, grown from the sub_dataset to the tree under the root node
Finally train the random forest model.
Plot the random classification model for the training and test dataset.
