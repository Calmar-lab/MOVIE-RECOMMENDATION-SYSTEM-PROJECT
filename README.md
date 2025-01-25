# MOVIE-RECOMMENDATION-SYSTEM-PROJECT
This project aims to develop a recommendation system that provides personalized movie suggestions to users based on their past ratings. The goal is to predict and recommend the top 5 movies that a user is likely to enjoy. 
## Features
- **Collaborative Filtering:** Utilizes user-item interaction data to predict ratings for unseen movies.
- **Top-5 Recommendations:** Generates personalized movie suggestions for users.
- **Performance Evaluation:** Implements metrics like RMSE and MAE to assess the accuracy of predictions.
- **Data Preprocessing:** Handles missing values, duplicates, and encodes categorical data.
- **Hybrid Approach (Optional):** Combines collaborative and content-based filtering to address cold start issues.

## Dataset
The project uses the "small" MovieLens dataset, which contains 100,000 user ratings and metadata for movies.

- **Ratings Dataset:** Contains user IDs, movie IDs, explicit ratings, and timestamps.
- **Movies Dataset:** Contains movie IDs, titles, and associated genres.

You can find the dataset [here](https://grouplens.org/datasets/movielens/).

## Requirements
The following libraries are used in the project:
- **Python 3.7+**
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `surprise` (for collaborative filtering)

### Installation
To install the required dependencies, use the following commands:  
```bash
pip install pandas numpy matplotlib seaborn scikit-learn scikit-surprise
