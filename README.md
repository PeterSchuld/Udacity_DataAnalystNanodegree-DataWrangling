# Udacity Data Analyst Nanodegree - Data Wrangling
Project No. 4 in the Udacity Data Analyst Nanodegree Winter 2019-2020

Real-world data rarely comes clean. Using Python and its libraries, we gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it. This is called data wrangling. We document our wrangling efforts in a Jupyter Notebook, plus showcase them through analyses and visualizations using Python (and its libraries) and/or SQL.

#### Project Description ####
The dataset that we wrangle (and analyze and visualize) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

#### Data ####
WeRateDogs downloaded their Twitter archive and sent it to Udacity via email exclusively for us to use in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017. However, we need to gather more detailed data via the Twitter API (in json format). Furthermore, we use a Udacity database for the photographs of the dogs in the tweets to get predictions for the breeds of the dogs.   

#### The following packages (libraries) need to be installed#### 
Pandas, NumPy, requests, tweepy, json
