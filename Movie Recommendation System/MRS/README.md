# Movie Recommender System using TMDB Dataset

## Overview

This project implements a content-based movie recommender system using cosine similarity. The recommender system utilizes the TMDB (The Movie Database) dataset to provide personalized movie recommendations based on user input.

## Files

- `app.py`: This Python script contains the implementation of the movie recommender system. It uses Streamlit for the web interface and leverages the TMDB API to fetch movie information and posters.

- `model/movie_list.pkl`: Pickle file containing the movie list data.

- `model/similarity.pkl`: Pickle file containing the precomputed cosine similarity matrix.

## How to Run

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/movie-recommender-system-tmdb-dataset.git
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the Streamlit app:

    ```bash
    streamlit run app.py
    ```

4. Open the provided URL in your web browser to access the Movie Recommender System.

## Usage

1. Upon running the Streamlit app, a web interface will be displayed.

2. Choose a movie from the dropdown menu or type the name of the movie you are interested in.

3. Click the "Show Recommendation" button to get personalized movie recommendations.

4. The system will display the top 5 recommended movies along with their posters.

## Data Sources

- TMDB API: [https://www.themoviedb.org/documentation/api](https://www.themoviedb.org/documentation/api)

## Acknowledgments

This project is inspired by the idea of content-based movie recommendation systems and utilizes the TMDB dataset for movie information.
