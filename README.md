. Introduction (1 minute)

Hello everyone, my name is [Your Name].
In this project, I worked on Customer Satisfaction Score Prediction for an E-commerce Customer Support System.

When customers contact support through chat, call, or email, they give a CSAT score, which means Customer Satisfaction Score.
The goal of this project is to predict how satisfied a customer will be based on different factors such as product category, handling time, support channel, and customer remarks.

This is important because companies want to identify dissatisfied customers early and improve their service.

2. Dataset Explanation (1 minute)

The dataset used in this project contains information about customer support interactions in an e-commerce platform.

Some important features in the dataset are:

channel_name – how the customer contacted support (call, chat, email)

category and sub-category – type of problem the customer faced

Customer Remarks – text written by the customer

Item_price – price of the product

connected_handling_time – time taken to handle the issue

Agent Shift – working shift of the support agent

CSAT Score – customer satisfaction score

The CSAT Score is the target variable, which we want to predict.

3. Data Understanding and Cleaning (1 minute)

Before building any machine learning model, we first understand the data.

We checked:

the number of rows and columns

missing values

duplicate records

Then we cleaned the dataset by:

handling missing values

converting date columns into proper datetime format

removing unnecessary columns

creating new features like response time

Cleaning the data is very important because machine learning models work best with clean data.

4. Data Visualization (1.5 minutes)

After cleaning the data, we performed Exploratory Data Analysis (EDA) using different charts.

We created 15 charts following the UBM rule:

Univariate analysis – analyzing one variable at a time

Bivariate analysis – relationship between two variables

Multivariate analysis – relationship between multiple variables

Some important insights we found:

Some communication channels produce higher customer satisfaction scores

Higher handling time sometimes reduces satisfaction

Certain product categories receive more complaints

Customer satisfaction varies depending on agent shifts and cities

These visualizations help us understand patterns in the data.

5. Hypothesis Testing (1 minute)

After visualizing the data, we tested some assumptions using hypothesis testing.

For example:

whether handling time affects customer satisfaction

whether communication channels influence CSAT scores

whether item price has any relationship with satisfaction

Using statistical tests, we calculated p-values to determine whether these relationships were statistically significant.

This step helps validate our findings scientifically.

6. Feature Engineering and Preprocessing (1 minute)

Next, we prepared the dataset for machine learning.

We performed several preprocessing steps:

handling missing values

encoding categorical variables

scaling numerical features

processing text data from customer remarks

For text preprocessing, we applied:

tokenization

stopword removal

POS tagging

TF-IDF vectorization

This converts textual information into numerical format so machine learning models can understand it.

7. Machine Learning Models (1.5 minutes)

After preprocessing the data, we built three machine learning models:

Logistic Regression

Decision Tree

Random Forest

Each model was trained using the training dataset and evaluated using the test dataset.

We evaluated the models using metrics such as:

Accuracy

Precision

Recall

F1 Score

We also performed hyperparameter tuning using GridSearchCV to improve model performance.

Among the three models, Random Forest performed the best, so we selected it as the final model.

8. Business Impact (40 seconds)

This model can help companies:

predict customer satisfaction levels

identify dissatisfied customers early

improve customer support efficiency

reduce response time

improve service quality

Using these insights, businesses can increase customer satisfaction and customer retention.

9. Conclusion (40 seconds)

In conclusion, this project demonstrates how data analysis and machine learning can be used to predict customer satisfaction.

By analyzing customer support interactions and building predictive models, organizations can make data-driven decisions to improve customer experience.


Author 
Awala Aishwarya
Bhoj Reddy Engineering College

Thank you.
