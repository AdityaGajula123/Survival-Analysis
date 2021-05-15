# Survival-Analysis
Motivation: Performed to obtain likelihood of survival for each donor with time. 
Survival Analysis is a regression modelling technique used to figure out how long a particular donor will remain with the business.  Gives an estimate on how long we expect a donor to keep making donations to the fraternity.
Cox Proportional-Hazards Model: Survival Regression technique in which we regress covariates (Donor’s ratings, Number of Donations, Lifetime Value) against a duration variable (Number of days between donations)
The model takes into account the cumulative distribution function of various Donor’s attributes, learns the pattern based on the event variable ( in our case it is the Average number of days between donations) and gives the estimated probability of survival for the future.
