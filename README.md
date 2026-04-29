# CSCI-1070-Final-Project
This repository will house both the code and presentation for my CSCI 1070 final project
For my project I attempted to create a model that could predict if a MLB player is our is not a hall of famer.
For my data set I used a data set of all mlb players past and present who have had over 3500 Plate apperances (about 7 seasons).
The data set had the following variables:

Name
HOF_status -- is a player in the hall of fame, not in the hall of fame, or active
G -- games played
PA -- plate apperances
HR -- Homeruns
R -- Runs
RBI -- Runs Batted in
SB -- stolen bases
AVG -- batting average
OBP -- on base percentage
SLG -- Slugging percentage
wRC+ -- Weighted runs created
Off -- Offensive Value
Def -- Defensive value
WAR -- Wins above replacement

I then split my data set into active and retired players and ran a logistic regression model 
and a decision tree model on the retired players to use the other variables to predict HOF status

After creating our models, I used the logistic regression model to predict which active players would be hall of famers 
