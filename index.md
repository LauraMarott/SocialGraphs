## Investigation of IMDb-data

Do you love movies? Are movies a big part of your life either private or professional? And are you interested in understanding what makes some movies successful while others tend to be unsuccessful? Then you have come to the right page!

<figure style="text-align: center;">
  <img src="./images/WeLoveMovies.png" width="300" />
</figure>

This website strives to investigate IMDb-data to find out what patterns contribute to making a movie successful - if any at all. In this regard the term *successful* is based on good IMDb-score and reviews. There are many ways to investigate this topic. Thus, this website allows you to jump around between different analyses using many different methods to hopefully enlightening all of us. The different sections are meant to be able to be read independently. At the bottom of this page you can read our interpretations and questions for further investigation.

Are you ready to join us through this investigation? Then, let's roll!

*Click on the sections below you want to know more about. Here you can find some interesting analyses.*

#### What is IMDb? And what is the IMDb-score?
Oh, wait. Before we get started for real, it is important to know the concepts of this whole investigation:

[IMDb](https://www.imdb.com/) is one of the biggest online databases of information related to movies and tv-programs. IMDb is especially known for their respectable ratings based on the movie-watchers' scores for the movies. 

The scores are on a scale from 1 to 10 and are calculated as a weighted average rating, meaning that IMDb try to keep the scores as representative as possible by not letting all ratings have the same weights. The algorithms behind are secret. For more information, visit [IMDb's help center](https://help.imdb.com/article/imdb/track-movies-tv/ratings-faq/G67Y87TFYYP6TWAV#).

Aaand now we are ready. Enjoy!

### [Understanding the Movie Data](https://lauramarott.github.io/SocialGraphs/BasicStats)

The main data is IMDb-data extracted from [kaggle](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset). The data is build around the movies where each line represents one movie.
After preparation the dataset only contains movies released in 2010 or after. Download this dataset [here](https://github.com/LauraMarott/SocialGraphs/blob/master/dataset.csv).

Furthermore, the [IMDbPY](https://imdbpy.github.io/) package is used to scrape the reviews from IMDb.com. 

To understand the IMDb-dataset, the basic stats are explored. See the analysis [here](https://lauramarott.github.io/SocialGraphs/BasicStats).

### [Investigation of Actors](https://lauramarott.github.io/SocialGraphs/Actors)

This investigation centers around actors and movie ratings. For this, a Network Analysis is made based on the movies as nodes and the shared actors as edges. Click [here](https://lauramarott.github.io/SocialGraphs/Actors) to learn more abot this topic.

### [Review Investigation based on Rankings](https://lauramarott.github.io/SocialGraphs/RankingReviews)

Here an anlysis of the user reviews of the movies (extracted with the IMDbPY package) is conducted to investigate the low, medium and high ranked movies using text analysis. You can see this investigation [here](https://lauramarott.github.io/SocialGraphs/RankingReviews).

### [Investigation of Communities](https://lauramarott.github.io/SocialGraphs/Community)

This investigation aims to look into the [Movie Network](https://lauramarott.github.io/SocialGraphs/Actors) with a new set of glasses. Here, the communities are analysed to find out if there are any patterns between movies which are densely connected. 
The reasons for these connections are investigated using the network and text analysis. You can dive into the analysis [here](https://lauramarott.github.io/SocialGraphs/Community).

### [Investigation of Genres](https://lauramarott.github.io/SocialGraphs/Genres)

A frequent assumption is that genres are connected to the success of a given movie since many people have preferences. Therefore, this is investigated [here](https://lauramarott.github.io/SocialGraphs/Genres). This analysis is mainly based on text analysis of the reviews and basic statistics for the movies in the different genres.

### Main Findings and Further Work

At this point, the above analyses shoud have provided you with your own ideas of what makes a movie successful. As shown, many parameters can contribute to the success of a movie. Some of them are anlysed at this website, and we have discovered patterns that indicates that the use of popular actors can be important as well as the genre of the movie seems to have an influence on the success. 
Other things that could be investigated are:
* Directors
* More in depth about profits
* What time of the year a movie is released
* The marketing of the movie

You can probably think of many more things, that you could imagine to investigate, right? 

Regarding the term *success* it might be relevant for IMDb to rethink the ratings, since it is mainly the upper part of the scale that is used according to the above analyses. Maybe a more adequate use of the scale will make it easier to see differences in the analyses conducted here. Or what do you think? 

We hope that no matter why you have visited this website you have learned something and most important gained motivation to learn more about *What makes a movie successful*.

### Explainer Notebook and Data used

For more detailed analyses and the coding behind, see the [Explainer Notebook](https://nbviewer.jupyter.org/github/LauraMarott/SocialGraphs/blob/master/Movies-Explainer-Notebook.ipynb). 

* [The full dataset](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset) can be found on kaggle.
* [The reduced dataset](https://github.com/LauraMarott/SocialGraphs/blob/master/dataset.csv) can be downloaded here.
* [The file for the sentiment dictionary](https://github.com/LauraMarott/SocialGraphs/blob/master/AFINN-111.txt) can be downloaded here.
