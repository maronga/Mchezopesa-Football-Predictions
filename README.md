# Mchezopesa-Football-Predictions
#Overview
Create a model to predict the result of a game between team 1 and team 2, based on who's home and who's away, and on whether or not the game is friendly or not.

The two possible approaches (as shown below) have been used to make predictions given the below inputs

Input: Home team, Away team, Tournament type (World cup, Friendly, Other)
Approach 1: Polynomial approach
The model should use the below features:

Rank of home team
Rank of away team
Tournament type
Model 1: Predict how many goals the home team scores Model 2: Predict how many goals the away team scores

Approach 2 Logistic approach
Feature Engineering: Figure out from the home team’s perspective if the game is a Win, Lose or Draw (W, L, D)

Context
A more detailed explanation and history of the rankings is available here

An explanation of the ranking procedure is available here

Dataset Columns
Some features are available on the FIFA ranking page

Rank
Country Abbreviation
Total Points
Previous Points
Rank Change
Average Previous Years Points
Average Previous Years Points Weighted (50%)
Average 2 Years Ago Points
Average 2 Years Ago Points Weighted (30%)
Average 3 Years Ago Points
Average 3 Years Ago Points Weighted (20%)
Confederation
Date - date of the match
Home_team - the name of the home team
Away_team - the name of the away team
Home_score - full-time home team score including extra time, not including penalty-shootouts
Away_score - full-time away team score including extra time, not including penalty-shootouts
Tournament - the name of the tournament
City - the name of the city/town/administrative unit where the match was played
Country - the name of the country where the match was played
Neutral - TRUE/FALSE column indicating whether the match was played at a neutral venue
Deliverables
Perform Exploratory Data Analysis
Perform any necessary feature engineering
Check of multicollinearity
Build models
Cross-validate the models
Compute RMSE
Create residual plots for the models, and assess their heteroscedasticity using Bartlett’s test
Dataset
The dataset and glossary to use for this project can be found here
