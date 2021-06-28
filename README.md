# Analyzing Movie Profitability and Genre Trends

## Project Overview

- Develop actionable insights for Microsoft's new movie division as they determine what kinds of movies to make first
- Analyze provided datasets and collect additional data as required

## Methodology

**1. Explore provided datasets and develop direction for analysis**

**2. Collect additional data as needed**

- Developed a web scraping pipeline to collect data on Netflix's Top Ten feature
- Pass Netflix data through the TMDB API to collect additional data about the titles

**3. Analyze data and prepare findings**
- Using budget and gross data, determine ROI and analyze the relationship between ROI and budget
- Find commonalities among Netflix Top Ten movies from 2021 to help indicate most current viewer trends

## Findings

### Actor Profitability

There is a significant market gap for big budget films led by women. A tentpole movie with a female lead has the potential to stand out from the crowd.

Looking at most profitable actors, the majority of their profits come from Marvel movies -- this points towards a desire for superhero movies, but the absense of non-Marvel superhero movies leads to the conclusion that further analysis is needed to determine whether Marvel's monopoly can be broken.

![Top Grossing Actor Popularity](https://github.com/zelda4669/movie-data-analysis/blob/main/Charts%20and%20Graphs/Top%20Grossing%20Actor%20Popularity.png)

![Actor Profitability](https://github.com/zelda4669/movie-data-analysis/blob/main/Charts%20and%20Graphs/Actor%20Profitability.png?raw=true)

### Domestic ROI

In general, while big budget movies may produce the largest box office numbers, modest budgets provide a much greater ROI. The median budget for top ROI movies is **\$2.75MM**

![Budget vs ROI](https://github.com/zelda4669/movie-data-analysis/blob/main/Charts%20and%20Graphs/Return%20on%20Investment%20by%20Budget.png?raw=true)

When compared to the distribution of genres in the entire dataset, horror and thriller movies greatly outperform other genres in terms of ROI

![Top ROI Genre Distribution](https://github.com/zelda4669/movie-data-analysis/blob/main/Charts%20and%20Graphs/Top%20ROI%20Genres.png?raw=true)

![Full Genre Distribution](https://github.com/zelda4669/movie-data-analysis/blob/main/Charts%20and%20Graphs/Genre%20Distribution.png?raw=true)


### Insights from Streaming Services

Due to the pandemic, analyzing streaming services is the best way to determine the most recent trends. Analyzing the genres of movies from Netflix Top Ten shows the continued dominance of dramas, as well as a potential surge in popularity for comedies.

![Netflix Top Ten Genres](https://github.com/zelda4669/movie-data-analysis/blob/main/Charts%20and%20Graphs/Genres%20of%20Netflix%20Top%20Ten.png?raw=true)
