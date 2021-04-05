# Data Analysis Portfolio
This portofolio is a compilation of web scraping, data cleaning, and data analysis. Each project is in the separate repository and the link to each project is added in this portfolio.  

## Scraping Box Office Info Using Scrapy
[Link](https://github.com/yjeong5126/scraping_boxofficemojo) to the scraping project

This shows how to scrape the *Boxofficemojo* website using **Scrapy** in **Python**. I check all the movies released in the US during certain periods of time and extract useful information about the individual movies. For each movie, the elements that I scrape here are *Domestic Revenues, Worldwide Revenues, Distributor, Opening, Budget, MPAA, Genres, and In Release*. The detailed explanation is [here](https://medium.com/analytics-vidhya/scraping-box-office-info-with-scrapy-f23f1f2d684f).

## Analysis of Movies and their Trailer Release Dates
[Link](https://github.com/yjeong5126/movietrailer_releasedate) to the project

This is based on the movie information scraped by using the method in **Scraping Box Office Info Using Scrapy**. I examine whether the variation in the promotion period is one of the strategies for promoting the movies. To test this, I examine the factors related to the decision about the length of the promotion period. The factors to be tested are budget, distributors, MPAA, and genres. The detailed explanation is [here](https://medium.com/@yjeong5126/analysis-of-movie-trailer-release-date-3c6e30681aea).

## Predicting Housing Prices using Cross Validation and Grid Search in Regression Models
[Link](https://github.com/yjeong5126/housing_prices) to the project

In this project, I analyze the factors related to housing prices in Melbourne and perform the predictions for the housing prices using several machine learning techniques. The models used in this analysis are *Linear Regression, Ridge Regression, K-Nearest Neighbors (hereafter, KNN), and Decision Tree*. Using the methods of the *Cross Validation* and *Grid Search* techniques, I find the optimal values for hyper parameters in each model, and compare the results to find the best machine learning model to predict the housing prices in Melbourne. For more detailed explanation, read [this](https://medium.com/@yjeong5126/predicting-housing-prices-in-melbourne-e3d5f49abf20).

## Creating a Database and Practicing SQL Queries
[Link](https://github.com/yjeong5126/sql_sample_sales_data) to the project

In this project, I show how to convert a data in one spreadsheet to a relational database for SQL. After the database is created, I perform several SQL queries using the database.

## The Analysis for Glassdoor Job Postings
[Link](https://github.com/yjeong5126/glassdoor_data_analyst) to the project

In this project, I scrape over 3000 job postings for 'Data Analyst' from the Glassdoor website. Since the Glassdoor website is dynamic, I use the *Selenium* library in the Python to scrape the job postings related to 'Data Analyst'. After scraping the job postings, I clean the scraped data using the Python and convert it to the format for the Relational Database to store it in the SQL format. Lastly, I visualize the data using *Tableau*, showing the salary distributions by state, city, sector, and skills.

## Cohort Analysis
[Link](https://github.com/yjeong5126/eCommerce-Analysis/blob/master/cohort_analysis/e_commerce_cohort_analysis.ipynb) to the project

In this project, I implement the cohort analysis using eCommerce data from UIC machine learning repository. In the code, I show how to create the matrix for cohort analysis from the raw ecommerce data. 

## Making a Content-based Movie Recommender
[Link](https://github.com/yjeong5126/movie_recommender/tree/master/content_based) to the project

Among the several recommendation models, I build a **content-based** recommendation engine in this practice. I used a movie data set from the **MovieLens**, which has 9742 movies. The first step is to quantify the movie features using the **Term Frequency and Inverse Document Frequency (tf-idf)**, and the next step is to calculate the similarities between movies using the **cosine similarity**. Furthermore, I add the '**Did you mean...?**' function to the recommender in order to make the searching process easier. The additional explanation can be found [here](https://yjeong5126.medium.com/creating-content-based-movie-recommender-with-python-7f7d1b739c63).


