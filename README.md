# Data-Cleaning

Dirty data can appear because of duplicate values, mis-spellings and wrong labels, data-type parsing errors or incorrect data. Most data professionals do data cleaning 20-60% of the time, this is one of the major skills to have as a data professional.  
Each datatype has its unique format and incorrect datatype labelling can result in wrong information on charts and visualizations, bad prediction, mis-information and mis-leadings.                                                                                       
Datatypes with Examples 
1. Text data - First name, last name, address, product name
2. Categories - Marriage status, gender
3. Decimals - Temperature, Exchange rate
4. Integers - Subscribers, products sold
5. Dates - Order date, shipping date, birth date
6. Binary -yes/no, true/false, is_married. It is extremely important ensure that variables have the correct datatype. 
Common issues that require cleansing in a datasets include; Data type constraint, numerical/text or categorical features, data range constraints, unique constraints, inconsistency in capitalization, membership constraints, trailing space, phone number column...


The data cleaning cycle involves importing dataset, merging datasets, identifying missing values, dropping or filling in missing values, renaming or throwing out unnecessary columns  taking out duplicates,purging contaminated data and correcting leaking pipelines, fixing string and datetime issues, removing duplicates or analyzing them separetly, standardizing and normalizing, verifying data adequacy and other added processes according to the data science issue at hand. 


This data cleaning project will be written in Python using the Pandas, Numpy and Matplotlib libraries as well as using Google Colab as IDE.

**Data cleaning process;** 

1)Importing the Dataset; downloaded my dataset for the data cleaning project from Kaggle.com (https://www.kaggle.com/imdevskp/cholera-dataset). I have always been interested in Health Analytics and working on this dataset is an opportunity for me to work on something I enjoy. 

2)Summarizing the first and last 5 rows of my data to get a view of what my table looks like. 

3)Checking dtype of the columns available in the dataset to for further reference in processes

4)Generating the shape and info of the dataset to know the total number of columns and rows available in the dataset. 

5)Renaming some of the columns for easy access during further processing.

6)Using isnull().sum() to generate the total number of nulls in each column and filling these null values with 0

7)Removed whitespaces from the dataset and replaced the unknown values with 0

8)Checked for incorrect spellings in the Country and WHO Region column. 
