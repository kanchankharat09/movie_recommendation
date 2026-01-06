# movie_recommendation
Built a content-based movie recommendation system using NLP techniques. Processed movie metadata (overview, genres, keywords, cast, director), vectorized text using CountVectorizer with stemming, and applied cosine similarity to recommend top 5 similar movies. The model was saved using pickle for deployment and reuse.



Files Required

movie_recommendation.py
tmdb_5000_movies.csv
tmdb_5000_credits.csv

How to Run (Google Colab / Python)

Open Google Colab
Upload all files:
movie_recommendation.py
tmdb_5000_movies.csv
tmdb_5000_credits.csv

Run the Python file:

!python movie_recommendation.py
Get movie recommendations:
recommend("Batman Begins")

Technologies Used
Python
Pandas, NumPy
Scikit-learn
NLTK

Output
Displays top 5 similar movies based on content similarity.


Create requirements.txt

Just say 👍
