# Netflix Movies and TV Shows Data Analysis using SQL

![](https://github.com/gavi25/Netflix-Analysis-SQL-/blob/main/Netflix%20logo.png)

<h3>Project Overview</h3>

- This project aims to analyze Netflix content using SQL queries to gain insights into various aspects of movies and TV shows. By querying a dataset of Netflix content, we can derive valuable statistics and trends that reveal information about content distribution, popularity, and characteristics. The analysis covers a broad range of questions including content counts, ratings, genre distributions, release trends, and specific content characteristics.

<h3>  Problem Statement </h3>

- With the extensive and diverse content available on Netflix, it can be challenging to derive actionable insights from the dataset. This project addresses several key questions to better understand Netflix's content landscape, such as:

    - The distribution of movies vs. TV shows.
    - Popularity and commonality of ratings.
    - Trends in content releases by year and country.
    - Detailed content characteristics such as the longest movie, content without directors, and the presence of specific keywords.

<h3>  Objectives </h3>

The primary objectives of this project are:

     1) Content Distribution Analysis: To determine the number of movies and TV shows available, and to identify the most common ratings for each type of content.
     2) Release Trends: To list content released in specific years, find the top countries with the most content, and analyze content added in the last five years.
     3) Content Characteristics: To identify the longest movie, find all movies/TV shows by a specific director, and list TV shows with more than five seasons.
     4) Genre and Actor Analysis: To count the number of content items in each genre, find movies with a specific actor, and identify top actors appearing in Indian movies.
     5) Content Categorization: To categorize content based on keywords in descriptions and count the number of items in each category.

<h3>  Schema </h3>


```sql
DROP TABLE IF EXISTS netflix;
CREATE TABLE netflix
(
    show_id      VARCHAR(5),
    type         VARCHAR(10),
    title        VARCHAR(250),
    director     VARCHAR(550),
    casts        VARCHAR(1050),
    country      VARCHAR(550),
    date_added   VARCHAR(55),
    release_year INT,
    rating       VARCHAR(15),
    duration     VARCHAR(15),
    listed_in    VARCHAR(250),
    description  VARCHAR(550)
);
```
