# ETL Challenge

## Purpose

The purpose of this challenge is to write an ETL function to read three data files with information about movies, and then extract and transform such information using Python to create a a movie database.

## ETL_function_test

The ETL_function test file shows an ETL function to read three datafiles: wikipedia-movies.json, ratings.csv, and movies_metadata.csv

## ETL_wiki_movies

The ETL_wiki_movies file extracts and transforms the Wikipedia data

## ETL_clean_kaggle_data

The ETL_clean_kaggle_data file extracts and transforms the Kaggle (ratings.csv) data.

- The kaggle metadata is cleaned
- The Wikipedia and Kaggal DataFrames are merged
- The movies_df and movies_with_ratings_df is created

## ETL_create_database

The ETL_create_database file creates the movie database using Python, Pandas, the ETL process, code refactoring and PosgreSQL. The movies_df dataframe and MovieLens rating CSV data is added to a SQL database.
# movies_ETL_challenge
