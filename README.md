# Movie-Recommendation-system
A machine learning project. Use to recommend movies just like Netflix.

Objective: The project aimed to develop a movie recommendation system similar to Netflix's recommendation engine.

Data Source: The data for the project was collected from the TMDB (The Movie Database) website, which likely included information such as movie titles, genres, actors, directors, ratings, etc.

Machine Learning Techniques:
CountVectorizer: This technique from the sklearn library was likely used to convert text data such as movie plots, genres, or keywords into numerical vectors.
Cosine Similarity: Cosine similarity was employed to calculate the similarity between movies based on their feature vectors. It measures the cosine of the angle between two vectors, indicating their similarity regardless of their magnitude.

Platform for Development and Deployment:
VS Code: Visual Studio Code was utilized as the primary development environment for writing and debugging code. It provides features for Python development and integrates with various extensions for enhanced functionality.
Google Colab: Google Colab served as a platform for utilizing cloud-based computing resources, particularly useful for training machine learning models on large datasets or running computationally intensive tasks.
Programming Language: Python was the chosen programming language for implementing the recommendation system. Python offers a rich ecosystem of libraries for data manipulation, machine learning, and web development.

Process:
Data Collection: Movie data was collected from TMDB.
Data Preprocessing: Text data was transformed into numerical vectors using CountVectorizer.
Similarity Calculation: Cosine similarity was computed between movie vectors to determine their similarity.
Recommendation Generation: Based on the computed similarity scores, the system recommended movies similar to those a user has already watched or liked.
Deployment: After development and testing, the recommendation system could be deployed on platforms like VS Code for local usage or Google Colab for cloud-based access.
