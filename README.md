# reddit scraped worldnews dataset

We extract posts from 2012 and 2013 for one popular news
community on reddit: r/worldnews. Once we extract all
posts, we extract the voting score, number of comments,
post title, and news story urls from each post. These news
story urls are used to scrape a sample of news articles, including
the body text and title text, using a mix of our own
code and the Python Goose library. We will filter out any
article that is under 100 characters or blocked by a paywall.
This reddit data comes from Tan and Lee’s reddit
post data set (Tan and Lee 2015) and Hessel et al.’s full
comment tree extension to that reddit dataset (Hessel, Tan,
and Lee 2016). Both of these data sets are based on a reddit
API collection originally done by Jason Baumgartner of
pushshift.io. Our newly collected data set of news articles
with corresponding reddit engagement statistics is found in this repository.

If you use this data set, please cite:

Horne, Benjamin D., and Sibel Adali. "The Impact of Crowds on News Engagement: A Reddit Case Study" The 2nd International Workshop on News and Public Opinion at ICWSM (2017).
