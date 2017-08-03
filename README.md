# Movies-HiveQL
This repository contains some brief HiveQL querying examples on an open-source movie database.
 
## Dataset
The data for this project can be found here (100K dS): https://grouplens.org/datasets/movielens/.
For this project, only the u.data and u.item tables are used. 
   ### u.data
   This file contains 100000 ratings by 943 users on 1682 items. It is a tab separated list of: <br />

     user id | item id | rating | timestamp 
     
   Timestamp is in unix seconds.
   
   ### u.item
   This file contains information about each item (movies). It is a tab separated list of: <br />

    movie id | movie title | release date | video release date | IMDb URL | unknown | Action | Adventure | Animation |Children's | Comedy | Crime | Documentary | Drama | Fantasy |Film-Noir | Horror | Musical | Mystery | Romance | Sci-Fi |Thriller | War | Western

   The last 19 fields contain genres (1 indicating the movie belongs to the genre and 0 indicates it does not).

## Skills
This analysis relies on HiveQL statements and includes SELECT, WHERE, GROUP BY, ORDER BY, LIMIT and JOIN commands. 

## Analysis
Queries on this dataset include:
 * How many records are in each table?
 * What are the names of the movies released in 1990?
 * What are the movie id's for the 10 films that recieved the most ratings?
 * What are the titles of the movies with the 10 most ratings?
 * What is the highest average rated sci-fi movie?
 * Are there any movies with no ratings?
