# Yelp_data
# Recommender System using Yelp dataset

   - Helaleh Alimohammadi - https://www.linkedin.com/in/helaleh-alimohammadi/

**Introduction**

   In this project we have used various different machine learning methods to explore the large dataset that is provided by Yelp on kaggle. (https://www.kaggle.com/yelp-dataset/yelp-dataset)


## Part 1: EDA-Visualization

   This part of the project we chose Toronto which has the highest number of businesses in Canada. Since the restaurant business has the greatest number of user reviews we decided to analyse more on restaurant businesses in Toronto.

Here you can see

   * what are the popular Vegetarian restaurants and what are the popular restaurants by checkins?,
   * what are the top categories comparison for 4 different cities in North America (Toronto, Las Vegas, Calgary, Montreal)?,
   * what are the user characteristics based on their reviews?,
   * who are the most influencers?,
   * what is the trend of user activity over time?

## Part 2: Prediction-sentimental anaylis (NLP)

   To classify reviews to positive and negative, natural language processing method was used:
   
   * creating the bag of words by using TF-IDF method with different n-grams (1-3)
   * word clouds for positive and negative reviews
   * sentiment prediction of user reviews using different machine learning models (Logistic Regression, Random Forest, XGBoost)

## Part 3: Recommender Systems

   We used two different recommender methods to recommend restaurants:

   **1. Content based:** 
   
   We used k-Nearest neighbour Classifier from pandas sklearn to find similar restaurants for a specific restaurant.

   **2. Collabaretive Filtering:**
   
   Here, we recommend restaurants to the popular restaurant based on similar users interest (ratings).
   
   * SVD - Singular value Decompossion
   * Neural Network - Keras

**Thank you!**
