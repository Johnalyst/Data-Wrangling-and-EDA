##ReadME

This project demonstrates the data wrangling process for the tweet archive of WeRateDogs Twitter account. 
WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. 
In this project I will be going through different the data wrangling techniques that I used to gather, assess and clean all the necessary data before the analysis.

I will like to note also, that so much work is  put into the wrangling process and it's definitely not to give the dataset some sort of aesthetical feel or look, but 
sometimes you just really have to appreciate the finish product of the wrangling process. Taking a look of the dataset after wrangling process, it just sets you 
ahead towards creating some amazing insights and analysis. 
Imagine, how can someone be critical and creative while working on a dirty environment, definitely not me. That's why it's always important to clean up the dataset
before proceeding into analysis, as this would not only give you a clean and well structured dataset at the end of the wrangling process, but it would connect you more 
with the dataset you're working on, inspire you towards amazing insights and asking the right questions about the dataset. 

Having said all that, I'm so much eager towards getting started with this dataset, exploring, visualizing and drawing data influenced conclusions.

In this project, I will be working with three datasets:
The first will be WeRateDogs Twitter archive, that can be downloaded from [here](https://d17h27t6h515a5.cloudfront.net/topher/2017/August/59a4e958_twitter-archive-enhanced/twitter-archive-enhanced.csv)
The second dataset is the tweet image predictions dataset that can be downloaded from [here](https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv), while the dataset I will be working with contains additional data via the Twitter API, which contains each tweet's retweet count and favorite ("like") count. I collected this set of data using the tweet IDs in the WeRateDogs Twitter archive, query the Twitter API for each tweet's JSON data using Python's [Tweepy](http://www.tweepy.org/) library and store each tweet's entire set of JSON data.
