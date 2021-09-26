# Tweets
This folder contains the Twitter data regarding tweets from the Toronto area with the #TTC hashtag. The specific contents are
* files of the form tweets_xxxx.csv, where xxxx is a year between 2014 and 2021, inclusive
  * These files contain the scraped Twitter data for tweets from their respective year. The development version of [snscrape](https://github.com/JustAnotherArchivist/snscrape) was the scraper used to extract these tweets.
* tweets_per_day_post_part_1.csv
  * In Part 1 we used the available Twitter data to create a useful dataframe called tweets_per_day. Rather than recreate this dataframe in Parts 2 and 3 it will be easier to just load it from this saved copy.
* tweets_post_part_1.csv
  * This file consists of the cleaned Twitter data which we obtained in Part 1.
