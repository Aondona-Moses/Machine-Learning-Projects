Getting started with machine learning great tool/algorithm to start with is Decision tree and random forest.

Decision tree works by breaking samples/large dataset into smaller nodes/branch which represent a possible decision.

For the Iris dataset I used Decision Tree Classifier which performed well both on training and validation set with accuracy score of a 100%

I didn't have to Encode (converting categorical data into numerical values) the Target variable (Species) since we are using the classifier.

All the parameters of Decision tree were left as default with only the random_state set to be zero.

in a large dataset you will have to fine tune some parameters for a better performance.

Random forest work by creating multiple decision trees, the majority of the trees is chosen.

No tuning was made all parameters were left as default, our model performed well both on training and validation set.

Again, on a large dataset set, parameters like max_leaf_nodes, n_estimators will have to be tuned for better accuracy.

My plans were to either scale values of the features (SepalLenthCm, SepalWidthCm, petalLengthCm, PetalWidthCm down using StandardScalar or Encode the target variable (Species) to numerical values and see how that will increase performance.

You will realize from the scattered plot that we almost had three completely distinct classes especially with Iris-setosa, the other two classes Iris-versicolor and Iris-virginica where a bit mixed at some point but can still be differentiated.
I think that indicate why the model performed so well both on training and validation set and the fact that it's a small dataset, the model can quickly learn and recognize patterns.
