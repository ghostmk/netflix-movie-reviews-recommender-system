# netflix-movie-reviews-reccomender-system

Netflix provided a lot of anonymous rating data, and a prediction accuracy bar that is 10% better than what Cinematch can do on the same training data set. (Accuracy is a measurement of how closely predicted ratings of movies match subsequent actual ratings.)

For a given movie and user we need to predict the rating would be given by him/her to the movie. 

Objectives:

Predict the rating that a user would give to a movie that he has not yet rated.
Minimize the difference between predicted and actual rating (RMSE and MAPE) 

Get the data from : https://www.kaggle.com/netflix-inc/netflix-prize-data/data

Data files :

```combined_data_1.txt
combined_data_2.txt
combined_data_3.txt
combined_data_4.txt
movie_titles.csv
```
The first line of each file [combined_data_1.txt, combined_data_2.txt, combined_data_3.txt, combined_data_4.txt] contains the movie id followed by a colon. Each subsequent line in the file corresponds to a rating from a customer and its date in the following format:

CustomerID,Rating,Date

MovieIDs range from 1 to 17770 sequentially.
CustomerIDs range from 1 to 2649429, with gaps. There are 480189 users.
Ratings are on a five star (integral) scale from 1 to 5.
Dates have the format YYYY-MM-DD.
