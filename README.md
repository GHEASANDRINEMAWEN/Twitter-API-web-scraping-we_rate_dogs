# Twitter-API-web-scraping-we_rate_dogs

WeRateDogs is a popular Twitter account that is recognized for its dog photographs and
commentary (https://twitter.com/dog rates). Its popularity is based on several factors, including
the internet's obsession with dogs, a scoring system that consistently awards scores above the 10
as numerator and denominator of 10 that is (13/10, 11/10 etc), and commentary that has given
rise to a distinct language through observations about the pictures and both snarky and humorous
remarks to other user accounts. In the analysis, I aim to answer the following questions:

1) Relationship between retweet count and favourite count

2) What are most common 10 dogs' names?

3) Distribuion of the different Sources from which the tweets were made.

4) The most common dog personality

# Twitter-API-web-scraping-we_rate_dogs
- The main analysis file is Udacity_Project2_GAC.ipynb
- The final report is act_report.pdf

## Requirements
- Jupyter Notebook
- Pandas
- Numpy
- Requests
- Tweepy
- json
- Matplotlib
- Scipy
- Twitter API

## Installation

To get the Jupyter Notebook running, execute the following in the command line and select Udacity_Project2_GAC.ipynb from the Jupyter Notebook dashboard. The conda environment setup is optional; I have provided the base environment in base.yaml.
```ruby
$ git clone https://github.com/evanchen13/weratedogs.git
$ cd weratedogs
$ conda env create -f base.yaml
$ jupyter notebook
```
tweet_json.txt is provided in this repository, but can be downloaded programmatically using the Twitter API. This requires a developer account. To apply for access, visit this link and click the "Apply for a developer account" button. Then, be sure to edit the following lines in cell 5:

```ruby
consumer_key = 'CONSUMER_KEY'
consumer_secret = 'CONSUMER_SECRET'
access_token = 'ACCESS_TOKEN'
access_secret = 'ACCESS_SECRET'
```
