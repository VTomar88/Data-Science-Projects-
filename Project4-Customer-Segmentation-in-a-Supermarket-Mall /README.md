## Customer Segmentation in a Supermarket Mall using Unsupervised Machine Learning Techniques

### Abstract
This project focuses on customer segmentation within a supermarket mall using unsupervised machine learning techniques. The goal is to identify distinct customer groups based on demographic attributes and spending behavior. The project employs unsupervised machine learning algorithms, specifically K-means and Density-Based Clustering (DBSCAN), to achieve this segmentation. The dataset used for analysis was obtained from Kaggle and contains customer information such as age, gender, annual income, and spending score. The project involves exploratory data analysis, feature engineering, and cluster analysis to reveal valuable insights about customer behavior and preferences.

### Table of Contents
1. Introduction
2. Business Problem
3. Dataset
4. Methods
5. Results and Discussion
  - Detailed Information on the Dataset
   - Exploratory Data Analysis
    - Feature Engineering
     - Unsupervised Modeling - K-means
      - Unsupervised Modeling - Density-Based Clustering (DBSCAN)
6. Ethical Considerations
7. Challenges
8. References

### Introduction
This project aims to leverage unsupervised machine learning techniques to perform customer segmentation within a supermarket mall. By analyzing customer data using unsupervised machine learning algorithms, we aim to group customers based on their demographic attributes and spending patterns. The results of this segmentation can provide valuable insights for targeted marketing and business strategy development.

### Business Problem
Understanding the customer base is crucial for effective marketing campaigns. Customer segmentation allows us to identify specific groups with distinct preferences and behaviors, enabling the marketing team to tailor strategies that resonate with each segment. This project addresses the challenge of segmenting customers based on their demographic information and spending behavior.

### Dataset
The dataset used for this project was obtained from Kaggle and includes the following attributes:

CustomerID: Unique ID assigned to the customer.
Gender: Male or Female customer.
Age: Age of the customer.
Annual Income (k$): Annual Income of the customer.
Spending Score (1-100): Score assigned by the mall based on customer behavior and spending nature.

### Methods
The project employs the following methods:

Exploratory Data Analysis: Understanding the data distribution, identifying missing values, and gaining insights into customer demographics and spending behavior.

Feature Engineering: Converting categorical data to numerical format and identifying correlations among variables to prepare the data for modeling.

Unsupervised Modeling:

K-means: Clustering customers based on annual income and spending score to identify distinct segments.
Density-Based Clustering (DBSCAN): Utilizing DBSCAN to cluster customers based on density patterns in the data.

### Results and Discussion

 #### Detailed Information on the Dataset
The dataset contains 200 rows and 5 columns. It includes attributes such as age, gender, annual income, and spending score. Exploratory data analysis revealed valuable insights into the dataset's characteristics, including customer age distribution, income levels, and spending patterns.

 #### Exploratory Data Analysis
Histogram plots of age, annual income, and spending score provided a visual understanding of customer demographics and behavior. Analysis of gender distribution indicated a higher number of female customers.

#### Feature Engineering
Feature engineering involved converting the categorical "Gender" column to numerical format. Correlation analysis helped identify relevant features for modeling. Customer ID, having a high correlation with annual income, was removed, resulting in a less correlated dataset.

 #### Unsupervised Modeling - K-means
K-means clustering identified five customer clusters representing different spending behaviors: financially conservative, balanced, high-end shoppers, impulsive buyers, and frugal spenders.

 #### Unsupervised Modeling - Density-Based Clustering (DBSCAN)
DBSCAN clustering revealed challenges due to weak density patterns and a small number of outliers in the dataset. The clustering performance was moderate, indicating potential difficulties in forming distinct clusters.

### Ethical Considerations
Protecting customer privacy and adhering to data protection regulations are essential. Measures will be taken to ensure data anonymization and aggregation to prevent individual identification.

### Challenges
Ensuring comprehensive and accurate dataset.
Selecting relevant features for segmentation.
Interpreting and deriving insights from clustering results.
Evaluating algorithm performance and parameter selection.

### References
1.	Celebi, E.M. and Aydin, K. 2016. Unsupervised Learning Algorithms. Springer.
2.	Patel, A. 2019. Hands-On Unsupervised Learning Using Python: How to build Applied Machine Learning Solutions from Unlabeled data. 1st Edition. O’Reilly Media.
3.	Walker, M. 2020. Python Data Cleaning Cookbook: Modern techniques and Python tools to detect and remove dirty data and extract key insights. Packt Publishing.
4.	Kaggle. Mall Customer Segmentation Data. [](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

