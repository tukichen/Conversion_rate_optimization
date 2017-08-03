# Conversion Rate Optimization using Classification Model

The data revolution enable us to collect all sorts of data about customers who purchase on a website as well as potential customers who had not yet purchase. These data can reveal insights on what's working well (and potentially scale it even further) and what's not working well (and fix it).

The goal of this project is to build a model that predicts conversion rate and, based on the model, come up with ideas to improve revenue.


## Goal
* Predict conversion rate
* Come up with recommendations for the product team and the marketing team to improve conversion rate


## Description of data
Website users information: 
* Whether they converted or not ; 
* User characteristics: Country; The marketing channel; Age; Repeat users or not; The number of pages visited during that session (as a proxy for site activity/time spent on site).

### Columns:
* country : user country based on the IP address
* age : user age. Self-reported at sign-in step
* new_user : whether the user created the account during this session or had already an account and simply came back to the site
* source : marketing channel source
* Ads: came to the site by clicking on an advertisement
* Seo: came to the site by clicking on search results
* Direct: came to the site by directly typing the URL on the browser
* total_pages_visited: number of total pages visited during the session. This is a proxy for time spent on site and engagement during the session.
* converted: this is our label. 1 means they converted within the session, 0 means they left without buying anything. The company goal is to increase conversion rate: # conversions / total sessions.


## 1. Exploratory Data Analysis and Feature Generation 
### 1.1 Read data from csv file
### 1.2 Data cleaning
### 1.3 Exploratory analysis
### 1.3.1 Histogram of numeric variables
### 1.3.2 Frequency table of categorical features by Converted
### 1.4 Build a python class for feature generation 
## 2. Build models to predict whether a user will convert.
### 2.1 Split data into training set and test set
### 2.2 Fit different classifiers to training data and plot ROC curve using test data
### 2.3 Fit the final model using all data
## 3. Recommendations for the product team and the marketing team
