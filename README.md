# Movies-ETL
Module 8 - ETL

## Deliverable 1: Write an ETL Function to Read Three Data Files

Load in the Kaggle metadata and MovieLens ratings csv file into DataFrames. Read in the Wikipedia JSON file. Create three DataFrames. See ETL_function_test.ipynb for the code.

## Deliverable 2: Extract and Transform the Wikipedia Data

Using the code from Deliverable 1 and adding to it to clean the wiki_movies_df. Create a try-except block to catch any errors. Parse the money columns. Clean the date columns. See ETL_clean_wiki_movies.ipynb for the code.

## Deliverable 3: Extract and Transform the Kaggle Data

Using Deliverable 2 code, add to it to clean the kaggle_metadata. Drop unnecessary columns. Fill in missing data with a function. See ETL_clean_kaggle_data.ipynb for the code.

## Deliverable 4: Clean the Movie Database

Using code from Deliverable 3 and adding on to it to move the 'movies' and 'ratings' tables to PostgreSQL database. See ETL_create_database.ipynb for the code.

Confirming correct counts from each table in SQL database:

![ratings_query](https://user-images.githubusercontent.com/95837693/155245373-c3bf6ebe-14e9-40c4-bda2-1d88e177acd6.PNG)

![movies_query](https://user-images.githubusercontent.com/95837693/155245377-6d418635-ca65-407e-8521-e76abc3681b9.PNG)
