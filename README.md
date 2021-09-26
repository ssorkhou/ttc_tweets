# Sentiment Analysis of #TTC Tweets [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ssorkhou/ttc_tweets/HEAD)
I conduct sentiment analysis on tweets featuring the #TTC hashtag originating from the Toronto area. The Twitter data is highly informative and I was able to uncover some interesting trends, such as the observation that positive tweets on average were liked and retweeted more often than negative ones. Plenty of additional findings are discussed in the project.

Furthermore, I examine data pertaining to scheduled subway closures as well as bus, streetcar, and subway delays. After exploring these datasets I attempt to discover any relationships between these datasets and the Twitter data. I must admit that the results here are rather surprising to me as subway closures and transit delays have less of an impact on Twitter sentiment than I anticipated.

The project is split into three parts. In the first I investigate the Twitter data on its own, in the second part I introduce the subway closure data, and in the third I also investigate data relating to transit delays. Thus the project consists of the three Jupyter notebooks in this repository. To follow along with the notebooks interactively, click on the "launch binder" button above.

**Note: The heatmap near the end of Part 1 is interactive. Consequently, it will only render properly when following along with Binder**.

In addition to the Jupyter notebooks, this repository also contains the following folders:

* closures - contains the with subway closure data
* delays - contains the bus, streetcar, and subway delay data
* tweets - contains the scraped Twitter data
