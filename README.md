# Data wrangling: We Rate Dogs
## by Folami Balogun

## About WeRateDogs
[WeRateDogs](https://twitter.com/dog_rates) is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent."  

## Data gathering
The twitter-archive-enhanced.csv file was generously provided by WeRateDog for this exercise. The dataset contains 2356 rows and 17 columns.

The image_predictions.tsv file was downloaded from Udacity's servers programmatically using the Requests library and the following URL: https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv. The dataset contains 2075 rows and 12 columns.

The tweet_json.txt file was obtained from querying the Twitter API for each tweet's JSON data using Python's Tweepy library and storing each tweet's entire set of JSON data in it.

## Data assessment
The data was assessed visually and programatically using several functions available in python. Several quality and tidiness issues were picked up on and documented in the wrangle_report.pdf file

## Data cleaning
The files were cleaned in python and a twitter_archive_master.csv created for the purpose of exploratory data analysis