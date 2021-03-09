This is a simple report and analysis of the information acquired using PowerBI.

Before the analysis, an python script was made to create addicional cvs files: "Genre" and "Stars" columns were separated and relatations created from the original file. This allows for better looking at this data, since you couldn't work with the original fields together.

The first analysed was the comparison between the IMDB rating and the MetaScore. Since the database is IMDB's top 1000 (actually 842, since some entries were removed due to null fields), the IMDB rating was obviously biased. MetaScore ratings vary wildly, having an IMDB score 1 to 2 points higher in comparison (in a 0 to 10 rating) while others, like the movies in the "Film Noir" genre, being in average 1.37 points lower. However, the distribution of the difference between these two ratings seems to follow a normal distribution, varying in 1 point normally. 

In relation to the movies itself, the drama genre composes more than half of the movies (probably because it's a really "open" genre, without an exact definition), followed by comedy, adventure and crime.

Looking at the directors and actors, the count of movies they directed/starred in was used instead of the average rating, since the second option was biased to directors that had few movies in the list. Considering it's only the top 1000, the said director could have one good movie and one hundred bad ones, so counting the ones inside the list made more sense.

For directors, we have Hitchcock with 14 movies, followed by Spielberg with 13 and Miyazaki with 11.

In relation to actors, we have Robert De Niro starring in 16 movies, Al Pacino in 13 and Tom Hanks also in 13 movies.
