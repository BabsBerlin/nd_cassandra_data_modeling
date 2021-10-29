# Data Modeling with Cassandra

## Introduction
For this project I build a Cassandra database for the fictitious music streaming app **SPARKIFY**. It was part of my *[Udacity Nanodegree in Data Engineering](https://www.udacity.com/course/data-engineer-nanodegree--nd027)*.

## The Task
A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.

They'd like a data engineer to create an Apache Cassandra database which can create queries on song play data to answer the questions, and wish to bring you on the project. Your role is to create a database for this analysis. You'll be able to test your database by running queries given to you by the analytics team from Sparkify to create the results.

## The Datasets
For this project we'll be working with one dataset: `event_data`. The directory of CSV files partitioned by date. Here are examples of filepaths to two files in the dataset:
- `event_data/2018-11-08-events.csv`
- `event_data/2018-11-09-events.csv`

## The Project Files
- `Cassandra_db_modeling.ipynb`
- `event_datafile_new.csv`
- `images/`
    - `image_event_datafile_new.jpg`
- `event_data/`
    - `2018-11-01-events.csv`
    - `2018-11-02-events.csv`
    - `2018-11-03-events.csv`
    - `...`

## Project Steps
The project is devided into two steps:
1. ETL pipeline for pre-processing the files in `event_data/`
2. Data modeling and creating an Apache Cassandra Database 

You will find the code and a detailed description for both steps in the notebook `Cassandra_db_modeling.ipynb`. 

Happy Coding! 🚀

