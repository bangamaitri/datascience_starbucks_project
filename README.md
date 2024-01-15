## Udacity Data Scientist Nanodegree Starbucks Project: Analysing the Impact of Demographic Features on Offer Completion in Starbucks Rewards Program

### Project Overview

The dataset contains simulated data that mimics customer behaviour on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free).

### Motivation for the Project
This project is the final capstone project of the Udacity Data Scientist Nanodegree Program.

The goal of this project is to build a machine-learning model to predict whether a customer would complete an offer provided by the Starbucks rewards program. The primary expectation is to assess the influence of demographic factors such as age, gender and income on the likelihood of a customer completing an offer.

### Approach

Data Preprocessing: Handling missing values, encoding categorical variables, and feature engineering.
Exploratory Data Analysis (EDA): Analyzing patterns, distributions, and relationships within the data to gain insights.
Model Development: Constructed a machine learning model, considering feature importance and prediction accuracy.
Evaluation: Utilized metrics such as F1 score to assess the model's performance.

### Libraries Used

- numpy and pandas for data analysis
- math and json
- matplotlib and seaborn for data visualisation
- sklearn for machine learning models implementation

### About the Files

data -- folder consisting of the three data files - profile.json, portfolio.json and transcript.json
**portfolio.json** - containing offer ids and meta data about each offer (duration, type, etc.)
**profile.json** - demographic data for each customer
**transcript.json** - records for transactions, offers received, offers viewed, and offers completed

Starbucks_Offer_Analysis -- Notebook where all the processes mentioned above have been implented.

### Summary of the Analysis

The following are the outcome of our analysis - 

- Majority of the customers using the starbucks app lie in the age group of 45 to 65 and the income of most of the customers lies between 55k to 75k.
- More males are using the app, but the average spending of females is more.
- Most customers joined in 2017 and then in 2018. There are more male customers joining the program every year.
- 75 % of the offers were viewed out of the total offers received, and 48.8 % of the offers were completed out of the total offers received.
- Male and Female almost equally complete the offer. So offers should be sent equally among them.
- Customers having income range 50k to 80k are completing the most offers and more offers (BOGO and Discount) should be sent to them. 
- The customers between the age of 50-70 are the most active in completing the offers

The Gradient Boosting algorithm achieved the highest F1 score followed by Decision Tree and then Ada Boost.

Overall, considering the trade-offs between runtime and performance, the Gradient Boost Classifier appears to be the most promising choice for this dataset.

### Acknowledgemts 

I would like to thank Udacity and Starbucks for providing an amazing learning experience. The knowledge and skills acquired during the project have been substantial towards developing my understanding of data science.




