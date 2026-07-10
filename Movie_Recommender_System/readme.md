This project implements a content-based movie recommendation system using the TMDB 5000 Movies and TMDB 5000 Credits datasets. 
It recommends movies similar to a given title by analyzing metadata such as genres, keywords, cast, crew, and movie overviews.

The recommendation pipeline includes:
Data cleaning and preprocessing of movie metadata.
Feature engineering by combining relevant textual attributes into a unified representation.
Text vectorization using CountVectorizer.
Similarity computation using Cosine Similarity to generate movie recommendations.

Upcoming Features:
Deploy the recommendation system as an interactive Streamlit web application.
Integrate the TMDB API to fetch movie posters, ratings, release dates, and other real-time movie details.
Enhance the user interface with search functionality and visually rich recommendation cards.
