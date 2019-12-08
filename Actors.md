## Investigation of Actors

*Return to [HOME](https://lauramarott.github.io/SocialGraphs/)*

One hypothesis is that the use of actors influences the popularity of the movies and thus the ratings made by the IMDb-users. To investigate this, a Network Analysis is conducted here. 

### Description of the Network
The network is an undirected network, where the movies are the nodes and the edges between them are shared actors. This means that the network is weighted since two movies can share more than one actor. The edge weights are therefore between 1 and 3, since the dataset has only noted the three first mentioned actors for each movie. 
The network is simple since it is not possible for a movie to link to itself. Below, the network is visualised. 

### Overall Network and Biggest Component

First the overall network is plotted below:

<figure style="text-align: center;">
  <img src="./images/overall_network1.png" width="500"/>
</figure>

This plot shows how some of the movies have no shared actors with other movies. The reasons for them to not be connected could be if they are from other countries than USA or UK, or if the actors are unknown. These movies are not interesting for the further investigation. The not-connected movies represents 18 % of the dataset, and when removing them the graph still consists of 774 nodes. Therefore, the biggest component is considered representative. This is plotted below:

<figure style="text-align: center;">
  <img src="./images/big_component1.png" width="500"/>
</figure>

The attentive reader will notice color change of the nodes. The explanation for this is, that the nodes are now colored based on the rankings of the movies. The ranking is divided into three intervals based on the findings from the [Basic Stats](https://lauramarott.github.io/SocialGraphs/BasicStats) with almost the same amount of movie in each rank-category. 
* The high ranked movies are BLUE
* The medium ranked movies are GREEN
* The low ranked movies are RED

### Degrees and Centralities Plots
#### Degree

The network is plotted with nodesize depending on the degree of the nodes, meaning how many connections a movie has to other movies. 

<figure style="text-align: center;">
  <img src="./images/graph_degree1.png" width="500"/>
</figure>

The degree sizes shows that there area difference in the number of connections between the movies, however no clear pattern regarding the ratings can be seen with the naked eye, meaning that this plot does not confirm the hypothesis of good movies using the same popular actors. 
Another way to invesstigate this is the look at the top and bottom 10 movies and there degree and ranking:

<figure style="text-align: center;">
  <img src="./images/degree_nodes_top.png" width="500"/>
</figure>

The table above shows that the top 10 movies based on degrees are all ranked either high or medium, which might indicate that the actors after all have some influence on the ranking.

<figure style="text-align: center;">
  <img src="./images/degree_nodes_bottom.png" width="500"/>
</figure>

This table above on the other hand shows that the bottom 10 movies based on degrees have no clear pattern in which ranks are seen. 

To sum up there might be a very small indicator of popular actors having influence on the popularity when looking at the high/medium ranked movies.

#### Betweenness Centrality

The betweenness is meant to examined the centrality of a movie based on how many shortest paths going through this movie. 

<figure style="text-align: center;">
  <img src="./images/graph_betweenness1.png" width="500"/>
</figure>

Here no pattern is seen at all. The top and bottom betweenness centralities are also investigated:

<figure style="text-align: center;">
  <img src="./images/betweenness_nodes_top.png" width="500"/>
</figure>

It is seen from the above table that nothing is to be said here, since both high, medium and low ranked movies are occuring in the table. 

<figure style="text-align: center;">
  <img src="./images/betweenness_nodes_bottom.png" width="500"/>
</figure>

The same no-pattern can be seen from the bottom movies of betweenness centrality, where no shortest paths are going through any of these movies. 

To sum up, the betweenness centralities show no tendencies on the rankings being influenced by this popularity.

#### Eigenvector Centrality

### Understanding the Network further

### Conclusion
