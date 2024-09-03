# Movie Recommendation System with Data Analysis

## Description

This is a Movie Recommendation System that uses collaborative filtering techniques to provide personalized movie recommendations based on user ratings and preferences. The system also includes data cleaning, preprocessing, and exploratory data analysis (EDA) to gain insights into the dataset.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Data Sources](#data-sources)
- [Data Cleaning](#data-cleaning)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Model Training](#model-training)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Installation

To use this Movie Recommendation System, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies using [pip](https://pip.pypa.io/en/stable/): 
pip install pandas numpy matplotlib seaborn surprise

3. Run the Jupyter Notebook or Python script to perform data cleaning, preprocessing, analysis, and train the recommendation model.

Memory updated
To create a detailed description for your GitHub project on a Movie Recommendation System with Data Analysis, you can use the following template:

Movie Recommendation System with Data Analysis
Overview
This project is a comprehensive Movie Recommendation System that leverages collaborative filtering techniques to provide personalized movie suggestions to users. The system uses data analysis and machine learning algorithms to predict user preferences based on their historical ratings and movie interaction data.

Features
Collaborative Filtering: Uses collaborative filtering methods (such as Matrix Factorization using SVD) to predict user ratings for movies they haven't watched yet.
Data Analysis: Performs exploratory data analysis (EDA) to understand user behavior, movie trends, and rating distributions.
Model Evaluation: Evaluates the recommendation model using metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) to ensure accuracy and reliability.
User-Friendly Interface: Provides an intuitive interface for users to view their top recommended movies.
Data
The dataset used in this project includes:

User Data: Information about users including their unique user IDs.
Movie Data: Details about movies such as movie IDs, titles, genres, etc.
Ratings Data: User-movie interactions, containing user ratings for different movies.

##Requirements
To run this project, you need the following libraries and tools:

Python 3.x
pandas
numpy
scikit-learn
scipy
matplotlib (for data visualization)
seaborn (for data visualization)
## Usage

To get movie recommendations, users can input their preferences, and the system will return a list of recommended movies based on their ratings and other users' similar preferences.

## Data Sources

The data for this project comes from three CSV files: `movies.csv`, `ratings.csv`, and `tags.csv`. The dataset contains information about movies, user ratings, and user-generated tags.

## Data Cleaning

The data cleaning process involved handling missing values and duplicates. Missing values in the `rating` column were replaced with the median value.

## Data Preprocessing

Data preprocessing steps included merging the three datasets based on common `movieId` and `userId` columns. Timestamp columns were converted to datetime format for time-based analysis.

## Exploratory Data Analysis

EDA was performed to understand the distribution of movie ratings, the most popular movies, and the distribution of movie genres. Time-based analysis was done for tags and ratings to observe trends over time.

## Model Training

The Movie Recommendation System uses the Singular Value Decomposition (SVD) algorithm, a popular collaborative filtering technique, to build the recommendation model. The Surprise library was used to implement and train the SVD model.

## Results

The system provides movie recommendations for each user in the test set. The top N recommendations with the highest predicted ratings are displayed for each user.

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvement, feel free to open an issue or create a pull request.



