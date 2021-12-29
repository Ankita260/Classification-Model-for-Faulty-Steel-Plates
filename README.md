# Classification-Model-for-Faulty-Steel-Plates

## Abstract
The objective of this project is to analyze the dataset and build a prediction model using various machine learning algorithms to the type of surface defects in stainless steel plates .For this analysis I have applied different classification algorithms such as DecisionTreeClassifier,RandomForestClassifier, AdaBoostClassifier, Neural network model by using keras for the dataset and find the algorithm which fits this dataset. Accuracy is the evaluation measures that is taken to find the performance of the models.

## Introduction
Steel is one of the most essential construction materials in today's world. Steel buildings are resistant to natural and man-made wear, making them commonplace all over the world. Detecting flaws will aid in the more efficient manufacture of steel. The dataset used in this project is taken by from Semeion, research center of sciences of communication and the dataset is a multi-class classification type of dataset. According to the research report, Semeion was commissioned for this assignment by the Centro Sviluppo Materiali (Italy), hence data on the nature of the 27 indicators used as Input vectors or the types of the 6 defect classes are unavailable.

## DataSet 
II.DATASET DESCRIPTION
The semeions, research center of the sciences of communication provides the dataset which consist of total 34 columns and 1941 records. From the 34 columns 27 are considered as input features and 7 are considered as output paramters or defect type features.

## Data Preprocessing
A.Import the useful libraries
This covers not only the Keras functionality we need, but also data loading from pandas, data preparation, and model assessment from scikit-learn.
B.Import the Dataset
Load the dataset b using pandas librarires and then split the data into attributes into input variable and target variable
C. Check the Null values
By using the isna functiom check out the null values in the datset. Luckily there are no nan values in the given dataset
D.Check the datatypes
By using the dtypes function check out the datatypes of each function.
E.Encode the target variable
The target variable contains different values and when utilizing neural networks to represent multi-class classification problems, it's best to reshape the output attribute from a vector containing values for each class value to a matrix containing a boolean for each class value and
whether a specific instance has that class value. This is called one hot encoding

##IV. Classifiers
Classifier algorithm can be used to anticipate and understand what qualities relate to a given class or target by mapping input data to a target variable using decision rules.
A. Decsion Tree Classifier
A decision tree is a tree-like structure in which internal nodes represent attributes, branches represent decision rules, and leaf nodes indicate outcomes. This is accomplished by dividing the data into distinct partitions based on an attribute selection measure, in this case the Gini index.
B. RandomForestClassifier
A random forest is a meta estimator that uses averaging to increase predicted accuracy and control over-fitting by fitting a number of decision tree classifiers on various sub-samples of the dataset.
C. AdaBoostClassifier
An AdaBoost classifier is a meta-estimator that starts by fitting a classifier on the original dataset, then fits further copies of the classifier on the same dataset, but adjusts the weights of poorly classified instances so that future classifiers focus more on difficult cases.
D. Neural network model
In Keras, there is a KerasClassifier class that may be used as an Estimator in scikit-learn, the library's base type of model. As an argument, the KerasClassifier takes the name of a function. This function must return the neural network model that has been built and is ready to be trained.

## Evaluation
A. Test Train Split
Split the dataset into training and testing value 30% for testing and 70% for training
B. Build Model
D. Fit the Model And Run 100 epochs

## Conclusion
I tried using the data in various classification models and found that model constructed with Keras and TensorFlow produced a respectable result for this dataset and should be considered for future modeling endeavors.
