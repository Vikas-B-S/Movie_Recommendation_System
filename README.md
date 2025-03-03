# Movie_Recommendation_system

# 📌 Project Overview

This project builds a Movie Recommendation System using Python, Pandas, Matplotlib, Seaborn, and Scikit-Learn. The system provides movie recommendations based on popularity and collaborative filtering techniques.

# 📂 Dataset

The project utilizes two datasets:

[movies.csv](https://github.com/Vikas-B-S/Movie_Recommendation_System/blob/main/movies.csv) – Contains metadata for movies (e.g., movie ID, title, genres).

[ratings.csv](https://github.com/Vikas-B-S/Movie_Recommendation_System/blob/main/ratings.csv) – Contains user ratings for movies (e.g., user ID, movie ID, rating score).

# 🛠️ Features Implemented

## 1️⃣ Data Preprocessing & Cleaning

- Merged movies.csv and ratings.csv for analysis.
- Removed duplicates and missing values to improve data integrity.
- Standardized data for efficient processing.

## 2️⃣ Exploratory Data Analysis (EDA)

- Identified top-rated and most-rated movies.
- Visualized trending movies and rating distributions using Matplotlib & Seaborn.

## 3️⃣ Recommendation System Development

### Popularity-Based Recommendation

- Suggests top movies based on genre and rating threshold.
- Returns the highest-rated movies within a selected genre.

### Collaborative Filtering (User-Based)

- Uses K-Nearest Neighbors (KNN) and Cosine Similarity to recommend movies based on similar users' preferences.
- Constructs a user-movie rating matrix to find similarities.

# 📊 Technologies Used

- Programming Language: Python
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
- Machine Learning Techniques: KNN, Cosine Similarity

# 🚀 How to Run

Clone this repository:
```
git clone https://github.com/Vikas-B-S/Movie_Recommendation_System.git
cd Movie_Recommendation_System
```
Install dependencies:
```
pip install pandas numpy matplotlib seaborn scikit-learn
```
Run the Jupyter Notebook (Mid_Project_01.ipynb) to execute the recommendation models.

# 📌 Future Improvements

- Implement content-based filtering for personalized recommendations.
- Enhance the system with deep learning models (e.g., Neural Networks).
- Deploy the recommendation system as a web application.

## 💡 Feel free to fork this repo and contribute to improving the recommendation system! 🚀
