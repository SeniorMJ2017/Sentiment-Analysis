# Sentiment-Analysis
RapidMiner is an integrated environment for text and data mining, predictive and business analytics and machine learning.
Download and install RapidMiner Studio. You can find it at https://rapidminer.com/. Create an account so that you can login to the software.
The trumptastic_hildog_tweets.xlsx file contains a collection of tweets tweeted about Trump and Hillary. 
I was able to use text processing and rapid miner Aylien extension which let us process text and do analysis. 
The sentiment analysis technique used here looks through the data for tweets containing trump and hillary and counts words as it goes.
These tweets are then classified as being negative, neutral or positive.  
The process begins by using process documents operator which retrieves the data followed by a set role, sample and the sentiment analysis processes attached to each other.
The four processes are connected to each other using nodes.
The process document operator lets us use tokenize operator which  breaks up our document into words removing punctuation,
transform words to upper or lower case and filter stopwords. 
The sample process takes 50 sample of the tweets and is used to generalize about the overall tweet.
By setting the attribute name as text and using random sample of 50. 
We were able to count the words and categorize them using the bar chart as being neutral, positive or negative to ACA
