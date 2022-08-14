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


The video for the Robo Advisor using Amazon Lex with a Lambda function is located here:  [Amazon Lex with Lambda function.](https://youtu.be/L2iDKACYBhE)

The video shows the outcome for each risk level, followed by the age restriction along with invalid age error, finally the video shows the error for the minimum needed to invest.


---

## Information about datasets

Functions:

parse_int, Securely converts a non-integer value to integer.

build_validation_result, Define a result message structured as Lex response.

get_investment_recommendation, Returns an initial investment recommendation based on the risk profile.

validate_data,  Validates the data provided by the user.

elicit_slot, Defines an elicit slot type response.

delegate, Defines a delegate slot type response.

close, Defines a close slot type response.

recommend_portfolio,  Performs dialog management and fulfillment for recommending a portfolio.

dispatch, Called when the user specifies an intent for this bot.

lambda_handler, Route the incoming request based on intent.  The JSON body of the request is provided in the event slot.





---

## Libraries used in analysis

datetime

dateutil.relativedelta

---

## Contributors


**Chris Miskovich**

Contact Information:

Email: cmiskovich@verizon.net

[LinkedIn](https://www.linkedin.com/in/christopher-miskovich-9a61b0234/) 

---

## License

[MIT](/license.txt)
