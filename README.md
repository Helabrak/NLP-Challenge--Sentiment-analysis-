# NLP-Challenge-Sentiment-analysis
## NETFLIX Squidgame 

![image](https://user-images.githubusercontent.com/84380899/137283680-1dd032af-895d-4656-939d-0ae38edd42c8.png)

### Introduction: 

Squid game series on Netflix is now trending with a strong buzz on social media and this project aimes at analysing audience tweets to evaluate audience perception for the series.
An NLP sentiment analysis was done using Twint, Textblob for sentiment classification and labeling. The finall objective is to deploy an app on Streamlite to allow users to enter a tweet and get whether it's a poitive or negative towards the series

### Project planning: 

A Trello board was created with the same name: https://trello.com/b/3kKWu0BE/nlp-challenge-sentiment-analysis
An MVP of 300 tweets was selected 

#### Coming Up: 
- A full fledged model on 25000 tweets should be deployed 

### Tweet Scraping: 
The first step was to scrap the tweets that will be used to train the model to be later deployed. two ways were tried at this stage: 
  - Using Twitter API and Tweepy python library for tweet scraping, a request was sent to get keys from Twitter API, but due to the fact that no answer is received during the project plan B was used 
  - Using Twint to scrape 25000 tweets on the series 
 
 ### Tweets cleaning and Preprocessing: 
 - To be able to feed the scraped tweets into the model the followinfg was done: 
 -  1- selecting only English tweets 
 -  2- removing all unncessary spaces, URLs, special characters, and emojis from the text.  
 -  3-
 ### Sentiment Classification:
  - Textblob was used to classify and calculate sentiment to positive, negative and neutral tweets
 
 ### Visualization: 
  - Wordcloud was used to visualize the sentiments from the tweets 

positive tweets:
  - ![Positive tweets](https://user-images.githubusercontent.com/84380899/137282109-c37b7747-7657-43b9-8b6a-16c6592ee350.png)
 
 Negative tweets:
  - ![negative tweets](https://user-images.githubusercontent.com/84380899/137283000-aa1313ce-871e-4f06-bd07-0731e41d821f.png)



### Deployment: 
- Deployment using Streamlit is planned
- 

