# Zee_movie_Recommender_Systems

**Summary: Building a Personalized Movie Recommender System**

**Problem Statement and Data Formatting:**
- The objective is to create a personalized movie recommender system based on user ratings and demographic information.
- Data files are provided for ratings, users, and movies, with specific formats and dictionaries.

**EDA, Data Cleaning, and Feature Engineering:**
- Conducted exploratory data analysis (EDA) to understand the dataset's structure and characteristics.
- Cleaned the data by handling missing values, inconsistencies, and performing type conversions.
- Engineered features like 'Release Year' and grouped data based on average rating and number of ratings.

**Recommender System based on Pearson Correlation:**
- Created a pivot table of movie titles and user IDs, handling missing values appropriately.
- Utilized the item-based approach with Pearson Correlation to recommend similar movies based on user input.

**Recommender System based on Cosine Similarity:**
- Implemented Cosine Similarity to compute user and item similarity matrices.
- Developed a recommender system using the nearest neighbors algorithm and Cosine Similarity for movie recommendations.

**Recommender System based on Matrix Factorization:**
- Employed matrix factorization using libraries like cmfrec/Surprise to build a recommender system.
- Evaluated the model's performance using metrics like Root Mean Squared Error (RMSE) and Mean Absolute Percentage Error (MAPE).

**Embeddings for Visualization and Similarity-based Models:**
- Redesigned similarity functions to incorporate embeddings for item-item and user-user similarity.
- Visualized embeddings with different dimensions and analyzed their impact on recommendation accuracy.


**Evaluation Criteria:**
- Defined problem statement and formatted data appropriately (20 points).
- Conducted EDA, data cleaning, and feature engineering effectively (20 points).
- Built recommender systems based on Pearson Correlation, Cosine Similarity, and Matrix Factorization, with appropriate evaluation (60 points).

This summarization outlines the steps involved in creating a comprehensive movie recommender system, covering various approaches and evaluation criteria for ensuring accuracy and effectiveness.
