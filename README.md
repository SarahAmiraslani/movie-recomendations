# Ethical Movie Recommendations

## Objective

The Ethical Movie Recommendations project aims to create a sensitive movie recommendation system that takes into account users' preferences for both what they want to see and what they wish to avoid. The goal is to demonstrate the need for recommendation systems that are considerate of users' content preferences, especially regarding potentially triggering or inappropriate material.

## Deliverables

We have developed a user interface using Altair that provides movie recommendations based on user input. Users can specify both the types of movies they are interested in and the types of content they wish to avoid. The recommendation algorithm filters movies based on these inputs and returns the top-rated movies according to user reviews.

## Motivation

Traditional recommendation systems primarily focus on maximizing user engagement, which can sometimes lead to presenting content that users might find triggering or inappropriate. Our project addresses this issue by allowing users to filter out unwanted content, providing a safer and more personalized movie-watching experience.

## Data Sources

We utilized several datasets for this project:

1. **MovieLens** : Contains 25 million ratings and one million tag applications applied to 62,000 movies by 162,000 users. [Dataset link](https://files.grouplens.org/datasets/movielens/ml-25m.zip)
2. **IMDB Reviews** : Contains 5,571,499 unique reviews from the IMDB website. [Dataset link](https://www.kaggle.com/datasets/ebiswas/imdb-review-dataset)
3. **Movie Posters** : Contains 41,979 unique poster URLs identifiable by movie title and year. [Dataset link](https://www.kaggle.com/datasets/dadajonjurakuziev/movieposter)

## Data Manipulation Methods

Our data manipulation involved cleaning and processing text data, applying the Porter Stemming algorithm to normalize tags, and joining datasets to create a comprehensive dataset for movie recommendations. We used Dask for handling large datasets to mitigate memory issues during data processing.

## Analysis

We explored the MovieLens and IMDB datasets to understand rating distributions, identify popular genres, and analyze user sentiment through word clouds. These analyses informed the development of our recommendation system by highlighting key trends and preferences.

## Visualizations

The user interface includes search fields for entering desired and undesired keywords, with a tooltip providing detailed information about each recommended movie. The inclusion of movie poster images enhances the expressiveness of recommendations. If poster images are unavailable, a short dataframe with relevant movie details is presented.

## Statement of Work

* **Sarah Amiraslani** : Data cleaning and ethical implications.
* **Gabriel Alon** : Project description, document organization, prerequisite coursework assessment, visualization section code, and writing.
* **Kevin Deloria** : Exploratory data analysis, parts of data cleaning, UI, and data importation.

## References

* Halevy, A. (2022, December 28). Your Personal Data Timeline: Data timelines will protect your privacy and make AI better. DeepLearning.AI The Batch. January 8, 2023.
* Alfaddagh, M. (2020, January 3). What Are the Top Rated 25 Movies? Medium.
