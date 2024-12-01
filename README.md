**# email-ctr-rate-prediction**
--------------------------------
The goal of this project is to maximize the Click Through Rate (CTR) of emails for clients. Email communication is one of the popular ways for companies pitch products to their users and build trustworthy relationships with them.


**------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------**
**PROJECT SPECIFICS**
**----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------**

**Problem Statement:**
--------------------------------
To build a machine learning-based approach to predict the CTR of an email campaign.

**Information on Dataset:**
--------------------------------
The data holds information of past email campaigns containing the email attributes like subject and body length, no. of CTA, date and time of an email, type of the audience, whether its a personalized email or not, etc and the target variable indicating the CTR of the email campaign.

**Data Dictionary:**
--------------------------------
Data for the project is taken from kaggle and contains 3 files - train.csv, test.csv and data_to_test.csv

**Train and Test Set:**
--------------------------------
Train and Test set contains different sets of email campaigns containing information about the email campaign. Train set includes the target variable click_rate and you need to predict the click_rate of an email campaign in the test set.

**Dataset Variable Description:**
--------------------------------
campaign_id - Unique identifier of a campaign

sender - Sender of an e-mail

subject_len - No. of characters in a subject

body_len - No. of characters in an email body

mean_paragraph_len - Average no. of characters in paragraph of an email

day_of_week - Day on which email is sent

is_weekend - Boolean flag indicating if an email is sent on weekend or not

times_of_day - Times of day when email is sent: Morning, Noon, Evening

category - Category of the product an email is related to

product - Type of the product an email is related to

no_of_CTA - No. of Call To Actions in an email

mean_CTA_len - Average no. of characters in a CTA

is_image - No. of images in an email

is_personalised - Boolean flag indicating if an email is personalized to the user or not

is_quote - No. of quotes in an email

is_timer - Boolean flag indicating if an email contains a timer or not

is_emoticons - No. of emoticons in an email

is_discount - Boolean flag indicating if an email contains a discount or not

is_price - Boolean flag indicating if an email contains price or not

is_urgency - Boolean flag indicating if an email contains urgency or not

target_audience - Cluster label of the target audience

click_rate (Target Variable) - Click rate of an email campaign

**--------------------------------**

**------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------**
**__MODEL TESTING__**
**----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------**

**Evaluation File Format:**
--------------------------------
data_to_test.csv contains 2 variables - campaign id and click_rate

**Variable - Description:**
--------------------------------
campaign_id - Unique Identifier of a campaign id
click_rate (Target Variable) - Click rate of an email campaign

**Evaluation metric:**
--------------------------------
The evaluation metric for this project would be r2_score.

**Data Split:**
Test data is further divided into Public (40%) and Private (60%) data. Public data is generic data that attract customers based on interests and offers. Private data is sourced from companies targetting customers for particular product. This split between the two, trains the model for world scenarios and can be later enhanced using advance ML models. 
