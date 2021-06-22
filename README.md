# WeRateDogs Twitter Data Analysis
## by Xinqi Lin


> There are 3 data sources in this WeRateDogs project. [WeRateDogs](http://twitter.com/dog_rates) is a Twitter account that rates 
people's dogs with a humorous comment about the dog.
The first dataset is `The WeRateDogs Twitter archive`, which I uploaded a csv file called 'twitter-archive-enhanced.csv'. I'll need its tweet IDs later.
Then I used requests module to get tweet image predictions data using url 
'https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv'.
The last dataset I gathered was additional data from Twitter API. To use Twitter API, I created my first Twitter account and applied for a developer account. 
Luckily, I passed the application! With a developer account, I created a project and got token and secret, which I used for authentication. 
Then I was able to use tweepy module to query Twitter's API for JSON data for each tweet ID in the `The WeRateDogs Twitter archive`. 
The data I extracted via API was tweet_id, favorite_count and retweet_count.
I mainly used seaborn and matplotlib modules for my analysis, and it covered one-variable distribution, two-variable correlation etc.


