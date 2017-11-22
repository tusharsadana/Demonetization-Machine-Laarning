# Demonetization-Machine-Laarning
Demonetization Analysis using Machine Learning on Tweeter's Data.

The demonetization of ₹500 and ₹1000 banknotes was a step taken by the Government of India on 8 November 2016, ceasing the usage of all old ₹500 and ₹1000 banknotes as a form of legal tender in India from 9 November 2016.

The announcement was made by the Prime Minister of India Narendra Modi in an unscheduled live televised address to the nation at 20:15 Indian Standard Time (IST) the same day. In the announcement, Modi declared circulation of all ₹500 and ₹1000 banknotes of the Mahatma Gandhi Series as invalid and announced the issuance of new ₹500 and ₹2000 banknotes of the Mahatma Gandhi New Series in exchange for the old banknotes.

The data contains 6000 most recent tweets on #demonetization. There are 14940 tweets and 14 keys per tweet.

Keys:

Text (Tweets)
favorited
favoriteCount
replyToSN
created
truncated
replyToSID
id
replyToUID
statusSource
screenName
retweetCount
isRetweet
retweeted
The Data is extracted using Python (tweepy) and dumped in MongoDb Databasein json format , which is later exported as .json file for further analysis.

Load the data into pandas dataframe and then perform required Data preprocssing.
Perform Sentiment Analysis of the tweets and based on the scores plot bar graph for positive negative and neutral tweets.
Also plot sentiment score vs time plot and predict if the overall sentiment trend changes with time.

What percentage of tweets are negative, positive or neutral?
 Use clustering to plot them. 

Plot graph using seaborn and matplotlib on the basis of number of tweets/re-tweets per hour per day.
What are the most famous/re-tweeted tweets?
