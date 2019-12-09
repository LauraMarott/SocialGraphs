## Investigation of IMDb-data

Do you love movies? Are movies a big part of your life either private or professional? And are you interested in understanding what makes some movies successful while others tend to be unsuccessful? Then you have come to the right page!

This website strives to investigate IMDb-data to find out what patterns contribute to making a movie successful if any at all. In this regard successfull is based on good imdb-score and reviews. There are many ways to investigate this topic. Thus, this website allows you to jump around between different analyses using many different methods to hopefully enlightening all of us. The different sections can be read independently then. At the bottom of this page you can read our interpretations and questions for further investigation.

Are you ready to join us through this investigation? Then, let's roll!

#### What is IMDb? And what is the IMDb-score?
Oh, wait. Before we get started for real, it is important to know the concepts of this whole investigation:

[IMDb](https://www.imdb.com/) is one of the biggest online databases of information related to movies and tv-programs. IMDb is especially known for their respectable ratings based on the viewers scores for the movies. 

The scores are on a scale from 1 to 10 and is calculated as a weighted mean rating, meaning that they try to keep the scores as representative as possible by not letting all ratings have the same weight. The algorithms behind are secret. For more information, visit [IMDb's help center](https://help.imdb.com/article/imdb/track-movies-tv/ratings-faq/G67Y87TFYYP6TWAV#).

### [Understanding Data](https://lauramarott.github.io/SocialGraphs/BasicStats)

The main data is IMDb-data extracted from [kaggle](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset). The data is build around the movies where each line represent a movie.
After preparation the dataset only contains movies from 2010 and newer. Download this dataset [here](https://github.com/LauraMarott/SocialGraphs/blob/master/dataset.csv).

Furthermore, the IMDbPY package is used to scrape the reviews from IMDb.com. 

To understand the data, the basic stats are explored. See the analysis [here](https://lauramarott.github.io/SocialGraphs/BasicStats).

### [Investigation of Actors](https://lauramarott.github.io/SocialGraphs/Actors)

This investigation centers around actors and movie ratings. For this, a Network Analysis is made based on the movies as nodes and the shared actors as edges. Click [here](https://lauramarott.github.io/SocialGraphs/Actors) to learn more abot this topic.

### [Review Investigation based on Rankings](https://lauramarott.github.io/SocialGraphs/RankingReviews)

Here an anlysis of the user reviews of the movies is conducted to investigate the ranking divisions using text analysis. You can see this investigation [here](https://lauramarott.github.io/SocialGraphs/RankingReviews).

### [Investigation of Communities](https://lauramarott.github.io/SocialGraphs/Community)

This investigation aims to look into the [Network](https://lauramarott.github.io/SocialGraphs/Actors) with a new set of glasses. Here, the communities are analysed to find out if there are any patterns between movies which are densely connected. 
The reasons for the connections are investigated using the network and the text analysis. You can follow the analysis [here](https://lauramarott.github.io/SocialGraphs/Community).

### [Investigation of Genres](https://lauramarott.github.io/SocialGraphs/Genres)

An frequent assumption is that genres are connected to the success of a given movie. Therefore, this is investigated [here](https://lauramarott.github.io/SocialGraphs/Genres). This analysis is mainly based on text analysis of the reviews and basic statistics for the movies in the different genres.

### Conclusion and further work

### Explainer Notebook

For more detailed analyses and the coding behind, see the Explainer Notebook. 
