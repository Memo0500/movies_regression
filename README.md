# Movies Regression

## Project proposal

In this project our task is to scrape a website to get the data for the Exploratory Data Analysis and then design a regression model to predict the possible revenues of movies for production companies. 


The Approach
============

### Our plan in the project is to find

- Scrape the data from themoviedb.org to get the information for the movies and other related info like the year and the rating.
- Scrape the website box office to get the related information like:
The budget, the revenue for the movies, the release date, and the price of the tickets. 


### Question(s):
- Investigate the relationship between movie user rating and revenue. What is the expected revenue for a movie given a specific user rating?
- Can we predict user rating for a movie given the total budget and the number of genres which the movie belongs to?
### Data Description

The columns that will be collected from (themoviedb.org) are

- Name of the movie (Title)
-	Genre Count
-	Genre
-	Cast Size
-	Ratings
-	Keywords Count
-	Budget
-	Release Date	
-	Revenue
-	Duration
-	Country
-	Language
-	id


In this project I will be using
=======================

### Tools
-	Jupyter.
-	Git.

### Libraries

-	Matplotlib.
-	Seaborn.
-	SQLite.
-	Pandas.
-	BeautifulSoup 4.
-	Selenium. 
-	Requests.

# Original data: 
- (3621 rows,11 columns)
- After EDA: (1871 rows, 11 columns)
- After the Feature engineering: (1871 rows, 29 columns)
- 28 features and one predictor.
