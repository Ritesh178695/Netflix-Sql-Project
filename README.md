# Netflix-Sql-Project
![Netflix Logo](https://upload.wikimedia.org/wikipedia/commons/0/08/Netflix_2015_logo.svg)

# Netflix SQL Data Analysis Project
Project Overview

This project focuses on analyzing the Netflix dataset using SQL queries to extract meaningful insights related to movies and TV shows.
The goal is to demonstrate data analysis, SQL querying skills, and business-oriented thinking using a real-world dataset.

# Dataset Description

The dataset contains information about Netflix content, including:

Show ID

Title

Type (Movie / TV Show)

Director

Cast

Country

Date Added

Release Year

Rating

Duration

Genre (Listed In)

Description

# Objectives

Analyze Netflix content distribution

Perform filtering, aggregation, and sorting

Use SQL functions to answer business questions

Improve SQL querying and data analysis skills

# Tools & Technologies Used

PostgreSQL (any SQL-supported DB)

GitHub (Project hosting)

 # Key Analysis Performed

Total number of movies and TV shows

Content released per year

Movies vs TV Shows comparison

Top countries producing Netflix content

Most common genres

Longest duration movies

Content added in recent years

Rating-wise distribution

# Sample SQL Queries
-- Count total movies and TV shows
SELECT type, COUNT(*) AS total
FROM netflix
GROUP BY type;

-- Top 5 countries with most content
SELECT country, COUNT(*) AS total_content
FROM netflix
GROUP BY country
ORDER BY total_content DESC
LIMIT 5;

# Insights & Learnings

SQL is powerful for data exploration and analysis

Aggregation functions help summarize large datasets

Real-world datasets improve analytical thinking

This project strengthens skills needed for Data Analyst roles

# How to Run This Project

Import the dataset into your SQL database

Open Netflix Sql Project.sql

Execute queries one by one

Analyze the results

# Use Case

Data Analyst Portfolio Project

SQL Practice Project

Interview Preparation

Academic Mini Project

# Conclusion

This project demonstrates practical SQL skills applied to a real-world dataset.
It is ideal for beginners and aspiring data analysts to showcase their SQL proficiency on GitHub.
