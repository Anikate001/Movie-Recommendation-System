# Movie-Recommendation-SystemMovie Recommendation System


A user-based collaborative filtering movie recommendation system built with Python and pandas using the MovieLens dataset.

This project builds a recommender that predicts user ratings and suggests movies tailored to their tastes based on similar users’ preferences.

Dataset
Based on the MovieLens ml-latest-small dataset (containing ratings and movie metadata).

Dataset files required: ratings.csv and movies.csv.

Features
Loads and preprocesses MovieLens data.

Creates user-movie ratings matrix.

Calculates user-user similarity using cosine similarity.

Predicts movie ratings weighted by similar users.

Recommends top-N movies to a given user.

Evaluates the system with mean squared error (MSE) & mean absolute error (MAE).

Visualizes recommended movies with predicted rating scores.

Usage
Upload ratings.csv and movies.csv from the MovieLens dataset.

Run the notebook cells sequentially to perform data loading, training, evaluation, and recommendations.

Use recommend_movies_with_scores(user_id, user_movie_matrix, user_similarity, movies) to get visual recommendations for any user.

Evaluate accuracy metrics (MSE, MAE) to assess model performance.

Results Example
Test MSE: 10.4012

Test MAE: 3.0590

Top recommended movies for User 1 include:

Twelve Monkeys (1995)

Apollo 13 (1995)

Shawshank Redemption, The (1994)

Aladdin (1992)

Terminator 2: Judgment Day (1991)

Godfather, The (1972)

The Sixth Sense (1999)

Lord of the Rings: The Fellowship of the Ring (2001)

Lord of the Rings: The Two Towers (2002)

Lord of the Rings: The Return of the King (2003)

Visualization
![Recommendation Bar Chart]
<img width="824" height="313" alt="image" src="https://github.com/user-attachments/assets/3f09b68d-1d37-4e53-8aca-c944f91a4e23" />


Dependencies
The project requires the following Python libraries:

pandas

numpy

scikit-learn

matplotlib

You can install them with:

bash
pip install -r requirements.txt
requirements.txt
text
pandas
numpy
scikit-learn
matplotlib


