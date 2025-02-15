# MOVIE-RECOMMENDATION-SYSTEM-PROJECT
This project aims to develop a recommendation system that provides personalized movie suggestions to users based on their past ratings. The goal is to predict and recommend the top 5 movies that a user is likely to enjoy. 
## Authors:
1. Calmar Isoe

2. Daniel Karue

3. Vernesser Pamelah

4. Precious Kalia

5. Sharleen Liz


## Project Files

The project files can be found in the repository's file directory:

- **Datasets** – Available in the `links.csv`, `movies.csv`, `ratings.csv`, and `tags.csv` folders.
- **Data Report** – Located in the `Data Report.pdf` folder.
- **Non-Technical Presentation** – Found in the `Non_technical_presentation.pdf` folder.
- **Jupyter Notebook** – Available in the repository's main directory as `MOVIE_RECOMMENDATION_SYSTEM_PROJECT.ipynb`.


## PROJECT OVERVIEW
The MovieLens Recommendation System project aims to develop a recommendation system that provides personalized movie suggestions to users based on their past ratings. The goal is to predict and recommend the top 5 movies that a user is likely to enjoy. Leveraging the MovieLens dataset, which contains 100,000 user ratings, this project applies collaborative filtering techniques to recommend movies that align with user preferences based on their rating history.


## BUSINESS UNDERSTANDING
The project aims to develop a personalized movie recommendation system using the MovieLens dataset. With an ever-growing library of movies, users often struggle to find content that aligns with their preferences. This recommendation system leverages collaborative filtering to predict user ratings and suggest the top 5 movies for each user based on their past interactions.

  ### Objectives

   - Conduct thorough exploratory data analysis (EDA) to understand user preferences and rating trends.

   - Develop a recommendation system that provides personalized movie recommendations based on user ratings.

   - Implement collaborative filtering and content-based approaches to improve recommendation accuracy.

   - Evaluate the recommendation system using appropriate performance metrics to ensure relevance and accuracy.

   - Provide actionable insights to stakeholders to enhance user satisfaction and engagement strategies.


   
## DATA UNDERSTANDING
The dataset used in this project is sourced from the GroupLens Research team and is titled "MovieLens Latest Small Dataset." It is a CSV-based dataset containing user ratings, movie information, and additional features relevant to building a recommendation system. You can access it here: [MovieLens Dataset](https://grouplens.org/datasets/movielens/latest/).
The data are in the files `links.csv`, `movies.csv`, `ratings.csv`, and `tags.csv`.

All ratings are contained in the file `ratings.csv`. (0.5 stars - 5.0 stars).

Movie information is contained in the file `movies.csv`. 



## DATA CLEANING & PREPARATION
1. Handling missing values: There were no missing values.
  
2. Checking for duplicated values: there were no duplicates.

3. Handling outliers: they were left as they were.

4. Merging Datasets: Relevant datasets were merged based on common keys to create a unified dataset for analysis.

   
   
## DATA VISUALIZATION

   ![pic1](https://github.com/user-attachments/assets/31ecfa55-02f9-4969-8eaa-8a4e11cb8c41) 
   How are ratings distributed across the dataset to identify trends like whether users tend to give higher or lower ratings?
   

   ![pic2](https://github.com/user-attachments/assets/608e7128-32d1-429b-aad2-48403e03ed12)
   ![pic3](https://github.com/user-attachments/assets/b8a685e8-86ee-49e8-ae24-81d1102af53e)
   Examined which genres receive the most ratings as well as the highest average ratings to understand audience preferences.


   ![pic4](https://github.com/user-attachments/assets/11985307-a33e-409f-b67e-7e17d6f31f49)
   ![pic5](https://github.com/user-attachments/assets/f1b66f5e-14e8-41b1-a17b-e9fd0590856b)
   Identify movies with the highest average ratings and those with the most ratings to determine popular movies. We'll also see whether the results here will be consistent with the 
   analysis of genre popularity


   ![pic6](https://github.com/user-attachments/assets/a3b41fc0-d795-499b-9db1-0c38a838ba8d)
   Visualized the ratings trends over time to investigate how ratings have changed over the years.


   ![pic7](https://github.com/user-attachments/assets/90fbdb05-52d0-476b-8555-9e73a5a36997)
   Checked if highly active users tend to rate movies differently compared to less active users.


   ![pic8](https://github.com/user-attachments/assets/7db7fa85-d7f8-4348-80b4-bb45a7f17b0e)
   ![pic9](https://github.com/user-attachments/assets/e4750bad-0063-4614-a45a-c59ad56e7e16)
   Investigated new users or movies with very few ratings, which could impact the effectiveness of recommendations.


   ![pic10](https://github.com/user-attachments/assets/0269f703-0232-4a0f-afaf-1234908cb335)
   Visualized sparsity in ratings



## SUMMARY OF KEY FINDINGS FROM EDA
The following insights were derived from the MovieLens Recommendation System project:

- **The majority of the ratings cluster around 3 and 4**: The distribution of ratings shows that most users tend to rate movies with a score of 3 or 4. With this insight, stakeholders can 
      focus on movies that consistently receive ratings above 4 for promotional efforts and personalized recommendations.
  
- **Certain genres dominate user preferences**: Popular genres such as Drama, Comedy, and Action receive the highest number of ratings, showing they align with audience interests. 
      Therefore, these genres can be prioritized in marketing campaigns, and content acquisition can focus on similar genres to boost engagement.
   
- **Highly active users provide more stable ratings**: Analysis showed that users with higher activity levels tend to rate movies more consistently, whereas less active users show 
      greater variability. With this insight, stakeholders can consider loyal and active users segmentation for premium recommendation services or loyalty rewards.

- **Fluctuating trends in ratings over the years**: The number of ratings fluctuates over time, with notable increases during specific years, possibly due to platform growth or popular 
      movie releases. Understanding peak activity periods can help the stakeholders plan marketing campaigns or feature releases during high-engagement times.

- **Most-rated movies vs. highest-rated movies differ**: Some of the most frequently rated movies don't necessarily have the highest average ratings, indicating that popularity does not 
      always align with quality. Stakeholders should differentiate between "popular" and "high-quality" movies when curating recommendations for users.

- **Variation in ratings across different genres**: Some genres, such as Documentary and Film-Noir, tend to receive higher average ratings but have fewer overall ratings compared to 
      mainstream genres. Promoting niche genres with high satisfaction rates can attract dedicated audiences and differentiate content offerings.


## RECOMMENDATIONS
Based on our findings, we suggest the following strategies:

1. **Personalized promotion strategies**:
Focus marketing efforts on movies consistently rated above 4 and promote highly rated niche genres to attract dedicated audiences.

2. **Genre-based content expansion**:
Increase content acquisition and production in high-demand genres like drama, comedy, and action to align with user preferences.

3. **User segmentation for targeted engagement**:
Develop loyalty programs and premium recommendation services for highly active users who provide more stable and valuable feedback.

4. **Peak engagement planning**:
Leverage historical rating trends to schedule content releases and promotions during peak engagement periods to maximize impact.

5. **Differentiated recommendation strategies**:
Offer separate recommendation lists for "popular" and "high-quality" movies to cater to diverse user preferences and expectations.

6. **Cold-start mitigation**:
Introduce content-based filtering or hybrid models to enhance recommendations for new users with limited rating history.



## NEXT STEPS
- **Build a hybrid recommendation model**: Combine collaborative and content-based filtering to improve accuracy and address limitations of individual approaches.

- **Expand feature engineering**: Incorporate additional user and movie features, such as demographics, review text, and browsing history, to enrich the recommendation model.

- **Deploy and monitor the system**: Implement the model in a real-world environment, track its performance over time, and continuously refine it based on user feedback and new data.

- **Collect more data that is also diverse**: Collect additional data to improve the model's robustness.
