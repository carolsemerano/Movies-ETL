# Movies-ETL

## Overview

This project aims extract data from CSV and JSON files contaning movies info from Wikipedia and Kaggle websites. Then transform and clean data using Jupyter Notebook. Finally, load cleaned and merged dataframes into a Postgres database.

## Summary

The cleaning process was an incremental process, because of that multiple Jupyter notebooks were created to test and execute each step, that were combined into a final code on [ETL_create_database.ipynb](ETL_create_database.ipynb).

Files available in this repository:

- ETL_function_test.ipynb: Create an ETL function to read the files
- ETL_clean_wiki_movies.ipynb: Extract and transform Wikipedia data
- ETL_clean_kaggle_data.ipynb: Extract and transform Kaggle data
- ETL_create_database.ipynb: Uses all code created in the previous files, and create the movie database
- Resources folder: Store the screenshots of Postgres tables and data files.
