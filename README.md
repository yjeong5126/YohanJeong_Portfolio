# YohanJeong_Portfolio
This Portfolio contains data-related projects.  

## [Project 1: Scraping Box Office Info Using Scrapy](https://github.com/yjeong5126/scraping_boxofficemojo)

This shows how to scrape the *Boxofficemojo* website using **Scrapy** in **Python**. I check all the movies released in the US during certain periods of time and extract useful information about the individual movies. For each movie, the elements that I scrape here are *Domestic Revenues, Worldwide Revenues, Distributor, Opening, Budget, MPAA, Genres, and In Release*.

[Medium Post](https://medium.com/analytics-vidhya/scraping-box-office-info-with-scrapy-f23f1f2d684f)

## [Project 2: Analysis of Movies and their Trailer Release Dates](https://github.com/yjeong5126/movietrailer_releasedate)

This is based on the movie information scraped by using the method in **Scraping Box Office Info Using Scrapy**. I examine whether the variation in the promotion period is one of the strategies for promoting the movies. To test this, I examine the factors related to the decision about the length of the promotion period. The factors to be tested are budget, distributors, MPAA, and genres. 

[Medium Post](https://medium.com/@yjeong5126/analysis-of-movie-trailer-release-date-3c6e30681aea)

## Predicting Housing Prices using Cross Validation and Grid Search in Regression Models

In this project, I analyze the factors related to housing prices in Melbourne and perform the predictions for the housing prices using several machine learning techniques. The models used in this analysis are *Linear Regression, Ridge Regression, K-Nearest Neighbors (hereafter, KNN), and Decision Tree*. Using the methods of the *Cross Validation* and *Grid Search* techniques, I find the optimal values for hyper parameters in each model, and compare the results to find the best machine learning model to predict the housing prices in Melbourne. 

[Code](https://github.com/yjeong5126/housing_prices)

[Article](https://medium.com/@yjeong5126/predicting-housing-prices-in-melbourne-e3d5f49abf20)

## Creating a Database and Practicing SQL Queries

In this project, I show how to convert a data in one spreadsheet to a relational database for SQL. After the database is created, I perform several SQL queries using the database.

[Code](https://github.com/yjeong5126/sql_sample_sales_data)

## The Analysis for Glassdoor Job Postings

In this project, I scrape over 3000 job postings for 'Data Analyst' from the Glassdoor website. Since the Glassdoor website is dynamic, I use the *Selenium* library in the Python to scrape the job postings related to 'Data Analyst'. After scraping the job postings, I clean the scraped data using the Python and convert it to the format for the Relational Database to store it in the SQL format. Lastly, I visualize the data using *Tableau*, showing the salary distributions by state, city, sector, and skills.

[Code](https://github.com/yjeong5126/glassdoor_data_analyst)

## Cohort Analysis

In this project, I implement the cohort analysis using eCommerce data from UIC machine learning repository. In the code, I show how to create the matrix for cohort analysis from the raw ecommerce data. 

[Code](https://github.com/yjeong5126/eCommerce-Analysis/blob/master/cohort_analysis/e_commerce_cohort_analysis.ipynb)

## Making a Content-based Movie Recommender

Among the several recommendation models, I build a **content-based** recommendation engine in this practice. I used a movie data set from the **MovieLens**, which has 9742 movies. The first step is to quantify the movie features using the **Term Frequency and Inverse Document Frequency (tf-idf)**, and the next step is to calculate the similarities between movies using the **cosine similarity**. Furthermore, I add the '**Did you mean...?**' function to the recommender in order to make the searching process easier.

[Code](https://github.com/yjeong5126/movie_recommender)

[Article](https://yjeong5126.medium.com/creating-content-based-movie-recommender-with-python-7f7d1b739c63)

## Making a Item-based Collaborative Filtering

Among the several recommendation models, I build an **item-based** collaborative filtering for movie recommendation. I used a movie data set from the **MovieLens**. In order to predict a rating for a movie by a selected user, the first step is to find similar movies to the movie using the **cosine similarity**. The next step is to calculate the weighted average of ratings for the similar movies by the user. Then, the average can be the predicted rating for the movie by the selected user. Applyting this algorithm, I built a movie recommendation for the movie dataset.

[Code](https://github.com/yjeong5126/movie_recommender)

[Article](https://yjeong5126.medium.com/item-based-collaborative-filtering-in-python-91f747200fab)
