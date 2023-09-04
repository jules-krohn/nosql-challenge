# nosql-challenge
Module 12 Challenge

In this challenge I analyzed data of restaurant establishements in the UK for the editors of a food magazine, Eat Safe, Love, in order to help their journalists and food critics decide where to focus future articles.

The "set-up" notebook imports JSON data to the database, adds a new restaurant (Penang Flavours), changes latitude/longitude/Rating values to integers, and deletes unwanted documents.

The "analysis" notebook answers these questions:
1. Which establishments have a hygiene score equal to 20?
2. Which establishments in London have a RatingValue greater than or equal to 4?
3. What are the top 5 establishments with a RatingValue rating value of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
4. How many establishments in each Local Authority area have a hygiene score of 0?

Each question is answered with a corresponding pandas DataFrame

Bibliography

All code used was taken from class activities

* Code syntax for finding the latitude/longitude ranges for question 3:

https://www.scaler.com/topics/range-query/

