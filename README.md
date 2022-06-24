# Movies-ETL
 Challenge 8

# UofM-Data-Viz-Analytics-Boot-Camp
# Ron Hankey - University of Minnesota Data Visualization and Analytics Boot Camp
#                   Assignment: Challenge 8 - Movies-ETL
#                           Student: Ron Hankey
#                           Date: June 15, 2022

# Module 8 - ETL, Extract, Transform, Load 

## Overview of Project
* Create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables.
* Deliverable 1: Write an ETL Function to Read Three Data Files
* Deliverable 2: Extract and Transform the Wikipedia Data
* Deliverable 3: Extract and Transform the Kaggle data
* Deliverable 4: Create the Movie Database

## Analysis Four Jupyter notebooks
*  Write a function that reads in the three data files and creates three separate DataFrames.
*  Extract and transform the Wikipedia data so you can merge it with the Kaggle metadata.
*  Extract and transform the Kaggle metadata and MovieLens rating data, then convert the transformed data into separate DataFrames. 

## Summary  End Result
* Deliverable 1, the output matched the rubric:
![kaggel_metadata](https://github.com/lykkelig/Movies-ETL/blob/main/Images/deliverable1_kaggle_metadata.png)
![ratings_df](https://github.com/lykkelig/Movies-ETL/blob/main/Images/deliverable1_ratings.png)
![wiki_movies_df](https://github.com/lykkelig/Movies-ETL/blob/main/Images/deliverable1_wiki_movies_df.png)
* Deliverable 2, the output matched the rubric:
![wiki_movies_df_2](https://github.com/lykkelig/Movies-ETL/blob/main/Images/deliverable2_wiki_movies_df.png)
![columns_names](https://github.com/lykkelig/Movies-ETL/blob/main/Images/deliverable2_columns.png)
* Deliverable 3, the output matched the rubric:
![movies_df](https://github.com/lykkelig/Movies-ETL/blob/main/Images/deliverable3_movies_df.png)
![movies_with_ratings]https://github.com/lykkelig/Movies-ETL/blob/main/Images/deliverable3_movies_with_ratings_df.png
* The movie database was successfully created!
* Deliverable 4, the output matched the rubric.
*     The count of ratings matched the rubric:
![ratings_writes](https://github.com/lykkelig/Movies-ETL/blob/main/Resources/ratings.png)
*     Also used SQL to verify the ratings count:
![ratings_count_sql](https://github.com/lykkelig/Movies-ETL/blob/main/Resources/ratings_sql.png)
*     The count of movies also matched the rubric:
![movies_count_sql](https://github.com/lykkelig/Movies-ETL/blob/main/Resources/movies.png)

* What a FUN project!!!