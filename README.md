# MovieMatch – Intelligent Movie Recommendation System

MovieMatch is a machine learning based movie recommendation web application built using Python and Streamlit. The system suggests similar movies based on content such as genre, director, actors, and plot description.

## Project Overview

This project uses Natural Language Processing (NLP) techniques to analyze movie metadata and recommend similar movies to users.

The recommendation engine works by:

- Taking a movie selected by the user
- Analyzing its content features
- Comparing it with other movies
- Displaying the top 5 most similar movies

## Features

- Movie recommendation based on content similarity
- Displays movie posters
- Shows IMDb rating
- Shows release year
- Interactive user interface
- Background styled web app using Streamlit

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Streamlit
- TF-IDF Vectorizer
- Cosine Similarity
- Jupyter Notebook

## Dataset

Dataset used:
IMDB Top 250 Movies Dataset

Contains:

- Title
- Genre
- Director
- Actors
- Plot
- Poster
- IMDb Rating
- Year

## Machine Learning Approach

### Data Preprocessing

The following columns were selected:

- Title
- Genre
- Director
- Actors
- Plot

Missing values were handled using:

- fillna()

A combined feature column was created by merging:

- Genre
- Director
- Actors
- Plot

### Vectorization

TF-IDF Vectorization was applied to convert text into numerical vectors.

### Similarity Calculation

Cosine Similarity was used to compare movies and find related recommendations.

## Project Structure

IMDB MOVIE RECOMMENDATION/

data/
- IMDB_Top250Engmovies2_OMDB_Detailed.csv

notebook/
- imdb_recommendation.ipynb
- app.py

requirements.txt
README.md

## How to Run

1. Install requirements

pip install -r requirements.txt

2. Run application

streamlit run app.py

## Future Improvements

- Search bar autocomplete
- Genre filtering
- User login
- Personalized recommendations
- Deployment on cloud
- Mobile responsive design



Student | Artificial Intelligence and Data Science

Built as a machine learning portfolio project.
