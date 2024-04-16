# Anime Reviews Scraper, Visual Analysis, and Rating Prediction

This project aims to scrape user reviews and ratings from [MyAnimeList](https://myanimelist.net), perform visual analysis and rating prediction using ML algorithms on the scraped data. MyAnimeList is a popular platform for anime fans to rate and review their favorite shows.

## Features
1. *scraping_reviews.ipynb* \
Scraping User Reviews: The project includes a web scraper that extracts user reviews and ratings from MyAnimeList. It navigates through the website, collects data, and stores it as a .csv for further analysis.

2. *preprocessing.ipynb* \
Data Cleaning and Preprocessing: Before analysis, the scraped data undergoes cleaning and preprocessing to remove extra characters, non-English reviews, and standardize the format for consistency.

3. *data_analysis.ipynb* \
Visual Analysis: The cleaned data is then utilized to generate insightful visualizations using Seaborn. These visualizations provide an overview of distribution of reviews per show, reviews lengths, and ratings.

4. *rating_prediction_with_ML.ipynb* \
Predicting anime ratings based on their reviews: Applying machine learning algorithms to the vector representations of the reviews to perform a regression task and predict the ratings (used SGDRegressor with RandomizedSearchCV).