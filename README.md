# WeRateDogs Data Exploration

## Dataset

This project involved gathering 3 datasets using 3 different methods: manually, 
programmatically and web scrapping using Twitter API. The twitter-archive-enhanced.csv was 
downloaded manually from the Udacity classroom, the image-predictions.tsv dataset was 
downloaded programmatically using the Requests library and the URL provided in the 
classroom while the Twitter API dataset was to be gotten using Tweepy but due to the denied 
elevated access from Twitter, the tweet-json.txt file provided by Udacity was used. 
The combined Twitter dataset used for analysis has 1,994 rows and 20 columns which include 
tweet_id, timestamp, text, dog_stage, favorite_count, and retweet_count. 


## Summary of Findings

During the Assessing Data phase, 11 Quality issues and 2 Tidiness issues were found and all 
the issues identified were successfully cleaned using Python and pandas after which a tidy 
master dataset with the necessary pieces of gathered data called the Twitter-archive-master.csv 
was created.
In the exploration, I found a positive correlation between favorite_count and retweet_count and 
also found that the Pupper dog stage has the highest frequency in the WeRateDogs Twitter account.

I created a new column called "year" from the timestamp column and got the following insights:

 -  Out of the 3 years in the dataset(2015, 2016, and 2017), 2016 has the highest frequency.
 - The favorite count increased as the year increased though their retweets dropped tremendously.