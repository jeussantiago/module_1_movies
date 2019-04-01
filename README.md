# Visual Analysis of Profitability by Genres


#Project Method:
The data for the movies in the last ten years was attainable through themoviedb api. To pull more data for the movies, information was webscrapped off the_numbers website focused on the information for the top 500 grossing movies for an equivalent number of years. The visuals for this project were plotted using Pyplot, a matplotlib plotting framework.


#Lab Mates:
- Jeus Santiago <br/>
- Alex Mitrani <br/>

#Motivation
Many movies are flops in the sense that they lose money even though they have a high revenue. There seems to be an underlying cost to the staff, actors, theaters, banks, etc, after a movie is made. This analysis focuses on trying to ease that lost and gives the highest chance of turning a profit in terms of movie genres.

#Spectrum of the Profitability of Movies Given a budget
(scatter plot)
This graph shows the relationship between the budget a movie was given and the profitability it received. It broke any preconceived notion that a higher budget meant a larger revenue which in turn leads to a larger profit. For example, Justice League, which was excluded from the graph had a budget of $500 mil and had a profitability of 1.31 while Paranormal Activity, which was also not included in the plotting because it was a major outlier, had a budget of $15,000 and had a profitability of 12,890. Although these are outlier examples, many movies followed this pattern.

#Getting the Money Spent Back
A movie does not earn 100% of its revenue. There are cost after the movie is made to the crew, theater, and bank. If a movie had a revenue $10 mil, then it will recieve about 45% and if a movie had a revenue of $300 mil, then it would make back about 60%. A movie was considered successful, in this analysis, if it was able make back 50% of its revenue which equates to a profitability score of 2 or more. 

(Bar Graph - Movie Success/Failure in Each Genre)

In the graph above, we see the number of movies in each genre that were considered successful and a failure by the standards we have previously placed. As expected, most movies would contain elements of drama, comedy, action, and thriller most often than others. Unexpectedly, drama and thriller have a high amount of unsuccessful movies. 

(Bar Graph - Percentage of Success/Failure Movies)

The Graph above focuses again on the successful and failed movies set by the standards we have placed but instead in terms of it's percentages. The most surpising result is that documentaries had the highest percentage of success, even though, when you take a look at the previous graph, it had the lowest number of movie releases. Genres like animation and family followed a similar pattern as they had some of the highest chances to succeed though they didn't have as large of a release number as drama or even action.<br/>

