# Movie Recommendation System

## Project Overview
This project develops a movie recommendation system using the MovieLens dataset. The system suggests five movies to new users based on their provided ratings, employing collaborative filtering techniques with potential hybrid approaches to address cold start issues.

## Project Goal
- Objective: Develop a movie recommendation system capable of suggesting five movies to new users based on their provided ratings.
- Dataset: Utilizes the MovieLens dataset with CSV files for movies, ratings, tags, and links.

## Data
The project uses the MovieLens dataset, which includes:
- ratings.csv: User ratings for movies
- movies.csv: Movie information including titles and genres
- links.csv: Links to movie pages on IMDb and TMDb
- tags.csv: User-generated tags for movies

## Methodology
1. **Data Loading & Cleaning:**

- Loaded data from CSV files: movies.csv, ratings.csv, tags.csv, links.csv.
- Conducted data cleaning to handle duplicates, null values, and ensured data consistency.

2. **Exploratory Data Analysis (EDA):**

- Performed feature engineering: created columns for 'year_produced' and 'movie'
- Visualized most watched genres and trends over the years.

3. **Modeling:**

- Baseline Model: Implemented KNN algorithms for collaborative filtering.
- Advanced Model: Used SVD (Singular Value Decomposition) with hyperparameter tuning for better accuracy.
- Hybrid Approach: Combined collaborative filtering with content-based filtering (genres and tags) to address cold start issues and improve recommendations.

4. **Evaluation:**

- Evaluated models using metrics such as RMSE (Root Mean Squared Error) and MAE (Mean Absolute Error).
