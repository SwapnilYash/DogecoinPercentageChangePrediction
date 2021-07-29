# DogecoinPercentageChangePrediction
Dogecoin Percentage Change Prediction based on Elon Musk's Tweets (Sentiment Score)


# Research is based on 4 parameters : 
1. Extracting Elon Musk's tweets on dogecoin through Twint API 
   Elon'sTweets.ipynb

2. Getting Sentiment Score of tweets through VADER
 
3. Here Y - Dependent variable is Percentage Change 
   and  X - Independent variable that is Tweet's Sentiment Score
   So after checking for hypothesis we found null hypothesis is fail to except that means there is realtion between X and Y
   
   This Part's Data Analysis is done in Excel :   Data - Data Analysis - Regression
   
4. Prediction Part  - LSTM STACKED MODEL is used for predicting values, where 
                      there are features trained to model are sentiment score, ohlc , volume and percentage change.
 
