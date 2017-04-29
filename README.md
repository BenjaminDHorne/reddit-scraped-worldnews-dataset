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

In this repository, there are two csv files that contain meta data about each reddit news post, including time, url, score, and the number of comments made on the post. Each ID in the csv files will correspond to 3 files in the "Articles and Data" rar file: 1 for the news story title, 1 for the news story body content, and 1 for the reddit post title. All are plain text files.

Copyright (c) 2016, Benjamin D. Horne, Dorit Nevo, Jesse Freitas, Heng Ji & Sibel Adali

All rights reserved.

Redistribution and use in any form, with or without modification, are permitted provided that the above copyright notice, this list of conditions and the following disclaimer are retained.

Any publication resulting from the use of this work must cite the following publication::

Horne, Benjamin D., and Sibel Adali. "The Impact of Crowds on News Engagement: A Reddit Case Study" The 2nd International Workshop on News and Public Opinion at ICWSM (2017).

THIS DATASET IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.


