# 🎬 Movie Recommendation Engine

A Machine Learning-based Movie Recommendation System that suggests movies similar to the one selected by the user.

## 📌 Project Overview

This project uses content-based filtering to recommend movies based on genres, keywords, cast, crew, and movie descriptions. The recommendation engine analyzes similarities between movies and suggests the most relevant options.

## 🚀 Features

* Recommend similar movies instantly
* User-friendly Streamlit interface
* Content-based recommendation system
* Uses movie metadata for accurate suggestions
* Fast and interactive predictions

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit
* Pickle

## 📂 Dataset

TMDB 5000 Movie Dataset

Files Used:

* tmdb_5000_movies.csv
* tmdb_5000_credits.csv

## ⚙️ How It Works

1. Load movie and credits datasets
2. Merge and clean the data
3. Extract genres, cast, keywords, and director information
4. Create tags for each movie
5. Convert text into vectors using CountVectorizer
6. Calculate similarity using Cosine Similarity
7. Recommend the top 5 most similar movies

## ▶️ How to Run

1. Clone the repository

git clone https://github.com/ananyathoke2-netizen/movie-recommendation-engine.git

2. Install required libraries

pip install pandas numpy scikit-learn streamlit

3. Generate recommendation files

python model.py

4. Run the application

streamlit run app.py

## 📸 Screenshots

Add screenshots of:

* Home Page
* Movie Selection
* Recommendation Results

## 📊 Sample Recommendation

Input Movie:
Avatar

Recommended Movies:

* Titan A.E.
* Small Soldiers
* Independence Day
* Ender's Game
* Aliens vs Predator: Requiem

## 🎯 Future Improvements

* Add movie posters using TMDB API
* Show ratings and release dates
* Deploy online using Streamlit Cloud
* Add search functionality
* Improve recommendation accuracy

## 👩‍💻 Author

Ananya Rahul Thoke

B.Tech Engineering (AI & ML)

GitHub: https://github.com/ananyathoke2-netizen

Email: [ananyathoke2@gmail.com](mailto:ananyathoke2@gmail.com)

---

⭐ If you like this project, please give it a star.
