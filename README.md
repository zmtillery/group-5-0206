# group-5-0206
## Overview


## Business Understanding 
    Stakeholders: Computing vision - An innovative and dynamic movie production company dedicated to creating their first film that showcases cutting-edge visual effects and makes a mark on the cinematic storytelling industry.

    Business Problem: Provide actionable insights that the head of Computing Vision's new movie studio can use to help decide what type of films to create. The insights were determined by data aggregation and alaysis techniques as well as statistical analysis'
    
    Key Business Questions: What metric's do Computing Vision want to track and use to gauge success of the movie studio? Are there any predefined limitations on budget, writers/directors, etc. that could impact the recommendations given?


## Data Understanding 
    We retrieved our data from tn.movie_budgets.csvfile and the IMDB SQL database, which served as the primary sources of our analysis. The   tn.movie_budgets.csv dataset provided insight into the production budget of each movie as well as the gross domestic revenue and the total     worldwide revenue of the movie. The IMDB dataset provided insight into categorical data about the movies including writers, directors, genre, runtime, ratings, etc. These datasets also both include the name of the movie, which allows us to join the datasets together so that we were able to analyze and make recommendations
    
## Data Analysis
________________________
    
## Comparing Production Budget vs. Profit
![production](./Visualizations/download.png)

## Comparing Top 10% Directors Profit vs All Profit
![directors](./Visualizations/to50_dir.png)

## Example of Top 10 Directors
![top_directors](./Visualizations/top10_dir.png)


## Statistical Inference 
________________________________


## Comparing Profits by Genre 
![genres](./Visualizations/genres.png)

## TTest Graph of Adventure Genre
![adventure](./Visualizations/AdvTtest.png)

## TTest Graph of Animation Genre
![animation](./Visualizations/aniTtest.png)

## Results:
Adventure: P-Value: 6.24 * 10-7 with a sample size of 200

Animation: P-Value: 0.10 with a sample size of 21


## Intrepretation of Results:
Tested adventure and animation at a 95% confidence interval
Relationship between adventure genre and profit is statistically significant
Can not confirm that relationship between the animation genre and profit is statistically significant



## Conclusion
____________________

## Recommendations

The analysis of production budget vs profits showed that Computing Vision should allocate a production budget that maximizes the chance of profitability and maintains a reasonable financial risk to Computing Vision

The analysis of directors vs profit showed that computing vision should hire one of the top 10% of directors to direct their movie 

The statistical analysis showed that computing vision should make an adventure movie. 











