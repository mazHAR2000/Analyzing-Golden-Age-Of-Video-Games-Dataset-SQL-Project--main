# Analyzing-Golden-Age-Of-Video-Games-Dataset-SQL-Project-
This repository contains SQL queries analyzing a dataset from the Golden Age of Video Games. With eight tasks fulfilled, explore trends in genres, regional sales, and more for insightful insights into this iconic era of gaming.

Tables :

1. game_sales
column	     type	          meaning
game	      varchar	      Name of the video game
platform	  varchar	      Gaming platform
publisher	  varchar	      Game publisher
developer	  varchar	      Game developer
games_sold	float	        Number of copies sold (millions)
year	      int	          Release year

2. reviews

column	        type	         meaning
game	         varchar	     Name of the video game
critic_score	 float	       Critic score according to Metacritic
user_score	   float	       User score according to Metacritic


TASK 1:
Find the ten best-selling video games in game_sales.

Select all columns for the top ten best-selling video games (based on games_sold) in game_sales.
Order the results from the best-selling game down to the tenth best-selling game.

TASK 2:
Determine how many games in the game_sales table are missing both a user_score and a critic_score.


TASK 3:
Find the years with the highest average critic_score.

TASK 4:
Find game critics' ten favorite years, this time with the stipulation that a year must have more than four games released in order to be considered.

TASK 5:
Use set theory to find the years that were on our first critics' favorite list but not the second.
Select the year and avg_critic_score for those years that were on our first critics' favorite list but not the second due to having four or fewer reviewed games.
Order the results from highest to lowest avg_critic_score.

TASK 6:
Update your query from Task Four so that it returns years with ten highest avg_user_score values.

TASK 7:
Create a list of years that appear on both the top_critic_years_more_than_four_games table and the top_user_years_more_than_four_games table.
Using set theory, select only the year results that appear on both tables.

TASK 8:
Add a column showing total games_sold in each year to the table you created in the previous task.
