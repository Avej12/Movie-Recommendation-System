# Movie-Recommendation-System
The project focuses on building a content-based recommendation system to suggest five movies similar to a user-selected movie. It uses metadata like genres, keywords, and other features to compute similarities between movies.
# Workflow
Problem Understanding:
I aimed to recommend movies based on the preferences of users by analyzing the attributes of movies they liked.

Dataset Preparation:
The dataset included metadata such as movie titles, genres, keywords, and other descriptive features.
Data cleaning involved handling missing values and normalizing the text data (e.g., converting text to lowercase, removing special characters).

Feature Engineering:
I extracted and preprocessed key features (e.g., genres, keywords) to create a numerical representation of movie attributes.
Text data was transformed into a vector format using techniques like TF-IDF or Count Vectorizer.

Similarity Computation:
Implemented cosine similarity to calculate the closeness between movies based on their feature vectors.
Movies with higher cosine similarity to the selected movie were ranked as more relevant.

Recommendation Output:
The system outputs the top 5 movies with the highest similarity scores to the user-selected movie.
