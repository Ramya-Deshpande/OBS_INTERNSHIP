Task name: Movie Data Analysis

Objective:
To analyze a movie dataset to extract meaningful insights related to user ratings, movie popularity, and external IMDb rating. By laveraging data manipulation, statistical analysis, and web scraping techniques, the project helps in understanding trends, user preferences, and movie recommendation strategies.

Dataset Overview: Movie Ratings and Metadata 

Introduction :
The dataset consists of multiple CSV files containing information about movies, user ratings, 
and additional metadata. It is commonly used for movie recommendation systems, data 
analysis, and statistical modeling. The dataset includes key details about movies, user 
interactions, and external ratings from IMDb. 

Dataset Components :
movies.csv 
Contains details about movies, including: 
movieId: A unique identifier for each movie. 
title: The movie’s name, including the release year. 
genres: A list of genres associated with the movie, separated by | (e.g., "Action|Sci-Fi"). 

ratings.csv 
Stores user ratings for movies: 
userId: Unique identifier for each user. 
movieId: The ID of the movie being rated. 
rating: A numeric score given by the user (typically between 0.5 and 5.0). 
timestamp: The time when the rating was submitted. 

tags.csv 
Contains user-generated tags describing movies: 
userId: The ID of the user who added the tag. 
movieId: The ID of the tagged movie. 
tag: A short text description added by users (e.g., "mind-bending," "classic"). 
timestamp: The time when the tag was submitted. 

links.csv 
Provides links between movie IDs and external databases: 
movieId: The internal movie identifier. 
imdbId: The corresponding IMDb ID, used for fetching additional data. 
tmdbId: The corresponding ID for The Movie Database (TMDb). 

Key Use Cases 
1.Movie Recommendation Systems: Analyze user ratings to predict movies users may like. 
2.Statistical Analysis: Examine rating distributions, trends, and biases. 
3.Genre-Based Filtering: Identify popular movies within a specific genre. 
4.IMDb Rating Scraping: Enrich movie data with external IMDb ratings. 
5.User Behavior Analysis: Understand how different users rate and tag movies.

Requirements:
Python 3.x
Pandas
Numpy 

Contents of folder:
moviedataanalysis.ipynb: Python notebook consisting of several questions and code solution.
links.csv
ratings.csv
movies.csv
tags.csv