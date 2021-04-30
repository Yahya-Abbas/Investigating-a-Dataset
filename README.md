# Udacity Advanced Data Analysis: Investigate a Dataset (TMDb movie data) Project

In this project, I analyze the TMDB movies dataset and communicated my findings about it.

What determines if a movie is considered good or bad?
There could be several factors influencing the quality of a movie, as for example the budget, genre, etc. Here, I explore some of the success criteria for movies.

First some Data Wrangling was applied, before the data was cleaned in order to perform Exploratory Data Analysis.

## The TMDB Dataset

This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.

> **General Info about this dataset**:
>
> -   It has a total of 10866 rows and 21 columns
> -   Certain columns, ('cast', 'director', 'keywords', 'genres', 'production_companies'), contain multiple values separated by pipe (|) characters.
> -   There are some odd characters in the ‘cast’ & 'director' columns.
> -   The final two columns ending with “\_adj” show the budget and revenue of the associated movie in terms of 2010 dollars, accounting for inflation over time

## Interesting Questions

1. Which genres are most popular from year to year?

2. What kinds of properties are associated with movies that have high revenues?

3. Does higher average vote (rating) corellate with higher revenues? (we can check for this using raw revenues or revenues_adj to account for inflation)

4. What is the film with the highest budget each year?

## Files

-   `Investigate TMDB Dataset.ipynb`: the main code and report for the data wrangling and analysis process.
-   `Investigate_a_Dataset.html`: the exported HTML file of the jupyter notebook.
-   `tmdb-movies.csv`: the original data from TMDB.

## Requirements

-   [Pandas](https://pandas.pydata.org/) `version 0.25.0 or higher`
-   [NumPy](https://numpy.org/)
-   [Matplotlib](https://matplotlib.org/)
