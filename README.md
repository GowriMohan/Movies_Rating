# Movies_Rating

You are given the dataset “movieReplicationSet.csv” which features ratings data of 400 movies from 1097 research participants.

The dataset details are as:

1st row: Headers (Movie titles/questions)
Columns 1-400: These columns contain the ratings for the 400 movies (0 to 4, and missing)
Columns 401-420: These columns contain self-assessments on sensation seeking behaviors (1-5)
Columns 421-464: These columns contain responses to personality questions (1-5)
Columns 465-474: These columns contain self-reported movie experience ratings (1-5)
Column 475: Gender identity (1 = female, 2 = male, 3 = self-described)
Column 476: Only child (1 = yes, 0 = no, -1 = no response)
Column 477: Movies are best enjoyed alone (1 = yes, 0 = no, -1 = no response)

•	We are going to impute the missing ratings with a blend (50:50) of the arithmetic mean of each column and each row. (Let’s say that the rating of user 350 for movie 200 is missing and that the average rating of this user for other movies is 4 and the average rating (by other users) for this movie is 3, then the to-be-imputed rating would be 3.5, using this method.)
