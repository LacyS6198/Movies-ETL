# Overview
The purpose of Module 8 was to learn ETL functions (extract, transform, load). The module lessons covered how to extract data from both CSV and JSON format. After the data was extracted, it was read and analyzed to understand what transformations were required. Once the data was understood, the data was transformed. It was transformed in multiple ways including:

- Filling blank data
- Removing NULLS
- Changing field formatting
- Merging dataframes

Once all data transformtaion was complete, the data was then loaded to tables in PostgreSQL. 

# Extraction 
Data was extracted from three files: 
 - wikipedia.movies.json
 - movies_metadata.csv
 - ratings.csv

# Transformation
The data was cleaned to remove unwanted data, remove NULLS, update field formatting, change column headers, and merge data in a dataframe(s). 

The data transformation process included:

- Removing TV series
- Removing duplicate data based on IMDB ID values
- Removing NULL values for certain columns
- Normalizing field values that were stored differently in the raw data (ex: budget and box office dollar amounts)
- Reformatting dates to standard datetime formatting
- Removing duplicate colmn names between the files during the merge process
- Updating empty or inconsistent fields in one file with those from another
- Renaming columns

# Loading Data
Once the data was extracted and transformed, it was then loaded into SQL tables using PostgreSQL. 
