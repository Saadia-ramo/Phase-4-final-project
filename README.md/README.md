# MOVIE RECOMMENDER SYSTEM PROJECT
# PROJECT OVERVIEW

In this project i developed a movie recommender system using MovieLens dataset. I applied machine learning techniques to suggest movies to users based on their preferences and past ratings. This system combines both content-based filtering and collaborative filtering techniques to develop a hybrid system in order to improve recommendation quality. I, Later on developed a hybrid recommender system to eliminate the challenges of the two systems and leverage their capabalities.

# Problem Statement
With the large number of movies available, user often struggle to find relevant content. This project aims to solve this problem by building a system that can predict and recommend movies a user is likely to enjoy.

# Objectives
- Load and explore the MovieLens dataset
- Perform data cleaning and preprocessing
- Conduct Exploratory Data Analysis (EDA)
- Build recommendation models using:
 - content-based filtering
 - collaborative filtering
- Evaluate model performance using RMSE
- Improve model accuracy through hyperparameter tuning
-Build a hybrid model

# Dataset
The project uses the MovieLens dataset which includes:
- Movies dataset ( movie titles and genres)
- Ratings dataset (user ratings for movies)
- Tags dataset (user-generated tags)

# Methodology
 Data Loading- Import and inspect datasets
 Data Preprocessing - Merge datasets and handle missing values
 Exploratory Data Analysis - Understand rating patterns and genre distribution
 Feature Engineering - Convert text data using TF-IDF
 Model Building:
 - Content-based filtering using cosine-similarity
 - Collaborative filtering using SVD
 Model Evaluation - Using RMSE to measure prediction accuracy
 Hyperparameter Tuning - using GridSearchCV to improve performance

 # Results
 The model was evaluated using RMSE. After tuning, the performance improved compared to the baseline model,showing better prediction accuracy.

 # Technologies used
 -Python
 -Pandas
 -Surprise library
 -Scikit-learn
 -Jupyter Notebook
 -Git & Github

 
