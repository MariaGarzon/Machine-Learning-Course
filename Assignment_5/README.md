## Boosting Decision Trees & Random Forest

### Overview:

In this assignment, we delve deep into tree-based algorithms, one of the foundational techniques in machine learning. Specifically, we focus on Decision Trees, their enhanced version using AdaBoost, and the ensemble-based Random Forests. We make use of the Breast Cancer dataset from UCI to learn, predict, and compare these models.

### Dataset:

The dataset used in this assignment is the Breast Cancer Wisconsin (Diagnostic) dataset, which can be fetched from UCI's Machine Learning Repository.

### Decision Tree 

Data Splitting: Start by dividing the data into a training set (80%) and a test set (20%).

Decision Tree Model: Utilizing Scikit-Learn, we train a Decision Tree Classifier. This model makes use of all the available features in the dataset and is then tested against our reserved test data.

Hyperparameter Tuning: To find the optimal model, a Grid Search is employed over decision tree depths ranging from 1 to 6, and for both Gini Impurity and Entropy impurity measures.

Model Visualization: The best model, as determined by the grid search, is visualized using the plot.tree() method.

Model Boosting: To enhance the Decision Tree, the AdaBoost technique is applied, aiming to increase its accuracy.

Performance Metrics: Finally, the boosted model's accuracy is evaluated on the test data set.

### Random Forest

Reuse of Data: We utilize the same train-test split from Part 2.

Random Forest Model: A RandomForest classifier is trained. 

Parameter Analysis: A comparison is made between the parameters of the Random Forest classifier and the Decision Tree classifier. 
The task is to determine the number of parameters that overlap and those that differ.

Hyperparameter Tuning: Grid Search is employed once more. We search over tree depths (from 1 to 6), both Gini and Entropy impurity measures, and 
ensure to use "out-of-bag" samples for accuracy calculation.

Performance Metrics: The accuracy of the RandomForest model is evaluated on the test set.

Comparative Analysis: A performance comparison is drawn between the Boosted Decision Tree and the Random Forest to determine which model has superior performance.

### Conclusion:

This assignment serves as a comprehensive exercise to understand, implement, and compare tree-based algorithms. 





