# Big-Data-Analytics

The goal of this analytics is to find out the key factors impacting the check-in volume of the business owners on Yelp platform and provide suggestions for increasing the check-in volume the business owners on Yelp can benefit from.

This analytics is based on the big raw data(2.5G) of Yelp business which is deployed on AWS.

# Raw data
11 tables of Yelp users' info and Yelp business owners' info.
Table names:
"attribute"   "business"    "category"    "checkin"     "elite_years" "friend"      "hours"       "photo"     "review"      "tip"         "user"   

# Package
sqldf;
MatchIt;
dplyr;
ggplot2;
corrgram;
car;
MASS

# Other tools assited analyzing
Tableau

# Prediction Model
Poisson / Quasi-Possion Regression
