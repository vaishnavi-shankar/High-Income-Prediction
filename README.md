# High-Income-Prediction
## About the data 
The dataset has a total of 23,000 rows, each of which contains details 
about one specific consumer. Information about whether or not a consumer has a high income has 
been provided to you for 20,000 of the cases, while this information has not been provided for the 
remaining 3,000 cases.The 20,000 rows for which we have complete 
information to train and test a variety of machine learning models. Once we have identified your 
final, best-performing model, we  will then use that model to predict whether or not the remaining 
3,000 consumers can be classified as high income. 

 The columns contained in the dataset are: 
 
• id – A unique identifier for each consumer. 

• age – The consumer’s age (in years). 

• employer_type – A textual label describing the type of employer for which the consumer 
works (non_government, government_federal, etc.). 

• highest_education_completed – A textual label describing the highest level of education that 
the consumer has attained (bachelors_degree, high_school, etc.). 

• marital_status – A textual label describing the consumer’s marital status (married, divorced, 
etc.). 

• occupation_code – A numeric code representing the category of the consumer’s occupation. 

• race_code – A numeric code indicating the consumer’s self-reported race. 

• gender – A numeric code indicating the consumer’s self-reported gender. 

• capital_gains – The amount (in dollars) of capital gains that the consumer reported on their 
taxes during the previous year. 

• capital_losses – The amount (in dollars) of capital losses that the consumer reported on their 
taxes during the previous year. 

• hours_worked_per_week – The average numer of hours that the consumer works each week. 

• native_country_code – A numeric code indicating the consumer’s native country. 

• salary_greater_than_100k – A numeric code indicating whether or not the consumer earns 
more than $100,000 per year 

## Steps followed##
## Importing the pandas library
## Data Exploration
## Imputation
## Data preprocessing - Log transformation and MinMaxScaler
## Correlation heatmap to find best features
## Spiltting into Train and Test data
## classification models 
***Logistic - Accuracy : 86%***

***Decision tree - Accuracy: 84%***

***K- nearest neighbhour - Accuracy:***

***Gausian NB - Accuracy : 86%***

***Adaboost with Gausian NB - Accuracy :87.5%***

***Support Vector Machine - Accuracy : 81%***

## Prediction 
