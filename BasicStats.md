## Understanding the Movie Data
*Return to [HOME](https://lauramarott.github.io/SocialGraphs/)*

Before even trying to tell anything about what makes a movie successful, it is important to understand the data used for the analyses, don't you think? 
To understand the movie data it is here examined on the following parameters:
* Genre
* Budget and Income
* Profit 
* Budget and Ratings
* Ratings

This analysis strives to also understand patterns in the industry based on the above factors. Therefore, the purpose of this is to give YOU a better insight in what is going on in the movie industry. 

### Genres

Here, you can see how the movies are distributed into different genres. Each movie can be assigned several genres by IMDb. This means that one movie can appear in more bars in the plot below:

<figure style="text-align: center;">
  <img src="./images/genres_bar.png" width="500" />
</figure>

The plot shows a very dominating top 4 which indicates that all movies can be categorised as either drama, comedy, thriller or action. If the movies were only allowed one genre, this picture might be very different.

### Budget and Income

In all industries, the relationship between budget and income is essential. A scatter plot is therefore made to investigate this relationship for the movies:

<figure style="text-align: center;">
  <img src="./images/budget_income.png" width="500" />
</figure>

It is seen that there are some correlation between the budget and the gross income for a movie. The relation is however not linear, as the gross income does not 'grow' as fast compared to the budget. The plot indicates that there might be a limit for how high income a movie can make no matter the budget. The budget, on the other hand, seems to have no limit. 

### Profit

Another way to look at the above relationship is to translate it into profit. The profit distribution for the movies is plotted below:

<figure style="text-align: center;">
  <img src="./images/profit.png" width="500"/>
</figure>

It is an interesting finding, that so many movies have a profit below or around 0. Average profit is 13 million dollars. This strengthens the finding from above; there must be a limit for how big profit a movie can have.  

### Budget and Ratings

The relationship between budget and ratings are also interesting to take a look at, since the money used on a movie maybe have an influence on the success:

<figure style="text-align: center;">
  <img src="./images/budget_rating.png" width="500"/>
</figure>

The plot shows that there is a relation between the budget and rating. It seems like high budget movies are 'secured' high ratings. This might be due to the special effects afforded to make that extra touch on the movies or what do you think?

### Ratings

The ratings are essential to analyse, since this whole investigation of movies are based on the assumption that a movie is successful if it has a high IMDb-score. The boxplot below shows the distribution of the ratings:

<figure style="text-align: center;">
  <img src="./images/ratings.png" width="500" />
</figure>

The average rating is very high (6.5), and it is even more interesting that the 25 % quantile is 5.9. The given ratings are therefore very high, which indicates that either few bad movies exists or people are too nice when rating. This is an interesting finding to keep in mind in later analyses. 

### Conclusion

Hopefully, you have now gained an idea of what the movie data looks like which reflect the market of movies. These insights are the first step to understand what makes a movie successful. 

You can now go back to [home](https://lauramarott.github.io/SocialGraphs/) and continue the investigation. Enjoy!
