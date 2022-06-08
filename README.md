# Microsoft Movie Analysis

Rew and Eli

## Overview

## Business Problem
Microsoft is opening a movie studio in response to competition's creation of video content. However, they are not well voiced in the realm of movie production so it is our job to analyze data and create suggestion for; potential studios the company could buy, the range of runtimes to stay within to maximize profits, and what genres of films to make to maximize profits . We used a variety of analyses to determine what the most important factors in movie success are. It is important to take into consideration total revenue for each genre, how long a movie is compared to its profits, how much a studio made from the films they produced.(According to our data analysis) We wanted to answer the question of, "What can Microsoft do to produce successful movies?". Through our data analyzation we were able to come up with answers to this question to maximize profits.

- Buy/Partner with a studio
- Keep movies length's with a range
- Make movies that are condisdered  one of the top 3 grossing genres.


## Data Understanding

We used data from a few different sources, [TheMovieDataBase](https://www.themoviedb.org/), [Rotten Tomatoes](https://www.rottentomatoes.com/), [Box Office Mojo](https://www.boxofficemojo.com/). Using this data we were able to determine important details such as, genres associated with a movie, runtimes, domestic and forgien revenue, studios, years the movies where released, and much more data that we had to then clean to accurately answer the question of, “What can Microsoft do to produce successful movies?” 

## Data Preparation

To prepare our raw data to be useful in our analysis, we had to tke steps to clean our data. We did this buy removing row with nulls for values we needed, in some situations, in other situations we changed the null values to 0. Most times we had to deal with nulls was when we wanted to change the type of an entire column. For example, in one of the databases the forgein gross column were all string types and had nulls as values. When we tried to add data in this column with the data from another column to create a new column as the total it would not work. We had to make those values null the sting ‘0’ and then turn all of the values in that column into floats to add to the other column whose values were floats.

## Evaluation

 <figure>
<img src="genre.png" alt="genre"/>
</figure>

One of the first questions we posed was “which genres generate the most money?” According to our graph, the top three money makers are Science-Fiction, Animated movies, and Adventure movies. For Microsoft to make the most money, they should look to the top genres. Another thing they could look for is what combinations of genres are most profitable. 

<figure>
<img src="studio.png" alt="studio"/>
</figure>

The next question we examined was which studios were able to generate the most money. As Microsoft is new to the movie industry, they may have increased success by partnering with one of these companies, or at the very least, using their strategies and business models to succeed. According to our table, the best three Studio’s to work with would be Imag., Scre., or Argo. in that order. They could also buy one of the studios that was not making as much as the other companies and use their resources to shape a studio in their image.

<figure>
<img src="scatter.png" alt="scatter"/>
</figure>

According to our data, we would recommend Microsoft to keep the runtime of their movie between 100 and 150 minutes. These movies have the highest profitability. Past 150 minutes, there is a steep decrease in revenue. Similarly, movies shorter than 90 minutes do not make a lot of money. 
