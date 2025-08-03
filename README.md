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

## Folder Structure

movie-recommendation-system/
│
├── index.py         # Main script for recommendation
├── requirements.txt # Python dependencies
├── README.md        # Project overview and instructions
└── data/            # (Optional) Folder for dataset files
Edit
python index.py
Follow the prompts to get movie recommendations.
