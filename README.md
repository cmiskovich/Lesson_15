# Lesson_15
# Primary application file

Create a Robo Advisor using Amazon Lex and Amazon Lambda.  The Robo advisor will advise you how to invest for retirement based on your level of risk you want to take.


---

## Technologies

The following Technologies were used to develop this program:

Python 
    Version 3.9.7

Terminal
    Version 2.12.5 (444)

Visual Studio Code
    Version: 1.66.2 (Universal)
    Commit: dfd34e8260c270da74b5c2d86d61aee4b6d56977
    Date: 2022-04-11T07:49:20.994Z
    Electron: 17.2.0
    Chromium: 98.0.4758.109
    Node.js: 16.13.0
    V8: 9.8.177.11-electron.0
    OS: Darwin x64 21.4.0
    
Amazon Lex

Amazon Lambda
    


---

## General information about analysis.
There are three parts to this Lesson:

First, configure the initial robo advisor: Define an Amazon Lex bot with a single intent that establishes a conversation about requirements to suggest an investment portfolio for retirement.

Next, build and test the robo advisor: Make sure that your bot works and accurately responds during the conversation with the user.

The Robo Advisor using Amazon Lex can be viewed at this link. [Amazon Lex](https://youtu.be/9In63Aeqz7U)

Finally, enhance the robo advisor with an Amazon Lambda function: Create an Amazon Lambda function that validates the user's input and returns the investment portfolio recommendation. This includes testing the Amazon Lambda function and integrating it with the bot.

The code used for the Amazon Lambda function can be found in this link:
[Lambda Code.](/recommendPortfolio.py)


---

## Information about datasets

Data frame for OHLCV dataset:

ohlcv_df

Filter date index and pct_change function to generate returns from close prices:

signals_df

Assign a copy of the sma_fast and sma_slow columns:

X

Create target set for Signal column:

y

Set training beginning and ending dates, train data, and test data:

training_begin, training_end

X_train, y-train

X_test, y_test

Using StandardScaler fit and transform data:

scaler, X_scaler, X_train_scaled, X_test_scaled

Using SVC classifier model, fit, and predict data:

svm_model, svm_pred

Classification report from SVC model predictions:

svm_testing_report

Create a dataframe with predictions, actual returns, and strategy returns:

predictions_df

Logistic Regression model:

logistical_regression_model

Fit and predict model:

model, pred

Classification report:

test_pred

Create a dataframe with predictions, actual returns, and strategy returns for Logistic Regression model:

lr_predictions_df





---

## Libraries used in analysis

pandas

numpy

Path

hvplot

matplotlib

svm

StandardScaler

DateOffset

classification_report

LogisticRegression


---

## Contributors


**Chris Miskovich**

Contact Information:

Email: cmiskovich@verizon.net

[LinkedIn](https://www.linkedin.com/in/christopher-miskovich-9a61b0234/) 

---

## License

[MIT](/license.txt)
