![Thunderhouse Films](images/GH_Header.png)

# Thunderhouse Films Box Office Analysis
Authors: 
- [Lillian Lakes](https://github.com/lillianlakes) [(GitHub Lead)](https://www.linkedin.com/in/lillianlakes/)
- [Madeleine Smithers](https://github.com/MaddieSmithers) [(Technical Lead)](https://www.linkedin.com/in/madeleinesmithers/034123/)
- [Stuart Clark](https://github.com/sclarkHOUis-project/tree/Stuart) [(Presentation Lead)](https://www.linkedin.com/in/stuart-clark-185034123/)


## For More Information
To explore our findings further, please view our [Project Deck](box_office_presentation.pdf). 

## Overview

This project presents an analysis of past film data that aims to provide concrete recommendations to Thunderhouse Films, an emerging film studio. It analyzes production budgets, box office revenue, genres, and release times in order to predict the most profitable strategy for producing and releasing films. Descriptive analysis and regression analysis of production budget and gross sales data show that horror films in the mid-budget range bring in the highest returns on investment, especially when released in the weeks leading to Halloween. Thunderhouse films can use our analysis to target movies with the highest ROI as they launch their new movie studio and later expand.

## Business Problem

Entering the movie business requires a certain level of risk and capital allocation. By analyzing data of past films, we hope to devise a strategy that will make the most effective use of each dollar our client spends as a new film studio. The most important metric in this case is the Return on Investment (ROI) from each film, since producing a film is an expensive endeavor and we want to ensure the payoff is maximized. We saw three main categories that a new entrant into the industry would need to consider. These include how much to spend on a film, what genre to produce, and when to release the film. We first start off by segmenting the market into low, mid, and high-budget films, as these three segments all differ in their optimal strategy. We then use the main genre associated with each film to look across our market segments for the highest median ROI, in order to account for outliers. Finally, we assess the best time to release a film by analyzing our top genre across each month of the year to find where films repeatedly yield high returns. 

## Data Understanding

Our initial data comprised of datasets from [Box Office Mojo](https://www.boxofficemojo.com/), [IMDB](https://www.imdb.com/), [Rotten Tomatoes](https://www.rottentomatoes.com/), [TheMovieDB](https://www.themoviedb.org/), and [The Numbers](https://www.the-numbers.com/). For our specific goals of analyzing budget ranges, genres, and release dates, we decided to use data from The Numbers and IMDB, as these were the most informative and robust for our purposes. We did notice limitations in our available data from the beginning, including the lack of additional revenue streams outside of the box office, missing information on costs to produce films which would have complemented production budget data, and not accounting for inflation. After appropriate data cleaning and exploration, we decided to filter out films that were not released theatrically since we could only compare revenue from the box office. We also decided to only use data on films released between 2010 and 2020, since this window is where we had the most reliable data. 

## Methods

This project uses descriptive analysis, including snapshots of top movies and top genres by median ROI for each budget category and a display of median ROI by month of release for the mid-budget horror category, to support our recommendations. We also ran a regression to show how much variation in worldwide gross sales is explained by production budget and support our decision to use ROI as a metric since we calculated ROI as worldwide gross sales divided by production budget multiplied by 100.

## Results


## Conclusions
Horror Films Bring in Scary High ROIs 
![Clown from 'It' movie](images/IT_Header.png)

### Next Steps


## Repository Contents
