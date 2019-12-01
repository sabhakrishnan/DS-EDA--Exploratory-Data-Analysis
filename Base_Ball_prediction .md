# Data Science Case Study.
# Base - Ball Player Prediction
One of the most compelling stories of sports analytics made popular by the 2011 movie Moneyball, the Oakland Athletics team of 2002 created history by winning 20 consecutive games between August 13 and September 2002. Much of the Oakland Athletics (popularly referred to as the A’s) success in that season is attributed to their General Manager, Billy Beane and former Assistant General Manager, Paul DePodesta.

DePodesta, a graduate in Economics from Harvard University joined the A’s in 1999 and quickly started incorporating analysis of baseball statistics to value and purchase players.

# Features of the data sets
RA - Runs Allowed
RS - Runs Scored
OBP - On Base Percentage
SLG - Slugging Percentage
BA - Batting Average
OOBP - Opponent's OBP
SLG - Opponent's SLG
W - No of wins in that season
Statistical Analysis Clip from Moneyball (2011)

# DATA CLEANING: 
There are a few missing values in the OOBP and OSLG columns. We have to remove these rows of observations in order to plot a proper relationship.

# Model Buliding:
1. Our first model is used to predict ‘runs scored’. Our independent variables as on-base percentage, slugging percentage, batting average.
2. Similarly, we build a model for ‘runs allowed’ using opponent’s on-base percentage and opponent’s slugging percentage as independent variables.
3. model for predicting wins from runs difference.

# Model Predictions:
Here are the Oakland Athletics statistics in 2001 before the playoffs.

OBP: 0.339

SLG: 0.430

OOBP: 0.307

OSLG: 0.373 Lets plug in these values into the above models to generate predictions.

