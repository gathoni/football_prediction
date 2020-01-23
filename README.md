# football_prediction
A prediction result of a game between team 1 and team 2, based on who's home and who's away, and on whether or not the game is friendly



## Football Prediction - Regression Analysis
### 1. Defining the Question
#### a) Specifying the Question
You have been recruited as a football analyst in a company - Mchezopesa Ltd and tasked to accomplish the task below. A prediction result of a game between team 1 and team 2, based on who's home and who's away, and on whether or not the game is friendly (include rank in your training). You have two possible approaches (as shown below) given the datasets that will be provided

Input: Home team, Away team, Tournament type (World cup, Friendly, Other)

### Approach 1: Polynomial approach

What to train given:

Rank of home team
Rank of away team
Tournament type
Model 1: Predict how many goals the home team scores.

Model 2: Predict how many goals the away team scores.

### Approach 2: Logistic approach

Feature Engineering: Figure out from the home team’s perspective if the game is a Win, Lose or Draw (W, L, D)

#### b) Defining the Metric for Success
Using Polynomial regression, the Root Mean Squared Error will be used to measure the performace of the model.

The prediction of model using logistic regression model will be measured using the accuracy score

#### c) Understanding the context
As a data analyst at Mchezo Ltd, the following task is required of you: Make a prediction of a game between team 1 and team 2 , based on who's home and who's away and on whether or not the game is friendly.

A more detailed explanation and history of the rankings is available here: link

An explanation of the ranking procedure is available here: link

#### Dataset Columns

Some features are available on the FIFA ranking page Link

#### d) Recording the Experimental Design
Perform your EDA
Perform any necessary feature engineering
Check of multicollinearity
Build the model
Cross-validate the model
Compute RMSE
Create residual plots for your models, and assess their heteroscedasticity using Bartlett’s test
Perform appropriate regressions on the data including your justification
Challenge your solution by providing insights on how you can make improvements.
