# Movie Data ETL

## Overview:
Amazing Prime wants to predict which new low-budget movies will become popular so they can buy the streaming rights at a bargain. To create this predictive algorithm, they are sponsoring a hackathon. However, the programmers need a clean dataset from which to work with. Our challenge is to build an ETL process that creates this dataset.
## Process:
The ETL process has become an automated pipeline that pulls in data from three files: Wikipedia data, Kaggle metadata, and MovieLens ratings, and first transforms it by removing bad data and improving the usability of the remaining data. Then dataframes are merged so one dataset is then available for use. Finally this merged dataset is uploaded to PostgresSQL so the programmers in the hackathon can use it.