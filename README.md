# Shivam_Kannoujia_Propensify

# Propensify - Model to identify how likely certain target groups customers respond to the marketing campaign
## Introduction:

Are you aware of what, when, and why your customers will make a purchase? Many businesses undertake an intense pursuit to discover these answers, dedicating valuable resources to data-driven campaigns and high-cost strategies - yet the actual outcomes often remain elusive and disappointing.
Customer information is considered to be a valuable asset, however its true worth can only be established when it is used. Many companies have large collections of data that appear to be impressive, but upon further examination, they may contain outdated or unimportant information. 
Propensity modeling is a method that aims to forecast the chance that individuals, leads, and customers will engage in specific actions. This method uses statistical analysis which takes into account all the independent and confounding factors that impact customer behavior.
As a Data Scientist, one’s company is commissioned by an insurance company to develop a tool to optimize their marketing efforts.
This project is aimed at building a propensity model to identify potential customers.

## Data:

The project uses a dataset containing customer information such as age, profession, marital status, education, and previous marketing campaign interactions. The data includes both numerical and categorical variables and is used to train and test the propensity model.
- **train.xlsx** - This excel file contains the historical data provided by the insurance company. It includes features of customer demographics, their past interactions and whether or not each customer ultimately purchased insurance. 
- **test.xlsx** - It is a data containing a list of potential customers to whom to the model will be applied to make predictions. 

## Project assets:

1.	Propensify – Machine Learning Model.ipynb – This python notebook is containing the source code of this project which contains all the methodologies applied in this model building.
2.	Propensify – Machine Learning Model.pdf - A report (PDF) detailing description of design choices and Performance evaluation of the model and discussion of future work.

## Methodology:

The following recommendation of the steps that should be employed towards attempting to solve this problem statement: 
-	**Exploratory Data Analysis:** Analyze and understand the data to identify patterns, relationships, and trends in the data by using Descriptive Statistics and Visualizations. 
-	**Data Cleaning:** This might include standardization, handling the missing values and outliers in the data. 
-	**Dealing with Imbalanced data:** This data set is highly imbalanced. The data should be balanced using the appropriate methods before moving onto model building.
-	**Feature Engineering:** Create new features or transform the existing features for better performance of the ML Models. 
-	**Model Selection:** Choose the most appropriate model that can be used for this 
-	**Model Training:** Split the data into train & test sets and use the train set to estimate the best model parameters. 
-	**Model Validation:** Evaluate the performance of the model on data that was not used during the training process. The goal is to estimate the model's ability to generalize to new, unseen data and to identify any issues with the model, such as overfitting. 
-	**Model Deployment:** Model deployment is the process of making a trained machine learning model available for use in a production environment.

## Conclusion:

The Propensify project demonstrates a comprehensive approach to predicting customer behavior with accuracy of 90.35%. These insights can drive more effective marketing strategies and enhance customer engagement, contributing positively to business outcomes. Future work could explore additional model improvements and the integration of newer, more diverse data sources to refine predictions further.

## Requirements:

-	Python
-	Numpy
-	Pandas
-	Scikit-learn
-	Matplotlib
-	Seaborn
-	Sweetviz
-	Joblib

## Contributor:
*Shivam Kannoujia* (shivamkannoujia007@gmail.com)



