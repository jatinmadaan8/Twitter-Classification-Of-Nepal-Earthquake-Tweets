

# Twitter Classification Of Nepal Earthquake Tweets

## Introduction

Microblogging sites like Twitter are increasingly being used for aiding relief operations during various mass emergencies.  A lot of critical situational information is posted on microblogging sites during disaster events. However, messages posted on microblogging sites often contain rumors and overstated facts. In such situations, identification of factual or fact-checkable tweets, i.e., tweets that report some relevant and verifiable fact (other than sympathy or prayer) is extremely important for effective coordination of post-disaster relief operations. Additionally, cross verification of such critical information is a practical necessity  and resource availability. Hence, automated Machine Learning  techniques are needed to identify the tweets that talk about the need of resources or availability of resources.

## Data Fields Explanation

The Twitter Classification Of Nepal Earthquake Tweets dataset consists of 18226 Tweet Entries. This Dataset consists of a Text data (Train.txt)(We need to convert it first into csv data (Tweets.csv)). The columns in the table are:

* TweetClass: Class of Tweet Type(Irrelevant,Need,Availability)
* TweetId: Unique Id
* Tweet: Text data of Tweets

## Class Description:

0: The tweet doesn't talk about any resources needed or available (Irrelevant tweets)

1: The tweet mentions a resource that is needed (Need Tweets)

2: The tweet mentions a resource that is available (Availability tweets)

## Prerequisites

We would highly recommend that before the hack night you have some kind of toolchain and development environment already installed and ready. If you have no idea where to start with this, try a combination like:
* Python
* scikit-learn/sklearn
* Pandas
* NumPy
* Matplotlib
* Seaborn
