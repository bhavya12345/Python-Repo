# Data Mining And Sentiment Analysis For Twitter Data

## Libraries Used
* Tweepy - For the extraction of the tweets from Twitter
* TextBlob - For performing the Sentiment Analysis On Tweets

The csv files generated after running the code in the given project are as follows:

1.	realdonaldtrump_tweets.csv (all tweets written from Donald Trump Profile after 2016)

2.	@realdonaldtrump_tweets.csv (all tweets written by other twitter profile (Other People) addressing Donald Trump using his twitter handler @realdonaldtrump after 2016)

3.	#realdonaldtrump_tweets.csv (all tweets written by other twitter profile (Other People) addressing Donald Trump using his twitter hash tag #realdonaldtrump after 2016)

## Sentiment Analysis

Performed sentiment analysis of every tweet and found –ve , +ve and neutral sentiments. Marked scores from -2, -1, 0, +1, +2. The files in which sentiment analysis for the tweets was performed are as follows:

4.	realdonaldtrump_sentiments.csv

5.	@realdonaldtrump_sentiments.csv

6.	#realdonaldtrump_sentiments.csv

## Description about the python files:

1. @realdonaldtrump_file.ipynb - This file was used to extract tweets with the search query- '@realdonaldtrump' using the Tweepy API. Here, using the same code, tweets for '#realdonaldtrump' can be found out by making a change in the search query. These tweets were stored to their respective csv files.

2. realdonaldtrump_tweets.ipynb - This file was used to extract all tweets from Donald Trump profile after 2016. Here, a separate method of Tweepy API has been used.

3. Date+Time+Manipulation+for+Donald+Trump.ipynb - This file was used to extract up the tweets after 2016 for one of the csv files. Same code can be used for the other 2 files as well by changing the file names.

4. Semtiment+Analysis+for+all+files - This file was used to perform the sentiment analysis for all the files using Textblob and assigning the tweets appropriate sentiment scores.

