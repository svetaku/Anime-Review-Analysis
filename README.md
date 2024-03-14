# Anime Reviews Scraper and Visual Analysis

This project aims to scrape user reviews and ratings from [MyAnimeList](https://myanimelist.net) and perform visual analysis on the scraped data. MyAnimeList is a popular platform for anime fans to rate and review their favorite shows.

## Features
1. *scraping_review.ipynb* \
Scraping User Reviews: The project includes a web scraper that extracts user reviews and ratings from MyAnimeList. It navigates through the website, collects data, and stores it as a .csv for further analysis.

2. *preprocessing.ipynb* \
Data Cleaning and Preprocessing: Before analysis, the scraped data undergoes cleaning and preprocessing to remove extra characters, non-English reviews, and standardize the format for consistency.

3. *data_analysis.ipynb* \
Visual Analysis: The cleaned data is then utilized to generate insightful visualizations using Seaborn. These visualizations provide an overview of distribution of reviews per show, reviews lengths, and ratings.

*I collected this data in order to perform aspect-based sentiment analysis on it and ideally build a keyword recommender system. Will be posting updates*