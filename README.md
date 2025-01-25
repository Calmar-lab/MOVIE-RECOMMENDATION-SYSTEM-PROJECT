![images](https://github.com/user-attachments/assets/e5a94c75-f06e-4313-a3d3-f8570e563bb7)
# MOVIE-RECOMMENDATION-SYSTEM-PROJECT
## Authors:
1.Calmar Isoe

2.Daniel Karue

3.Vernesser Pamelah

4.Precious Kalia

5.Sharleen Liz

## Project overview
The MovieLens Recommendation System project aims to develop a recommendation system that provides personalized movie suggestions to users based on their past ratings. The goal is to predict and recommend the top 5 movies that a user is likely to enjoy. Leveraging the MovieLens dataset, which contains 100,000 user ratings, this project applies collaborative filtering techniques to recommend movies that align with user preferences based on their rating history.

## Business Understanding
The project aims to develop a personalized movie recommendation system using the MovieLens dataset. With an ever-growing library of movies, users often struggle to find content that aligns with their preferences. This recommendation system leverages collaborative filtering to predict user ratings and suggest the top 5 movies for each user based on their past interactions.

  ### Objectives

   .Conduct thorough exploratory data analysis (EDA) to understand user preferences and rating trends.

   .Develop a recommendation system that provides personalized movie recommendations based on user ratings.

   .Implement collaborative filtering and content-based approaches to improve recommendation accuracy.

   .Evaluate the recommendation system using appropriate performance metrics to ensure relevance and accuracy.

   .Provide actionable insights to stakeholders to enhance user satisfaction and engagement strategies.
   
## Data Understanding
The dataset used in this project is sourced from the GroupLens Research team, titled "MovieLens Latest Small Dataset." It is a CSV-based dataset containing user ratings, movie information, and additional features relevant for building a recommendation system. You can access it here: [MovieLens Dataset](https://grouplens.org/datasets/movielens/latest/).
The data are contained in the files `links.csv`, `movies.csv`, `ratings.csv` and `tags.csv`.

All ratings are contained in the file `ratings.csv`. (0.5 stars - 5.0 stars).

Movie information is contained in the file `movies.csv`. 

## Data Cleaning and Preparation
Tools and Libraries:
   .pandas
   
   .numpy
   
   .matplotlib
   
   .seaborn
   
   .sickit learn
   
   .surprise
   
   .jupyter notebook
   

   1.Handling missing values: There were no missing values.
   
   2.Checking for duplicated values: there were no duplicates.
   
   3.Handling outliers: they were left as they were.
   
   4.Merging Datasets: Relevant datasets were merged based on common keys to create a unified dataset for analysis.

   ## Data visualisation

   ![pic1](https://github.com/user-attachments/assets/31ecfa55-02f9-4969-8eaa-8a4e11cb8c41) 
   how ratings are distributed across the dataset to identify trends like whether users tend to give higher or lower ratings.
   

   ![pic2](https://github.com/user-attachments/assets/608e7128-32d1-429b-aad2-48403e03ed12)
   ![pic3](https://github.com/user-attachments/assets/b8a685e8-86ee-49e8-ae24-81d1102af53e)
   examine which genres receive the most ratings as well as the highest average ratings to understand audience preferences.


   ![pic4](https://github.com/user-attachments/assets/11985307-a33e-409f-b67e-7e17d6f31f49)
   ![pic5](https://github.com/user-attachments/assets/f1b66f5e-14e8-41b1-a17b-e9fd0590856b)
   identify movies with the highest average ratings and those with the most ratings to determine popular movies. We'll also see whether the results here will be consistent with the 
   analysis of genre popularity


   ![pic6](https://github.com/user-attachments/assets/a3b41fc0-d795-499b-9db1-0c38a838ba8d)
   visualize the ratings trends over time to investigate how ratings have changed over the years.


   ![pic7](https://github.com/user-attachments/assets/90fbdb05-52d0-476b-8555-9e73a5a36997)
   check if highly active users tend to rate movies differently compared to less active users.


   ![pic8](https://github.com/user-attachments/assets/7db7fa85-d7f8-4348-80b4-bb45a7f17b0e)
   ![pic9](https://github.com/user-attachments/assets/e4750bad-0063-4614-a45a-c59ad56e7e16)
   investigated new users or movies with very few ratings, which could impact the effectiveness of recommendations.


   ![pic10](https://github.com/user-attachments/assets/0269f703-0232-4a0f-afaf-1234908cb335)
   visualised sparcity in ratings

   ## Analysis Summary
   Our analysis process included:

   1.Data Cleaning and Preprocessing: Cleaning and merging datasets to ensure consistency across data sources.

   2.Exploratory Data Analysis (EDA): a detailed review of key columns to uncover trends and relationships within the data.

   3.Visualization and Insights: Creating visualizations to highlight key findings and trends in successful films, which we translated into actionable recommendations.

   ## Key Findings
   The following insights were derived from the MovieLens Recommendation System project:

   1.High Predictive Accuracy: The collaborative filtering model achieved an RMSE of 0.876, indicating accurate prediction of user ratings for unseen movies.

   2.Top Recommendations: For User 1, the system recommended the top 5 movies: [871, 660, 586, 896, 4673]. These recommendations were tailored based on the user's past preferences.

   3.The optimal parameters for the collaborative filtering model were identified as:
      n_factors = 10
      n_epochs = 20
      lr_all = 0.005
      reg_all = 0.02
      These settings significantly improved the model's performance.
      
   4.Popular Genres: Analysis of the genres for the recommended movies revealed a preference for genres such as Drama, Comedy, and Action, reflecting common user interests.
   
   5.Cold Start Problem: The system handled the cold start problem effectively by integrating a hybrid approach that uses movie metadata, such as genres, alongside collaborative 
    filtering.

## Recommendations 
Based on our findings, we suggest the following strategies:

1. Personalized promotion strategies:
Focus marketing efforts on movies consistently rated above 4 and promote highly rated niche genres to attract dedicated audiences.

2. Genre-based content expansion:
Increase content acquisition and production in high-demand genres like drama, comedy, and action to align with user preferences.

3. User segmentation for targeted engagement:
Develop loyalty programs and premium recommendation services for highly active users who provide more stable and valuable feedback.

4. Peak engagement planning:
Leverage historical rating trends to schedule content releases and promotions during peak engagement periods to maximize impact.

5. Differentiated recommendation strategies:
Offer separate recommendation lists for "popular" and "high-quality" movies to cater to diverse user preferences and expectations.

6. Cold-start mitigation:
Introduce content-based filtering or hybrid models to enhance recommendations for new users with limited rating history.

       









   



   

   
   

