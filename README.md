# Breast Cancer Classification and Clustering

## Overview
This project focuses on the classification and clustering of breast cancer data to assist in the diagnosis and treatment of patients. The dataset used for this project is the Breast Cancer dataset from the scikit-learn library. 

## Part I - Application: Load and Overview Data
The application is designed to load the Breast Cancer dataset and provide an overview of its key aspects. These include:
- Number of samples: 569
- Number of dimensions: 30
- Number of classes: 2
- Names of classes: ['malignant' 'benign']
- Number of samples per class: [212 357]

## Part II - Application: Clustering
In this part of the project, we applied clustering methods to partition the Breast Cancer dataset. The following steps were taken:

### Clustering Methods
1. KMeans Clustering
2. AffinityPropagation
3. MeanShift
4. AgglomerativeClustering

### Evaluation
To evaluate the clustering methods, we used appropriate metrics such as the Adjusted Rand index, Homogeneity, Completeness, and V-Measure. The evaluation was performed using the ground truth.

## Part III - Application: Classification: Training and Testing
In this part, we employed classification methods to distinguish between different classes of breast cancer. We utilized the following training and testing protocols:

### Training/Testing Protocols
1. Split the data into training (80%) and testing (20%).
2. K-fold cross-validation for K=10.

### Classification Methods
1. ILinearDiscriminantAnalysis
2. LogisticRegression
3. DecisionTreeClassifier
4. KNeighborsClassifier
5. RandomForestClassifier
6. AdaBoostClassifier
7. GaussianNB()

### Evaluation
For both training/testing protocols, we evaluated the classification approaches using appropriate metrics such as the Balanced Accuracy, F1-Score, and ROC AUC. Additionally, we generated ROC curves for all classification methods and plotted them on a single graph for easy comparison.

## Conclusion
Through this project, we successfully loaded and analyzed the Breast Cancer dataset, applied clustering methods for partitioning, and utilized classification methods for accurate class distinction. By evaluating the results using various metrics and optimizing the parameters, we achieved reliable classification and clustering outcomes, contributing to the diagnosis and treatment of breast cancer. 

## References
- Breast Cancer Dataset: (https://scikit-learn.org/stable/datasets/toy_dataset.html#breast-cancer-dataset)
- Scikit-learn Library: (https://scikit-learn.org)
