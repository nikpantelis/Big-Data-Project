# Big Data Management Project for Youtube Trending Videos

This project implements a Big Data batch-processing pipeline over muiltiple Youtube Trending Videos CSV files using Dask DataFrame.
The goal of the project is to go through the Data Science Process to answer questions about the data provided by the dataset.

The project follows the following implementation process:
- Load CSV files and data
- Cleaning and Normalization
- Feature engineering
- Core analyses
- Visualizations
- Export outputs
- NoSQL Ingestion
- Batch processing and aggregation with Dask

# What to do with the dataset

In order to make it work properly its suggested to download the dataset from [https://www.kaggle.com/datasets/datasnaek/youtube-new]
and create a folder named data/ which will contain the following csv files: 

GBvideos.csv, INvideos.csv, JPvideos.csv, RUvideos.csv and USvideos.csv

and from json files keep only the US_category_id.json.

The final directory should look like this:

project -
- youtube_trending_project.ipynb
- data/ (Which will contain all the csv files)
