# RECOMMENDATION-SYSTEM

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: GALI SUPRIYA

**INTERN ID**:CT12WJVC

**DOMAIN**: MACHINE LEARNING

**BATCH DURATION**:JANUARY 5TH TO APRIL 5TH,2025

**MENTOR NAME**:NEELA SANTHOSH

# Movie Recommendation System using SVD
A recommendation system is an essential part of modern digital platforms, providing personalized content to users. This project implements a *Movie Recommendation System* using *Collaborative Filtering* and *Matrix Factorization (SVD - Singular Value Decomposition)* to suggest movies based on user ratings. The model is trained on a * dataset from kaggle *, using **Surprise*, a Python library for recommendation systems.

## Tools and Technologies Used
- *Programming Language*: Python  
- *Libraries Used*:  
  - *Pandas & NumPy*: Data manipulation and analysis  
  - *Surprise*: Implementation of collaborative filtering techniques  
  - *Matplotlib*: Data visualization  
  - *GridSearchCV*: Hyperparameter tuning  
  - *Train-Test Split & Cross-Validation*: Model evaluation  

## Methodology
### 1. Data Preprocessing
- The dataset contains *userId, movieId, and rating* columns.
- Missing values were checked and handled.
- The dataset was formatted for use with the Surprise library.

### 2. Model Training (SVD - Matrix Factorization)
- The dataset was split into a *training set (75%)* and a *test set (25%)*.
- *SVD (Singular Value Decomposition)* was applied, which factorizes the user-item matrix into lower-dimensional matrices to predict missing ratings.

### 3. Evaluation & Results
- The *Root Mean Square Error (RMSE) = 0.94, and **Mean Absolute Error (MAE) = 0.74*, indicating good prediction accuracy.
- Cross-validation confirmed *consistent performance, with an average **RMSE of 0.95* and *MAE of 0.75*.

### 4. Generating Movie Recommendations
- For a given user, the system identifies *unrated movies* and predicts ratings for them.
- The top *10 movies* with the highest predicted ratings are recommended.
- Movie names were mapped to their respective IDs to provide meaningful recommendations.

## Outputs and Observations
- *Predicted Ratings: The recommended movies had predicted ratings between **3.8 and 4.5*, ensuring quality suggestions.
- *Rating Distribution Analysis*:
  - Most ratings ranged between *3.5 and 4.0*, indicating users tend to give positive reviews.                      
## Applications of the System
1. *Streaming Platforms (Netflix, Amazon Prime, Disney+)*: Personalized movie/show recommendations.
2. *E-Commerce (Amazon, Flipkart)*: Suggesting products based on customer reviews.
3. *Music and Podcast Platforms (Spotify, Apple Music)*: Recommending songs/podcasts based on user preferences.
4. *Online Learning (Coursera, Udemy)*: Course recommendations based on past enrollments.
5. *Retail Industry*: Predicting customer preferences for targeted marketing.
This project successfully demonstrates *how collaborative filtering and SVD can be used to build an effective movie recommendation system*, providing personalized experiences for users.

## Output of this Task
