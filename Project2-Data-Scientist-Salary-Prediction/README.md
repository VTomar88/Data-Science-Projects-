t## Data Scientist Salary Prediction

### Author : Varsha Tomar

This project contains a comprehensive analysis of hiring trends and average salaries in the data science field, based on data scraped from the Glassdoor website. The analysis includes data cleaning, exploratory data analysis (EDA), and model building to predict the salary of a data scientist. The goal of this project is to identify key factors that impact salaries and develop a reliable predictive model.

## Abstract
This paper presents a detailed analysis of data scientist salaries based on a dataset of 1000 job postings from Glassdoor. The analysis involves data cleaning, EDA, and model building techniques. The paper aims to uncover trends and factors that influence salaries in the data science field. A predictive model is also built to estimate average salaries for data scientists, providing insights for salary expectations.

## Introduction
The introduction provides an overview of the project, highlighting the importance of data cleaning, EDA, and model building in predicting data scientist salaries. It outlines the steps that will be covered in the paper and the key findings that will be presented.

### Data Retrieval
This section describes the process of scraping job postings for data scientists from the Glassdoor website using a script obtained from a Medium article. It explains that the data was saved in a CSV format and further analysis was performed using Python and Jupyter Notebook.
### Data Cleaning
The data cleaning process is explained in detail, including the handling of numerical and categorical columns. It mentions the conversion of per-hour salaries to per-annum salaries and the removal of outlier rows. The cleaned dataset consists of 742 rows and 15 columns. Additionally, key observations regarding job locations, keyword extraction from job descriptions, and skill requirements are mentioned.
### Exploratory Data Analysis (EDA)
The EDA section explores various aspects of the dataset to gain insights and understand patterns and relationships. It begins by analyzing company ratings, average salaries, and company age using histograms and box plots. The relationships between these variables and other relevant columns are examined. The analysis also includes bar plots for categorical variables such as location, company size, type of ownership, industry, sector, and revenue. Educational requirements and job specialties are also investigated.
### Model Building
The model building section outlines the steps involved in preparing the data, feature engineering, model selection and training, model evaluation, and fine-tuning. It explains the importance of data preparation and feature engineering in improving the model's performance. It mentions the use of techniques like creating dummy variables, linear regression, scaling numerical features, and generating interaction features. Various models such as linear regression, random forest, gradient boosting, and neural networks are discussed, with the random forest model identified as the best performer. The process of model evaluation and fine-tuning is explained, and the final model's parameters and performance metrics are presented.

## Conclusion
The conclusion summarizes the findings of the analysis and highlights the value of the systematic approach followed in this project. It emphasizes the insights gained, the predictive capabilities of the model, and the implications for individuals seeking data science job opportunities. The conclusion also acknowledges the references used in this project for data cleaning, EDA, and model building.

## References
1.	Walker, M. 2020. Python Data Cleaning Cookbook: Modern techniques and Python tools to detect and remove dirty data and extract key insights. Packt Publishing.
2.	Downey, A.B. 2014. Think Stats: Exploratory Data Analysis. O’Reilly.
3.	Albon, C. 2018. Python Machine Learning Cookbook: Practical solutions from preprocessing to deep learning. O’Reilly.
4.	Sakarya, O. 2019. Selenium Tutorial: Scraping Glassdoor.com in 10 minutes. https://mersakarya.medium.com/selenium-tutorial-scraping-glassdoor-com-in-10-minutes-3d0915c6d905
5.	Glassdoor.com https://www.glassdoor.com/Job/us-data-scientist-jobs-SRCH_IL.0,2_IN1_KO3,17.htm?locKeyword=United%2520States&srs=RECENT_SEARCHES
