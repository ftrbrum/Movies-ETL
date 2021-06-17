# Movies-ETL
Module 8

## Overview of Analysis

Amazing Prime wants to keep the dataset and updated on a daily basis. I've been asked to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. I’ll need to refactor the code from module 8 to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.


## Resources:

Data Source: 
- [movies_metadata.csv](Resources/movies_metadata.csv)<br/>
- [wikipedia-movies.json](Resources/wikipedia-movies.json)<br/>
- ratings.csv
 
Software: PostgreSQL v13.3, pgAdmin 4 v5.3, Jupyter Notebook, Anaconda 4.10.1, Python 3.7.6, Visual Studio Code, 1.56.0
 
Code:<br/>	
- [ETL_function_test.ipynb](ETL_function_test.ipynb)<br/>
- [ETL_clean_wiki_movies.ipynb](ETL_clean_wiki_movies.ipynb)<br/>
- [ETL_clean_kaggle_data.ipynb](ETL_clean_kaggle_data.ipynb)<br/>
- [ETL_create_database.ipynb](ETL_create_database.ipynb)<br/>


## Results: ETL_function_test


![wiki_movies_df.png](Images/wiki_movies_df.png)

![kaggle_metadata_df.png](Images/kaggle_metadata_df.png)

![ratings_df.png](Images/ratings_df.png)


## Results: ETL_clean_wiki_movies


![wiki_movies_df_2.png](Images/wiki_movies_df_2.png)

![wiki_movies_df_columns.png](Images/wiki_movies_df_columns.png)


## Results: ETL_clean_kaggle_data


![movies_with_ratings_df.png](Images/movies_with_ratings_df.png)

![movies_df.png](Images/movies_df.png)


## Results: ETL_create_database


![movies_query.png](Resources/movies_query.png)

![ratings_query.png](Resources/ratings_query.png)


## Summary

I have created the below deliverables for Amazing Prime.They will now be able to keep the dataset and update on a daily basis for years to come.