# Visual Analysis of Profitability by Genres


#Project Method:
The data for the movies over the last ten years was obtained through themoviedb api. Further information was webscrapped off the_numbers website focusing on information for the top 500 grossing movies for an equivalent number of years. The visuals for this project were plotted using Pyplot, a matplotlib plotting framework.


#Lab Mates:
- Jeus Santiago <br/>
- Alex Mitrani <br/>

#Motivation
Many movies are flops in the sense that they lose money even though they have a high revenue. There seems to be an underlying cost to the theaters and banks, etc, after a movie is made that is not accounted for in the budget. This analysis focuses on trying to ease that loss and gives the highest chance of turning a profit in terms of movie genres.

#Spectrum of the Profitability of Movies Given a budget
(scatter plot)
This graph shows the relationship between the budget of a movie and its profitability. It broke any preconceived notion that a higher budget meant a larger revenue which in turn leads to a larger profit. For example, Justice League, which was excluded from the graph had a budget of $500 mil and had a profitability of 1.31 times budget while Paranormal Activity, which was also not included in the plotting because it was a major outlier, had a budget of $15,000 and had a profitability of 12,890. Although these are outlier examples, many movies followed this pattern.

Genre Analysis:

#Getting the Money Spent Back
A movie does not earn 100% of its revenue. There are cost after the movie is made to the crew, theater, and bank. If a movie had a revenue $10 mil, then it will recieve about 45% and if a movie had a revenue of $300 mil, then it would make back about 60%. A movie was considered successful, in this analysis, if it was able make back 50% of its revenue which equates to a profitability score of 2 or more. 

(Bar Graph - Movie Success/Failure in Each Genre)

In the graph above, we see the number of movies in each genre that were considered successful and a failure by the standards we have previously placed. As expected, most movies would contain elements of drama, comedy, action, and thriller most often than others. Unexpectedly, drama and thriller have a high amount of unsuccessful movies. 

(Bar Graph - Percentage of Success/Failure Movies)

The Graph above focuses again on the successful and failed movies set by the standards we have placed but instead in terms of its percentages. The most surpising result is that documentaries had the highest percentage of success, even though, when you take a look at the previous graph, it had the lowest number of movie releases. Genres like animation and family followed a similar pattern as they had some of the highest chances to succeed though they didn't have as large of a release number as drama or even action.<br/>

We then decided to focus on the middle 80% of data points by profitability to eliminate outliers that were made on budgets far below what studios such as Lions Gate would typically allot per movie.

Our goal is to see if any movie genre(s) were consistently profitable over time. The chart titled "Average Movie Profitability By Genre Over Time" displays the profitability of each genre's middle 80% of data points over time. This was our first attempt to see if any genres consistently performed well over time. 

![Average Movie Profitability By Genre Over Time](https://user-images.githubusercontent.com/45886439/55345073-0733ef00-547d-11e9-9045-542df153a9d6.png)

This chart was heavily influenced by the count of movies by genre in each year. For instance: when a small number of films were made during that year in a particular genre the average would be greatly affected by the individual movies. This analysis further proved to be difficult to interpret.

<<"Top Three Movie Genres By Average Profitability: 2009 - 2018">>

The above figure shows the top three movie genres by profitability over the last ten years. The reasoning behind this chart is to see if any particular genre(s) consistently outperform others overtime. For instance, Family, Animated, and Documentary films consistently appeared in the top three genre categories over time. We found the performance of documentaries to be surprising because they don't traditionally have wide releases. 

The revenue of films by genre over the last ten years fell between 2.21 (in 2009) and 4.25 (in 2012) times their budget on average. If Lions Gate focuses on the genres that consistently outperform the average profitability of other genres then they could reasonably expect to create films that have a profitability within that range.


Next steps:

- Compare the performance of Lions Gate films to the average films on the same budget

- Examine movie genre combinations to see if any outperform the others

- Examine Actors and Directors to see if any are creating films that are outperforming others for a given salary level.

