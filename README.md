# The-Movie-Database-Analysis

## Overview

Welcome to the Movie Insights Project! In this analysis, we will explore a dataset of movies to gain insights into various aspects such as popular genres, movie properties associated with high revenues, average ratings for each director, and the top-rated movie titles and their directors. By examining these factors, we aim to provide valuable insights into the movie industry and inform decision-making processes in the production and distribution of movies.

## Importing Libraries Exploring the Data

To perform the analysis, we will utilize several libraries for data manipulation, analysis, and visualization. 

We will start by importing these libraries and loading the movie dataset (`tmdbmovies.csv`). We will then explore the data to understand its structure, contents, and any potential data quality issues.

## Data Wrangling:

* Handled missing values and outliers.

* Cleaned and transformed data for analysis.

* Check for duplicate data

* Getting overall statistics about the dataframe

* Display Title of movies having runtime >= 180

## Exploratory Data Analysis (EDA):

## Addressed key questions :

### Most Popular Genres from Year to Year

To determine the most popular genres from year to year, we will analyze the frequency of each genre in the dataset. By grouping the data by release year and genre and counting the occurrences of each genre in each year, we can identify the genres with the highest occurrence in each year. These genres represent the most popular ones during those periods.

![output](https://github.com/abbi1379/The-Movie-Database/assets/98527404/6d788997-7d60-466f-b14a-412b63e0d990)



### Properties Associated with High Revenue

To identify the properties associated with movies that have high revenues, we will analyze the relationship between revenue and various movie properties. Using statistical methods we can determine which properties have a significant impact on revenue. Some key properties to consider include budget, popularity, runtime, vote average, and vote count.

![output](https://github.com/abbi1379/The-Movie-Database/assets/98527404/857db494-6eff-4fe7-9df2-628a05472469)


![output1](https://github.com/abbi1379/The-Movie-Database/assets/98527404/f6d2bed4-e624-44a2-af86-b1b535db04b5)

### Average Rating for Each Director

To determine the average rating for each director, we will group the movie data by director and calculate the mean rating for each group. This will allow us to assess the performance of directors based on the average rating of their movies. By identifying directors with consistently high ratings, we can gain insights into the quality of their work.


![output4](https://github.com/abbi1379/The-Movie-Database/assets/98527404/97cc2c61-8bfd-4611-a5bb-2f8c2660e549)


### Top 10 Highest Rated Movie Titles and Directors

To find the top 10 highest-rated movie titles and their directors, we will sort the movie data by rating in descending order. This will enable us to identify the movies with the highest ratings and their corresponding directors. By analyzing these top-rated movies, we can uncover patterns and trends associated with critically acclaimed films.

![output2](https://github.com/abbi1379/The-Movie-Database/assets/98527404/17977e30-0f85-4103-8eef-c9f290c56795)


## Conclusion

Through this analysis, I aim to provide valuable insights into the movie industry by exploring popular genres, movie properties associated with high revenues, average ratings for each director, and the top-rated movie titles and their directors. 

## Performing Linear Regression

* We perform linear regression on the movie database based on various features. 

* After training the model, we calculate the mean squared error (MSE) and R-squared to evaluate its performance.

## Libraries Used
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Author

* Hiro Worku Gomoro
* Id No: DBUR/1400/12
