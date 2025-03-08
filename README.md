# Movie Recommendation System

📌 Project Overview

This project is a Movie Recommendation System that suggests similar movies based on user input. The model utilizes Natural Language Processing (NLP) and Machine Learning to analyze movie metadata and provide recommendations. The dataset used for this project is TMDB 5000 Movies Dataset.

![recc](https://github.com/user-attachments/assets/16c86e83-0dc6-4a53-95c4-35bf6aec8882)


![reccc](https://github.com/user-attachments/assets/c896921a-fc50-4db3-91bc-160f141863f3)



📂 Dataset Details

The dataset includes information about movies such as titles, genres, keywords, cast, crew, and overviews. The dataset is preprocessed to extract relevant features for content-based filtering.

🛠️ Technologies Used

Python (pandas, numpy, scikit-learn, NLTK)

Natural Language Processing (NLP) (TF-IDF Vectorization)

Machine Learning (Cosine Similarity for recommendations)

Streamlit (for web application, if applicable)

Flask/FastAPI (if deploying as an API)

🎯 Model Explanation

1️⃣ Feature Engineering

Text Preprocessing: Stopword removal, stemming (NLTK, Porter Stemmer)

Vectorization: TF-IDF vectorizer to transform text into numerical vectors

Similarity Calculation: Cosine Similarity to find similar movies

2️⃣ Recommendation Function

Extracts movie features (title, genre, overview, etc.)

Computes cosine similarity between movies

Returns top N recommended movies based on the similarity scores

📌 Example Usage

Input: "The Dark Knight"

Output: List of 5 most similar movies
