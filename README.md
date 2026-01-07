# Netflix-Sql-Project
![Netflix] Logo(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAFwAAABcCAMAAADUMSJqAAAAaVBMVEUAAACxBg/lCRR2BAm2Bg/pCRSWBQyrBg+uBg/sCRSGBAunBQ+jBQ+PBA2aBA7wCRXeCBPQCBJZAgh+BAtvBAjDBxFFAgZmAwgzAgTXCBIuAQODAw06AgQPAAFQAwe9BxAXAAAfAAFgAwjm7H2TAAACYUlEQVRoge3Y2XKjMBAFUIlFuwRYtrFDYmfy/x85chbodmpe4NY80Y+k6pRyaaslhNhrr732+r91bORSgTx3pA4r8Wzbpezr/Dw1pOq1K++rpVo1P1fkH1qN16eW4AMY1wSvujMYHwhuExZvtCV6D8ZTRZf+03UgPLBXarC49vSV9m9QXEaaSzdi8cRyabC4T7RfLBY38UrxDMVlamguJyweFO2X9gLFtWO5OChulPm1NcJwGRztl+4Fins30KU/RkaE4TrSXb29QnGTHNsabwU3MDxMLJdyCnAwXPoYnkaG0waF65TZKD0I52F4yeVpZExB4/CY6NIrkcOy9I249GqipyM7HhMO12m6s5ExpjC/0q14ySXSfqlqtSx9M+5VzXLxDoknx0bGkNXcL1txqUsubGS4GDwKN0HxLcAsuWzHSy58ZEwqoHDpQ3Qslxh/Qt+O66Ayy6WZc9mOP3LxbGusFRJXNf0Z2ZILDNchjazV71PSIPyx9OPIcpmUx+EhC5pLm75zAeClXybBWv004XDjnTh0dOn5K3QIrsspkW2NIXoULk3BA98CPnPB4FGIGxsZLsFwWXBxpUsv5zworizNxXkY/jjevtB+sS5AccG2RqkMFGcXgavTUPzCRoYKUFzwC3XC4pnlUm4BSFyw23ryWJxfqBMWH2mrVxGLv7FvjV5D8aeREbD4gW2NCYvzkQGORbBvR4PG4mc2SsE43xpP2/GmaeYvuUJ1nx/Uv/T+uBa/F7ScWbxyLo/z40u5zMnT0Fdta22XV+KH+uP2+v7vv/85f9Rq7cr32muvvdbWX/e3JBdGyW86AAAAAElFTkSuQmCC)

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
