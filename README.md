# Box Office Prediction
Project title: Predicting a Movie’s Popularity and Box Office Revenue Using 5000 Movie Database from TMDB and IMDB
Team members: Keyi Jiang, Freya Wang, Rita Xu
Data Set:
- Description: For this project, we are using the data set from TMDB 5000 Movie Dataset and IMDB 5000 Movie Dataset from two mainstream movie rating and review websites. These two datasets contain multiple facets of information about the top 5000 movies including numeric data like budget, category data including issue company, crew information, genre and keyword tag, text data including plot overview and reviews, and etc. Two datasets we are using are slightly different in some columns and we plan to merge them when needed.
- data set 1 from TMBD:
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5
000_movies.csv
- data set 2 from IMBD:
https://github.com/Godoy/imdb-5000-movie-dataset/blob/master/data/movie_ metadata.csv
Project Idea:
We want to develop a model to predict popularity and revenue of the movie with all the information before issuing. It would be useful for movie studio and investor to assess the potential of an movie before the production and releasing. Also, it can be used for the movie company to determine their marketing strategy regarding cinema scheduling and public promotion.
The Machine Learning tools we plan to use are:
1. Since we have multiple variables, we want to use PCA to explore the data set.
Maybe we will replace the highly correlated variables with fewer variables.
2. We plan to use KNN, Random Forest, Boosting, SVM and CNN to predict the popularity and revenue of different movies. And we will use the prediction
accuracy to compare these models.
3. Since the data set includes character variables such as the overview and
tagline, we plan to do the sentiment classification and turn it into a categorical
varibale, which will be included in our prediction model.
4. We also want to do cluster analysis to find the typical patterns of similar
movies.
