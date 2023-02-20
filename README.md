### Assignment Title
Practical Application III: Comparing Classifiers
**Author**

Behailu Desta

#### Executive summary

Overview: In this practical application, your goal is to compare the performance of the classifiers we encountered in this section, namely K Nearest Neighbor, Logistic Regression, Decision Trees, and Support Vector Machines. We will utilize a dataset related to marketing bank products over the telephone.

#### Rationale
Marketing expenditure in the banking industry is massive, meaning that it is essential for banks to optimize marketing strategies and improve effectiveness. Understanding customers’ need leads to more effective marketing plans, smarter product designs and greater customer satisfaction.

#### Research Question
Increase the effectiveness of the bank's telemarketing campaign. This project will enable the bank to develop a more granular understanding of its customer base, predict customers' response to its telemarketing campaign and establish a target customer profile for future marketing plans.

#### Data Sources
What data will you use to answer you question?
Our dataset comes from the UCI Machine Learning repository link. The data is from a Portugese banking institution and is a collection of the results of multiple marketing campaigns. We will make use of the article accompanying the dataset here for more information on the data and features.

#### Methodology
What methods are you using to answer the question?

#### Results
What did your research find?
PCA reduced the number of features needed to train classifiers, reducing the number of non-important features by about 17 (53 to 36 principal components). The percent cumulative variance explanation was 95% with number of principal components at 36.

SVM and Decision Tree Classifier performed the best with the highest f1-scores (see PRC-Figure above and Table with scores). SVM took about 3000 to 67 times longer than the Decision Tree Classifier.

We used the GridsearchCV for the best hyperparameters. These were used with the Decision Tree Classifier to estimate the Gini-feature Importance for the 53 features. We find that the feature importance is the highest for the duration of the phone marketing calls, the number of days previous contact, and age. The months also factor in with March, October and June being most important. This is similar finding with the Moro and Laureano paper.

#### Outline of project

- [Link to notebook 1]()
- [Link to notebook 2]()
- [Link to notebook 3]()


##### Contact and Further Information