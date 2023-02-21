### Assignment Title
Practical Application III: Comparing Classifiers

The Goal is to compare the performance of the classifiers we encountered in this section, namely K Nearest Neighbor, Logistic Regression, Decision Trees, and Support Vector Machines. 

**Author**
Behailu Desta

#### Executive summary

Overview: In this practical application, your goal is to compare the performance of the classifiers we encountered in this section, namely K Nearest Neighbor, Logistic Regression, Decision Trees, and Support Vector Machines. We will utilize a dataset related to marketing bank products over the telephone.

The Bank of Portugal is seeking to develop a model capable of forecasting which potential customers will sign up for their term deposit service. By implementing a successful predictive model, they aim to improve the efficiency of their marketing campaigns by targeting individuals who are more likely to subscribe to their service. This will enable them to allocate their resources more effectively. The dataset under consideration pertains to the direct phone marketing campaigns conducted by a Portuguese bank between May 2008 and November 2010, which were designed to encourage existing customers to opt for their term deposit service.

#### Rationale
Marketing expenditure in the banking industry is massive, meaning that it is essential for banks to optimize marketing strategies and improve effectiveness. Understanding customers’ need leads to more effective marketing plans, smarter product designs and greater customer satisfaction.

Background: In the present time, the banking industry is spending a significant amount of money on marketing. As a result, it is crucial for banks to enhance the efficiency of their marketing strategies. By gaining an understanding of the customers' requirements, banks can develop more effective marketing plans and create smarter product designs, which ultimately leads to greater customer satisfaction.

Through the examination of customer characteristics, such as demographic information and past transactions, the bank can anticipate the saving habits of its customers and pinpoint the group of customers who are more inclined to make term deposits. By targeting these customers, the bank can allocate its marketing resources more efficiently, resulting in a more effective deposit acquisition strategy. Additionally, this approach can lead to improved customer satisfaction as it reduces the frequency of irrelevant advertisements for certain customers.

#### Research Question
Increase the effectiveness of the bank's telemarketing campaign. This project will enable the bank to develop a more granular understanding of its customer base, predict customers' response to its telemarketing campaign and establish a target customer profile for future marketing plans.

The aim of this project is to enhance the efficiency of the bank's telemarketing campaign. This can be achieved by gaining a more detailed understanding of the bank's customer base, predicting the customers' reactions to the telemarketing campaign, and identifying a target customer profile that can be used for future marketing strategies.

#### Data Sources

Our dataset comes from the UCI Machine Learning repository link. The data is from a Portugese banking institution and is a collection of the results of multiple marketing campaigns. We will make use of the article accompanying the dataset here for more information on the data and features.

#### Methodology
we have used the four common classification models namely, 
- K Nearest Neighbor.
- Logistic Regression.
- Decision Trees.
- Support Vector Machines.

prior to using the classification models we have cleaned  the 

![plot](./image/pca.jpg)

#### Results/Findings

PCA reduced the number of features needed to train classifiers, reducing the number of non-important features by about 17 (53 to 36 principal components). The percent cumulative variance explanation was 95% with number of principal components at 36.

SVM and Decision Tree Classifier performed the best with the highest f1-scores (see PRC-Figure above and Table with scores). SVM took about 3000 to 67 times longer than the Decision Tree Classifier.

We used the GridsearchCV for the best hyperparameters. These were used with the Decision Tree Classifier to estimate the Gini-feature Importance for the 53 features. We find that the feature importance is the highest for the duration of the phone marketing calls, the number of days previous contact, and age. The months also factor in with March, October and June being most important. This is similar finding with the Moro and Laureano paper.

#### Outline of project

- [Link to notebook 1](www.google.com)
- [Link to notebook 2]()
- [Link to notebook 3]()


