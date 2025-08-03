# Movie Recommendation System

A simple Python-based Movie Recommendation System that suggests movies to users based on collaborative filtering with cosine similarity.

## Features

- Reads movie ratings dataset and user data
- Calculates movie similarity using cosine similarity
- Provides personalized movie recommendations
- Supports querying recommendations for a specific user

## Tech Stack

- Python 3
- pandas
- scikit-learn (for cosine similarity)
- numpy

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/sadiya2005/movie-recommendation-system.git
   cd movie-recommendation-system
2. Install dependencies:

```bash
pip install -r requirements.txt
```
3. Run the main script:

## Dataset
The system uses a user-movie ratings dataset (ratings.csv or similar).

You can add your own dataset in the expected format (userId, movieId, rating).

## This is a Movie Recommendation System I developed using Python and machine learning techniques. It recommends similar movies to a user’s favorite movie using content-based filtering. I used the TF-IDF Vectorizer to convert movie overviews into numerical vectors and calculated similarity scores using cosine similarity. The system finds the closest match to the user's input using difflib, then ranks and displays the most relevant movie suggestions. The goal was to build a personalized and efficient recommendation engine, and I learned how NLP techniques like TF-IDF and similarity measures play a major role in such systems.


