# Recommendation-System
This project builds a Movie Recommendation System that suggests movies similar to a user’s choice based on collaborative filtering and cosine similarity. The model analyzes user–movie interactions and recommends movies that are most similar in terms of user ratings.
## 🧠 Objective
To develop a recommendation system that can accurately suggest similar movies based on user preferences and historical ratings data.
## 📂 Dataset Used 
[Dataset] (https://github.com/alisha2926/Recommendation-System/blob/main/ratings.csv)
## ⚙️ Technologies & Libraries Used

-Python 3.11+

-NumPy  

-Pandas

-SciPy

-Scikit-learn

-TensorFlow (for environment setup)

-Jupyter Notebook

## 🏗️ Project Workflow
1️⃣ Data Preprocessing

-Loaded dataset using pandas

-Removed missing values and duplicate records

-Mapped userId and movieId to numerical indices

2️⃣ Matrix Creation

-Created a User–Movie Rating Matrix using csr_matrix from SciPy

3️⃣ Model Building

-Used Nearest Neighbors from scikit-learn

-Similarity metric: Cosine similarity

-Algorithm: Brute-force search

4️⃣ Recommendation Function

-Takes a movie title as input

-Finds top K most similar movies

-Returns recommended titles

## Output
<img src= " https://github.com/alisha2926/Recommendation-System/blob/main/Recommendation%20System%20Output%20pic.png">
