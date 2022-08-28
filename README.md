# Movies ETL

Using Extract, Transform and Load (ETL) processes in Python, Pandas, and Jupyter Notebook to scrub data and export into a SQL Postgres database

## Overview of Project

ETL of movie data to provide a clean dataset on movies released in a certain timeframe

### Purpose

Amazing Prime Video is setting up a hackathon in the local community in which users will attempt to determine which movies will become popular. Amazing Prime Video will use those results to buy streaming rights at a bargain. Datasets obtained from a Wikipedia webscrape, Kaggle, and MovieLens files will need to be scrubbed using ETL processes to provide relevant and clean data for the upcoming hackathon. Movies from 1990 to 2018 will be analyzed with the combined 3 datasources.

## Results

A =dataframe was created in Jupyter Notebook using the combined Wikipedia and Kaggle information. Where one lacked data, at times it could be filled in with information from the other dataset. In the end, the data was scrubbed down to 6,052 movies during 1990 and 2018. This was then exported to SQL Postgres for the upcoming hackathon. 

A sample of the completed movies SQL table:

![movies_dataset](https://user-images.githubusercontent.com/108373151/187052826-5f37c5bb-9bea-4f60-a1b4-a5e3d2106cae.png)