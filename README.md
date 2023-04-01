# Movies_Rating

The dataset contains ratings data from 400 movies submitted by 1097 research participants.

• We will impute the missing ratings using a 50:50 blend of the arithmetic means of each column and row. (For example, if user 350's rating for movie 200 is missing and his average rating for other movies is 4 and the average rating (by other users) for this movie is 3, the to-be-imputed rating would be 3.5 using this method.)

• To predict the ratings for each of the 400 films, use a simple linear regression model. Use the ratings of the *other* 399 movies in the dataset to predict the ratings of each movie (this means you'll have a total of 399 predictions).The average COD (Coefficient of determination) of those 400 simple linear regression models is then calculated and a histogram of these 400 COD values (Coefficient of determination) is plotted. 
