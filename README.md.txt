# Project-1

# Motivation:
This project analysed the Boston and Seattle Airbnb data and displayed popular Airbnb price range and the top 5 airbnb monthly earning in 2017 Jan
as well as produce the review_scores_rating prediction model

# Libraries used:
pandas, numpy, matplotlib, sklearn

# Files in the repository:
Boston Airbnb folder: contains Boston Airbnb data downloaded from Kaggle,
Seattle Airbnb folder: contains Boston Airbnb data downloaded from Kaggle,
project 1.ipynb: The jupyter notebook file which loads, cleans, analyses and models the Boston and Seattle Airbnb data

# Question and results:
Question 1: Compare Boston and Seattle Airbnb price and find the most common price range
Result: 
Seattle_price_pattern
(100.0, 200.0]      10926
(0.0, 100.0]         7959
(200.0, 300.0]       4330
(300.0, 500.0]       2524
(500.0, 1000.0]       429
(1000.0, 1650.0]        6
Boston Airbnb price range:
(100.0, 200.0]      8589
(300.0, 500.0]      8563
(200.0, 300.0]      7793
(500.0, 1000.0]     4790
(0.0, 100.0]        3435
(1000.0, 7163.0]     513

![price_range](https://user-images.githubusercontent.com/62674988/112771419-89108000-9077-11eb-9090-0e5b56af975b.PNG)

Question 2: Build model to predict review_scores_rating for Boston Airbnb,

r2_score=  0.711550954843015
mean_squared_error=  27.523603293962353

Question 3: Top 5 Airbnb earning at Boston and Seattle in 2017 Jan

Boston_top5_earning [124000.  41695.  40300.  38285.  31000.  30969.]
Seattle_top_earning [2000. 2000. 1950. 1900. 1800. 1798.]

A blog post in the below link:

https://czeng98.medium.com/analysis-of-airbnb-in-boston-and-seattle-in-2017-ff4c0748ff74