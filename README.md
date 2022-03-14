# MovieRecommendation_using_ML
In this project we use a dataset with around 4800 movies and their metadata to predict similar movies to the user.
The libraries used in this are:
Pandas- to load the dataset into a dataframe.
SciKit Learn- two functions from this module are used in our code, TfidfVectorizer() and cosinesimilarity().
Difflib- the function get_close_matches() present in this module is used to find the closest matches to the name entered by the user.

The model works in the fllowing steps: 

-------------------------DATA LOADING AND PREPROCESSING-------------------
1) Loading the dataset into a dataframe.
2) Selecting relevent features to predict the movie names.
3) Replacing the empty cells in those features with empty strings.
4) Combinig the features and then converting the features into feature vectors.
5) Finding the similarity score of all the movies.
--------------------------------------------------------------------------

--------------------GETTING THE MOVIE NAME AND PREDICTION-----------------
6) Accepting the movie name.
7) Making a list of all the move names given in the dataset.
8) Making a list of all the movies that resemble the name of themovie entered by the user.
9) Choosing the movie name at index [0] as this movie is the closest match to the name entered.
10) Finding the index of the movie found in step (9) and enumerating all the similarity scores present at that index and making a liist of them.
11) Sorting this list in descending order and then printing the first 10-15 entries.
--------------------------------------------------------------------------
