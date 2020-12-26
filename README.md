# Sparkify Songplays Analytics Database

Project 01 for the Udacity Data Engineering Nanodegree

This database can be used to analyse the popularity of music on the sparkify music app.

It consists of the Fact table:
* Songplays
And the Dimension tables:
* Users
* Songs
* Artists
* Time

Topics that can be explored with the db include:
* What are the most played songs on the app?
* How many songs do users play on average?
* What is the most popular time for using the app?
* Who is the most popular artist on the app?


The DB can be initialised using the following two python scripts in order:
1. create_tables.py
2. etl.py

The file sql_queries.py is a dependency.


Notes -
* 'ON CONFLICT DO NOTHING' statements were used to handle duplicates.
