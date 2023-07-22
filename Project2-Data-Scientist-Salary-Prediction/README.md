## Data Scientist Salary Prediction

### Author : Varsha Tomar

## Abstract
This project comprehensively analyzes hiring trends and average salaries in the data science field based on 1000 job postings from the Glassdoor website. The analysis includes data cleaning, exploratory data analysis (EDA), and model building to predict the salary of a data scientist. This project aims to identify key factors that impact salaries and develop a reliable predictive model. The dataset includes information on job titles, average salaries, job descriptions, company details, and other relevant variables. The project aims to identify key observations, trends, and factors that impact salaries in the data science field. Furthermore, a predictive model is built to estimate average salaries for data scientists, with a practical example showcasing the prediction of the author's salary after completing an M.S. in Data Science.

## Introduction
This project delves into the process of data cleaning, exploratory data analysis (EDA), and model building to predict the salary of a data scientist. The analysis is based on a dataset containing information about various job postings for data scientists. Each step of the process is detailed, presenting the key findings and insights obtained from the analysis.

### Data Retrieval
The dataset used in this project was obtained by scraping job postings for data scientists from the Glassdoor website. The data was saved in CSV format as "glassdoor_jobs.csv." The subsequent data cleaning, EDA, and model building were performed in Python using Jupyter Notebook and relevant data-related libraries.

### Data Cleaning
The first step in the analysis is data cleaning. The dataset contains both numerical and categorical columns. There are 2 numerical and 12 categorical columns. To ensure consistency, the salaries listed on an hourly basis were converted to an annual basis. Outliers (values of -1) in the 'Salary Estimate' column were removed to train the salary prediction model. After cleaning, the processed data-frame consists of 742 rows and 15 columns.

During the data cleaning process, it was observed that California (CA), Massachusetts (MA), and New York (NY) have the highest number of data scientist job listings on Glassdoor. Additionally, specific keywords from job descriptions, such as 'Python', 'Power BI', 'Tableau', 'MATLAB', 'R Studio', 'Spark', and 'AWS', were extracted to determine the frequency of their mentions in the job postings. The analysis revealed that 'Python' and 'Excel' are highly sought-after skills in data scientist job descriptions, while 'R Studio' is relatively less in demand. Furthermore, 85 job descriptions require citizenship requirements.

### Exploratory Data Analysis (EDA)
After data cleaning, the next step is exploratory data analysis (EDA) to gain insights and understand patterns and relationships within the dataset. EDA involves examining various aspects of the data, including company ratings, average salaries, company age, and relationships between relevant columns.

Company ratings follow a normal distribution, with most companies having ratings above average. Average salaries for data scientists are right-skewed, indicating a higher concentration of salaries in the lower range. The dataset predominantly consists of relatively new companies (ages ranging from 0 to 25 years), with a few outliers surpassing 250 years.

EDA also explores the relationships between various columns. Company age is found to be strongly related to both job description length and the number of competitors. Additionally, average salary is related to both job description length and the number of competitors.

Further analysis involves examining categorical columns, including location, company name, type of ownership, industry, sector, and revenue. The distribution and trends within these categories are visualized, with a focus on the top 10 values for certain columns due to the large number of unique values.

The EDA also covers educational requirements for data scientist positions, identifying the top job titles for data scientists, and analyzing the frequency of specific skills mentioned in job descriptions.

### Model Building
Following data cleaning and EDA, the next step is model building to predict the salary of a data scientist based on various features. The model building process involves several steps:

- **Data Preparation**: Encode categorical variables and split the dataset into training and testing sets.
- **Feature Engineering**: Create dummy variables for categorical features and scale numerical features to a standard range.
- **Model Selection and Training**: Choose an appropriate model and train it on the training set.
- **Model Evaluation**: Evaluate the model's performance using the testing set and relevant evaluation metrics.
- **Model Fine-Tuning**: Fine-tune the model to improve its accuracy and predictions.
- **Final Model Deployment**: Deploy the fine-tuned model for salary predictions.
  
The Random Forest model, with optimized parameters, was found to be the best performer for salary prediction, achieving an R-squared value of 0.77.

## Conclusion
In conclusion, this project provides valuable insights into hiring trends and average salaries in the data science field. The systematic approach of data cleaning, exploratory data analysis, and model building yielded an accurate predictive model for salary estimation. The model can help individuals make informed decisions about job opportunities and have realistic salary expectations in the data science domain.

## References
1.	Walker, M. 2020. Python Data Cleaning Cookbook: Modern techniques and Python tools to detect and remove dirty data and extract key insights. Packt Publishing.
2.	Downey, A.B. 2014. Think Stats: Exploratory Data Analysis. O’Reilly.
3.	Albon, C. 2018. Python Machine Learning Cookbook: Practical solutions from preprocessing to deep learning. O’Reilly.
4.	Sakarya, O. 2019. Selenium Tutorial: Scraping Glassdoor.com in 10 minutes. https://mersakarya.medium.com/selenium-tutorial-scraping-glassdoor-com-in-10-minutes-3d0915c6d905
5.	Glassdoor.com https://www.glassdoor.com/Job/us-data-scientist-jobs-SRCH_IL.0,2_IN1_KO3,17.htm?locKeyword=United%2520States&srs=RECENT_SEARCHES
