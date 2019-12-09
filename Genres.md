## Investigation of Genres
*Return to [HOME](https://lauramarott.github.io/SocialGraphs/)*

The genres are investigated to see how they relate to the success of a given movie. In the dataset one movie can be assigned several genre and therefore each movie can be a part of more genres in the below analyses. 
The investigation here consists of the following parts:
* Understanding the Genres
* Wordclouds
* Collocations
* Sentiment Analysis
  * Positive Wordclouds
  * Negative Wordclouds

Let us dive into it!

### Understanding the Genres

The first thing is to understand the behaviour of the genres in terms of successfulness, which is here evaluated on the parameters IMDb-score (rating), Facebook likes, budget and profit:

<figure style="text-align: center;">
  <img src="./images/genre_investi.png" width="500" />
</figure>

First of all, the above shows that all movies have a rating around the median at 6.5 found in the [Basic Stats](https://lauramarott.github.io/SocialGraphs/BasicStats) but some outliers are seen. For instance, Biography and History have a high average rating. The reason for this might be that they are "niche-movies", where the viewers are really interested in that kind of movies and therefore give high ratings. 

In terms of profit, Animation and SciFi have the highest profit. These movies contains many special effects which indicates that this is what the viewers want to see. 

This have provided an overview of how the genres behaves compared to each other. We are now ready to continue the investigation. 

### Wordclouds

The wordclouds are made based on the IMDb-user reviews. The wordclouds shows which words af frequent and unique for each genre, taking into account how unique the given word is across the different genres. For more information of the review behaviour, see [Review Investigation based on Rankings](https://lauramarott.github.io/SocialGraphs/RankingReviews).

The wordclouds for each genre can be seen below:

<figure style="text-align: center;">
  <img src="./images/genre_wordclouds1.png" width="500" />
</figure>

The words in the wordclouds are very consistant with the words known for each genre, for instance in the Horror wordcloud where the biggest words are "scare" and "zombie". 
It is also clear that some of the movies reappear in more genres, for instance "avengers" being big in both Action, Adventure and SciFi. This complicates the possibility of making clear conclusions for the different genres when the movies reappear in such an extent. 

### Collocations

Another way to analyse the reviews is through collocations, here being bigrams that shows the frequent two words occuring together. The top ten collocations for each genre is shown below:

<figure style="text-align: center;">
  <img src="./images/genre_collo1.png" />
  <img src="./images/genre_collo2.png" />
  <img src="./images/genre_collo3.png" />
  <img src="./images/genre_collo4.png" />
  <img src="./images/genre_collo5.png" />
</figure>

The collocations confirms the themes of the different genres, but are also providing further insight, for instance Drama including bigrams like "character development", "pleasently surprised" and "subject matter".

### Sentiment Analysis

A sentiment analysis is conducted to analyse the mood of the reviews in the different genres. The sentiment analysis is based on the fact that some words are more or less positive or negative than other, which is quantified for the genres, as seen below: 

<figure style="text-align: center;">
  <img src="./images/genre_mean_std.png" width="200" />
</figure>

The average sentiment score correlates to the themes and content of the genres. For instance, the highest sentiment scores are Musical and Western which is romanticised genres. Likewise, the lowest scores are War and Horror which is very frightening genres. 
Another way to show the sentiments are by there distributions below:

<figure style="text-align: center;">
  <img src="./images/genre_sentiment1.png" width="500" />
</figure>

Again, Musical is very high scored and the number of low sentiment reviews are very limited. 
The sentiment analysis have shown us, that the sentiments correlates with the content of the genres but not with the ratings of the genres. Therefore, it is interesting to investigate the positive and negative reviews in each genre using wordclouds. 

#### Positive and Negative Wordclouds

The **positive** reviews for each genre is seen below:

<figure style="text-align: center;">
  <img src="./images/genre_positive.png" width="500" />
</figure>

The **negative** reviews for each genre is seen below:

<figure style="text-align: center;">
  <img src="./images/genre_negative.png" width="500" />
</figure>

The positive and negative word clouds can immediately be used for two things:

First, the good and bad movies in each genre can be identified by using this method. In Action, the positive wordcloud clearly shows that James Bond movies are positively reviewed, while the negative wordclouds indicates the dinosaur movies (maybe Jurrasic World) are being reviewed negatively. 

Secondly, the division in positive and negative words can provide a deeper insight into the experiences when watching the movies. For instance, the positive Action wordcloud includes words like "relevant" and "precisely" and the negative Action wordcloud includes "clichés" and "absurd". 

Feel free to examine each genre like the Action genre is examined above to really understand the differences. 

### Conclusion

A lot of insight has been provided from the analysis of the genres, and it seems like the genres influences the overall success of a movie. However, the fact that the movies are assigned several genres can be misleading for the investigation. Therefore other investigations of other factors has to been conducted as well. You can go back to [home](https://lauramarott.github.io/SocialGraphs/) to look into these other investigations. Good hunt!
