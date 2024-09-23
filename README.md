# MOVIE_RECOMMENDATION_SYSTEM
This project is a Movie Recommendation System built using Cosine Similarity on IMDB dataset sourced from Kaggle. The model recommends the top 5 movies based on user preferences.

## Project Overview
The goal of this project is to develop a content-based movie recommendation system. Using Cosine Similarity and CountVectorizer, the system finds similar movies based on features such as genre, director, and keywords from the IMDB dataset. The top 5 movies are recommended to users based on similarity scores.

## Project Workflow
### Data Preprocessing:

### Cleaned and preprocessed the IMDB dataset.
> Merged various features like title, genre, and keywords into a single feature for similarity comparison.
Vectorization:

> Used CountVectorizer to convert text features into a sparse matrix of token counts.
Cosine Similarity:

> Calculated the cosine similarity between the movies based on their feature vectors.
Recommendation Engine:

> Built a function to recommend the top 5 similar movies based on the cosine similarity score.

## Results
The recommendation system outputs the top 5 movies most similar to the movie selected by the user, offering a personalized movie suggestion experience.
