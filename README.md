# Collaborative Filtering Model on Movies database (Kaggle)
The dataset is taken from Kaggle. It consists of movies released on or before July 2017. Data points include cast, crew, plot keywords, budget, revenue, posters, release dates, languages, production companies , countries, TMDB vote counts and vote averages. The dataset also has files containing 26 million ratings from 270,000 users for all 45,000 movies. Ratings are on a scale of 1-5 and are obtained from the official GroupLens website.

The objective is to create a collaborative filtering based recommendation system. We achieve this goal by discovering the preferences of users from the data, creating a utility matrix consisting of each user-item rating values and predicting the blank cells in this utility matrix.
