# Popularity-Prediction-on-Twitter

## Part 1:
A useful practice in social network analysis is to predict future popu-
larity of a subject or event.

Download training data from [here](https://ucla.box.com/s/nv9td9kvvfvg3tya0dlvbs1kn5o87gmv). This data is collected by querying popular hashtags to the 2015 Superbowl spanning a period from 2 weeks before the game to a week after the game. 

Twitter is a good platform to do such analysis. Given the current and previous hashtag tweet activity, can we predict the future activity of the hashtag? Let's explore. 

We will train a model on the data of such popular hashtags and predict the popularity of the given hashtag. We need to first prepare the data, extract features from the data and then fit the model. 

We will also deal with how to choose good features. 

We will test our model on testdata obtained from [here](https://ucla.box.com/s/ojvvthudugp9d2gze5nuep9ogwjydnur)
The test data consists of
tweets containing a hashtag in a specified time window, and we will use your model
to predict number of tweets containing the hashtag posted within one hour immediately
following the given time window.

The tweets are stored in separate files for different hashtags and files
are named as tweet_[#hashtag].txt 

Training data: The tweet file contains one tweet in each line and tweets are sorted with respect
to their posting time. Each tweet is a JSON string that you can load in Python as a
dictionary.
